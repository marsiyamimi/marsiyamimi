#include<stdio.h>
int fact(int x,int i=1){
    if(x==i)
        return x;
    return i*fact(x,i+1);
}

int main(){
int n,i;
printf("Factorial of n :");
scanf("%d",&n);
int result =fact(n);
printf("Result of factorial is :%d",result);
}

