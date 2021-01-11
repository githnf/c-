# c-
#include<stdio.h>
int main()
{
	
	double je,rate=0.0325,interest,total;
	scanf("%lg",&je);
	interest=je*rate;
	total=je+interest;
	printf("本金：%12.2g\n",je);
	printf("利息：%12.2g\n",interest);
	printf("总额：%12.2g\n",total);
	return 0;
 } 
