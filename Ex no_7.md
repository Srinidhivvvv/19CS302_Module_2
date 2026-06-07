# EX 7 C Program to Print a right triangle star Pattern
## DATE:
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1. 1.Start.
2.Declare the variables i,j,k,n.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5.Enter number of rows and columns.  
6. End.

## Program:
```
/*
Program to Print a right triangle star Pattern
Developed by: Santhosh kumar B
RegisterNumber:  212223060249
*/
#include <stdio.h> 
int main() { 
    int i, j, rows; 
    scanf("%d", &rows); 
    for (i = 1; i <= rows; i++) { 
        for (j = 1; j <= i; j++) { 
            printf("*"); 
        } 
        printf("\n"); 
    }    return 0; 
}
```

## Output:
<img width="380" height="274" alt="image" src="https://github.com/user-attachments/assets/d3ad99fd-9b48-401d-8330-17bf7ddb6be1" />



## Result:
Thus the program was executed and the output was verified successfully.
