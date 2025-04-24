#include <stdio.h>

int num1, num2, soma;

int main() {
    // Lendo dois números
    printf("Digite o primeiro número: ");
    scanf("%d", &num1);

    printf("Digite o segundo número: ");
    scanf("%d", &num2);

    // Calculando a soma dos dois números
    soma = num1 + num2;

    printf("A soma é: %d\n", soma);

    return 0;
}
