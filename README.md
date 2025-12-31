# Task2-Staxtech-
import java.util.Scanner;
class Calculator{
public static void main(String args[]){
Scanner s=new Scanner(System.in);
int num1,num2;
num1=s.nextInt();
num2=s.nextInt();
System.out.printl("Simple Calculator");
String choice=s.next();
switch(choice){
case add:
add=num1+num2;
System.out.println("Addition of two numbers:"+add);
break;
case sub:
sub=num1-num2;
System.out.println("Subtraction of two numbers:"+sub);
case mul:
mul=num1*num2;
System.out.println("Multiplication of two numbers:"+mul);
break;
case div:
System.out.println("Division of two numbers:"+div);
default:
System.out.println("Invalid choice");
}}}

