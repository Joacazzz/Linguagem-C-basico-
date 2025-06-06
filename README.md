# Linguagem-C-basico-
Exercicio de Linguagem C - Nivel Basico

#include "stdio.h"
main(){
	float C, F;
	printf("mostre o valor em celsius");
	scanf("%f", &C);
	F = (9/5*C+32);
	printf("o valor em fahreiheit é %2.f", F);
	getchar();
}
