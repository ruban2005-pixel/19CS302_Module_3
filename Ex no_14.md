# EX 14 C program to delete first element in an array.
## DATE:
## AIM:
To write a C program to delete first element in an array.

## Algorithm
Start.
Define a variables i,j,a.
Read the value using scanf.
Ask the user to make an input
Print out the answer
End.
## Program:
```
#include<stdio.h> 
int main() 
{ 
int i,n,a[10]; 
scanf("%d",&n); 
for(i=0;i<n;i++) 
{ 
scanf("%d",&a[i]); 
} 
for(i=1;i<n;i++) 
printf("%d ",a[i]); 
}
```

## Output:
<img width="691" height="145" alt="441027119-bfd5f214-1a95-48a8-951b-a18433d9010a" src="https://github.com/user-attachments/assets/b6a34016-b07d-4ad0-b7ed-60139cf0b272" />

## Result:
Thus the program was executed and the output was verified successfully.
