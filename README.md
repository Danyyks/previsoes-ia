# 🤖 Previsão de Score de Crédito com Inteligência Artificial

Projeto em Python que utiliza Machine Learning para prever o score de crédito de clientes bancários, classificando-os como Bom, Ok ou Ruim com base em dados históricos.

## O que ele faz?

Ao executar o notebook, o projeto:  
**Carrega os dados:** Importa informações de clientes a partir de arquivos CSV.  
**Prepara os dados:** Converte variáveis categóricas em valores numéricos.  
**Treina modelos:** Aplica algoritmos de Machine Learning.  
**Avalia desempenho:** Compara modelos e mede a precisão.  
**Faz previsões:** Classifica o score de novos clientes automaticamente.

## Anatomia do Modelo

**Dados:** Informações financeiras e comportamentais de clientes.  
**Pré-processamento:** Transformação de dados textuais.  
**Modelos testados:** Random Forest e Nearest Neighbors (KNN).  
**Modelo final:** Random Forest (≈ 82% de precisão).  
**Entrega:** Classificação do score de crédito.

## Por que isso é legal?

**Aplicação real:** Problema comum no setor financeiro.  
**IA na prática:** Uso real de Machine Learning supervisionado.  
**Decisão baseada em dados:** Apoia concessão de crédito.  
**Didático:** Ideal para quem está aprendendo ML com Python.

## Dados Utilizados

**clientes.csv:** Base histórica para treinamento do modelo.  
**novos_clientes.csv:** Dados usados para novas previsões.  
**Origem:** Base educacional para fins de aprendizado.

## O que você precisa

Python 3.x.  
Jupyter Notebook.  
Bibliotecas: pandas e scikit-learn.  
Instalação das dependências:

```bash
pip install pandas scikit-learn
```

## Como usar

1. Certifique-se de que os arquivos abaixos estão na mesma pasta:  
   inicial.ipyns  
   clients.csv  
   novos_clientes.csv
2. Inicie o Jupyter Notebook:

```bash
jupyter notebook
```

3. Abra o arquivo inicial.ipynb
4. Execute as células em sequência para acompanhar:  
   Treinamento.  
   Avaliação.  
   Previsões.
