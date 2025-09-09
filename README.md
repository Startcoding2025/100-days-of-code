# 100-days-of-code
Task to send 100 codes

// 1. Write a program to input two numbers and display their sum.

#include <stdio.h>
int main()
{
    int a, b, sum;
    printf("Enter two numbers:");
    scanf("%d %d", &a, &b);

    sum = a + b;

    printf("sum = %d\n", sum);
    return 0;
}



// 2. Write a program to input two numbers and display their sum, difference, product, and quotient.

#include <stdio.h>

int main()
{
    float num1, num2;
    float sum, differnce, product, quotient;

    printf("Enter first number:");
    scanf("%f", &num1);

    printf("Enter second number:");
    scanf("%f", &num2);

    sum = num1 + num2;
    differnce = num1 - num2;
    product = num1 * num2;

    printf("\nResults:\n");
    printf("Sum = %.2f\n", sum);
    printf("Difference = %.2f\n", difference);
    printf("Product = %.2f\n", product);

    if (num2 != 0)
    {
        Quotient = num1 / num2;

        printf("Quotient= %.2f\n", quotient);
    }
    else
    {

        printf("Quotient= Undefined (division by zero)\n");
    }

    return 0;
}






// 3. Write a program to calculate the area and perimeter of a rectangle given its length and breadth.

#include <stdio.h>
int main()
{
    int length, breath, area, perimeter;
    printf("Enter length and breadth of rectangle:");
    scanf("%d %d", &length, &breath);
    area = length * breath;
    perimeter = 2 * (length + breath);
    printf("Area = %d\n", area);
    printf("perimeter = %d\n", perimeter);
    return 0;
}




// 4. Write a program to calculate the area and circumference of a circle given its radius.

#include <stdio.h>
#include <math.h>

int main()
{
    float radius, area, circumference;
    printf("Enter the radius of the circle:");

    scanf("%f", &radius);

    area = M_PI * radius * radius;
    circumference = 2 * M_PI * radius;

    printf("Area of the circle: %.2f\n", area);
    printf("circumference of the circle : %.2f\n", circumference);

    return 0;
}



// 5. write a program to convert temperature from celsius to Fahrenheit

#include <stdio.h>
int main()
{
    float celsius, fahrenheit;
    printf("Enter temperature in celsius:");
    // Input temperature in celsius
    scanf("%f", &celsius);
    // conversion formula
    fahrenheit = (celsius * 9 / 5) + 32;
    // output
    printf(" Fahrenheit: %.2f\n", fahrenheit);
    return 0;
}




// 6. write a program to swap two numbers using a third variable.

#include <stdio.h>
int main()
{
    int a, b, x;
    printf("Enter two numbers to swap;");

    scanf(" %d %d", &a, &b);

    x = a;
    a = b;
    b = x;
    printf("After swapping: a=%d, b=%d\n", a, b);

    return 0;
}

// 7. write a program to swap two numbers without using third variable.

#include <stdio.h>
int main()
{
    int a, b;
    printf("Enter two numbers to swap;");

    scanf(" %d %d", &a, &b);

    a = a + b;
    b = a - b;
    a = a - b;
    printf("After swapping: a=%d b=%d \n", a, b);

    return 0;
}



// 8.write a program to find and display the sum of the first n natural numbers.

#include <stdio.h>
int main()
{
    int n, sum = 0, i = 1;
    printf("Enter a postive intger:");
    scanf("%d", &n);

    for (i = 1; i <= n; i++)

    {
        sum += i;
    }
    printf("sum=%d\n", sum);
    return 0;
}




// 10. Write a program to input time in seconds and convert it to hours:minutes:seconds format.
#include <stdio.h>
int main()
{
    int totalseconds, hours, minutes, seconds;

    printf("Enter time in seconds \n");

    scanf("%d", &totalseconds);

    hours = totalseconds / 3600;
    minutes = (totalseconds % 3600) / 60;
    seconds = totalseconds % 60;

    printf("%d:%d:%d\n", hours, minutes, seconds);

    return 0;
}
