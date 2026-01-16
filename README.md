# 🤖 Projeto Python IA: Previsão de Score de Crédito

Este projeto utiliza Inteligência Artificial para prever o score de crédito de clientes de um banco. Com base nas informações dos clientes, o modelo classifica o score como **Bom**, **Ok** ou **Ruim**.

## 📝 Descrição

O objetivo deste projeto é construir um modelo de Machine Learning que analise os dados de um cliente e determine automaticamente seu score de crédito. Isso ajuda o banco a tomar decisões mais rápidas e precisas sobre a concessão de crédito.

## 🚀 Como Funciona

O projeto é desenvolvido em um notebook Jupyter (`inicial.ipynb`) e segue os seguintes passos:

1.  **Carregamento dos Dados** :
    *   Os dados dos clientes são carregados a partir do arquivo `clientes.csv`.

2.  **Pré-processamento dos Dados** :
    *   As informações em texto (como `profissao`, `mix_credito` e `comportamento_pagamento`) são transformadas em números para que o modelo de IA possa entendê-las.

3.  **Treinamento do Modelo** :
    *   Dois modelos de Inteligência Artificial são treinados:
        *   **Random Forest** (Árvore de Decisão)
        *   **KNN** (K-Nearest Neighbors)
    *   Os modelos aprendem a partir dos dados de clientes existentes para identificar padrões.

4.  **Avaliação do Modelo** :
    *   Os modelos são avaliados para ver qual deles faz as previsões mais precisas. Neste caso, o modelo **Random Forest** foi o melhor, com uma precisão de aproximadamente 82%.

5.  **Novas Previsões** 🔮:
    *   O modelo treinado é usado para prever o score de crédito de novos clientes, que estão no arquivo `novos_clientes.csv`.

## 🛠️ Como Usar

Para executar o projeto, você precisa ter o Python e o Jupyter Notebook instalados. Siga os passos:

1.  **Abra a pasta do projeto:**
    *   Certifique-se de que todos os arquivos do projeto (`inicial.ipynb`, `clientes.csv`, `novos_clientes.csv`) estejam na mesma pasta.
2.  **Instale as dependências:**
    ```bash
    pip install pandas scikit-learn
    ```
3.  **Abra o Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  **Execute o notebook `inicial.ipynb`** para ver todo o processo de análise e previsão.

## 📁 Arquivos

*   `inicial.ipynb`: O notebook com todo o código do projeto.
*   `clientes.csv`: A base de dados com as informações dos clientes.
*   `novos_clientes.csv`: A base de dados com os novos clientes para fazer a previsão.
*   `README.md`: Este arquivo que você está lendo. 😊
