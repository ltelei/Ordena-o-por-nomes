# Ordena-o-por-nomes
Ordenação por nomes
Algoritmo "semnome"
//
//
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 24/04/2023
Var
nome : vetor [1..11] de caractere
x, troca: inteiro
temp: caracter


Inicio
para x de 1 ate 11 faca
      escreval("Digite um nome")
      Escreva ("---> ")
      leia(nome[x])
   fimpara
   troca <- 1
   enquanto (troca = 1) faca
      troca <- 0
      para x de 1 ate 11 - 1 faca
         se nome[x] > nome[x+1] entao
            temp <- nome[x+1]
            nome[x+1] <- nome[x]
            nome[x] <- temp
            troca <- 1
         fimse
      fimpara
   fimenquanto

   para x de 1 ate 11 faca
      escreval
      escreval(nome[x])
   fimpara

Fimalgoritmo
Fimalgoritmo
