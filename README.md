# include <stdio.h>

int main ()
{
	int d=0;
	
	while( d%2 ==1 || d<10 )
	{
		printf("%d\n", d+1);
		d=d+2;
	}

	return 0; 
}
