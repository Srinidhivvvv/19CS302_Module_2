# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1.Start.
2.Declare the variables.
3.Prompt the user to enter a value.
4.Read the value using scanf.
5.Enter factorial of the number.
6.End.

## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by:Santhosh kumar B 
RegisterNumber: 212223060249
*/
#include <stdio.h> 
int main() { 
    int n, i; 
    unsigned long long factorial = 1; 
    scanf("%d", &n); 
 
    if (n < 0) { 
        printf("Factorial is not defined for negative numbers.\n"); 
    } else { 
        for (i = 1; i <= n; i++) { 
            factorial *= i; 
        } 
        printf("Factorial of %d = %llu\n", n, factorial); 
    } 
    return 0; 
}
```

## Output:
<img width="518" height="199" alt="image" src="https://github.com/user-attachments/assets/33b2ddcc-6d08-4c7e-89e3-1fa360213cc4" />



## Result:
Thus the program was executed and the output was verified successfully.
