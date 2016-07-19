# EvenOrOdd
import java.util.Scanner;

public class EvenOrOdd {
	public static void main(String []arg)
	{
		Scanner get=new Scanner(System.in);
		long input=get.nextInt();
		if(input%2==1)
		{
			System.out.println("it is Odd");
		}
		else
		{
			System.out.println("it is Even");
		}
	}

}
