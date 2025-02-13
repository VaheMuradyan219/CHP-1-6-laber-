using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Yndhanur_Amenamec_Bajanarar
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("1-in tiv    ");
            int a = int.Parse(Console.ReadLine());
            Console.Write("2-rd tiv    ");
            int b = int.Parse(Console.ReadLine());

            Console.WriteLine("Ynhanur mec bajanarar    " + TheGreatestDivisor(-10, 4));

            Console.ReadKey();
        }

        private static int TheGreatestDivisor(int a, int b)
            {
            if (a < 0)
            {
                a *= -1;

            }
            if (b < 0)
            {
                b *= -1;
            }

            if (a < b)
            {
                int c = a;
                a = b;
                b = c;
            }

            for (int i = b; i > 1; i--)
            {
                if (a % i == 0 && b % i == 0) 
                {
                    return i;
                }
            }

            return 1;
        }
    }
}
