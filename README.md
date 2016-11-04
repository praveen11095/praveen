import java.util.Scanner;

public class fact1 {

	
	public static void main(String[] args){
		
		  int i,num,fact=1;  
			 Scanner in = new Scanner(System.in);
			// i = in.nextInt();
			 num = in.nextInt();
			// fact = in.nextInt();
			  //It is the number to calculate factorial    
			  for(i=1;i<=num;i++){    
			      fact=fact*i;    
			  }
		
	System.out.println("Factorial of "+num+" is: "+fact);    

		
	}
		 
	
}
	
