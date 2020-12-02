algoritmo "professora"
var
   trabalho, seminario, prova, media :numerico
   alunos, conta : inteiro
inicio
   escreval("Digite a quantidade de alunos da turma: ")
   leia(alunos)
   para conta de 1 ate alunos passo 1 faca
        escreval("Digite a nota do trabalho:")
        leia(trabalho)
        escreval("Digite a nota do seminario:")
        leia(seminario)
        escreval("Digite a nota da prova:")
        leia(prova)
        media <- (trabalho * 20 + seminario * 30 + prova * 50) / 100
        escreval("Media do aluno: ", media)
    fimpara
fimalgoritmo
