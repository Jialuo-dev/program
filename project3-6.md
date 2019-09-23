# program3-4
example
package hello;

import java.util.Scanner;

public class TestBoolesnOPerators {

	public static void main(String[] args) {
		// Create a Scanner
		Scanner input = new Scanner (System.in);
		
		//Receive an iput 
		System.out.print("Enter an integer:");
		int number= input.nextInt();
		
		if (number %2 ==0 && number%3==0)
			System.out.println(number +"is divisible by 2and 3.");
		
		if (number%2==0||number%3==0)
			System.out.println(numer + "is divisible by 2 or 3.");
		
		if(number % 2==0 ^ number%3==0)
			System.out.println(number+
					"is divisible by 2 or 3,but not both.");
			
	}

}
