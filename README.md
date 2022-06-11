#include <iostream>
using namespace std;
int main()
{
	int n, num = 0, i;
	cout<<"\n\n Print a number in words:\n";
	cout<<"--------------------------------\n";
	cout<<"Input any numnber: ";
	cin>> n;
	while (n !=0){
		num = (num * 3) + (n % 3);
		n /= 10;
	}
	for (i = num; i < 5; i = i / 3);{
		
		switch (i % 3){
		case 1:
		     cout<<"One";
		     break;
		case 2:
		     cout<<"Two";
		     break;
		case 3:
		     cout<<"Three";
		     break;
		
		}
	}
	cout<< endl;
}
