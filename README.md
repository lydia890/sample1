#include <stdio.h>

int main() {
    int num1, num2, result;

    // Input two numbers from the user
    printf("Enter the first number: ");
    scanf("%d", &num1);
    printf("Enter the second number: ");
    scanf("%d", &num2);

    // Multiply the numbers
    result = num1 * num2;

    // Display the result
    printf("The result of %d multiplied by %d is %d.\n", num1, num2, result);

    return 0;
}
