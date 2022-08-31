# matrix-difference
This is a program for subtraction in matrix using 2 dimensional array.
#include<stdio.h>
#include<conio.h>
void main()
{
	int a[3][3], b[3][3], c[3][3];
	int i,j;
	printf("Enter 9 numbers for first matrix: ");
	for(i=1;i<=3;i++)
	{
		for(j=1;j<=3;j++)
		{
			scanf("%d",&a[i][j]);
		}
	}
	printf("Enter 9 numbers for second matrix: ");
	for(i=1;i<=3;i++)
	{
		for(j=1;j<=3;j++)
		{
			scanf("%d",&b[i][j]);
		}
	}
	for(i=1;i<=3;i++)
	{
		for(j=1;j<=3;j++)
		{
			c[i][j]=a[i][j]-b[i][j];
			printf("%d \t",c[i][j]);
		}
		printf("\n");
	}
}
