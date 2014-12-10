Chapter-6
=========
import java.util.Scanner;
public class Quiz 
{
	public static void main(String[] args) 
	{
		Scanner scan = new Scanner (System.in);
		int key = 0;
		int userAnswer = 0;
		int numCorrect = 0;
		System.out.println("How many questions? ");
		key=scan.nextInt();
		int[] answers= new int[key];
		for (int i=0; i<key; i++)
		{
			System.out.println("Enter the answers: ");
			answers[i]=scan.nextInt();
		}
		for (int i=0; i<key; i++)
		{
			System.out.println("Enter your attempted answers: ");
			userAnswer=scan.nextInt();
		}
		
		
		

	}

}
