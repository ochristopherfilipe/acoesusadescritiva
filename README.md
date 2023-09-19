# Análise Descritiva de Volatilidade das Ações nos EUA

Este código realiza uma análise descritiva da volatilidade das ações da Apple (AAPL), Amazon (AMZN) e Disney (DIS) no período de setembro de 2021 a setembro de 2023. A análise inclui a coleta de dados, cálculo da amplitude de variação diária e a criação de um gráfico de linha para visualizar a variação da amplitude ao longo do tempo.

## Passos para Executar o Código

1. Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las com os seguintes comandos:
```Python
pip install yfinance pandas plotly
```
2. Execute o código Python fornecido no arquivo analise_acoes_usa.py. Este código realiza as seguintes etapas:

- Baixa os dados das ações da AAPL, AMZN e DIS no período especificado usando a biblioteca yfinance.
- Salva os dados em um arquivo CSV na pasta "output".
- Calcula a amplitude de variação dentro do dia para cada ação.
- Cria um gráfico de linha com o Plotly para visualizar a variação da amplitude ao longo do tempo.

3. Os resultados da análise e o gráfico estão no arquivo.

## Observações da Análise
A análise destaca que, durante o período em questão, a Apple (AAPL) apresentou maior volatilidade em seu preço de ação em comparação com a Amazon (AMZN) e a Disney (DIS). Isso sugere que a Apple experimentou oscilações significativas provavelmente devido à natureza dinâmica do mercado de tecnologia. Por outro lado, a Amazon e a Disney mantiveram relativa estabilidade, aproveitando sua diversificação de negócios e resiliência em seus respectivos setores.

Esse código pode ser usado como ponto de partida para análises mais aprofundadas ou estudos comparativos de volatilidade de ações no mercado financeiro dos EUA.
