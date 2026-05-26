Projeto realizado para trabalho de conclusão, foi aplicado algoritmo de regressão linear ao conjunto de dados que
consta no link https://www.kaggle.com/datasets/harlfoxem/housesalesprediction.

Conforme proposto no documento o modelo foi treinado para prever o preço de venda
baseado em informações como número de banheiros, número de quartos, área e outros
dados contidos no conjunto extraído do Kaggle.

Após diversas transformações nos dados o modelo foi treinado utilizando uma proporção
de 80% base de treino e 20% base de testes.

Utilizando o Coeficiente de Determinação (R²) o modelo chegou a uma explicabilidade de
70,1% da variabilidade dos preços com base nos dados fornecidos.

Já o Erro Médio Absoluto (MAE) chegou a $127.493 indicando um erro médio em relação
aos preços reais.

Após remoção dos outliers o MAE chegou a $86.165 uma redução significativa em relação
a primeira modelagem, já o R² teve seu valor diminuído para 68,7%.

Projeto possue arquivo .PY e relatorio do trabalho realizados.
