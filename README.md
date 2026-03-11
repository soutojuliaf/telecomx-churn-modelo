# TelecomX — Modelos Preditivos de Churn

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3+-F7931E?logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20desenvolvimento-yellow)

---

## Sobre o Projeto

Este repositório contém a **Parte 2** do desafio TelecomX, focada na construção de **modelos preditivos de churn** (evasão de clientes).

A TelecomX vem sofrendo com um alto índice de cancelamentos e, a partir dos dados tratados na etapa de ETL (Parte 1), o objetivo agora é identificar **quais clientes têm maior probabilidade de cancelar o serviço** — antes que isso aconteça.

>  **Parte 1 — ETL e Análise Exploratória:** [link para o repositório da Parte 1]

---

## Estrutura do Repositório

```
telecomx-churn-modelo
 ┣ TelecomX_Modelo.ipynb   # Notebook principal com os modelos preditivos
 ┣ dados_tratados.csv      # Dataset limpo e tratado (gerado na Parte 1)
 ┗ README.md               # Este arquivo
```

---

## Objetivos

- Carregar os dados tratados da Parte 1
- Preparar os dados para modelagem (encoding, normalização, balanceamento)
- Treinar e avaliar modelos preditivos de classificação
- Identificar as variáveis mais importantes para o churn
- Gerar recomendações baseadas nos resultados dos modelos

---

## Modelos Utilizados

| Modelo | Biblioteca |
|--------|-----------|
| Regressão Logística | scikit-learn |
| Random Forest | scikit-learn |
| Gradient Boosting (XGBoost) | xgboost |

---

## Métricas de Avaliação

- Acurácia
- Precisão, Recall e F1-Score
- Matriz de Confusão
- Curva ROC / AUC

---
## Dados

Os dados utilizados nesta etapa foram gerados na Parte 1 do desafio, após o processo de ETL:

```python
## Autora: Julia Souto

Feito como parte do **Challenge de Data Science — Alura**

---


Este projeto está sob a licença MIT.
