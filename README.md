# githubtest

#include<stdio.h>
#include<stdlib.h>

int main(void)
{
    int i=0,sum;
    printf("Enter a number: ");
    scanf("%d",&i);
    for(i=0;i<5;i++)
    sum += sum + i;
    printf("sum: ",sum);
}