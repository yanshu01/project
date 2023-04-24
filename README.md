# project
import com.sun.source.tree.ContinueTree;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
       double num1, num2;
       Scanner sc = new Scanner(System.in);
       System.out.println("Enter the number ");

       num1 = sc.nextDouble();
       num2 = sc.nextDouble();
       System.out.println("enter the operater (+,-,*,/)");

       char op = sc.next().charAt(0);

       double o = 0;
       switch (op){
           case'+':
               o = num1 + num2;
               break;
           case'-':
               o = num1 - num2;
               break;
           case'*':
               o = num1 * num2;
               break;
           case'/':
               o = num1 / num2;
               break;
           default:
               System.out.println("you enter the wrong input");
       }
       System.out.println("the final result is herer");
       System.out.println();
       System.out.println(num1 + "" + op + "" + num2 + "=" + o);
    }
    }

