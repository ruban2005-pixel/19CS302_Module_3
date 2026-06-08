# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
Start.
Declare a integer variable
Define a function named dectobin.
Return the integer.
Read the value using scanf.
Convert decimal to binary value.
Print the dectobin
End. 

## Program:
```
/*
Program to C Program to convert a given decimal value to binary using function without arguments with return type.
Developed by: Santhosh J 
RegisterNumber: 212223060248 
*/
  #include<stdio.h> 
  Int dectobin(int d){ 
int bin =0,base=1,rem; 
while(d>0) 
{ 
rem=d%2; 
bin=bin+rem*base; 
d=d/2; 
base=base*10; 
} 
printf(" = %d in binary",bin); 
return 0; 
} 
int main() 
{ 
int dec; 
scanf("%d",&dec); 
printf("%d in decimal",dec); 
dectobin(dec); 
return 0; 
} 

```

## Output:
<img width="821" height="236" alt="441027366-6092ab3b-7c24-4c24-8c3b-23662be759ee" src="https://github.com/user-attachments/assets/7b11d01f-c094-4d5a-b4f6-8002285380b8" />

## Result:
Thus the program was executed and the output was verified successfully.
