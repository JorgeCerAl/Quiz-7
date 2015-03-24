# Quiz-7
Quiz


/*
Quiz #7
Main: GCD
By: Jorge Cervantes
#TC1017
Referencia: XXXXXXXXXX
---------------------------------------------------------------------
*/

#include <iostream>

using namespace std;

int Taco(int a, int b){
	int x, z;

	do{

		z = (b % a);
		b = a;
		x = a;
		a = z;


	}while(z != 0);

return x;

}

int main(){
	int a, b;

cout << "GCD(a,b)\n";
cout << endl;
cout << "Imprime a" << endl;
cin >> a;
cout << "Imprime b" << endl;
cin >> b;
cout << endl;

int x = Taco(a,b); 
cout << "GCD( " << a << ", " << b << " ) = " << x << endl;


return 0;
}
