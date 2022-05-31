1 – Carregar o data set Iris (ele está disponível na sci-kit learn) e gerar gráficos 2D escolhendo a cada gráfico 2 atributos dos 4 disponíveis na base de dados, colorindo os elementos de acordo com sua classe.

2- Usando a ferramenta tree da sci-kit learn, crie uma árvore de decisão usando a base de dados. Além disso, gere uma visualização da árvore gerada usando a ferramenta graphviz.

3- Crie um classificador naive bayes usando a função GaussianNB.

4- Compare o desempenho dos dois classificadores que criou. Para isso, você deve separar a base de dados em duas bases menores: treinamento, com 60% dos dados e teste, com 40%. Para isso, você pode usar a função train_test_split, que divide automaticamente as duas bases de maneira aleatória. Depois de dividida a base, você deve realizar o treinamento e o teste dos dois modelos (árvore de decisão e naive bayes). Por fim, você deve usar a função metrics.accuracy_score para verificar quanto do resultado da classificação foi correto. Como a função train_test_split gera bases de maneira aleatória, você deve executar tal procedimento 30 vezes e por fim calcular a média dos resultados de cada modelo para definir qual foi o modelo de melhor desempenho.
