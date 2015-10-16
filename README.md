#include <stdio.h>
int main()
{
    int n, count;
    int factorial=1;
    scanf("%d",&n);
    if ( n< 0)
        printf("0");
    else
    {
       for(count=1;count<=n;++count)    
       {
          factorial*=count;             
       }
    printf("%d",factorial);
    }
    return 0;
}
