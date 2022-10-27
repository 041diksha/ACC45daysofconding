
#include<stdio.h>

#include<conio.h>

void main()

{
clrscr();

int a,b,c,d;

printf("\n Enter two Nos.:");

scanf("%d %d",&a,&b);

c = a+b;

printf("Sum of two numbers: %d",c);

c = a-b;

printf("Difference of two numbers: %d",c);

c = a*b;

printf("Multiplication of two numbers: %d",c);

c = a/b;

d = a%b;

printf("After division of two numbers, result with remainder is:%d %d",c,d);

getch();

}
