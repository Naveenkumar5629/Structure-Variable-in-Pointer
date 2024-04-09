# Structure-Variable-in-Pointer
#include<stdio.h>
struct student{
    int roll;
    char a[20];
    float marks;
};
int main(){
    struct student st1={1,"anbu",75.23};
    struct student *ptr;
    ptr=&st1;
    //scanf("%d%s%f",&st1.roll,&st1.a,&st1.marks);
    printf("%d%s%f",ptr->roll,ptr->a,ptr->marks);
    return 0;
}
