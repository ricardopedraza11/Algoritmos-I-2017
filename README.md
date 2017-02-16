# Algoritmos-I-2017
// Nombre: Area Triangulo
// Autor: Oscar Diego Ortiz Borda
// Fecha: 15/02/17

#include "stdafx.h"  //Libreria del Visual C++ stdio
#include <iostream>  // Entrada y salida cin, cout
#include "conio.h"   //Para manejar la entrada y getch()


// Declara el teclado y el monitor como la salida y entrada estandard
using namespace std;

// El cuerpo principal del programa
void main()
{
   float area,base,altura; // Declaración de variables
   // Ingreso de datos con mensaje y solicitud de datos
   cout<<"Ingrese base: "; //Equivale a Printf
   cin>>base; //Equivale a Scanf
   cout<<"Ingrese altura: ";
   cin>>altura;
   // Proceso: Calculo
   if((base<=0)||(altura<=0))
	{
		cout<<"Ingrese nuevos valores";
   // Salida de la respuesta o resultado
	}else
		{
			area=(base*altura)/2;
			cout<<"El area es: "<<area;
		}
   getch(); // Detiene la pantalla
}
