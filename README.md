# String-True-or-False-in-java

Program:

import java.util.*;
public class Main
{
  public static void main (String[]args)
  {
    Scanner sc=new Scanner(System.in);
	String s1 = new String();
	System.out.print("Eter your name :");
    s1 =sc.nextLine();
    String s2= new String();
    System.out.print("Enter your crush name:");
    s2=sc.nextLine();
	if (s1.equals (s2))
	  {
		System.out.print ("false");
	  }
	else
	  {
		System.out.print ("true love");
	  }
  }
}
