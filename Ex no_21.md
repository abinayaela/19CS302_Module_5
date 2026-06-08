# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:
08.06.2026
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
1.Start.

2.Declare three variable value of type float.

3.Prompt the user to enter values.

4.Read the values using scanf.

5.Find the area of triangle using formula

6.End

## Program:
```
#include <stdio.h>
int main() {
 float base, height, area;
 float *pBase = &base, *pHeight = &height;
 scanf("%f", pBase);
 scanf("%f", pHeight);
 area = 0.5 * (*pBase) * (*pHeight);
 printf("%.2f\n", area);
}

```

## Output:
<img width="577" height="193" alt="image" src="https://github.com/user-attachments/assets/199c5832-6b6f-47c3-8ad9-3dc33342cb46" />




## Result:
Thus the program was executed and the output was verified successfully.
