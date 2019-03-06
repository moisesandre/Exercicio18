# Exercicio18

#include <stdlib.h>
#include <stdio.h>
main ()
{
    system("color 0b");

    int n, soma=0;

    while (n>=0)
    {
        printf("digite um numero: ");
        scanf("%d",&n);
        soma=soma+1;
    }

    printf("Foram digitados %d", soma-1);

    return 0;
}
