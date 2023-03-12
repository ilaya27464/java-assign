# JAVA_FULL_STACK.
```
Java Full Stack Assignment 1.
Developed by : Ashmi.S
Register number : 212221040021.

```


# 1)Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

## Program:
```
import java.util.Scanner;
public class MathOperation{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the numbers:");
int num1 =sc.nextInt();
int num2= sc.nextInt();
int sum=num1+num2;
System.out.println("Sum of two numbers: "+sum);
int sub=num1-num2;
System.out.println("Subtraction of two numbers: "+sub);
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
![MathOperations](https://user-images.githubusercontent.com/103128410/224521300-02c6b64f-ab4a-4346-bf47-2ba22238fad2.png)



# 2)Write a Java program to compare two numbers.

## Program:
```
import java.util.Scanner;
public class Comparison{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the numbers:");
int num1 =sc.nextInt();
int num2= sc.nextInt();
if(num1==num2)
{
    System.out.println("Both the numbers are equal.");
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

![comparison](https://user-images.githubusercontent.com/103128410/224521491-127f4db7-62b8-48ef-873e-b1a55e7a547d.png)



#  3)Write a Java program to convert a string to an integer.

## Program:
```
)import java.util.Scanner;
public class StringToInteger{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the string:");
        String str= sc.nextLine();
        int num= Integer.parseInt(str);
        System.out.println("The integer value of the string is: "+num);
    }
}
```

## Output:

![stringtoint](https://user-images.githubusercontent.com/103128410/224521631-f19a6d36-a336-4c61-8aad-c086623b5784.png)


# 4) Java Program to find area of rhombus.

## Program:
```
import java.util.Scanner;
public class AreaOfRhombus{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the first diagonal length(d1):");
        float d1= sc.nextFloat();
        System.out.println("Enter the second diagonal length(d2):");
        float d2= sc.nextFloat();
        float area=d1*d2/2;
        System.out.println("The area of the rhombus in sq. units: "+area);
    }
}
```

## Output:

![areaofrhombus](https://user-images.githubusercontent.com/103128410/224521814-ed8e1bd2-ac1a-4ee0-8b22-2881db766b3e.png)


# 5)Write a Java program to find the number of days in a month.

## Program:
```
import java.util.Scanner;
public class DaysInMonth{
    public static void main(String[] args){
        Scanner sc= new Scanner(System.in);
        System.out.print("Enter the month in number:");
        int month=sc.nextInt();
        System.out.print("Enter the year:");
        int year=sc.nextInt();
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
                if(year%4==0)
                {
                    System.out.print("\nThis month has 29 days.");
                }
                else
                {
                    System.out.print("\nThis month has 28 days.");
                }
            break;
            default:
                System.out.print("Enter a valid number of the month.");
        }
    }
}
```

## Output:

![daysinmonth](https://user-images.githubusercontent.com/103128410/224521944-4f40e3f5-50c6-4802-84b0-5ef8dfca70e2.png)


# 6)Write a Java program to print the even numbers from 1 to 20.

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

![evennumbers](https://user-images.githubusercontent.com/103128410/224522049-84e6ccdf-5e1f-4ce0-bdfe-7e263868abf2.png)

# 7) Write a Java program to create a simple calculator.

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


# 8) Write a Java program to print multiplication table of given number.

## Program:
```
import java.util.Scanner;
public class Tables{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the number for which the table has to generated: ");
        int num=sc.nextInt();
        System.out.print("Enter the limit for the table: ");
        int limit=sc.nextInt();
        for(int i=1;i<=limit;i++)
        {
            System.out.print(num+"x"+i+"="+num*i);
            System.out.print("\n");
        }
    }
}
```

## Output:

![tables](https://user-images.githubusercontent.com/103128410/224522251-dd528134-fd9c-4e0c-8e25-c26ae56c7ef5.png)
