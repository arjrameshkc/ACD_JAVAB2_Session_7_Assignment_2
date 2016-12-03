# ACD_JAVAB2_Session_7_Assignment_2

import java.util.Scanner;

public class SubstringOfString {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		 String str1, sub1;
		 boolean subStringFound;
	      Scanner scan = new Scanner(System.in);
	      System.out.println("Enter the main string");
	       str1 = scan.next();
	       System.out.println("Enter the sub string");
	       Scanner scan1 = new Scanner(System.in);
	       sub1 = scan1.next();
	       subStringFound = str1.contains(sub1);
	       if (subStringFound = true)
	       {
	    	   System.out.println("Substring is found in mainstring" );
	       }
	       else
	       {
	    	   System.out.println("Substring  not found in mainstring" );
	       }   
	 	      
}
}
