# EX 23 C program to store and display the name, id, age and salary of an employee using structure(using array of structure).
## Aim:
To write a C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## Algorithm:
1. Start.
2. Define a variables.
3. Write program to to store and display the name, id, age and salary of an employee
using structure(using array of structure).
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.  

## Program:
```
#include<stdio.h>
struct emp
{
    int id;
    char name[10];
    int age;
    int salary;
};
int main()
{
    struct emp e[n];
    int i,n;
    printf("Employee Details\n");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        scanf("%d%s%d%d",&e[i].id,e[i].name,&e[i].age,&e[i].salary);
    }
    for(i=0;i<n;i++)
    {
        printf("%d  %s  %d  %d\n",e[i].id,e[i].name,e[i].age,e[i].salary);
    }
}
```
## Output:
![Screenshot 2025-05-07 091417](https://github.com/user-attachments/assets/978c6dfd-9a53-453f-80e5-802cb6b2022c)


## Result:
Thus the program was executed and the output was verified successfully.
