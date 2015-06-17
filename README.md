# java-sample
simple program
abstract class add
{
int a=5,b=10;
	abstract void show();
	void display()
	{
	int c=a+b;
	System.out.println("the addition of two numbers......"+c);
	}
}
class subj extends add
{
	void show()
	{
	System.out.println("we are in abstract sub class.....");
	
	}
	void display()
		{
		int c=a-b;
		System.out.println("the value of c is..."+c);
		}
	
public static void main(String args[])
	{
	add t1=new subj();
	t1.show();
	t1.display();
	
	}	
}
