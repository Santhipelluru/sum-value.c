#include<stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    int i=1,s=0;
    while(i<=n)
    {
        s+=i;
        i++;
    }
    printf("sum is: %d",s);
    }
