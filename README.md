#include<stdio.h>
int main()
{
	int n, a, sum=0; 	//Initialisation of variables.
	printf(" Enter any number : "); 
	scanf("%d",&n);		//To scan & store the input.
	while(n>0)			//Recursive function to calculate the sum of digits.
	{
		sum += n%10 ;	
		n /= 10;
	}
	printf("\n The sum of digits of given number is %d.",sum);
	return 0;
}
