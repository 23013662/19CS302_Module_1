# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1.Input Age – Read an integer value from the user.

2.Check Eligibility – Compare the input age with 21.

3.Conditional Execution – If age is 21 or above, print "You are eligible for marriage."

4.Alternative Execution – If age is below 21, print "You are not eligible for marriage."

5.End Program – Terminate execution. 

## Program:
```
/*
Program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
Developed by:santhiya C 
RegisterNumber: 212223060247 
*/
#include <stdio.h>

int main() {
    int age;
    scanf("%d", & age);

    if (age >= 21) {
        printf("You are eligible for marriage.\n");
    } else {
        printf("You are not eligible for marriage.\n");
    }

    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/6856a018-6fed-4d6d-9194-3a7624526153)



## Result:
Thus the program was executed and the output was verified successfully.
