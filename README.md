# Cnote-
 
#include<iostream>
using namespace std;
int main()
{
	int T;
	cin>>T;
	while(T--)
	{
	long int X,Y,K,N,P,C,f=0,fd=0;
		cin>>X>>Y>>K>>N;
		for(int i =0;i<N;i++)
		{
			cin>>P>>C;
			
			
		
		if(P>=(X-Y)&& C<=K)
		f=1;
		else
		fd=1;
	}
	
	
	if(f==1)
	cout<<"\nLuckyChef";
	else
		cout<<"\nUnluckyChef";
		}
    return 0;
}
   
