# CursoJS

JavaScript /* comentário para JS e css */  <!---- comentário para html ---->
Variáveis - recebem dados e devem: - começa com letras, $ ou _.
                                   - Não podem começar com números.
                                   - Data types:
                                   - String
                                   - Number
                                   - Boolean
window.prompt() - sempre retorna uma string
+ serva concatenação de strings e para adição de numeros
para somar dois números que vieram de um prompt é necessário converter eles de string para números: Number.parseInt(n) - numero inteiro
                                                                                                    Number.parseFloat(n) - numero com vírgula
#06                                                                                                    Number(n) - o JS sabe e se vira
de numeros para strings: String(n) ou n.toString()
s.length // quantos caracteres tem a string
s.toUpperCase() // todo para MAIÚSCULO
s.toLowerCase() // tudo para minúsculo
<strong> Para negrito  </stong>

formatando números:
n1.toFixed(2) - duas casas depois da virgula
n1.toFixed(2).replace( ".", ",") - duas casas depois da virgula e trocar o ponto pela virgula
n1. toLocaleString('pt-BR', {style: 'currency, currency: 'BRL'})

#07 OPERADORES
Aritiméticos - igual a Python
Atribuição - Ps: x = x + 1 é a mesma coisa que x +=1 e também igual a x++. n = 10</br> n += 5 </br> n == 15
Identidade - 5 == "5" --> True, pois 5 = 5 agora, 5 ==="5" --> False, pois não é to mesmo tipo um é n e o outro s. 
Lógicos - ! - primeiro - negação / && -  segundo- onjunção (and) consegui as duas fico satisfeito /  terceiro - || -  disjunção (ou) consegui pelo menos uma
idade >=15 $$ idade<= 17// a idade está entre 15 e 17?
estadp =="SP" || estado =="RJ"// o estado é igual ao SP ou a RJ?
slário > 1500 $$ sexo != "M" // o salário é acima de 1500 e não é homem? 
Ternários: 
Ex: media > 7,5? "APROVADO": "REPROVADO"
  se for verdade? TRUE: FALSE
#08 DOM - Document Object Model 
![Captura de Tela 2023-10-01 às 20 29 57](https://github.com/rafasborges/CursoJS/assets/107574229/ea2edaad-0242-4e48-93c8-40745deb530a)
