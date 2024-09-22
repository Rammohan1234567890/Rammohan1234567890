#include<stdio.h>
int main()
{
	int n,rem,sum=0;
	printf("Enter your numbert n");
	scanf("%d",&n);
	int g=n;
	while(n!=0)
	{
		rem=n%10;
		sum=sum+rem*rem*rem;
		n=n/10;
			}
	if(g==n)
	printf("this is armstrong number");
	else
	printf("this number is not armstrong number");
    
	
	
}
