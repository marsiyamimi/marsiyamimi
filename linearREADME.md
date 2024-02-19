#include<stdio.h>
int main()
{
    int arr[100]= {0},n,i,key;

    printf("Enter the element :");
    scanf("%d",&n);

    printf("Enter the array value: ");
    for(i=0; i<=n; i++)
    {

        scanf("%d",&arr[i]);
    }

    printf("Enter the key value :");
    scanf("%d",&key);

    for(i=0; i<=n; i++)
    {

        if(arr[i]==key)
        {
            printf("find the key value of %d in %d index",key,i);
            break;
        }
    }
    if(i=n)
    {
        printf("Not found");

    }

}
