# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
Start.
Declare a array size value of type int.
Prompt the user to enter a value.
Read the value using scanf.
Initialize array elements.
Replace all even elements to E
End.
## Program:
```
#include <stdio.h> 
int main() { 
    int arr[100], n; 
    scanf("%d", &n); 
    for (int i = 0; i < n; i++) { 
        scanf("%d", &arr[i]); 
    } 
    for (int i = 0; i < n; i++) { 
        if (arr[i] % 2 == 0) 
            printf("E "); 
        else 
            printf("%d ", arr[i]); 
    } 
    printf("\n"); 
    return 0; 
} 
```

## Output:

<img width="795" height="173" alt="441026934-b5b017d2-c90f-44b0-bf4c-410d2718f282" src="https://github.com/user-attachments/assets/1dcd04e7-7695-410e-ba13-d80f9f6615a8" />


## Result:
Thus the program was executed and the output was verified successfully.
