# method.cs
using System;


namespace MathOperationApp
{
    
    class MathProcessor
    {
        
        public void ProcessNumbers(int firstNumber, int secondNumber)
        {
            
            int result = firstNumber * 2;

            
            Console.WriteLine("Result of math operation on first number: " + result);

            
            Console.WriteLine("Second number is: " + secondNumber);
        }
    }

    
    class Program
    {
        static void Main(string[] args)
        {
            
            MathProcessor processor = new MathProcessor();

            
            processor.ProcessNumbers(5, 10);

            
            processor.ProcessNumbers(firstNumber: 8, secondNumber: 20);

            
            Console.WriteLine("Press any key to exit...");
            Console.ReadKey();
        }
    }
}

