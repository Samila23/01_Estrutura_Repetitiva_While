//Escreva um programa que repita a leitura de uma senha até que ela seja válida. Para cada leitura de senha
//incorreta informada, escrever a mensagem "Senha Invalida". Quando a senha for informada corretamente deve ser
//impressa a mensagem "Acesso Permitido" e o algoritmo encerrado. Considere que a senha correta é o valor 2002.

import java.util.Locale;
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner (System.in);
		int a = 2002;
		
		System.out.println("Digite sua senha");
		a = sc.nextInt();
		
		while (a != 2002) {
			System.out.println("Senha Inválida, tente novamente");
			a = sc.nextInt();
		}
		System.out.println("Acesso Permitido");
		sc.close();
		
}
}
