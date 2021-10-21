#include <iostream>
using namespace std;


	int main() {
		int days[12] = { 31,28,31,30,31,30, 31,31, 30, 31, 30, 31 };
		cout << "Enter the  month (e.g : 1 for January, 12 for December)\n";
		int month;
		cin >> month;

		switch (month) {
		case 1: cout << " Number of days:  " << days[0] << endl; break;
		case 2: cout << " Number of days:  " << days[1] << endl; break;
		case 3: cout << " Number of days:  " << days[2] << endl; break;
		case 4: cout << " Number of days:  " << days[3] << endl; break;
		case 5: cout << " Number of days:  " << days[4] << endl; break;
		case 6: cout << " Number of days:  " << days[5] << endl; break;
		case 7: cout << " Number of days:  " << days[6] << endl; break;
		case 8: cout << " Number of days:  " << days[7] << endl; break;
		case 9: cout << " Number of days:  " << days[8] << endl; break;
		case 10: cout << " Number of days:  " << days[9] << endl; break;
		case 11: cout << " Number of days:  " << days[10] << endl; break;
		case 12: cout << " Number of days:  " << days[11] << endl; break;
		default: cout << "Invalid input";
			break;

		}

	}
