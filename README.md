<h1>Amostragem Aleatória em R — Exemplos Práticos com a Base Iris</h1>

Este projeto apresenta, de forma direta e prática, como trabalhar com diferentes tipos de amostragem em R. A ideia é mostrar como gerar amostras simples, ajustar probabilidades, controlar a reprodutibilidade dos resultados e aplicar essas amostragens na famosa base iris. É um guia útil para quem está começando em estatística com R ou apenas quer revisar conceitos básicos de sorteio de dados.

A primeira parte explora amostragens simples, onde são gerados 150 valores compostos por zeros e uns, com reposição e probabilidades equivalentes. Isso permite observar como o R distribui os resultados quando ambos os valores têm a mesma chance de serem escolhidos. Em seguida, o mesmo processo é repetido, mas desta vez o zero recebe uma probabilidade maior do que o um. Esse ajuste deixa claro como a distribuição muda quando favorecemos um dos valores no sorteio.

Depois, o projeto avança para uma amostragem sem reposição, utilizando valores de 1 a 1000 para selecionar 150 elementos únicos. Esse tipo de amostragem é muito útil quando queremos garantir que nenhum número seja repetido, simulando sorteios mais restritivos ou seleções específicas dentro de um conjunto maior.

Com a base iris, o objetivo passa a ser criar uma amostra real aplicada a um conjunto de dados. Aqui é sorteada uma amostra onde aproximadamente 30% dos registros recebem o valor 1, permitindo filtrar apenas essa parte da base original. Dessa forma, é possível gerar um subconjunto menor da iris, ideal para testes, validações ou experimentos rápidos. O código também exibe as dimensões dessa amostra final, confirmando a proporção escolhida.

Por fim, é demonstrado como repetir experimentos garantindo sempre o mesmo resultado por meio de set.seed(). Esse passo é essencial em qualquer análise reprodutível, pois impede que cada execução produza valores diferentes — algo especialmente importante em projetos de ciência de dados.
