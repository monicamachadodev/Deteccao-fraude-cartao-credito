<img src="https://github.com/monicamachadodev/Deteccao-fraude-cartao-credito/blob/main/deteccao-de-fraude.png">

# Visão Geral

Este estudo tem como objetivo construir e comparar modelos de detecção de fraude em transações de cartões de crédito, utilizando técnicas de aprendizado de máquina, especificamente **Árvores de Decisão e Máquinas de Vetores de Suporte (SVM)**. O processo envolve o treinamento, a validação e a avaliação do desempenho de ambos os modelos, com o intuito de identificar qual abordagem apresenta maior eficácia na identificação de transações fraudulentas. A comparação será baseada em métricas de desempenho, como precisão, recall, F1-score e AUC-ROC, visando fornecer insights sobre as vantagens e limitações de cada método no contexto de detecção de fraude.

## Problema de Negócio: 

A instituição financeira enfrenta desafios constantes na detecção precoce de fraudes em transações de cartão de crédito. O volume de transações é significativo, e é crucial identificar padrões suspeitos que possam indicar atividades fraudulentas.

## Objetivos:

> - Desenvolver e comparar modelos de machine learning para a detecção de fraudes em transações de cartão de crédito.
> - Aprimoramento da precisão na identificação de transações fraudulentas, a minimização de falsos positivos.
> - Melhoria da eficiência do processo para lidar com grandes volumes em tempo real
> - Garantir a confiabilidade e segurança das transações para proporcionar uma experiência positiva aos clientes.

## Pré-requisitos 

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
### Bibliotecas:
  
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
```bash
pip install plotly pandas numpy
```

## Estrutura do Projeto
1. detecao_fraude_cartao_credito.ipynb: Jupyter Notebook contendo o código e a análise do projeto.
2. creditcard.csv: Conjunto de dados de transações de cartão de crédito.

## Executando o Código

Clone ou faça o download do repositório.

Certifique-se de ter os pré-requisitos instalados.

Execute o scripy:
```bash
detecao_fraude_cartao_credito.ipynb jupiter notebook
```

## Resultados obtidos:

1. **Análise Exploratória de Dados:**
O conjunto de dados inicial continha transações de cartão de crédito, com um número significativo de observações e variáveis.
Foi realizada uma análise exploratória para compreender a distribuição das classes e das características.

2. **Pré-processamento de Dados:**
O conjunto de dados foi inflado para aumentar a quantidade de observações, permitindo uma melhor generalização dos modelos.
A normalização e padronização foram aplicadas para preparar os dados para treinamento.

3. **Treinamento de Modelos:**
Foram treinados modelos de árvore de decisão e máquina de vetores de suporte (SVM) usando tanto `Scikit-Learn` quanto `Snap ML`.
Os modelos foram treinados utilizando a estratégia de pesos amostrais balanceados para lidar com o desbalanceamento das classes.

4. **Avaliação de Desempenho:**
Métricas como a Área sob a Curva ROC (ROC-AUC) foram utilizadas para avaliar o desempenho dos modelos.
Os modelos foram comparados quanto à precisão na detecção de fraudes e eficiência de treinamento.

5. **Resultados Específicos:**
O modelo de árvore de decisão e o modelo SVM treinados com `Snap ML` apresentaram velocidades de treinamento significativamente mais rápidas em comparação com suas contrapartes do `Scikit-Learn`.
As pontuações ROC-AUC indicaram desempenho competitivo entre os modelos treinados com ambas as bibliotecas.

# Conclusão:

O projeto desenvolveu modelos de Machine Learning para detecção de fraudes em transações de cartão de crédito, comparando eficiência entre `Scikit-Learn` e `Snap ML`. Os resultados sugerem que o 
`Snap ML` pode oferecer benefícios significativos em termos de eficiência de treinamento, sem comprometer o desempenho preditivo em relação ao `Scikit-Learn`.

As métricas de desempenho indicam que os modelos são capazes de identificar eficientemente transações fraudulentas, contribuindo para a segurança financeira e a confiança dos clientes. No entanto, é importante destacar que a escolha entre `Scikit-Learn` e `Snap ML` deve considerar não apenas a eficiência de treinamento, mas também a manutenção, escalabilidade e outros requisitos específicos do projeto.

## Contribuições
Contribuições são bem-vindas! 🫶 

Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests com melhorias.

[![PyPi license](https://badgen.net/pypi/license/pip/)](https://pypi.org/project/pip/)
