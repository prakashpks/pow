
import java.util.Scanner;
class number
{
	public static void main (String[] args){ 
	 	System.out.println("Enter number");
	  Scanner in =new Scanner(System.in);
	  Integer number,c=1,num;
	  num=in.nextInt();
	  number=in.nextInt();
	  while (number != 0)
	    {
	        c *= num;
	        --number;
	    }
	 	System.out.println(c);
	}
}
