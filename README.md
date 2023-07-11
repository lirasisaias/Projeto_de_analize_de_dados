## Projeto de ciência de dados - Ferramenta de Previsão de Preço de Imóvel

### Esse projeto se trata de um modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel no Airbnb do Rio de janeiro.

### As bases de dados foram retiradas do site kaggle: https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro

- As bases de dados são os preços dos imóveis obtidos e suas respectivas características em cada mês.
- Os preços são dados em reais (R$)
- Temos bases de abril de 2018 a maio de 2020, com exceção de junho de 2018 que não possui base de dados

## Primeiramente importo as bibliotecas

- Pandas
- Para gerenciar banco de dados
- Pathlib
- Para gerenciar pastas
- Numpy
- Para a manipulação de varios dados
- Seaborn
- Para visualizar melhor os dados
- Matplotlib
- Para gerar gráficos para a melhor manipulação de dados
- Sklearn
- Para fazer a previsão dos preços

### Apos a importação consolidamos a base de dados

- Como temos muitas colunas o modelo pode ficar lento.
- Além disso uma análise rápida permite ver que várias colunas não são necessárias para o nosso modelo, por isso, vamos excluir algumas colunas da nossa base de dados
- Tipos de colunas que vamos excluir:
    1. ID, links e informações não relevantes para o modelo
    2. Colunas repetidas ou extremamente parecidas com outra (que dão a mesma informação para o modelo)Ex: Data x Ano/Mês
    3. Colunas preenchidas com texto livre -> Não rodaremos nenhuma análise de palavras ou algo do tipo
    4. Colunas em que todos os valores são iquais

### Depois verificamos se esta tudo certo e os tipos da nossa base de tados.

### En fim fazemos uma Análise Exploratoria e finalizamos o banco de dados para fazemos o teste do modelo.

### Depois salvamo o nosso modelo e crio outro aruivo para podermos executar a nossa previsão.
