#include <stdio.h>
#include <stdlib.h>
struct employees
{
char name[20];
float id[20];
float experience[2];
float salary[8];
};
int main()
{
struct Employees n[5];
int i=0;
for(i=0;i<5;i++)
{
    printf("\nEnter name of employee%d:",i+1);
    scanf("%s",&n[i].name);
    printf("\nEnter id of employee%d:",i+1);
    scanf("%f",&n[i].id);
    printf("\nEnter experience of employee%d:",i+1);
    scanf("%f",&n[i].experience);
    printf("\nEnter salary of employee%d:",i+1);
    scanf("%f",&n[i].salary);
}
printf("\nEmployee Details");
for(i=0;i<5;i++);
{
printf("\nEmployee Number %d",i+1);
printf("\nName of employee: %s",n[i].name);
printf("\nID of employee: %f",n[i].id);
printf("\nExperience of employee: %f",n[i].experience);
printf("\nSalary of employee: %f",n[i].salary);
}
return 0;
}
