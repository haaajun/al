#include <stdio.h>
int main()
{
	int h;
	int m;
	int t;
	
	scanf("%d %d",&h,&m);
	scanf("%d",&t);
	
	if(m + t >= 60)
	{
		h += (m + t)/60;
		m = (m + t) % 60;
	}
	else if(m + t < 60)
	{
		m += t;
	}
	
	if(h >= 24)
	{
		h = h % 24;
	}
	
	printf("%d %d",h,m);
	
}
