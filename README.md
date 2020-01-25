# foss
WAP in c# to show the use of the continue and break statement.
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication10
{
    class ContinueBreak
   
    {
        static void Main(string[] args)
        {
            int n = 10;
            while (n < 200)
            {
                if (n < 50)
                {
                    Console.Write(" " + n);
                    n = n + 10;
                    continue;
                }
                if (n == 50)
                {
                    Console.WriteLine();
                    n = n + 10;
                    continue;
                }
                if (n > 90) break;
                Console.Write(" " + n);
                n = n + 10;
            }
            Console.WriteLine();
            Console.ReadKey();

        }
    }
}
