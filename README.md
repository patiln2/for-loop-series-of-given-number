using System;
namespace CSharp_Shell
{ 
public class Program 
    {
        public static void Main()
        {	
        	int i,n;
			Console.WriteLine("enter a number");
		    n=Convert.ToInt32(Console.ReadLine());
		    Console.WriteLine("series of 1 to 10 in  for loop:-");
		    for(i=1;i<=n;i++)
		    {
		    	Console.WriteLine(i); 
		    }		    
		    Console.ReadLine(); 
		    }}
}
