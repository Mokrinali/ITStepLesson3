/* დავალება პირველი

Console.Write("enter the number: ");
int n = int.Parse(Console.ReadLine());

for (int i = 1; i <= n; i++)
{
    Console.Write(i + " ");


}

int sum = 0;
for (int i = 1; i <= n; i++)
{
    sum += i;
}

Console.WriteLine(n + "+ all natural numbers:  " + sum);
           
 */



/* დავალება მეორე

Console.Write("Enter the Number: ");
int number = int.Parse(Console.ReadLine());


for (int i = 0; i <= 10; i++)
{
    Console.WriteLine($"{number} * {i} = {number * i}");
}

*/

/*

Console.Write("Enter the number (the height of the pyramid): ");
int height = int.Parse(Console.ReadLine());



for (int i = 1; i <= height; i++)
{

    Console.Write(new string(' ', height - i));


    for (int j = 1; j <= i; j++)
    {
        Console.Write(i + " ");
    }
    Console.WriteLine();

}

*/



  /*  დავალეაბ მესამე

Console.Write("Enter Pyramid Height: ");
int height = int.Parse(Console.ReadLine());


for (int i = 1; i <= height; i++)
{
   
    for (int j = 1; j <= i; j++)
    {
        Console.Write("*");
    }
    Console.WriteLine(); 

*/



    /* დავალება მეოთხე

    Console.Write("Enter n and we will calculate fatorial of n: ");
    int number= int.Parse(Console.ReadLine());

    int factorial = 1;
    for (int i = 1; i <= number; i++)
    {
    factorial *= i;
    }
    Console.WriteLine(number + "! = " + factorial);

    */

    /* დავალება მეხუთე

    Console.Write("Enter the Number (The Height Of The Pyramid): ");
    int height = int.Parse(Console.ReadLine());


    for (int i = 1; i <= height; i++)
    {

        Console.Write(new string(' ', height - i));


        for (int j = 1; j <= i; j++)
        {
            Console.Write(i + " ");
        }
        Console.WriteLine();

        */

    /* დავალება მეხუთე

    Console.Write("Enter The First Number: ");
    int firstNumber = int.Parse(Console.ReadLine());

    Console.Write("Enter The Second Number: ");
    int secondNumber = int.Parse(Console.ReadLine());


    int start = Math.Min(firstNumber, secondNumber);
    int end = Math.Max(firstNumber, secondNumber);


    Console.WriteLine($"Range Of Even Numbers {start} - {end}:");

    for (int i = start; i <= end; i++)
    {
        if (i % 2 == 0) 
        {
            Console.WriteLine(i);
        }


    }

    */
