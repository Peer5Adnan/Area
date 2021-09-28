# Area
import java.util.Scanner;
public class Area {
    public static void main(String args[])
    {
    double a;
    System.out.println("enter the area of circle ");
    Scanner obj = new Scanner(System.in);
    a=obj.nextInt();
    double pi;
    pi=3.14;
    double res;
    res=pi*(a*a);
System.out.println("the area is "+res);
}
}
