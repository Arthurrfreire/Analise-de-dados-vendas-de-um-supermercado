## Análise Exploratória de Dados de Vendas (EDA)

Este projeto realiza uma Análise Exploratória de Dados (EDA) em um conjunto de dados de vendas, com foco em entender os fatores que influenciam as vendas em diferentes lojas.
Estrutura do Projeto

    Train-Set.csv: Arquivo de dados de treinamento.
    README.md: Este arquivo de documentação.
    exploratory_data_analysis.ipynb: Notebook Jupyter com o código Python para a análise.

## Dependências

Certifique-se de ter as seguintes bibliotecas Python instaladas:

    pandas
    matplotlib

## Processo de Análise

    Carregamento dos Dados:
        O conjunto de dados Train-Set.csv é lido em um DataFrame Pandas.

    Análise Descritiva:
        Visualização das primeiras linhas e estatísticas descritivas das variáveis numéricas.
        Contagem de valores únicos nas variáveis categóricas.

    Visualização de Dados:
        Gráfico de barras da média de vendas por loja (OutletID).
        Gráfico de dispersão entre o preço máximo de varejo (MRP) e as vendas (OutletSales).
        Gráfico de barras das vendas médias por tipo de produto (ProductType).
        Gráfico de barras das vendas médias por tamanho da loja (OutletSize).
        Gráfico de barras das vendas médias por tipo de localização da loja (LocationType).
        Gráfico de barras das vendas médias por ano de estabelecimento da loja (EstablishmentYear).
        Gráfico de dispersão entre a visibilidade do produto (ProductVisibility) e as vendas (OutletSales).

## Interpretação dos Resultados

## A análise revela:

    Vendas por Loja: Há uma variação significativa nas vendas médias entre as diferentes lojas.
    
    MRP e Vendas: Uma relação positiva moderada é observada entre o MRP e as vendas.
    
    Tipo de Produto: O tipo de produto influencia as vendas médias.
    
    Tamanho da Loja: O tamanho da loja parece ter um impacto nas vendas médias.
    
    Localização da Loja: O tipo de localização da loja também afeta as vendas médias.
    
    Ano de Estabelecimento: Lojas estabelecidas em anos diferentes apresentam vendas médias diferentes.
    
    Visibilidade do Produto: A visibilidade do produto parece ter uma influência limitada nas vendas.

## Considerações Finais

Esta análise exploratória fornece insights valiosos sobre os fatores que podem influenciar as vendas em diferentes lojas. As informações obtidas podem ser usadas para aprofundar a análise, construir modelos preditivos, ou desenvolver estratégias de vendas mais eficazes.

**Lembre-se:** A EDA é um processo iterativo, e os resultados podem levar a novas perguntas e a um maior refinamento da análise.
