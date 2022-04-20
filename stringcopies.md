#include<iostream>
using namespace std;
	int main(){
		char strA [ 80 ] = "Ubaidullah Qureshi";
		char strB [ 80 ];
		
		char *ptrA;
		char *ptrB;
		
		ptrA = strA;
		ptrB = strB;
		
		while ( *ptrA != '\0' ){
			*ptrB++ = *ptrA++;
		}
		*ptrB = '\0';
		
		cout << "String in strA = " << strA << '\n';
		cout << "String in strB = " << strB << '\n';
		
		return 0;
	}
