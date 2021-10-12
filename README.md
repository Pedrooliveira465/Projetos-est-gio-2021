# Projetos-est-gio-2021
Meus projetos do estágio
programa {
	funcao inicio() {
		inteiro doces
		cadeia v
		real doce1 = 0.50, doce2 = 1.00, doce3 = 1.50, somadoce = 0.0, somadoce2 = 0.0
		
		
		escreva("==========================\n")
		escreva("        Bem-Vindo         \n")
		escreva("==========================\n")

		escreva("Temos as seguintes opções de doces: \n")
		escreva("1. Brigadeiro - R$ 0,50\n")
		escreva("2. Beijinho - R$ 1,00\n")
		escreva("3. Casalzinho - R$ 1, 50\n")
		escreva("Digite sua opção de doce: ")
		leia(doces)
		            se(doces == 1){
		            limpa()
		                somadoce = 0.50
		                escreva("Sua compra foi realizada, aproveite o brigadeiro.\n")
		            }
		            senao se(doces == 2){
		            limpa()
		                somadoce = somadoce + doce2
		                escreva("Sua compra foi realizada, aproveite o beijinho.\n")
		                somadoce = 1.0
		            }
		            senao se(doces == 3){
		            limpa()
		                somadoce = somadoce + doce3
		            escreva("Sua compra foi realizada, aproveite o casalzinho. \n")
		            somadoce = 1.50
	                }
	                
	                escreva("\nDeseja comprar mais alguma coisa? (s/n)\n")
                    leia(v)
	                                            
	                 se(v == "s"){
	                   escreva("==========================\n")
		               escreva("        Bem-Vindo         \n")
		               escreva("==========================\n")
		
		               escreva("=======================================\n")
		               escreva("  Temos as seguintes opções de doces: \n")
		               escreva("1. Brigadeiro - R$ 0,50\n")
		               escreva("2. Beijinho - R$ 1,00\n")
		               escreva("3. Casalzinho - R$ 1, 50\n")
		               escreva("Digite sua opção de doce: ")
		               leia(doces)
		                   se(doces == 1){
		                   limpa()
		                      somadoce2 = 0.50
		                      escreva("Sua compra foi realizada, aproveite o brigadeiro.\n")
		                      }
		                      senao se(doces == 2){
		                      limpa()
		                      escreva("Sua compra foi realizada, aproveite o beijinho.\n")
		                      somadoce2 = 1.0
		                      }
		                      senao se(doces == 3){
		                      limpa()
		                      escreva("Sua compra foi realizada, aproveite o casalzinho. \n")
		                      somadoce2 = 1.50
	                          }
	                          escreva("========================================\n")
		                      escreva("        Comanda\n")
		                      escreva("========================================\n")
                              escreva("1................",somadoce)
                              escreva("\n2................",somadoce2)
	                                               
}
}
}
