#include <stdio.h>

float base, height;

void areaNoArgNoReturn()
{
    printf("\nNo Arguments, No Return Value\n");
    printf("Enter base and height: ");
    scanf("%f %f", &base, &height);

    float area = 0.5 * base * height;
    printf("Area of triangle = %.2f\n", area);
}

void areaArgNoReturn(float b, float h)
{
    printf("\nArguments, No Return Value\n");
    float area = 0.5 * b * h;
    printf("Area of triangle = %.2f\n", area);
}

float areaNoArgReturn()
{
    return 0.5 * base * height;
}

float areaArgReturn(float b, float h)
{
    return 0.5 * b * h;
}

int main()
{
    float b, h, area;

    areaNoArgNoReturn();

    printf("\nEnter base and height: ");
    scanf("%f %f", &b, &h);
    areaArgNoReturn(b, h);

    area = areaNoArgReturn();
    printf("\nNo Arguments, Returns a Value\n");
    printf("Area of triangle (using stored base and height) = %.2f\n", area);

    area = areaArgReturn(b, h);
    printf("\nArguments, Returns a Value\n");
    printf("Area of triangle = %.2f\n", area);

    return 0;
}
