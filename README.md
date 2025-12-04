using System;

class Program
{
    static void Main()
    {
        Console.Write("Unesi dužinu dijagonale kvadrata d: ");
        double d = double.Parse(Console.ReadLine());

        double a = d / Math.Sqrt(2);

        Console.WriteLine("Dužina stranice kvadrata je: " + a);
    }
}
