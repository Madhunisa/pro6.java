# pro6.java
import java.io.*;
import java.util.*;
public class leap
{
    public static void main(String args[])
    {
        Scanner s=new Scanner(System.in);
        int n=s.nextInt();
        if(n%4==0)
        {
            System.out.println("leap yr");
        }
        else
        {
            System.out.println("non leap yr");
        }
    }
}
