# Praktikum_Aufgabe_5_2

#include <iostream>
using namespace std;

void approx_pi() {
	int i = 3;
	double pi = 4;
	double f = 4;
	int c = 3;

	while (i <= 10000) {

		if (c % 2 != 0) {
			pi -= f / i;
			c++;
		} else {
			pi += f / i;
			c++;
		}
		i += 2;

		cout << pi << endl;

	}

}
int main() {

	approx_pi();

	return 0;
}

