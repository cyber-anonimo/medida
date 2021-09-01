# medida
#include<iostream>
using namespace std;

int main(){
	
	float metros = 0;
	float po = 0;
	float pe = 0;
	float ja = 0;
	float cm = 0;
	float km = 0;
	float mi = 0;
	
	cout << "digite um numero: ";
	  cin >> metros;
	  
	  po = metros * 39.37;
      pe = metros * 3.281;
	  ja = metros * 1.094;
	  mi = metros / 1609;
	  cm = metros * 100;
	  km = metros / 1000;

	cout << "Polegadas: " << po << "\n";
	cout << "Jardas: " << ja << "\n";
	cout << "Kilometros: " << km << "\n";
	cout << "Milkhs: " << mi << "\n";
	cout << "Pés: " << pe << "\n";
	cout << "Centimetros: " << cm << "\n";
	
	
	return 0;
}
