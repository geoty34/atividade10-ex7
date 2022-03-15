# atividade10-ex7
programa
{
	
	funcao inicio()
	{

	inteiro nota
		escreva("Digite uma nota entre 1 e 10: ")
		leia(nota)

			enquanto(nota < 1 ou nota > 10 ){
				escreva ("Valor inválido, o valor deve estar entre 1 ou 10.\n Escreva novamente:")
				leia(nota)}

			se (nota < 6 e nota >= 1){
				escreva ("Você reprovou")
			}
			senao{
				escreva ("Você passou")
			}
		}
	}
