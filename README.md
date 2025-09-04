# Square-and-Cube-Using-Two-Functions
#include <stdio.h>

int square(int n) {
    return n * n;
}

int cube(int n) {
    return n * n * n;
}

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);

   printf("Square = %d\n", square(num));
    printf("Cube = %d\n", cube(num));
    return 0;
}
