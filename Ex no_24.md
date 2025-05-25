# EX 24 Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).
## DATE: 
## Aim:
To Create a structure program to read(empno,dept and basic pay) and store the data of 3 employees and calculate their Gross Salary(da =10% and HRA=30% from BP).

## Algorithm:
1. Start.
2. Define a variables.
3. Create a structure program to read(empno,dept and basic pay) and store the data of 3
employees and calculate their Gross Salary(da =10% and HRA=30% from BP).
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

## Program:
```
#include<stdio.h>
struct emp
{
    int n;
    int c;
    char dept[10];
};
int main()
{
    int i;
    struct emp e[3];
    printf("Details of the Employee: \n");
    for(i=0;i<3;i++)
    {
        scanf("%d%s%d",&e[i].n,e[i].dept,&e[i].c);
    }
    for(i=0;i<3;i++)
    {
        int q=e[i].c/10;
        int y=q*3;
        float tot=(e[i].c)+q+y;
        printf("%d %s %d %d %d %.2f\n",e[i].n,e[i].dept,e[i].c,q,y,tot);
    }
    return 0;
}
```
## Output:
![Screenshot 2025-05-07 092022](https://github.com/user-attachments/assets/3be925e9-e486-4464-9e11-839c8aabd77e)

## Result:
Thus the program was executed and the output was verified successfully.
