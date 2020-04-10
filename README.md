#include <stdio.h>
int main()
{
	int i;
	
	double n=1,t=0;
	while(i <= 64) {
		t= t+n;
		n=n*2;
		i++;
	}
	printf("t=%23.2f",t);
 } 
