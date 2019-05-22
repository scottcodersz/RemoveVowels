# RemoveVowels
Removes vowels from a string input by the user
import java.util.*;
import java.lang.*;
import java.io.*;
public class RemoveVowels {

	public static void main(String[] args) {
		System.out.println("Enter string: ");
		Scanner item = new Scanner(System.in);
		String statement = item.nextLine();
		System.out.println("The string after vowel removal is: ");
		String statement2 = statement.replaceAll("[aeiouAEIOU]", "");
		System.out.println(statement2);
		

	}

}
