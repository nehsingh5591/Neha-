package week1;
import java.util.*;
public class Calculation {

	public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
    System.out.println("enter two numbers");
    int a=sc.nextInt();
    int b=sc.nextInt();
    System.out.println("enter an operator do you want to calculate(+,-,*,%)");
    char op=sc.next().charAt(0);
    switch(op) {
    case'+':System.out.println(a+b);
            break;
    case'-':System.out.println(a-b);
            break;
    case'*':System.out.println(a*b);
            break;
    case'%':System.out.println(a%b);
            break;
    default:System.out.println("invalid input");
    
    }

	}

