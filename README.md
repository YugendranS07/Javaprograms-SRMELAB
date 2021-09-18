 Q. 2: Moons gravity
QUESTION DESCRIPTION

The Moons gravity is about 16.6 percent that of Earths.Write a program that computes your effective weight on the Moon.

Note:

Use Double Data Type
TEST CASE 1

INPUT
53
OUTPUT
8.798
TEST CASE 2

INPUT
75
OUTPUT
12.45
=================================================================
code:

import java.io.*;
import java.util.Scanner;
public class TestClass {
	 public static void main(String[] args) { 
	  Scanner s=new Scanner(System.in);
       double  w=s.nextInt();
       double mw=(w*(16.6))/100;
       System.out.println(mw);
       
	}
}
=================================
