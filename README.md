# Simple_Calculator
// my first very simplistic calculator

import java.util.Scanner;

public class Rechner {

	public static void main(String[] args) {
		
		Scanner scanner = new Scanner(System.in);
		int x;
		int y;
		int ergebnis;
		char operator;
		
		// Number-input User
		System.out.println("Please enter the first number now: ");
		x = scanner.nextInt();
		System.out.println("Now choose what you want to do with that number! (+, -, * und /:)");
		operator = scanner.next().charAt(0);
		System.out.println("Enter the second number now: ");
		y = scanner.nextInt();
		
		int addition = x + y;
		int substraktion = x - y;
		int multiplication = x * y;
		int division = x / y;
		
		if(operator == '+') {
			solution = x + y;
			System.out.println(solution);
		}
		else if(operator == '-') {
			solution = x - y;
		System.out.println(solution);
		}
		else if(operator == '*') {
			solution = x * y;
			System.out.println(solution);
		}
		else if(operator == '/') {
				solution = x / y;
		System.out.println(solution);
		}
		else {
			System.out.println("Invalid input!");
		}
		
	}
}
