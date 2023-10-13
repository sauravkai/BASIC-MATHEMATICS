#include<stdio.h>
#include<math.h>
#include<stdlib.h>

int main()
{
  float a,b,sum,division,multi,sub,remainder;
  printf("a = ");
  scanf("%f",&a);
  printf("b = ");
  scanf("%f",&b);
  sum=a+b;
  division=a/b;
  multi=a*b;
  sub=a-b;
  printf("sum = %f \n",sum);
  printf("division = %f \n",division);
  printf("multi = %f \n",multi);
  printf("sub = %f \n",sub);
return 0;
}
