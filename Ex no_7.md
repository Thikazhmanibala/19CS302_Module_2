# EX 7 C Program to Print binary number pattern of n rows and m columns using loop.
## AIM:
To write a C Program to Print binary number pattern of n rows and m columns using loop.

## Algorithm
1. Read number of rows and columns from the user.
2. Use an outer loop to repeat for each row.
3. Inside the outer loop, use an inner loop to print '*' for each column.
4. After each row, print a newline to move to the next row.
5. End the program.


## Program:
```
/*
Program to Print binary number pattern of n rows and m columns using loop.
Developed by: Thikazhmanibala.K
RegisterNumber:  212222060277
#include <stdio.h>
int main() 
{
    int a,b,i,j;
    scanf("%d %d",&a,&b);
    for(i=0;i<a;i++)
    {
      for(j=0;j<b;j++)
      {
         printf("*");
      }
      printf("\n");
    }
    
    return 0;
}
*/
```

## Output:


<img width="1001" height="286" alt="Screenshot 2026-03-18 220215" src="https://github.com/user-attachments/assets/0f844a92-291a-4c39-9ca9-0c91e5cd6978" />



## Result:
Thus the program was executed and the output was verified successfully.
