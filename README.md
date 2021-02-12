# Calculadora
Em Portugol, calculadora que imprima as 4 operações.

algoritmo "calculadora "
var
   n1,n2:real
   op:inteiro
inicio
    escreval("Informe o 1º número:")
    leia(n1)
    escreval("Informe o 2º número:")
    leia(n2)
    escreval("Informe a operação:")
    escreval("1-somar 2-subtrair 3-mutliplicação 4-divisão")
    leia(op)
    se(op = 1)entao
       escreval("A soma = ",n1+n2)
    fimse
    se(op = 2)entao
       escreval("A subtração = ",n1-n2)
    fimse
    se(op = 3)entao
       escreval("A mutiplicação = ",n1*n2)
    fimse
    se(op = 4)entao
        se(n2 = 0)entao
          escreval("Não exite divisão por zero")
        fimse
        se(n2>0)entao
           escreval("A divisão dos números eh: ",n1/n2)
        fimse
    fimse
fimalgoritmo
