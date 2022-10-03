using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace daddy
{
    internal class Class1
    {


        public static void My_Math()
        {
            Console.WriteLine("Let's divide two numbers.");

            Console.Write("Enter the Numerator: ");
            double the_numberator = Convert.ToDouble(Console.ReadLine());

            Console.Write("Enter the Denominator: ");
            double the_denominator = Convert.ToDouble(Console.ReadLine());
            double answer = the_numberator / the_denominator;
            Console.WriteLine($"{the_numberator} / {the_denominator} = {answer}");


            Console.ReadLine();
        }
    }
}





using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Xml.Linq;

namespace daddy
{
    internal class Program

    {
        static void Main(string[] args)
        {
            Class1.My_Math();
        }
    }

}
