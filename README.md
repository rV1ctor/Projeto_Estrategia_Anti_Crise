# 📊 Estratégia Anti-Crise - Análise Técnica usando Médias Móveis em ALPA4

## Descrição do Projeto

Este projeto tem como objetivo testar historicamente uma estratégia de **Análise Técnica** que utiliza o **cruzamento de médias móveis** para definir momentos de compra e venda do ativo **ALPA4**. A estratégia gerou um retorno positivo de **+160%**, comparado a uma desvalorização de **-90%** no ativo durante o mesmo período, validando a eficácia do modelo em momentos de crise.

## Desafio

Testar historicamente um modelo que compra ALPA4 baseado no cruzamento de médias móveis, comparando o desempenho da estratégia com o retorno do ativo e do índice Ibovespa.

## Passo a passo da implementação:

1. **Importar as bibliotecas** necessárias para a análise e modelagem.
2. **Obter os dados** históricos da ação ALPA4 através da API do Yahoo Finance.
3. **Definir as janelas** de tempo para as médias móveis curtas e longas.
4. **Calcular as médias móveis** de curto e longo prazo para determinar as tendências.
5. **Calcular o retorno diário** da ação ALPA4.
6. **Gerar sinais de compra e venda** com base no cruzamento das médias móveis.
7. **Calcular o retorno do modelo** com base nas operações sugeridas pelos sinais.
8. **Comparar o retorno do modelo** com o retorno da ação ALPA4 e do índice Ibovespa durante o mesmo período.
9. **Criar um gráfico** dos retornos da estratégia versus os retornos do ativo e do Ibovespa para visualizar o desempenho da estratégia.

## Resultados

Os resultados da análise mostram que a estratégia baseada no cruzamento de médias móveis conseguiu um desempenho significativamente melhor do que o ativo ALPA4 durante o período testado, com uma valorização de **+160%** frente a uma queda de **-90%** no preço do ativo.

## Tecnologias Utilizadas

- **Python**
- **Pandas**
- **Matplotlib**
- **Yahoo Finance API**
- **Numpy**

