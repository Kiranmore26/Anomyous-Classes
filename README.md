# Anomyous-Classes

package Inner_Class;

//Anonymous class with Abstract Method


abstract class Outer
{
	abstract void show();
	
}
public class Anonymous_Class 
{
	public static void main(String[] args) 
	{
		Outer o=new Outer() 
		{
			void show()
			{
				System.out.println("this is Show method...");
				
			}
		};
		o.show();
	}
}
