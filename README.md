# findinng-the-maximum-and-the-minimum-number-between-two-digits-using-function

#include <stdio.h>

int max(int num1, int num2);
int min(int num1, int num2);

int main()
{
    int num1,num2,maximum,minimum;
    
    printf("enter the two numbers: ");
    scanf("%d%d", &num1 , &num2);
    
    maximum = max(num1, num2);
    minimum = min(num1, num2);
    
    printf("\nmaximum=%d\n", maximum);
    printf("minimum=%d", minimum);
    
    return 0;
}



int max(int num1,int num2)
{
    return (num1>num2) ? num1:num2;
}


int min(int num1,int num2)
{
    return (num1>num2) ? num2:num2;
}
