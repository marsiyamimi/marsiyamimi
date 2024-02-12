#include<stdio.h>
int gcd(int,int);
int main(){
int a,b;
printf("Enter the value of a:");
scanf("%d",&a);
printf("Enter the value of b:");
scanf("%d",&b);
int result=gcd(a,b);
printf("Result of GCD:%d",result);

}
int gcd(int m,int n){
   if(m%n==0)
    return n;
   else
    return gcd(n,m%n);
}
