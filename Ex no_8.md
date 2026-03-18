# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1. Define functions to input numbers and return them.
2. Create functions to perform multiplication and division using these inputs.
3. In main, call multiplication function and store the result.
4. Call division function and store the result.
5. Display both multiplication and division results.
 

## Program:
```
/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
Developed by: Thikazhmanibala.K
RegisterNumber: 212222060277
#include<stdio.h>
int mul(int a,int b)
{
    int c;
    c=a*b;
    return c;
}
int div(int a,int b)
{
    int d;
    d=a/b;
    return d;
}
int main()
{
    int a,b,e,f;
    scanf("%d %d",&a,&b);
    e=mul(a,b);
    f=div(a,b);
    printf("Multiplication: %d",e);
    printf("\nDivision: %d",f);
}
*/
```

## Output:
<img width="837" height="247" alt="image" src="https://github.com/user-attachments/assets/ecc59af7-890f-4758-92e9-27d26bac22f8" />




## Result:
Thus the program was executed and the output was verified successfully.
