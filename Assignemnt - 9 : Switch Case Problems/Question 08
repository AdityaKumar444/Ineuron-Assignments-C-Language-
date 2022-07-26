#include <stdio.h>
int main()
{
    int n , a , b ;
    printf("Enter choice :\n");
    printf("1. Convert negative to positive number\n");
    printf("2. Convert positive to negative number\n\n");
    scanf("%d" , &n);
    switch(n)
    {
        case 1 :
        printf("Enter a number : ");
        scanf("%d" , &a);
        if(a>0)
        {
        printf("Error ! wrong entry , enter negative number\n");
        break;
        }
        else
        a = a * (-1) ;
        printf("\nconverted positive number is %d" , a);
        break;
        
        case 2 :
        printf("Enter a number : ");
        scanf("%d" , &b);
        if(b<0)
        {
        printf("Error ! wrong entry , enter positive number\n");
        break;
        }
        else
        b = b * (-1) ;
        printf("\nconverted negative number is %d" , b);
        break;
        
        default:
        printf("\nInvalid entry");
        break;
    }
    return 0 ;
}
