# Lab-19.20-
#include <iostream>
using namespace std;

void computeTemperature (double kelvin, double& celsius, double& fahrenheit) {
  celsius = kelvin - 273.15;
  fahrenheit = 1.8 * celsius + 32;

}

int main() {
  double kelvin;
  double celsius;
  double fahrenheit;
  cout << "Input a temperature in unit of Kelvin" << endl;
  cin >> kelvin;
  computeTemperature (kelvin,celsius,fahrenheit);
  cout << "The temperature in Kelvin is " << kelvin << endl;
  cout << "The temperature in Celsius is " << celsius << endl;
  cout << "The temperature in Fahrenheit is " << fahrenheit << endl;
}
