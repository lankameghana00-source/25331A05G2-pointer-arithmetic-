#include <stdio.h>
int main() 
{
    int arr[5] = {10, 20, 30, 40, 50};
    int *ptr;
    int i;
    ptr = arr;  // Pointer points to first element of array
    printf("Pointer Arithmetic Demonstration:\n");
    for(i = 0; i < 5; i++)
    {
        printf("Value = %d, Address = %p\n", *ptr, ptr);
        ptr++;  // Move pointer to next element
    }
    return 0;
}
