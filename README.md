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
![op1](https://user-images.githubusercontent.com/93427594/224527489-d5af3d53-e78f-451f-b6e6-8cbfd101ad67.png)### 2.Write a Java program to compare two numbers.
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
### Output:
![op2](https://user-images.githubusercontent.com/93427594/224527526-010e6fb8-795f-4610-95ba-83f3905af565.png)

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
### Output:
![opstring](https://user-images.githubusercontent.com/93427594/224527542-da86b56b-c638-4c0d-95cb-1c4c54bfd1aa.png)

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
 ### O/p:
 ![area](https://user-images.githubusercontent.com/93427594/224527955-3e361183-d4a0-4b44-afdc-7f7ff15df98b.png)

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
 ### O/p:
 ![month](https://user-images.githubusercontent.com/93427594/224527975-40d8674d-bff8-4710-93f3-be018df39785.png)

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
 ### O/p:
 ![even](https://user-images.githubusercontent.com/93427594/224527992-d1601b38-2aae-47f7-9215-2d72ead36c08.png)
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
### O/p:
![cal](https://user-images.githubusercontent.com/93427594/224528003-0f9a1303-1251-4887-8e6a-cf7bdae1b873.png)

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
### O/p:
![tab](https://user-images.githubusercontent.com/93427594/224528012-39aadd57-40d1-4182-a010-6864054dcc22.png)





