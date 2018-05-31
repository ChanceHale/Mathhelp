# Mathhelp
import java.lang.Math;
import java.util.*;

public class Mathhelp {
	
	public static void main(String[] args) {
		
		
		Scanner s = new Scanner(System.in);
		
		System.out.println("Hi, what is the value of X?");
		int x = s.nextInt();
		 System.out.println("Ok! What is the value of y?");
		 int y = s.nextInt();
		 System.out.println("Great! What is the value of h?");
		 int h = s.nextInt();
		 System.out.println("Amazing! What is the value of k?");
		int k = s.nextInt();
		double top = (y-k);
		//System.out.println("Top is: " + top);
		double bottom = ( x * x - 2 * x * h + h * h);
		//System.out.println("Bottom is: " + bottom);
		System.out.println("Your answer is:");
		System.out.println(top / bottom);
				
		
	}
	
}
