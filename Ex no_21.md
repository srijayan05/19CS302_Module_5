# EX 21 C program to calculate the area of a triangle using pointer.
## DATE: 
## Aim:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm:
1. Start.
2. Declare three variable value of type float.
3. Prompt the user to enter values.
4. Read the values using scanf.
5. Find the area of triangle using formula
6. End  

## Program:
```
#include <stdio.h>
int main()
{
 float base, height, area;
 float *pBase = &base, *pHeight = &height;
 scanf("%f", pBase);
 scanf("%f", pHeight);
 area = 0.5 * (*pBase) * (*pHeight);
 printf("Area of Triangle is:%.2f\n", area);
}

```
## Output:
![Screenshot 2025-05-07 085552](https://github.com/user-attachments/assets/22c6dc79-9fe1-4464-8d34-8e7a491a9310)


## Result:
Thus the program was executed and the output was verified successfully.
