#include<stdio.h>
int main()
{
    int x[3][3],i,j,sum=0;
    printf("Input elements in the matrix:\n");
    for(i=0;i<3;i++)
    {
        for(j=0;j<3;j++)
        {
            printf("element-[%d],[%d]:",i,j);
            scanf("%d",&x[i][j]);
        }
    }
    printf("The matrix is:\n");
    for(i=0;i<3;i++)
    {
        for(j=0;j<3;j++)
        {
           printf("%d\t",x[i][j]);
        }
        printf("\n");
    }
    for(i=0;i<3;i++)
    {
        sum= sum+x[i][i];
    }
    printf("Sum of all diagonal elements is:%d",sum);
    return 0;
}
