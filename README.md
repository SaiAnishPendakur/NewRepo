#include <stdio.h>

int main() {
  printf("SJCE college");
  scanf("sjce collge")
  return 0;
}
second code
#include <stdio.h>

int main() {
  printf("Hello World!\n");
  printf("I am learning C.");
  return 0;
}
#include <stdio.h>

int main() {
  // Create integer variables
  int length = 4;
  int width = 6;
  int area;

  // Calculate the area of a rectangle
  area = length * width;

  // Print the variables
  printf("Length is: %d\n", length);
  printf("Width is: %d\n", width);
  printf("Area of the rectangle is: %d", area);

  return 0;
}
#include <stdio.h>
#include <stdlib.h>
int main()
{
   int x, y, z, temp;

   system("clear");
  
   printf("Enter the values for x, y and z: ");
   scanf("%d %d %d", &x, &y, &z);

   printf("Values of x, y and z Before Rotation\n");
   printf("Value of X is %d\n", x );
   printf("Value of Y is %d\n", y );
   printf("Value of Z is %d\n", z );
 
   temp = x ;
   x = y ;
   y = z ;
   z = temp ;

   printf("Values of x, y and z After Rotation\n");
   printf("Value of X is %d\n", x );
   printf("Value of Y is %d\n", y );
   printf("Value of Z is %d\n", z );

   return 0;
}
/* Write a program to print the size of various data types in C using ‘sizeof’ operator. */

#include <stdio.h>
#include <stdlib.h>

int main()
{
   char ch;
   int i;
   float f;
   double d;

   system("clear");
   printf("\nSize of Character Type is %ld in Byte(s)", sizeof(char));
   printf("\nSize of Character Type is %ld in Byte(s)", sizeof(ch));

   printf("\nSize of Integer Type is %ld in Byte(s)", sizeof(int));
   printf("\nSize of Integer Type is %ld in Byte(s)", sizeof(i));

   printf("\nSize of Float Type is %ld in Bytes", sizeof(float));
   printf("\nSize of Float Type is %ld in Bytes", sizeof(f));

   printf("\nSize of Double Type is %ld in Bytes", sizeof(double));
   printf("\nSize of Double Type is %ld in Bytes", sizeof(d));

   return 0;
}
