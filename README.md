#include<stdio.h>
void main()
{
float x,p,n,s=0.0;
scanf("%f%f",&x,&p);
n=x;
if(x>=0 && x<=10000)
{
 if(p>=1 && p<=100)
 {
  while(x>p)
  {
   a=x-(x*(p/100));
   s=s+a;
   x=a;
  }
printf("%f",s+n);
printf("\n_________________");
 }
}
}

