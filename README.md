# WordsToNumbers
WordsToNumbers
package Assignments;

import java.util.Scanner;

public class WordToNumbers {
     public static void main(String[] args) {
		  
    	 Scanner scan = new Scanner(System.in);
    	 System.out.println("Please type any number from 0 to 10");
    	 String wordNumber = scan.nextLine();
    	
         if (wordNumber.equalsIgnoreCase("zero") || wordNumber.length()==4 && wordNumber.charAt(0)=='z' && wordNumber.charAt(1)=='e'  && 
    			 wordNumber.charAt(2)=='r' && wordNumber.charAt(3)=='o') {
    		 System.out.println("0");
    	 } else if (wordNumber.equalsIgnoreCase("one") || wordNumber.length()==3 && wordNumber.charAt(0) =='o' && wordNumber.charAt(1)=='n' && 
    			 wordNumber.charAt(2)=='e') {
    		 System.out.println("1");
    	} else if(wordNumber.equalsIgnoreCase("two") || wordNumber.length()== 3 && wordNumber.charAt(0)=='t' && wordNumber.charAt(1)=='w' && 
    			 wordNumber.charAt(2)=='o') {
    		 System.out.println("2");
    	} else if (wordNumber.equalsIgnoreCase("three") || wordNumber.length()==5 && wordNumber.charAt(0)=='t' && wordNumber.charAt(1)=='h' &&
    			 wordNumber.charAt(2)=='r' && wordNumber.charAt(3)=='e' && wordNumber.charAt(4)=='e') {
    		 System.out.println("3");
    	} else if (wordNumber.equalsIgnoreCase("four") ||wordNumber.length()==4 && wordNumber.charAt(0)=='f' && wordNumber.charAt(1)=='o' && 
    			 wordNumber.charAt(2)=='u' && wordNumber.charAt(3)=='r') {
    		 System.out.println("4");
    	} else if (wordNumber.equalsIgnoreCase("five") ||wordNumber.length()==4 && wordNumber.charAt(0) == 'f' && wordNumber.charAt(1)=='i' && 
    			 wordNumber.charAt(2)=='v' && wordNumber.charAt(3)=='e') {
    		 System.out.println("5");
    	} else if (wordNumber.equalsIgnoreCase("six") ||wordNumber.length()==3 && wordNumber.charAt(0) == 's' && wordNumber.charAt(1)=='i' && 
    			 wordNumber.charAt(2)=='x') {
    		 System.out.println("6");
    	} else if (wordNumber.equalsIgnoreCase("seven") || wordNumber.length()==5 && wordNumber.charAt(0)=='s' && wordNumber.charAt(1)=='e'&& 
    			 wordNumber.charAt(2)=='v' && wordNumber.charAt(3)=='e' &&wordNumber.charAt(4)=='n') {
    			 System.out.println("7");
    	} else if (wordNumber.equalsIgnoreCase("eight") || wordNumber.length()==5 && wordNumber.charAt(0)=='e' && wordNumber.charAt(1)=='i' && 
    				 wordNumber.charAt(2)=='g' && wordNumber.charAt(3)=='h' && wordNumber.charAt(4)=='t' ) {
    			 System.out.println("8");
    	} else if (wordNumber.equalsIgnoreCase("nine") ||wordNumber.length()==4 && wordNumber.charAt(0)=='n' && wordNumber.charAt(1)=='i' &&
    			 wordNumber.charAt(2)=='n' && wordNumber.charAt(3)=='e'){
    			System.out.println("9");
    	} else if (wordNumber.equalsIgnoreCase("ten") ||wordNumber.length()==3 && wordNumber.charAt(0)=='t' && wordNumber.charAt(1)=='e' && 
    			wordNumber.charAt(2)=='n') {
    		System.out.println("10");
    	} else {
    		System.out.println("System accepts numbers between 0 and 10");
    	}
    	 scan.close();
	}
}
