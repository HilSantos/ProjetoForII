# ProjetoForII
Idem

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ProjetoForII
{
    public class Program
    {
        static void Main(string[] args)
        {
            /*Receber um valor do usuario e esse valor será a quantidade de
             *vezes em que o sistema rodará e analisará se é par ou impar
            */
            Console.WriteLine("Informe um numero maior que 10: ");
            int numero=Convert.ToInt32(Console.ReadLine());

//Chamar a estrutura for para que ele faça a volta de acordo com o numero informado pelo usuario//
            for (int i = 1; i <= numero; i++)
            {
                //verificará se i é par ou impar
                if (i%2 == 0)
                {
                    Console.WriteLine($"{i} É PAR!");
                }
                else
                {
                    Console.WriteLine($"{i} É IMPAR!");
                }
            }


Console.ReadKey();
        }
    }
}
