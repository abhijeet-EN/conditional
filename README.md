# conditional
//Check whether a number is positive or negative.
#include<stdio.h>
int main ()
{
    int num;
    printf("Enter the number ");
    scanf("%d",&num);
    if (num<0)
    {
        printf("number is negative");
    }
    else
    {
        printf("number is positive");
    }
return 0;
}
Check whether a number is even or odd.
#include<stdio.h>
int main ()
{
    int num;
    printf("Enter the number :");
    scanf("%d",&num);
    if (num%2==0)
    {
        printf("number is even ");
    }
    else
    {
        printf("number is odd");
    }
return 0;
}

3. Find the greater of two numbers.
#include<stdio.h>
int main ()
{
    int num1,num2;
    printf("Enter the number 1:");
    scanf("%d",&num1);
    printf("Enter the number 2:");
    scanf("%d",&num2);
    if (num1<num2)
    {
        printf("number 2 is grater");
    }
    else 
    {
        printf("number 1 is grater ");
    }
    return 0;
}

Check whether a number is divisible by both 3 and 7.

#include<stdio.h>
int main ()
{
    int num;
    printf("Enter the number :");
    scanf("%d",&num);
    if (num%3==0 && num%7==0)
    {
        printf("divisiale by 7and 3");
    }
    else
    {
        printf("not divisiable");
    }
return 0;
}

Check whether a character is a vowel or consonant.#incomplete
#include<stdio.h>
void main ()
{
    char ch;
    printf("Enter the charcter :");
    scanf("%c",&ch);
    printf("%c",sizeof(ch));
    if (ch=="a");
    {
        printf("charcter is vovel ");
    }
    else
    {
        printf("charcter is consonet");
    }
}

Find the absolute value of a number.
#include<stdio.h>
int main()
{
    int n;
    printf("Enter the number :");
    scanf("%d",&n);
    if (n>0)
    {
        n=-n;
        printf("absolute value is : %d",n);
    }
    else 
    {
        printf("not absolute");
    }
    return 0;
}/

Determine whether a number is a multiple of 10.
#include<stdio.h>
int main()
{
    int num;
    printf("Enter the number :");
    scanf("%d",&num);
    if(num%10==0)
    {
        printf("number is multiple");
    }
    else
    {
        printf("number is not multiple");
    }
    return 0;
}

Find the roots of a quadratic equation.# important answer
#include<stdio.h>
#include<math.h>
int main()
{
    float a,b,c,discriminant;
    float root1,root2,realPart,imagPart;
    printf("Enter the value of a,b,c :");
    scanf("%f %f %f",&a,&b,&c);
    discriminant=((b*b)-4*a*c);
    if (discriminant >0)
    {
        root1 = (-b + sqrt(discriminant)) / (2 * a);
        root2 = (-b - sqrt(discriminant)) / (2 * a);
        printf("root1 = %f and root2 = %f\n", root1, root2);
    }
    else if(discriminant==0)
    {
        root1 = root2 = (-b / (2 * a));
        printf("root1 = root2 = %f\n", root1);
    }
    else
    {
         realPart =( -b / (2 * a));
        imagPart = sqrt(-discriminant) / (2 * a);
        printf("root1 = %f + %fi \n and root2 = %f - %fi\n", realPart, imagPart, realPart, imagPart);
    }
    return 0;
}

Check whether a number is a three-digit number.
#include<stdio.h>
int main ()
{
    int num;
    printf("Enter the number :");
    scanf("%d",&num);
    if (num>=100 && num<=999|| num<=-100 && num=-990)
    {
        printf("number is three digit number ");
    }
    else 
    {
        printf("number is not three digit number ");
    }
return 0;
}

21. Determine whether a year is a century year.
#include<stdio.h>
int main ()
{
    int year;
    printf("enter the year :");
    scanf("%d",&year);
    if(year%100==0)
    {
        printf("year is a century year");
    }
    else
    {
        printf("year is not century year");
    }
    return 0;
}

Check whether a character is a digit or alphabet.
#include<stdio.h>
void main ()
{
    char ch;
    printf("Enter the charcter :");
    scanf("%c",&ch);
    if ((ch >= 'a' && ch <= 'z') || (ch >= 'A' && ch <= 'Z'))
    {
        printf("charcter is a alphabet");
    }
    else
    {
        printf("charcter is not alplhabet ");
    }
}

Find the middle number among three numbers.
#include<stdio.h>
int main ()
{
    int a,b, c;
    printf("Enter the number 1 :");
    scanf("%d",&a);
    printf("Enter the number 2 :");
    scanf("%d",&b);
    printf("Enter the number 3 :");
    scanf("%d",&c);
    if (a<b&&b<c || b<c && b>a )
    {
        printf("b is middle :%d",b);
    }
    else if ((b < c && c < a) || (a < c && c < b))
    {
        printf("c is middle :%d",c);
    }
     else if ((c < a && a < b) || (b < a && a < c))
    {
        printf("a is middle :%d",a);
    }
    else 
    {
        printf("All equal");
    }
    return 0;
}

Find the smallest among three numbers.
#include<stdio.h>
 int main ()
{
   int a,b, c;
    printf("Enter the number 1 :");
    scanf("%d",&a);
    printf("Enter the number 2 :");
    scanf("%d",&b);
    printf("Enter the number 3 :");
    scanf("%d",&c);
    if (a<b && a<c)
    {
        printf("smallest number is a : %d",a);
    }
    else if (b<a&&b<c)
    {
        printf("smallest number is b :%d",b);
    }
    else 
    {
        printf("smallest number is c :%d",c);
    }
return 0;
}

Display month names using switch.
#include<stdio.h>
int main ()
{
    int month;
    printf("Enter the month no 1 to 12 :");
    scanf("%d",&month);
    switch(month)
    {
        case 1:
        printf("january");
        break;
        case 2:
        printf("febuary");
        break;
        case 3:
        printf("march");
        break;
        case 4:
        printf("april");
        break;
        case 5:
        printf("may");
        break;
        
        case 6:
        printf("june");
        break;
        case 7:
        printf("july");
        break;
        
        case 8:
        printf("augest");
        break;
        
        case 9:
        printf("september");
        break;
        case 10:
        printf("octomber");
        break;
        case 11:
        printf("november");
        break;
        case 12:
        printf("december");
        break;
        default:
        printf("invalid value");

    }
    return 0;
}

Create a simple calculator using switch.
#include<stdio.h>
int main ()
{
    char op;
    printf("Enter the opretor :");
    scanf("%c",&op);
    int num1,num2;
    printf("Enter the number1:");
    scanf("%d",&num1);
    printf("Enetr the number 2 :");
    scanf("%d",&num2);
    switch(op)
    {
        case '+':
        printf("%d",num1+num2);
        break;
        case '-':
        printf("%d",num1-num2);
        break;
        case '*':
        printf("%d",num1*num2);
        break;
        case '/':
        printf("%d",num1/num2);
        break;
        default:
        printf("Invalid charcter");
    }
    return 0;
}

Check whether a character is a vowel using switch.
#include<stdio.h>
int main ()
{
    char ch;
    printf("Enter the charcter :");
    scanf("%c",&ch);
    switch(ch)
    {
        case 'a':
        case 'e':
        case 'i':
        case 'o':
        case 'u':
        case 'A':
        case 'E':
        case 'I':
        case 'O':
        case 'U':
        printf("charcter is vovel ");
        break;
        default:
        printf("number is consonant");

    }
    return 0;
}

31. Find maximum using nested if.
#include<stdio.h>
int main ()
{
    int num1,num2, num3;
    printf("Enter the number 1:");
    scanf("%d",&num1);
    printf("Enter the number 2:");
    scanf("%d",&num2);
    printf("Enter the number 3:");
    scanf("%d",&num3);
    if (num1>num2)
    {
        if (num1>num3)
        {
            printf("Number 1 is max");
        }
        else
         {
            printf("Number 3 is max");
         }
    }
    else if (num2>num1) 
    {
        if (num2>num3)
        {
            printf("Number 2 is max ");
        }
        else 
        {
            printf("number 3 is max ");
        }
    }
 return 0;
}

Find minimum using nested if.
#include<stdio.h>
int main ()
{
    int a,b,c;
    printf("Enter the number 1 A=");
    scanf("%d",&a);
    printf("Enter the number 2 B=");
    scanf("%d",&b);
    printf("Enter the number 3 C=");
    scanf("%d",&c);
    if (a<b)
    {
        if (a<c)
        {
            printf("number 1 is small ",a);
        }
        else 
        {
            printf("number 3 is small ");
        }
    }
    else if (b<a)
    {
        if (b<c)
        {
            printf("b is small");
        }
        else 
        {
            printf("c is small ");
        }
    }
    return 0;
}

Check whether a year is a leap year using nested if.
#include<stdio.h>
int main ()
{
    int year;
    printf("Enter the year :");
    scanf("%d",&year);
    if (year%4==0)
    {
        if (year%100==0)
        {
            if (year%400==0)
            {
                printf("year is a leap year .");
            }
            else 
            {
                printf("year is not leap year.");
            }
        }
        else 
        {
            printf("%d year is leap year ",year);
        }
    }
    else 
    {
        printf("year is not leap year .");
    }
 return 0;
}

 Find the sum of digits of a number.
 #include <stdio.h>
#include <stdlib.h> // Used for abs() to handle negative numbers
int main ()
{
    int num ,sum=0,reverse;
    printf("Enter the number :");
    scanf("%d",&num);
    reverse=abs(num);
    if (num>0)
    {
        sum=(num+sum)%10;
        num/=10;
    }
    if (num>0)
    {
        sum =(num+sum)%10;
        num/=10;
    }
    printf("%d",sum);
}
 
