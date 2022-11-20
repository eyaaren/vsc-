# vsc- 
#include <stdio.h>
#include <math.h>


// labwork5, question2: Write a C program to read the age of a candidate and determine whether s/he is eligible for voting.

intmain (void){

    int age;
    printf("please enter your age:");
    
    if( age>=18)
    printf("you can vote!");
    else 
    printf(" you are not eligible for voting.");

    return 0; 

}