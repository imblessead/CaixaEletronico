# CaixaEletronico
Caixa Eletronico

package CaixaEletronica;

import java.util.Scanner;
// if e else eles fazem o teste verdadeiro ou falso.
// switch a unica comparação que ele faz se eles sao iguais 
public class CaixaEletronico {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Caixa eletronico braços curtos da Unipaulistana");
		System.out.println("");
		System.out.println("");
		System.out.println("1° Abastecimento");
		System.out.println("");
     	System.out.println("2° Operaçoes Financeiras ");
     	System.out.println("");
     	System.out.println("");
     	System.out.println("Digite opção desejada : ");
     	
     	int opcao=sc.nextInt();
     	
     	switch (opcao) {
     	case 1:
     		System.out.println("Voce escolheu a opcao abastecimento");
     		break;
     	case 2:
     		System.out.println("Voce escolheu a opcao Operação financeira");
     		break;
     		default:
     			System.out.println("A opção escolhido é inexistente . Selecione entre 1 é 2.");
     			break;
     	}
 sc.close();
	}

}
