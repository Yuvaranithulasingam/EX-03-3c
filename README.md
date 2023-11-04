# EX-3(C)         POSITIVE ARRAY ELEMENTS

## AIM:
To create  a C program to read n elements as input and print the last element of the array (integer).

## ALGORITHM:
1. Start the program.
2. Read a variable.
3. Read the array values n number of times.
4. Print the last element.
5. Stop the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
int n,i,a[10];
scanf("%d",&n);
for(i=0;i<n;i++)
scanf("%d",&a[i]);
printf("%d",a[n-1]);
}
```

## OUTPUT:
![image](https://github.com/Yuvaranithulasingam/EX-03-3c/assets/121418522/e6f4db9b-e0d7-4a40-b28f-7ceb36a3dfa9)

## RESULT:
Thus the program to read n elements as input and print the last element of the
array has been executed successfully.
