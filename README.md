# Análise dos Jogos Olímpicos de 2024

Este repositório contém uma aplicação para analisar e visualizar dados dos Jogos Olímpicos de 2024. O dataset fornece informações detalhadas sobre medalhas e países vencedores, permitindo diversas análises e visualizações.

## Conteúdo

- `olympics_2024.csv`: O dataset com informações sobre medalhas e países vencedores. **Este dataset foi obtido do [Kaggle](https://www.kaggle.com/datasets/x1akshay/olympics-2024?resource=download)**.
- `olympics_analysis.ipynb`: Notebook Jupyter (ou Google Colab) para análise e visualização dos dados.


## Colunas do Dataset

- **Competitions**: Nome do jogo.
- **Rank**: Ranking do país na competição.
- **NOC**: Nome do país.
- **Gold**: Número de medalhas de ouro ganhas pelo país.
- **Silver**: Número de medalhas de prata ganhas pelo país.
- **Bronze**: Número de medalhas de bronze ganhas pelo país.
- **Total**: Total de medalhas ganhas pelo país.

## Análise e Visualização

O notebook inclui análises e visualizações, tais como:

- **Estatísticas Descritivas**: Visão geral das estatísticas básicas dos dados.
- **Medalhas Totais por País**: Total de medalhas ganhas por cada país.
- **Medalhas por Competição**: Total de medalhas ganhas em cada competição.
- **Distribuição das Medalhas por Tipo**: Total de medalhas de ouro, prata e bronze.

## Instruções de Uso

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/GabrielAugustoFerreiraMaia/OlimpiadasBI/tree/main
   cd OlimpiadasBI
2. **Instale Dependências**

    O notebook requer pandas, matplotlib e seaborn. Você pode instalar essas dependências usando:

    ```bash
    pip install pandas matplotlib seaborn
3. **Execute a Análise**

    Abra o notebook olympics_analysis.ipynb no Jupyter Notebook ou Google Colab e execute as células para carregar e analisar os dados.

4. **Visualize os Resultados**

    As visualizações e análises serão exibidas diretamente no notebook.
## Contribuições

Se você deseja contribuir para este projeto, sinta-se à vontade para enviar pull requests ou abrir issues.