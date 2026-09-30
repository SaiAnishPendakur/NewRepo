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
   // Create variables
int myNum = 5;             // Integer (whole number)
float myFloatNum = 5.99;   // Floating point number
char myLetter = 'D';       // Character

// Print variables
printf("%d\n", myNum);
printf("%f\n", myFloatNum);
printf("%c\n", myLetter);

   printf("\nSize of Double Type is %ld in Bytes", sizeof(double));
   printf("\nSize of Double Type is %ld in Bytes", sizeof(d));
   float myFloatNum = 3.5;

printf("%f\n", myFloatNum);   // Default will show 6 digits after the decimal point
printf("%.1f\n", myFloatNum); // Only show 1 digit
printf("%.2f\n", myFloatNum); // Only show 2 digits
printf("%.4f", myFloatNum);   // Only show 4 digits

   return 0;
}
