# EX 25 C program to check whether a given character is a vowel or consonant using pointer
## DATE: 
## Aim:
To write a C program to check whether a given character is a vowel or consonant using pointer

## Algorithm:
1. Start.
2. Declare a variable value of type char.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Find vowel and consonants
6. End.

## Program:
```
#include<stdio.h>
int main()
{
    char a,*ptr1;
    scanf("%c",&a);
    ptr1=&a;
    if(a=='a'||a=='e'||a=='i'||a=='o'||a=='u'||a=='A'||a=='E'||a=='I'||a=='O'||a=='U')
    {
        printf("%c is Vowel.",*ptr1);
    }
    else
    printf("%c is consonant.",*ptr1);
}
```

## Output:
![Screenshot 2025-05-07 092413](https://github.com/user-attachments/assets/02c37426-4b4a-4be2-9094-d7478943d506)

## Result:
Thus the program was executed and the output was verified successfully.
