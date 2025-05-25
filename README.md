# pattern-with-asterisk.c
//  C program to  print pattern of asterisk      *    ***   *****  ******* *********  
//  C program to  print pattern of asterisk

    *
   ***
  *****
 *******
*********

#include <stdio.h>
int main() {
     int i,j;
    for(i=0;i<5;i++)
    {
        for(j=0;j<=3-i;j++)
         printf(" ");
         for(j=0;j<=2*i;j++)
         printf("*");
        printf("\n");
    }
    return 0;
}
