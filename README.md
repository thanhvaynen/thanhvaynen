#include <iostream>
using namespace std;

int main(){
	int k;
	float kq=0,m=1;
	cout<<"nhap k ";
	cin>>k;
	do{
		kq+=m/(m+1);
		m++;
	}while(m<=k);
	cout<<"ket qua la: "<<kq;
	return 0;
}
