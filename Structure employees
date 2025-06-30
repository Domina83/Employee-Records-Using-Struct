#include <stdio.h>
#include <stdlib.h>

struct Employee {
    char name[30];
    int empno;
    char dept_name[50];
    int salary;
};

int main()
{
    int i, n = 3;
    struct Employee employees[20];

    printf("Enter %d Employee Details\n\n", n);
    for(i = 0; i < n; i++)
    {
        printf("Employee %d:\n", i + 1);

        printf("Name: ");
        scanf("%s", employees[i].name);

        printf("Employee Number: ");
        scanf("%d", &employees[i].empno);

        printf("Department Name: ");
        scanf("%s", employees[i].dept_name);

        printf("Salary: ");
        scanf("%d", &employees[i].salary);

        printf("\n");
    }

    printf("------------ All Employees Details -------------\n");

    for(i = 0; i < n; i++)
    {
        printf("Name        : %s\n", employees[i].name);
        printf("Emp No      : %d\n", employees[i].empno);
        printf("Department  : %s\n", employees[i].dept_name);
        printf("Salary      : %d\n", employees[i].salary);
        printf("\n");
    }

    return 0;
}

