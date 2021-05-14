# Week-2-Coding-Assignment
public class secondWeekCodingAssignment {

	public static void main(String[] args) {
		boolean isHotOutside = true;
		boolean isWeekday = false;
		boolean hasMoneyInPocket = false;
		
		double costOfMilk = 12.99;
		double moneyInWallet = 40;
		int thirstLevel = 7;
		
		boolean shouldBuyIcecream = isHotOutside && !hasMoneyInPocket;
		boolean willGoSwimming = isHotOutside && !isWeekday;
		boolean isAGoodDay = isHotOutside && hasMoneyInPocket && (!isWeekday);
		boolean willBuyMilk = isHotOutside && (thirstLevel >=3) && (moneyInWallet >= (2*costOfMilk));
		
		
		
		System.out.println(shouldBuyIcecream);
		System.out.println(willGoSwimming);
		System.out.println(isAGoodDay);
		System.out.println(willBuyMilk);
		
		
		
	}

}


// This code is different from the code above.

public class Loops {

	public static void main(String[] args) {
		
		int i = 0;	
		while (i <= 100) {		
			if (i % 2 == 0) {
				System.out.println(i);
				
			} i++;
			
			

		}
		
		//question 5(b)
		
		
		int x = 100;
		while (x >=0) {
			System.out.println(x + " ");
			x-=3;
		
		}
		
		
		//	For loop printing number from 1-100	
		for (int z = 1; z <= 100; z=z+2) { 
			System.out.println(z);
		}
		
		//question 5(d)
		
		for(int j = 0; j <= 100; j++) {
			//check if the number is divisible by both 3 and 5 and print the message if so
			if((j%5 ==0) && (j%3==0)) {
				System.out.println("HelloWorld");
			}
			
			
			//check if the number is divisible by 5 and print the message accordingly
			else if (j%5 ==0) {
				System.out.println("World");
				
			}
			
			
			//check if the number is divisible by 3 and print the message accordingly
			
			else if(j%3 ==0) {
				System.out.println("Hello");
			}
			
			//else condition should be just print the number
			else {
				System.out.println(j);
			}
			
     }

	}
}

