#include <stdio.h> // Biblioteca padrão para entrada e saída

// ======================
// Definição de constantes
// =======================
const int BISPO_PASSOS = 5; // Bispo: 5 casas na diagonal superior direita
const int TORRE_PASSOS = 5; // Torre: 5 casas para a direita
const int RAINHA_PASSOS = 8; // Rainha: 8 casas para a esquerda

int main() {
// ======================
// Movimento do BISPO
// ======================
// O bispo e a diagonal superior direita → combinação de "Cima" e "Direita"
printf("Movimento do BISPO:\n");
for (int i = 1; i <= BISPO_PASSOS; i++) { //Estrutura de reprodução: for
printf("Cima\n");
printf("Direita\n");
}
printf("\n");

// =======================
// Movimento da TORRE
// =======================
// A torre anda apenas na horizontal → 5 casas para a direita
printf("Movimento da TORRE:\n");
int i = 1; // variável de controle
while (i <= TORRE_PASSOS) {  // Estrutura de repetição: while
    printf("Direita\n");
    i++;
}
printf("\n");

// =======================
// Movimento da RAINHA
// =======================
// A rainha anda 8 casas para a esquerda (movimento horizontal)
printf("Movimento da RAINHA:\n");
int contador = 0;
do {  // Estrutura de repetição: do-while
    printf("Esquerda\n");
    contador++;
} while (contador < RAINHA_PASSOS);

return 0;
}

