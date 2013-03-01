#include<stdio.h>

int main()
{
 float gradeTotal
 float averageTotal;
 int gradeEntered;
 int numValues;
//
 printf("Homework2:\n");
//
 printf("Please enter the quiz score for the correct numbered quiz.\n");
 numValues = 0;
 while (numValues < 13){
 numValues++;
 printf("Enter quiz number %d:",numValues);
 scanf("%d",gradeEntered);
 if (gradeEntered < 0 && gradeEntered > 100)
     printf("The grade entered is incorrect.\n");
  } while (gradeEntered < 0 && gradeEntered > 100);
//
 gradeTotal = gradeEntered;
//
 averageTotal = gradeEntered / 13
//
 printf("The total quiz grade average is %1.0f\n",averageTotal);

 return 0;
 }
