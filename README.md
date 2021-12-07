# Switch1
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
        Scanner in = new Scanner(System.in);
        System.out.println("Enter one of these operators");
        char c=in.next().charAt(0);
    switch (c)
    {
        case 'a':
            System.out.println(c);
            break;
        case 'b':
            System.out.println(c);
            break;
        case 'c':
            System.out.println(c);
            break;
                default :
            System.out.println("It is not an option");
    }
    }
}
