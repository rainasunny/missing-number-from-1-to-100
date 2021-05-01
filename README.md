# missing-number-from-1-to-100
#include <stdio.h>
 int main()
{
    int i,a[100],n=100,tot=0,sum=0;
    tot = (n*(n+1))/2;
    printf("Enter the numbers into the array one by one : ");
    for(i=0 ; i<99; i++){
        scanf("%d",&a[i]);
     sum = sum + a[i];
    }
    printf("Missing number is %d",tot-sum);
    return 0;
}
