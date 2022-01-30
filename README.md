# assignmentsog
q4)
public class loops {
	public static void main(String args[])
	{
	int	i=1;
while(i<10)
{
	i++;
	
System.out.println(i);
}
	}
}


q5)public class loops {
	public static void main(String args[])
	{
	int	i=10;
while(i>1)
{
	i--;
	
System.out.println(i);
}
	}
}
	
  
  
  
  q6)
  public class loops {
	public static void main(String args[])
	{
	int	i=0;
while(i<10)
{
	i=i+2;
	
System.out.println(i);
}
	}
}
	
	public class forloop {

	public static void main(String[] args) {
		int t=2;
		for(int i=1;i<=5;i++)
		{
		
			
			System.out.println(t*i);
		}

	}

}




q7)public class forloop {

	public static void main(String[] args) {
		int t=2;
		for(int i=10;i>=1;i--)
		{
		
			
			System.out.println(t*i);
		}

	}

}



public class loops {
	public static void main(String args[])
	{
	int	i=10;
while(i>1)
{
	i--;
	
	
System.out.println(i*2);
}
	}
}



q8)
import java.util.Scanner;
public class primenumber {
	public static void main( String args[])
	{
		Scanner s= new Scanner(System.in);
		System.out.println("enter the number");
		int num=s.nextInt();
		int temp=0;
		for(int i=2;i<=num-1;i++)
		{
			if(num%i==0)
			{
			temp=temp+1;
			}
			
		}
			if(temp==0)
			{
				System.out.println("prime number");
			}
			else
			{
				System.out.println("not a prime number");
		}
				
			}
		}
    
    q9)public class power {

	public static void main(String[] args) {
		int base = 3, exponent = 4;

	    long result = 1;

	    while (exponent != 0) {
	      result *= base;
	      --exponent;
	    }

	    System.out.println("Answer = " + result);
	  }
	

	}

q10)import java.util.Scanner;     
public class sum {

	public static void main(String[] args) {
		
	
		int num, i, sum = 0;  
		Scanner sc = new Scanner(System.in);  
		System.out.print("Sum from= ");  
		i = sc.nextInt();  
		System.out.print("Sum up to= ");  
		num = sc.nextInt();  
		while(i <= num)  
		{  
		sum = sum + i;    
		i++;  
		}
		System.out.println("Sum of  Numbers = " + sum);  
	}  
  
  
  q11)
  import java.util.Scanner;
public class factorial {
	

public static void main(String args[])
{
	Scanner s = new Scanner(System.in);
	System.out.println("enter the number");
	int num=s.nextInt();
	int fact=1;
	
	for(int i=1;i<=num;i++)
	{
  fact=fact*i;
		
	System.out.println("fact="+fact);

	}	
}
}


q12)import java.util.Scanner;
public class forloop {

	public static void main(String[] args) {
		Scanner s = new Scanner(System.in);
		System.out.println("enter the number");
	
	
		int num= s.nextInt();
		for(int i=1;i<=num;i++)
		{
		
			
			System.out.println(i*num);
		}

	}

}
q13)import java.util.Scanner;
public class forloop {

	public static void main(String[] args) {
		Scanner s = new Scanner(System.in);
		System.out.println("enter the number");
	
	
		int num= s.nextInt();
		for(int i=1;i<=num;i++)
		{
		
			
			System.out.println(i*num);
		}

	}

}
q14)
import java.util.Scanner;
public class Leapyear
{
	   public static void main(String[] args){
	      int year;
	      System.out.println("Enter an Year  ");
	      Scanner sc = new Scanner(System.in);
	      year = sc.nextInt();

	      if (((year % 4 == 0) && (year % 100!= 0)) || (year%400 == 0))
	         System.out.println("Specified year is a leap year");
	      else
	         System.out.println("Specified year is not a leap year");
	   }
	

}

q15)n\a
q16)
public class evenodd {
	    public static void main(String args[])
	    {
	        int number = 1235689012;
	        int value1 = 0;
	        int value2 = 0;
	        while (number > 0)
	        {
	            if ((number % 10) % 2 == 0)
	                value1 = value1 + number % 10;
	            else
	                value2 = value2 + number % 10;
	            number = number / 10;
	        }
	        System.out.print("Value1 = " + value1 + " Value2 =" + value2);
	    }
	}
  17)
  public class reverse {

		  public static void main(String[] args) {
		    
		    int num = 1234567, reversed = 0;

		    for(;num != 0; num /= 10) {
		      int digit = num % 10;
		      reversed = reversed * 10 + digit;
		    }

		    System.out.println("Reversed Number: " + reversed);
		  }
		}
    18)
    public class lefttriangle 
{   
	public static void main(String args[])   
	{    
	int i, j, row = 6;       
  
for (i=0; i<row; i++)   
	{  
      for (j=2*(row-i); j>=0; j--)         
	{  
	     System.out.print(" ");   
	}   
	  for (j=0; j<=i; j++ )   
	{   
     System.out.print("* ");   
	}   

	System.out.println();   
	} 
	}
  19)
  public class pyramid 
{
	public static void main(String args[])   
	{    
 
	int i, j, row = 6;       
 
for (i=0; i<row; i++)   
	{  
	      
for (j=row-i; j>1; j--)   
	{  
	 
	System.out.print(" ");   
	}   
 
  for (j=0; j<=i; j++ )   
	{   
      
	System.out.print("* ");   
	}   
	
	System.out.println();   
	}   
	}
	}
  

