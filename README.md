#include <stdio.h>

int main()
{
    int x=21;
    float y=15.2;
    int *p1;
    float *p2;
    p1=&x;
    p2=&y;
    printf("\n x=%d",x);
    printf("\n address of x is %u",p1);
    printf("\n address of x is %u",&x);
    printf("\n x=%d",*p1);
    printf("\n y=%f",y);
    printf("\n address of y is %u",p2);
    printf("\n address of y is %u",&y);
    printf("\n y=%f",*p2);
    return 0;
}
