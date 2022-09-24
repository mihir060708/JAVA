import java.util.*
import java.util.Scanner;

public class Main {
	public static void
	guessno()
	{
		Scanner sc = new Scanner(System.in);
		int number = 1 + (int)(10* Math.random());//to guess no. from more than 10 then replace the 10 here with your desired no.
		int K = 3; //change if you want to increase th no. of chances in game.
		int i, guess;
		System.out.println("A number is chosen"+ " between 1 to 10."+ "Guess the number"+ " within 5 trials.");
		for (i = 0; i < K; i++) {
			System.out.println("Guess number:");
			guess = sc.nextInt();
			if (number == guess) {
				System.out.println("Congratulations!"+ " You guessed it correct.");
				break;
			}
			else if (number > guess&& i != K - 1) {
				System.out.println("The number is "+ "greater than " + guess);
			}
			else if (number < guess&& i != K - 1) {
				System.out.println("The number is"	+ " less than " + guess);
			}
		}
		if (i == K) {
			System.out.println("You have exhausted"+" K trials.");
			System.out.println("The number was "+ number);
		}
	}
	public static void main(String arg[])
	{
		guessno();
	}
}
