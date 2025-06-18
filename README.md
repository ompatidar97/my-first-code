#include<stdio.h>
int main()
{
	int num1 =15, num2 =15, result;
	int ch;
	printf("Enter your choice: ");
	scanf("%d",&ch);
	switch(ch)
	{
		case 1:
			result = num1 + num2;
			printf("addition of %d and %d is %d",num1,num2,result);
			break;
			
		case 2:
			result = num1 - num2;
			printf("subtraction of %d and %d is %d",num1,num2,result);
			break;	
			
		case 3:
			result = num1 * num2;
			printf("multiplication of %d and %d is %d",num1,num2,result);	
	}
}
