# exception-handling
Using System;
namespace CSharp_Shell
{
 Public class Program 
    {
 Public static void Main()
   {
Try
	{
  	Int a=2;
   	Int b=0;
    	Int c=a/b;
  	Console.WriteLine(c);
 	}
   Catch(Exception e)
	{
	Console.WriteLine(“Exception occurred:-“+e);
	}
  Finally
	{
	Console.WriteLine(“Exception handled”);
	}       }        }     }
