#include<stdio.h>
struct data{
    char *name;
    int rollno;
};
typedef struct data info;//Here struct data is aliasing as info
int main()
{
    info student;
    student.name= "Steve";
    student.rollno=66;
    
    printf("student Name:%s\n",student.name);
    printf("student roll number:%d ",student.rollno);
    return 0;
}
