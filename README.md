#include<stdio.h>
#include<conio.h>
void main()
{
int i;
clrscr();
for(i=1;i<=100;i++)
{
if(i%3==0)
{if(i%15>0)
printf("fizz\t");}
if(i%5==0)
{if(i%15>0)
printf("buzz\t");}
if(i%3==0&&i%5==0)
{printf("fizzbuzz\t");}
else if(i%3!=0&&i%5!=0)
{printf("%d\t",i);}
}
getch();
}
