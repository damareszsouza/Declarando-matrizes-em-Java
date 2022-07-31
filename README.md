# Declarando-matrizes-em-Java
Ir para o conteúdo principal
 
Moodle - IFRS

Programação Básica com Java III - Turma 2022B
Painel Meus cursos  PBJIII2022B 3. Matrizes  3.3. Declarando Matrizes
3.3. Declarando Matrizes
Uma matriz pode ser declarada em pseudocódigo de forma muito semelhante à declaração de um vetor, pois um vetor é uma matriz de dimensão 1. A diferença é que ao declararmos matrizes, especificamos dois ou mais intervalos de índices dentro dos colchetes, separados por vírgulas. Assim, declaramos uma matriz bidimensional de N linhas e M colunas como:

VAR

                    nome da variável : VETOR [ 1..N, 1..M ] DE tipo

Assim, poderíamos declarar a matriz mostrada no tópico anterior como segue:

VAR


                   matriz : VETOR [ 1..3, 1..5 ] DE caractere

Podemos assim, declarar uma matriz para armazenar o estado do tabuleiro do jogo da velha e complementar o algoritmo do tópico 3.1, como mostrado abaixo. Utilizamos o tipo caractere pois pretende-se armazenar as letras X e O para indicar as jogadas efetuadas pelos jogadores.




Algoritmo “Jogo da Velha”

var


jogador: caractere


linha, coluna: inteiro


tabuleiro: vetor [1..3, 1..3] de caractere;


inicio

       jogador ← ‘X’


enquanto condição faça


       escreva “Jogador ”, jogador, “ é a sua vez.”


       leia linha, coluna


      


       fazer a jogada na linha e coluna indicadas


 


       se jogador = ‘X’ então


                    jogador ← ‘O’


       senão


                    jogador ← ‘X’


       fim se


fim enquanto

fim

Última atualização: domingo, 1 nov 2020, 18:58
Seguir para...
Academi
Dúvidas? 
Perguntas frequentes

Fale conosco | Suporte | Contato

Informação
Termos e Condições de Uso
Aviso de Privacidade e Proteção de Dados Pessoais
Contato
Rua Gen. Osório, 348, Bento Gonçalves/RS
Siga-nos
Copyright © 2017 - Desenvolvido por LMSACE.com. Distribuído por Moodle

Português - Brasil ‎(pt_br)‎
English ‎(en)‎
Español - Internacional ‎(es)‎
Français ‎(fr)‎
Italiano ‎(it)‎
Português - Brasil ‎(pt_br)‎
Mudar para o tema padrão
