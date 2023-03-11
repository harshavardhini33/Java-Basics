# JAVA BASICS - WEEK 01 ASSIGNMENT
## 1. Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int a,b,c;
        Scanner num = new Scanner(System.in);
        a = num.nextInt();
        b = num.nextInt();
        c = a+b;
        System.out.println(a+"+" +b+ "=" +c );
        System.out.println("multiply of two numbers: " +(a*b));
        System.out.println("Subtraction of two numbers: " +(a-b));
        System.out.println("Division of two numbers: " +(a/b));
        System.out.println("Remainder of two numbers: " +(a%b));
    }
}

```
## Output:
![Uploading pic 01.png…]()

##  Write a Java program to compare two numbers
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int a,b;
        Scanner num = new Scanner(System.in);
        a = num.nextInt();
        b = num.nextInt();
        if(a>b) {
            System.out.println("a is greater");
        } else if (a==b) {
            System.out.println("both are equal");
        } else {
            System.out.println("b is greater");
        }
    }
}
```
## Output:

