# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.
## DATE:
## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm
Start
Declare the variable i.
Read the value given using scanf.
Check whether the given number is prime or not using if-else statement condition.
If true,print ("%d is a prime number.",i).
If false, print ("%d is not a prime number.",i).
End.
## Program:
```
/*
C program to check whether the given number is prime or not using function without return type and with arguments.
Developed by: Santhosh J
RegisterNumber:  212223060248
*/
#include<stdio.h> 
int main() 
{ 
int i; 
scanf("%d",&i); 
if(i%2==1 && i%1==0) 
{ 
printf("%d is a prime number.",i); 
 
} 
else 
{ 
printf("%d is not a prime number.",i); 
} 
return 0; 
}

```

## Output:
<img width="394" height="143" alt="439184067-8a30ffee-099f-4226-a72f-3d4ebe61c38b" src="https://github.com/user-attachments/assets/016c5981-37bf-4da1-87ad-f36aaed36e23" />

## Result:
Thus the program was executed and the output was verified successfully.
