# Exercicio-4-AF
Exercicio 4 AF Vetores A e B 

  Declarar vetores A[] e B[]
  Declarar variável C
  Enquanto x < 5. Faça 
    Receber e atribuir valores de A e B
    Somar x + 1
  FimEnquanto
  Enquanto x < 5. Faça
    c = c + A[x] * B[x]
  FimEnquanto
  Exibir valor de c
  
  
  
  package exercicios_prof_ohata;

import java.util.Scanner;

public class vetores_a_b {

	public static void main(String[] args) {
		
		//Mostrar variáveis 
		int[] a = new int[5], b = new int[5];//armazenamento valores de A e B
		
		int c =0;// exibir valor final
		
		Scanner input = new Scanner(System.in);//Scanner para a entrar dados
		
		for (int x = 0; x < 5; x++) {//Repetição para atribuir valores de A e B
			
			//Entrada  de valores de A e B
			System.out.printf("Digite o %dº valor de A: ", (x + 1));
			a[x] = input.nextInt();
			System.out.printf("Digite o %dº valor de B: ", (x + 1));
			b[x] = input.nextInt();	
		}
		for (int x = 0; x < 5; x++) {//Repetição para multiplicar e somar os valores de A e B
			
			c = c + a[x] * b[x];//Soma e multiplicação dos valores de A e B
		}
		
		//Mostrar valor de C
		System.out.printf("O valor de C de é igual: %d", c);
	}

}


![image](https://user-images.githubusercontent.com/103973613/173459798-7390c0ef-d927-4a0a-a27c-12a948492563.png)
