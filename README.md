//# strcat.c//
#include<stdio.h>
#include<string.h>
int main()
{
    char a[20],b[20];
    printf("Enter first string:");
    scanf("%s",&a);
    printf("Enter second string:");
    scanf("%s",&b);
    strcat(a,b);
    puts(a);
}
