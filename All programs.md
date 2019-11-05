# Student Info
```
Name       :Kiran Devi Mishra
Class/Sec. :CE-C
Roll No.   :1914117
```
# 1.Addition of two integers
```

#include <stdio.h>

int main()
{
int firstNumber, secondNumber, sumOfTwoNumbers;
    printf("Enter two integers: ");
    scanf("%d %d", &firstNumber, &secondNumber);
    sumOfTwoNumbers = firstNumber + secondNumber;
    printf("%d + %d = %d", firstNumber, secondNumber, sumOfTwoNumbers);
return 0;
}
```
## Output
```
Enter two integers:2
3
2+3=5
```
# 2.Average of n numbers
```

#include<stdio.h>

int main()
{
    int n, i;
    float sum = 0, x;

    printf("Enter number of elements:  ");
    scanf("%d", &n);
    printf("\n\n\nEnter %d elements\n\n", n);
    for(i = 0; i < n; i++)
    {
        scanf("%f", &x);
        sum += x;
    }
    printf("\n\n\nAverage of the entered numbers is =  %f", (sum/n));
    return 0;
}
```
## Output
```
Enter number of elements:2
1
2
Average of the entered numbers is =  1.5
```
