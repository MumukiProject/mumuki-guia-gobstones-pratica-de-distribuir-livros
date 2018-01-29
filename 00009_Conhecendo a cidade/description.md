Falta apenas o último passo, fazer com que um facilitador percorra uma cidade completa. Assim é como se vê uma cidade com seis ruas no nosso tabuleiro:

<gs-board>
  GBB/1.0
    size 6 7
    cell 0 0 Rojo 6
    cell 0 1 Verde 3
    cell 2 1 Azul 6 Negro 3
    cell 3 1 Azul 13
    cell 0 2 Verde 5
    cell 1 2 Negro 3
    cell 3 2 Negro 7
    cell 4 2 Azul 13 Negro 13
    cell 5 2 Azul 5 Negro 1
    cell 0 3 Verde 2
    cell 1 3 Azul 15 Negro 4
    cell 2 3 Azul 11 Negro 1
    cell 0 4 Verde 3
    cell 1 4 Azul 4 Negro 4
    cell 2 4 Negro 7
    cell 3 4 Negro 10
    cell 0 5 Verde 4
    cell 4 5 Azul 2 Negro 2
    cell 0 6 Verde 1
    cell 1 6 Azul 1 Negro 2
    head 0 0
</gs-board>

Cada cidade tem uma quantidade de ruas diferente, e cada rua tem seu próprio comprimento. Isso já sinalizamos no tabuleiro da seguinte maneira:

* as pedras vermelhas da origem indicam **quantas ruas tem**  na nossa cidade;
* as pedras verdes de cada fila indicam **quão comprida é a rua**.

> Seu trabalho é escrever o procedimento `PercorrerCidade()`, que realize um **percurso** por todas as ruas da cidade, fazendo o trabalho necessário.