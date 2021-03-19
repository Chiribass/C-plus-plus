# C-plus-plus
#Глава 3, упражнение 3

#include <iostream>
using namespace std;
int main()
{
	double r;
	const double pi = acos(-1.0);
	cout << "введите радиус ";
	cin >> r;
	cout << "площадь круга: " << pi * r*r<<endl;
	cout << "периметр круга" << 2 * pi * r<<endl;
	system("pause");
	return 0;
}
