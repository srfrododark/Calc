using System;

public class Calculadora{

	public void soma(){

		System.Console.WriteLine("Digite o Numero: ");

		int numero1 = Convert.ToInt32( Console.ReadLine() );
		int numero2 = Convert.ToInt32( Console.ReadLine() );

		int resultado = numero1 + numero2; 

		Console.WriteLine("resultado é " + resultado);
	}

	public void subitracao(){

		System.Console.WriteLine("Digite o Numero");

		int numero1 = Convert.ToInt32(Console.ReadLine());
		int numero2 = Convert.ToInt32(Console.ReadLine());

		int resultado = numero1 - numero2; 

		Console.WriteLine("resultado é " + resultado);
	}

	public void multiplicacao(){

		System.Console.WriteLine("Digite o Numero");

		int numero1 = Convert.ToInt32(Console.ReadLine());
		int numero2 = Convert.ToInt32(Console.ReadLine());

		int resultado = numero1 * numero2; 

		Console.WriteLine("resultado é " + resultado);

	}

	public void divisao(){

		System.Console.WriteLine("Digite o Numero");

		int numero1 = Convert.ToInt32(Console.ReadLine());
		int numero2 = Convert.ToInt32(Console.ReadLine());

		int resultado = numero1 / numero2; 

		Console.WriteLine("resultado é " + resultado);
	}
}

	
public class Teste{

	public static void Main(){

		Calculadora tnc = new Calculadora();
		
		System.Console.WriteLine("Bem vindo a minha Calculadora");
		System.Console.WriteLine("Digite: ");
		System.Console.WriteLine("1. Para Somar");
		System.Console.WriteLine("2. Para Subtrair");
		System.Console.WriteLine("3. Para Multiplicar");
		System.Console.WriteLine("4. Para Dividir");

		int calc = Convert.ToInt32(Console.ReadLine());

		switch(calc){
			case 1:
				tnc.soma();
				break;
				
			case 2:
				tnc.subitracao();
				break;

			case 3:
				tnc.multiplicacao();
				break;

			case 4:
				tnc.divisao();
				break;

		}




	}

}
