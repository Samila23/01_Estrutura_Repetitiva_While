// Escreva um programa para ler as coordenadas (X,Y) de uma quantidade indeterminada de pontos no sistema
//cartesiano. Para cada ponto escrever o quadrante a que ele pertence. O algoritmo será encerrado quando pelo
//menos uma de duas coordenadas for NULA (nesta situação sem escrever mensagem alguma).


import java.util.Locale;
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner (System.in);
		Double x,y;
		
		System.out.println("teste Digite o valor que corresponde ao eixo X e Y, na respectiva ordem");
		x = sc.nextDouble();
		y = sc.nextDouble();
		
		while (x != 0 && y != 0 || x != 0 && y > 0 || y != 0 && x > 0 ) {
			if( x > 0 && y > 0) {
				System.out.println("Q1");
			}
			else if( x < 0 && y > 0) {
				System.out.println("Q2");
			}
			else if( x < 0 && y < 0) {
				System.out.println("Q3");
			}
			else if ( x > 0 && y < 0) {
				System.out.println("Q4");
			}
			System.out.println("Digite o valor que corresponde ao eixo X e Y, na respectiva ordem");
			x = sc.nextDouble();
			y = sc.nextDouble();
		}
		sc.close();
		
}
}



