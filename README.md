# Countdown
#For loop
#include<iostream>
using namespace std;
int main()
{
	for (int k = 10; k >= 0; k--)
	{
		if (k == 0)
		{
			cout << "We have lift off " << endl;
		}
		else 
		{
			cout << "K is " << k << endl;
		}
	}
	return 0;
}
