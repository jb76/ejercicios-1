# ejercicios-1
using System;
 
public class edad
{
    public static void Main()
    {
        float primerNumero;
		float edad;

		
 
        Console.WriteLine("Escribe un numero");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        edad = primerNumero;  
		
 
        Console.WriteLine("El resultado esperado:" ) ; 
       
		Console.WriteLine("{0} {0} {0} {0} ", 
		edad, edad);
		
		Console.WriteLine("{0}{0}{0}{0} ", 
		edad, edad);
			
       
		Console.WriteLine("{0} {0} {0} {0} ", 
		edad, edad);
		
		Console.WriteLine("{0}{0}{0}{0} ", 
		edad, edad);

		}
}
