# Linguagens_TrabalhoPratico1

## Sobre o Trabalho
* !!! O jogo não limita em nada utilizar qualquer predicado, somente diz o que se deseja e qual deve
ser o resultado.

Esse trabalho deve:
* Ser implementado em linguagem Prolog.
* Ser desenvolvido de forma individual ou dupla.
* Estar bem documentado e identificado.

## O problema
Considere uma matriz M de números inteiros e um marcador P em uma dada célula (X,Y) da M.
P pode andar para cima, para baixo, direita e esquerda de M, desde que essa célula tenha um valor
maior ou igual a zero. Quando P sai de (X,Y) para um nova célula, seu valor deverá ser decrementado.

Desevolva um programa lógico que dado uma matriz M qualquer e um posição para o marcador P,
determine uma lista de passos que deve ser seguidos para que essa matriz fique com o valor negativo
em todas as suas céluas. Deve-se anotar todas as possibilidades de passos e deve-se escrever em um
arquivo o seu resultado.

Por exemplo, é passado a Matriz 1 e a posição (0, 0). Caso desejamos ir para a direita, irá gerar a nova
Matriz 2, em que estamos na posição (0, 1), por´em a posi¸c˜ao (0, 0) agora é 0, assim, só é permitido
andar mais uma vez sobre essa posição.

Portando o objetivo é achar o caminho que seja capaz e andar por toda a matriz sem que se passe por
valores negativos. O passo a passo que tem que ser dado para alcançar todas as posições da matriz
