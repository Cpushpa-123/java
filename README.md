# java
program to convert minutes into no .of years and days
import java.util.*;
public class Test
{
public static void main (String[]args)
{
Scanner s=new Scanner(System.in);
int a;
a=s.nextInt();
int years,days,b,c;
b=60*24*365;
years=a/b;
System.out.print(years+"years");
a=a-(years*b);
c=60*24;
days=a/c;
System.out.print("and"+days+"days");
}
}


