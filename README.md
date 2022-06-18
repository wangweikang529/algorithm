# algorithm
By this summer ,let us brush up on the algorthm question together.From on June tenth,in 2022, we study .
#include<iostream>
#include<cstdio>
 
using namespace std;
 
int t,n,m;
 
int main()
{
	scanf("%d",&t);
	while(t--)
	{
		scanf("%d%d",&n,&m);
		long long cnt=0;
		
		while(n--)
		{
			int temp;
			scanf("%d",&temp);
			cnt+=temp;
			
		}	
		
		if(cnt<=m)puts("0");
		else printf("%d\n",cnt-m);
	}
	return 0;
	
}
