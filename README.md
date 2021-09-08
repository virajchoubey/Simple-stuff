# Simple-stuff
'#include <stdio.h>
#include <conio.h>
// Question - define a program to make a structure -
// containing - students name, class , rollno,marks1,marks2,marks3,etc
// write a program using a struct to read these values, calculate the total marks, the marks percentage and display the complete information on the screen.
struct student{
    char studname[50];
    int class;
    int rollno;
    int marks1;
    int marks2;
    int marks3;
    int totalmarks;
    int percentage;
};
struct student viraj,abhay,sandeep;
void main(){
    printf("Enter the name: \n");
    scanf("%s",viraj.studname);
    printf("\nEnter the class: \n");
    scanf("%d",&viraj.class);
    printf("\nEnter the rollno: \n");
    scanf("%d",&viraj.rollno);
    printf("\nEnter the marks of Physics: \n");
    scanf("%d",&viraj.marks1);
    printf("\nEnter the marks of chemistry: \n");
    scanf("%d",&viraj.marks2);
    printf("\nEnter the marks of maths: \n");
    scanf("%d",&viraj.marks3);
    viraj.totalmarks = (viraj.marks1+viraj.marks2+viraj.marks3);
    viraj.percentage=viraj.totalmarks/3; // since marks are outoff 100
    printf("Enter the name: \n");
    scanf("%s",abhay.studname);
    printf("\nEnter the class: \n");
    scanf("%d",&abhay.class);
    printf("\nEnter the rollno: \n");
    scanf("%d",&abhay.rollno);
    printf("\nEnter the marks of Physics: \n");
    scanf("%d",&abhay.marks1);
    printf("\nEnter the marks of chemistry: \n");
    scanf("%d",&abhay.marks2);
    printf("\nEnter the marks of maths: \n");
    scanf("%d",&abhay.marks3);
    abhay.totalmarks = (abhay.marks1+abhay.marks2+abhay.marks3);
    abhay.percentage=abhay.totalmarks/3; // since marks are outoff 100
    printf("Enter the name: \n");
    scanf("%s",sandeep.studname);
    printf("\nEnter the class: \n");
    scanf("%d",&sandeep.class);
    printf("\nEnter the rollno: \n");
    scanf("%d",&sandeep.rollno);
    printf("\nEnter the marks of Physics: \n");
    scanf("%d",&sandeep.marks1);
    printf("\nEnter the marks of chemistry: \n");
    scanf("%d",&sandeep.marks2);
    printf("\nEnter the marks of maths: \n");
    scanf("%d",&sandeep.marks3);
    sandeep.totalmarks = (sandeep.marks1+sandeep.marks2+sandeep.marks3);
    sandeep.percentage=sandeep.totalmarks/3; // since marks are outoff 100

    printf("\n Student names : \t %s \t %s \t %s \n",viraj.studname,abhay.studname,sandeep.studname);
    printf("\nStudents class : \t %d \t %d \t %d \n",viraj.class,abhay.class,sandeep.class);
    printf("\nStudents rollno: \t %d \t %d \t %d \n",viraj.rollno,abhay.rollno,sandeep.rollno);
    printf("\nstudent totalmarks: \t %d \t %d \t %d \n",viraj.totalmarks,abhay.totalmarks,sandeep.totalmarks);
    printf("\nStudent percentage : \t %d \t %d \t %d \n",viraj.percentage,abhay.percentage,sandeep.percentage);
    getch();



 
}'
















