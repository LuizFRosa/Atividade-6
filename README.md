# Atividade-6

#include <stdio.h>
#include <stdlib.h>

int main() {
	
    // Declaração da variável para armazenar o número
    float raio;
    
    printf("Digite o valor do raio \n");
    scanf("%f", &raio);

    // Verificar o resultado
    float area = 3.14 * (raio*raio);
	
	printf("A area do circulo e: %f", area); 
    
    return 0;
}
