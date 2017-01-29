using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Test2
{
    class Program
    {
        static void Main(string[] args)
        {
            Program test = new Program();
            int size = 30;
            int[] a = new int[size];
            test.Fibonacci(ref a, size);
            Console.ReadKey();
        }

    public void Fibonacci (ref int[] a, int size)
        {
            a[0] = 0; a[1] = 1;
            Console.Write("0, 1");
            for (int i = 2; i < size; i++)
            {
                int ans = 0;
                ans = a[i - 1] + a[i - 2];
                a[i] = ans;
                Console.Write(", " + ans);
            }
            return;
        }
    }
}
