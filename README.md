# exer27

#include <iostream>;
using namespace std;
int main() {

	int a;

	cout << "enter side tanginamo: " << endl;
	cin >> a;
	cout << " " << endl;

	switch (a) {
	case 3:
		cout << "triangle" <<endl;
			break;
	case 4:
		cout << "quadrilateral" <<endl;
			break;
	case 5:
		cout << "pentagon" << endl;
		break;
	case 6:
		cout << "hexagon" << endl;
		break;
	case 7:
		cout << "heptagon" << endl;
		break;
	case 8:
		cout << "octagon" << endl;
		break;
	case 9:
		cout << "nonagon" << endl;
		break;
	case 10:
		cout << "decagon" << endl;
		break;
	default:
		cout << "invalid" << endl;
	}
	cin.get();
	return 0;
}
