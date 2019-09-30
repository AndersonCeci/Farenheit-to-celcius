#include <iostream>

using namespace std;



int main()
{
	
	int celcius;
	int fahrenheit;
	
	
	cout << "Place temperature on farenhite : ";
	cin >> fahrenheit;
	
	celcius = (fahrenheit - 32) * 5 / 9;
	
	
	cout << "Temperature from farenheit to celcius is " << celcius;
	
	
		
	
	
	
	
	return 0;
}
