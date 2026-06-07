# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1. Start the program. 
2. Declare two global variables for the numbers.
3. Create two functions — one for multiplication and one for division — without arguments and return type. 
4. In main(), take input for the two numbers, then call both functions.
5. End

## Program:
```
#include <stdio.h>

int num1, num2;

void multiply() {
    printf("Multiplication: %d\n", num1 * num2);
}

void divide() {
    if(num2 != 0)
        printf("Division: %.2f\n", (float)num1 / num2);
    else
        printf("Division by zero is not allowed.\n");
}

int main() {
    scanf("%d%d", &num1, &num2);
    multiply();
    divide();
    return 0;
}
```

## Output:
<img width="374" height="198" alt="image" src="https://github.com/user-attachments/assets/0dfdec99-e9e9-4fd7-8a82-b56817eab58b" />

## Result:
Thus the program was executed and the output was verified successfully.

## Result:
Thus the program was executed and the output was verified successfully.
