# programacion-upsa
// areatriangulo.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include "conio.h"

using namespace std;

void main() {
	float base,altura,area;
	cout<<"ingresar base: ";
	cin>>base;
	cout<<"ingresar altura: ";
	cin>>altura;
	area=(base*altura)/2;
	cout<<"el area del triangulo es; "<<area;
	getch();
}
