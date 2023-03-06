#include <stdio.h>
#include <stdlib.h>

int main () {
    int A = 5;
    int B = 10;
    int memory = 0;

    printf("Variavel A é %d variavel B é %d\n", A, B);
    printf("Trocando A para B, e B para A\n");

    memory = A;
    A = B;
    B = memory;

    printf ("Variavel A é %d variavel B é %d\n", A, B);

   return 0;
}