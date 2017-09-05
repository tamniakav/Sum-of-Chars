# Sum-of-Chars
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _10.Sum_of_Chars
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());

            int sumOfChar = 0;

            for (int i = 0; i < n; i++)
            {
                char simbol = char.Parse(Console.ReadLine());
                sumOfChar += simbol;
            }

            Console.WriteLine($"The sum equals: {sumOfChar}");
        }
    }
}
