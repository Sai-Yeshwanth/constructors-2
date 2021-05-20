//calling constructors of class from a subclass

class Jala {
	int a=5,b=7;
	Jala()
	{
		System.out.println(a+b);
	}
	Jala(int c)
	{
		System.out.println(a+b+c);
	}
	Jala(int c,int d)
	{
		System.out.println(a+b+c+d);
	}
	public static void main(String[] args) {

		Newclass n = new Newclass();
		
	}
}
public class Newclass extends Jala{
	Jala a= new Jala(4,5);
	Jala b= new Jala(5);
}
