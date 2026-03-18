# EX 9 C program to find the sum of odd digits using do while loop.
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Read a number from the user.
2. Initialize sum to 0.
3. Use a while loop to extract each digit (num % 10).
4. If the digit is odd, add it to sum.
5. Divide the number by 10 in each iteration and print the sum at the end.


## Program:
```
/*
Program to find the sum of odd digits using do while loop.
Developed by: Thikazhmanibala.K
RegisterNumber: 212222060277
#include <stdio.h>
int main()
{
    int i=1,n,sum=0;
    scanf("%d",&n);
    while(n>=i)
    {
        for(i=1;i<=n;i++)
        {
            if(i%2!=0)
            {
                sum=sum+i;
            }
        }
        i++;
        
    }
    printf("%d",sum);
    return 0;
}
*/
```

## Output:


![image](https://github.com/user-attachments/assets/e2a2c8f2-6c91-45f2-9cbd-89d5613bad7d)


## Result:
Thus the program was executed and the output was verified successfully.
