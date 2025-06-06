# method.cs
class Program
{
    static void Main(string[] args)
    {
        
        MathOperations mathOps = new MathOperations();

        
        mathOps.DoMath(5, 10);

        
        mathOps.DoMath(number1: 7, number2: 20);

        
        Console.WriteLine("Press any key to exit...");
        Console.ReadKey();
    }
}
