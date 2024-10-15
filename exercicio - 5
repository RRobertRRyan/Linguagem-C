 #include <stdio.h>

int main() {
	float a, b, c, discriminante;
	
	do {
		// Leitura dos coeficientes
		printf("Digite os coeficientes a, b e c (ou 0 0 0 para sair): ");
		scanf("%f %f %f", &a, &b, &c);
		
		
		// Verifica a condição de saída
		if (a == 0 && b  == 0 && c == 0) {
			printf("Encerrando o programa.\n");
			break;
		}
		
		// Cálculo do discriminante
		discriminante = b * b - 4 * a * c;
		printf("O valor do discriminante e: %.2f\n", discriminante);
		
		// Verifica se as raízes são reais 
		if (discriminante >= 0) {
			printf("Existem raizes reais.\n");
		} else {
			printf("Não existem raizes reais.\n");
		}
		
	} while (1);
	
	return 0;
	
}
