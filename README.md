# SwitchCase
#include<stdio.h>
#include<stdlib.h>
int main(void)
{
	
	int a;
	system("clear");
	printf("Enter a :");
	scanf("%d",&a);
	switch(a)
	{
		case 1:
			printf("You entered 1\n");
			break;
		case 2:
			printf("You entered 2\n");
			break;
		case 3:
			printf("You entered 3\n");
			break;
		default:
		
			printf("You entered something else:\n");
			break;
	}
}
