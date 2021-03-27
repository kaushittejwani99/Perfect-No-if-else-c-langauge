# Perfect-No-for-loop-if-else-c-langauge
This program is check whether a given no is Perfect or not using for loop and  if -else.
#include<stdio.h>
#include<conio.h>
int main()
{
    int i,num,sum=0;
    clrscr();
    printf("Enter any no:-\n");
    scanf("%d",&num);
    for( i=1;i<=num;i++)
    {
	       if(i%num==0)
	        sum+=i;
    }
    if(sum==num)
    printf("%d is a perfect no.",num);
    else
    printf("%d is  not a perfect no.",num);
    getch();
    return 0;
}
