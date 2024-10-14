#include <iostream>
using namespace std;

int main() {
	int n; "MASUKAN JUMLAH DATA: ";
	cout << "MASUKAN JUMLAH DATA: ";
	cin >> n;

	int jumlahGanjil = 0;
	int jumlahGenap = 0;

	for (int i = 1; i < n; ++i) {

		if (i % 2 == 0) {
			jumlahGanjil += i;

		}
		else {
			jumlahGenap += i;
		}
	}
	cout << "JUMLAH TOTAL GENAP: " << jumlahGanjil << endl;
	cout << "JUMLAH TOTAL GANJIL: " << jumlahGenap << endl;

}
