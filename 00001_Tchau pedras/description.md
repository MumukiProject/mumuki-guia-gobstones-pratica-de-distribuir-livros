Como adiantamos na descrição dessa unidade, todo nosso **domínio** vamos representar com pedras de diferentes cores. O primeiro que vamos representar é quantos estudantes há em cada escola e, para isso, vamos usar pedras azuis (uma por estudante).

Poderíamos usar diretamente `Azul` cada vez que queremos falar de estudantes, mas isso tem alguns problemas:

1. não fica evidente que `Azul` quer dizer estudantes, e isso faz com que nosso programa seja mais difícil de compreender;
2. se em algum momento queremos mudar o `Azul` por outra cor, será necessário buscar **todos** os lugares em que diga `Azul` e mudar;
3. será mais difícil "decolar" do tabuleiro porque continuamos expressando nosso problema em termos de pedras.

> Devido a tudo isso, vamos  pedir então que você defina as seguintes funções:

> * `corEstudantes()`, que denote a cor `Azul` (sim, simples assim como você imagina);
> * `quantidadeEstudantes()`, que utilize a anterior e nos diga quantos estudantes há na célula atual.