import java.util.*;

import Exception.BadRequestAlertException;

import java.lang.*;

public class positive_emotion extends Exception {
	//public static final Throwable ENTITY_NAME = null;

	public static void main (String[] args) throws BadRequestAlertException{
		
		String keyword;
		//boolean hasUppercase = !keyword.equals(keyword.toLowerCase());
		
		Scanner sc = new Scanner (System.in);
		
		System.out.println("Enter your keywords : \n");
		keyword = sc.next();
		
		if(keyword.equalsIgnoreCase("SAD") ) {
			System.out.println("\nNegative");
	}
		else if (keyword.equalsIgnoreCase("FEAR")) {
			System.out.println("\nNegative");
		}
		
		else if (keyword.equalsIgnoreCase("LONELY")) {
			System.out.println("\nNegative");
		}
		
		else if (keyword.equalsIgnoreCase("LOVE")) {
			System.out.println("\nPositive");
		}
		
		else if (keyword.equalsIgnoreCase("HAPPY")) {
			System.out.println("\nPositive");
		}
	
		else if (keyword.equalsIgnoreCase("TRUST")) {
			System.out.println("\nPositive");
		}
		
		else {
			MyEmotions();
		}
		
	}
	
	
	private static void MyEmotions() {
		// TODO Auto-generated method stub
		System.out.println("Invalid Content");
		
	}
	
	

}

