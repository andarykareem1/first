#include <stdio.h>

int main() {
  int x;
  float y, z;
  printf("Enter number of days:\n");
  scanf("%d",&x);
 y=x/365;
   z=x/7;
  if(x>0)
  {
  printf("the number of years is: %f\n",y);
    printf("the number of weeks is : %f\n",z);
  }
    else
  {
    printf("enter a positive number\n");
  }
  return 0;
}
