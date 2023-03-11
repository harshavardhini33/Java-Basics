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


## 2. Write a Java program to compare two numbers
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

## 3. Write a Java program to convert a string to an integer
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        String harsha = ("143");
        int vardhini = Integer.parseInt(harsha);
        System.out.println(vardhini);

    }
}
```

## Output;

## 4. Java Program to find area of rhombus
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner haha = new Scanner(System.in);
        int a = haha.nextInt();
        int b = haha.nextInt();
        int c = (a*b)/2;
        System.out.println(c);
    }
}
```

## Output:

##  5. Write a Java program to find the number of days in a month
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int month=s.nextInt();
        int year=s.nextInt();
        if((month==1)||(month==3)||(month==5)||(month==7)||month==8||month==10||month==12)
        {
            System.out.println("This month has 31 Days.");
        }
        else if((month==4)||(month==6)||(month==9)||(month==11))
        {
            System.out.println("This month has 30 Days.");
        }
        else
        {
            if ((year % 400 == 0) || ((year % 4 == 0) && (year % 100 != 0)))
            {
                System.out.println("This month has 29 Days.");
            }
            else
            {
                System.out.println("This month has 28 Days.");
            }

        }
    }
}
```

## Output:

## 6. Write a Java program to print the even numbers from 1 to 20
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        int i;
        for(i=1;i<=20;i++)
        {
            if(i%2 == 0)
            {
                System.out.println(i+"\t");
            }
        }
    }
}
```

## Output:

## 7. Write a Java program to create a simple calculator
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        System.out.println("Enter Choice(1-add,2-sub,3-div,4-mul");
        Scanner s = new Scanner(System.in);
        int choice = s.nextInt();
        System.out.println("Enter 1st number: ");
        int a = s.nextInt();
        System.out.println("Enter 2nd number: ");
        int b = s.nextInt();
        switch(choice)
        {
            case 1:
            {
                System.out.println(a+b);
                break;
            }
            case 2:
            {
                System.out.println(a-b);
                break;
            }
            case 3:
            {
                System.out.println(a/b);
                break;
            }
            case 4:
            {
                System.out.println(a*b);
                break;
            }
            default:
            {
                System.out.println("Enter choice range btw 1-4");
                break;
            }
        }
    }
}
```

## Output:

## 8. Write a Java program to print multiplication table of given number
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        System.out.print("Enter a number: ");
        Scanner s = new Scanner(System.in);
        int a = s.nextInt();
        for(int i=1;i<=10;i++)
        {
            System.out.println(a+ " * " +i+ " = " +(a*i));
        }
    }
}
```
## Output:


