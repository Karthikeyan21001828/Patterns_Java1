# Patterns_Java1
## PROGRAM:
```
import java.util.Scanner;

public class Pattern
{
    public static void pattern1()
    {
        Scanner sc=new Scanner(System.in);
        int size = sc.nextInt();
        for (int i = 0; i < size; i++)
        {
            for (int j = 0; j < size; j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
    public static void pattern2()
    {
        Scanner sc=new Scanner(System.in);
        int rows = sc.nextInt();
        for (int i= 0; i<= rows-1 ; i++)
        {
            for (int j=0; j<=i; j++)
            {
                System.out.print(" ");
            }
            for (int k=0; k<=rows-1-i; k++)
            {
                System.out.print("*" + " ");
            }
            System.out.println();
        }
    }
    public static void pattern3()
    {
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
        for (int i = 1; i <= size; i++)
        {
            for (int j = 0; j < i; j++)
            {
                System.out.print("*");
            }
        System.out.println();
        }
        for (int i = 1; i <= size - 1; i++)
        {
            for (int j = 0; j < size - i; j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
    public static void main(String[] args)
    {
        pattern1();
        pattern2();
        pattern3();
    }
}

```
## OUTPUT:
![image](https://user-images.githubusercontent.com/93427303/224886706-f944ad9c-2197-4a3a-9535-040f0a2966cf.png)
