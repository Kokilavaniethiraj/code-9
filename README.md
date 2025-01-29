# code-9
Max value in an array

#include <stdio.h>

int main()
{
    int n, i,max;
    printf("enter the no of elements:");
    scanf("%d",&n);
     int arr[n];
    printf("Enter  %d elements\n",n);
    for(i=0;i<n;i++){
        scanf("%d",&arr[i]);
    }
     max=arr[0];
    for(i=0;i<n;i++){
        if(arr[i]>max){
            max=arr[i];
        }
    }
    printf("The largest elements is %d\n",max);
    return 0;
}
