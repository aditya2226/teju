# teju

import java.lang.System;
import java.lang.String;

import java.util.Scanner;

public class Sample1 {
	

	
	
	    public static void main(String args[])
	    {
	        int x, y, z, big;
	        Scanner s = new Scanner(System.in);
			
	        System.out.println("Enter Three Variable Numbers : ");
	        x = s.nextInt();
	        y = s.nextInt();
	        z = s.nextInt();
	        
	        // let x is the largest
	        
	        big = x;
	        
	        if(big<y)
	        {
	            if(y>z)
	            {
	                big = y;
	            }
	            else
	            {
	                big = z;
	            }
	        }
	        else if(big<z)
	        {
	            if(z>y)
	            {
	                big = z;
	            }
	            else
	            {
	                big = y;
	            }
	        }
	        else
	        {
	            big = x;
	        }
			
	        System.out.print("Largest Number is " +big);
	    }
	}

