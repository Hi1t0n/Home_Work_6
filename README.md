# Home_Work_6
/*Написать программу, которая выводит на экран прямоугольник символом *. 
Высота и ширина задаётся пользователем.*/
#include <iostream>
using namespace std;
int main()
{
	setlocale(LC_ALL, "Russian");
	int width, height;
	char symbol;
	cout << "Выберите символ из которого будет состоять фигура: ";
	cin >> symbol;
	cout << "Введите длину прямоугольника: ";
	cin >> width;
	cout << "Введите высоту прямоугольника: ";
	cin >> height;

	
	for (int j = 0 ; j < width; j++)
	{
	
		for (int i = 0 ; i < height; i++ )
		{ 
			cout << symbol ;
		}
		cout << endl;
	}
	

}
