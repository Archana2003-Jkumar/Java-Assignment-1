# Java-Assignment-1
```
Name : J.Archana priya 
Dept : AI-DS
```
## PROGRAMS
### 1. Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner sc= new Scanner(System.in);
        int n= sc.nextInt();
        int m= sc.nextInt();
        int add=m+n;
        System.out.println("ADD :"+add);
        int subb=n-m;
        System.out.println("Sub :"+subb);
        int  mul1=n*m;
        System.out.println("Mul :"+mul1);
        int div1=n/m;
        System.out.println("Div :"+div1);
    }
}
```
### Output:
![op1](./op1.png)
### 2.Write a Java program to compare two numbers.
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner sc= new Scanner(System.in);
        int m= sc.nextInt();
        int n= sc.nextInt();
        if (m>n)
        {
            System.out.println("Greater :"+m);
        }
        
        else
            System.out.println("Greater :"+n);

    }
    
}
```
### 3. Write a Java program to convert a string to an integer.
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
     Scanner sc= new Scanner(System.in);
        String str = sc.nextLine();
        int i=Integer.parseInt(str);
        System.out.println(i);
    }
}
```
### 4..Java Program to find area of rhombus.
```
import java.util.Scanner;
public class Main{
    public static void main(String args[]){
     Scanner sc= new Scanner(System.in);
        int d1= sc.nextInt();
        int d2 = sc.nextInt();
        int area = (d1*d2)/2;
        System.out.println("Area : "+area);
       
    }}
 ```
 ### 5. Write a Java program to find the number of days in a month.
 ```
  Scanner sc= new Scanner(System.in);
     int month= sc.nextInt();
    int year= sc.nextInt();
     if (month ==2 &&  (year%4==0) || ((year%100==0)&&(year%400==0)))
       System.out.println("Leap year");
       else if(month==1 || month==3 || month==5 || month==7 || month==8 || month==10 || month==12)
      System.out.println("Number of days is 31");

     else
      System.out.println("Number of days is 30");
 ```
 ### 6. Write a Java program to print the even numbers from 1 to 20.
 ```
 import java.util.Scanner;
public class Main{
    public static void main(String args[]) {
        Scanner sc= new Scanner(System.in);
        int a= sc.nextInt();
        int b = sc.nextInt();
        int i;
        for(i=a;i<=b;i++)
        {
            if(i%2==0)
            {
                System.out.println(i+" ");
            }
        }
    }
 ```
### 7. Write a Java program to create a simple calculator.
```
import java.util.Scanner;
public class Main{
  public static void main(String args[]) {
      Scanner sc= new Scanner(System.in);
      System.out.println("1.Add" +
              "2.Subtract" +
              "3.Multiply" +
              "4.Divide");
      int ch = sc.nextInt();
      int n= sc.nextInt();
      int m= sc.nextInt();
      if(ch==1) {
          int add = m + n;
          System.out.println("ADD :" + add);
      }
      else if(ch==2) {
          int subb = n - m;
          System.out.println("Sub :" + subb);
      }
      else if (ch==3){
          int  mul1=n*m;
          System.out.println("Mul :"+mul1);
      }
     else if(ch==4) {
          int div1 = n / m;
          System.out.println("Div :" + div1);
      }


  }
  }
```
### 8. Write a Java program to print multiplication table of given number.
```
import java.util.Scanner;
public class Main {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        int i;
        int res;
        for(i=1;i<=10;i++)
        {
            res=i*num;
            System.out.println(res);
        }
    }
}
```




