# MagicEightBall

import java.util.Scanner;

/** This is a program that acts as a Magic Eight Ball. 
 * Users can ask the computer questions, and the program will randomly 
 * choose from a list of predetermined enumerated answers.
 * This project is meant as an exercise to enhance my coding abilities
 * and as a platform on which I can experiment with GUI objects.
 */

public class MagicEightBall {
	
	public static void main(String[] args){
		Scanner scan = new Scanner(System.in);
		String question = prompt(scan);
		randomAnswer();
	}

	// prompts the user for a questions and
	// returns it
	private static String prompt(Scanner scan){
		System.out.println("Ask a question, and then press enter. . .");
		return scan.nextLine();
	}
	
	// this method will choose an answer randomly
	private static void randomAnswer() {
		// TODO Auto-generated method stub
		
	}
}
