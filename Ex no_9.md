# EX 9 C program to find the sum of odd digits using do while loop.
## DATE: 28/04/2025
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Start the program.
2. Read the input number from the user.
3. Initialize sum = 0.
4. Using a do while loop.
5. Repeat the loop until num becomes 0.
6. Display the sum.
7. End.

## Program:
```
#include <stdio.h>

int main()
{
    int num, digit, sum = 0;
    scanf("%d", &num);
    int temp = num; 
    do
{
        digit = num % 10;
        if (digit % 2 != 0)
 {
            sum += digit;
        }
        num /= 10;
    } while (num != 0);
    printf("Sum of odd digits of %d is: %d\n", temp, sum);
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/e08bad4e-eb4e-4088-9415-6652a806158a)



## Result:
Thus the program was executed and the output was verified successfully.
