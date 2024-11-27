Printing Right Triangle Number Pattern:
In this JAVA program we’re going to code basic right triangle number pattern program .

Take the input from user and store it in variable named as count and then take a main outer for loop start with i=1 to i++ inside this take another for loop start from j=1 to j++ inside this print count variable .

After the end of main loop take line changement statement

Here on this page you will get java program basic right triangle number star pattern . This program included all the algorithm of the program
Algorithm:
initalize an integer variable count=0 for incrementing
Take the number of rows as input from the user  and store it in any variable.(‘row‘ in this case).
Run a loop ‘row’ number of times to iterate through each of the rows. From i=1 to i<=row. The loop should be structured as for (int i = 1; i <= row; i++)
 Run a nested loop inside the main loop to print the digits in each row of the triangle. From  j=1 to j<=i. The loop should be structured as for (int j = 1; j <= i; j++)
In the nested loop increment count and print it.
In the main loop print a new line System.out.println();
Code in Java:
import java.util.Scanner;
public class Pattern1 {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int count=0;
		System.out.println("Enter row");
		int row = sc.nextInt();
		
		
		for (int i = 1; i <= row; i++) {
			for (int j = 1; j <= i; j++) {
				count++;
				System.out.print(count);
			}
			System.out.println();
		}
	}

}
