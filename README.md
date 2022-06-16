#include <stdio.h>
int main()
{
  printf("Average Calculation\n");
  float a,b,c,d,e,sum,avg;
  printf("Enter Physics Marks : ");
  scanf("%f",&a);
  printf("Enter Chemistry Marks : ");
  scanf("%f",&b);
  printf("Enter Maths Marks : ");
  scanf("%f",&c);
  printf("Enter Computer Science Marks : ");
  scanf("%f",&d);
  printf("Enter English Marks : ");
  scanf("%f",&e);
  sum=a+b+c+d+e;
  avg=sum/5;
  printf("Average : %f",avg);
  return 0;
 }
