# JAVA_FULL_STACK_ASSIGNMENT_1
```
Java Full Stack Assignment 1.
Submitted by : Ilayaraja.M
Register number : 212221040057.

```


# Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

## Program:
```
import java.util.Scanner;
public class Operations{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the numbers for performing operation:");
int num1 =sc.nextInt();
int num2= sc.nextInt();
int sum=num1+num2;
System.out.println("Sum of two numbers: "+sum);
int sub=num1-num2;
System.out.println("Difference of two numbers: "+sub);
int mul=num1*num2;
System.out.println("Product of two numbers: "+mul);
float divi=num1/num2;
System.out.println("Division of two numbers: "+divi);
int rem=num1%num2;
System.out.println("Remainder of two numbers: "+rem);
    }
}
```

## Output:
![Screenshot (241)](https://user-images.githubusercontent.com/127576283/224525817-290571bb-fad9-4abc-8a47-5ccb1052e874.png)




# Write a Java program to compare two numbers.

## Program:
```
import java.util.Scanner;
public class Comparing{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the first number:");
int num1 =sc.nextInt();
System.out.println("Enter the second number:");
int num2= sc.nextInt();
if(num1==num2)
{
    System.out.println("Both the numbers "+num1+" and "+num2+" are equal.");
}
else if(num1>num2)
{
     System.out.println(num1+" is greater than"+num2);
}
else
{
     System.out.println(num2+" is greater than "+num1);
}
    }
}
```

## Output:

![Screenshot (242)](https://user-images.githubusercontent.com/127576283/224525983-d4c3a1b7-a331-4c3c-9d9b-658a586f1ecf.png)



#  Write a Java program to convert a string to an integer.

## Program:
```
import java.util.Scanner;
public class StringToInt{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the string to be converted:");
        String str= sc.nextLine();
        int num= Integer.parseInt(str);
        System.out.println("The integer value is: "+num);
    }
}
```

## Output:

![Screenshot (243)](https://user-images.githubusercontent.com/127576283/224526548-3b52623d-64c9-4955-9c20-351f1d529c2c.png)


# Java Program to find area of rhombus.

## Program:
```
import java.util.Scanner;
public class Area{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the first diagonal:");
        float d1= sc.nextFloat();
        System.out.println("Enter the second diagonal:");
        float d2= sc.nextFloat();
        float area=d1*d2/2;
        System.out.println("The area of the rhombus : "+area);
    }
}
```

## Output:

![Screenshot (244)](https://user-images.githubusercontent.com/127576283/224526425-160b7d28-ab76-4050-bc36-e3f8acdab77f.png)

# Write a Java program to find the number of days in a month.

## Program:
```
import java.util.Scanner;
public class Days{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
        System.out.print("Enter the month in number:");
        int month=sc.nextInt();
        switch(month)
        {
            case 1:
            case 3:
            case 5:
            case 7:
            case 8:
            case 10:
            case 12:
                System.out.print("\nThis month has 31 days.");
            break;
            case 4:
            case 6:
            case 9:
            case 11:
                System.out.print("\nThis month has 30 days.");
            break;
            case 2:
                    System.out.print("\nThis month has 28 days.");
            break;
            default:
                System.out.print("Enter a valid number of the month.");
        }
    }
}
```

## Output:

![Screenshot (245)](https://user-images.githubusercontent.com/127576283/224526447-26dfe561-a62d-4880-9020-96c2d460e4a4.png)


# Write a Java program to print the even numbers from 1 to 20.

## Program:
```
public class EvenNumber{
    public static void main(String[] args){
        System.out.print("The even numbers from 1 to 20 are listed below:");
        int i;
        for(i=1;i<=20;i++)
        {
            if(i%2==0)
            {
                System.out.print("\n"+i);
            }
        }
    }
}

```

## Output:

![Screenshot (246)](https://user-images.githubusercontent.com/127576283/224526465-4333d40e-8b33-4c84-b687-0435b6a786d9.png)

# Write a Java program to create a simple calculator.

## Program:
```
import java.util.Scanner;
public class Calculator{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
        System.out.println("Enter the numbers for calculations:");
        int num1=sc.nextInt();
        int num2=sc.nextInt();
        int result;
        System.out.print("Enter the choice for doing your operation:");
        System.out.print("\n1.Addition.\n2.Subtraction.\n3.Multiplication\n4.Division.\n");
        int choice=sc.nextInt();
        switch(choice)
        {
            case 1:
                result=num1+num2;
                System.out.print("\nTh resultant of the addition operation is: "+result);
            break;
            case 2:
                result=num1-num2;
                System.out.print("\nTh resultant of the subtraction operation is: "+result);
            break;
            case 3:
                result=num1*num2;
                System.out.print("\nTh resultant of the multiplication operation is: "+result);
            break;
            case 4:
                result=num1/num2;
                System.out.print("\nTh resultant of the division operation is: "+result);
            break;
            default:
            System.out.print("\n Enter a valid operation to be performed.");
        } 
    }
}
```
## OUTPUT:

![calculator](https://user-images.githubusercontent.com/103128410/224522165-3ec79bc9-50b2-4e93-b4d2-f4961dd1a8c9.png)


# Write a Java program to print multiplication table of given number.

## Program:
```
import java.util.Scanner;
public class Tab{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the number for which the table has to generated: ");
        int num=sc.nextInt();        
        for(int i=1;i<=10;i++)
        {
            System.out.print(num+"x"+i+"="+num*i);
            System.out.print("\n");
        }
    }
}
```

## Output:

![Screenshot (247)](https://user-images.githubusercontent.com/127576283/224526477-961fd6ee-3d21-492f-8e88-1cda9e3dcf70.png)
