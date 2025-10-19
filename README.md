# Program-2D
C module 2
EX NO-2)D)a c program to find the sum of digits using while loop without using modulus operator
DATE:19/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a c program to find the sum of digits using while loop without using modulus operator
ALGORITHM:1)take a number as input from the user 2)traverse the digits using modulus operator.3)add the digits using while loop 4) print the output using printf() function.
PROGRAM:
```
#include<stdio.h>
int main()
{
    int n,sum=0,digit;
    scanf("%d",&n);
    while(n>0)
    {
        digit=n-(n/10)*10;
        sum+=digit;
        n/=10;
    }
    printf("%d",sum);
    
}
```
OUTPUT:
<img width="969" height="230" alt="Screenshot 2025-10-19 204441" src="https://github.com/user-attachments/assets/ffd54bb6-8101-40a3-94e5-d32d8bfe944e" />
RESULT:
Thus,a c program to find the sum of digits using while loop without using modulus operator has been successfully executed.
