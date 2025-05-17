# 🏋️‍♀️ Análise de Churn e Estratégias de Retenção na Academia Model Fitness

Este projeto tem como objetivo **prever a rotatividade (churn)** dos clientes da academia Model Fitness, entender os **padrões de comportamento**, identificar **grupos de risco** e propor **ações estratégicas** para aumentar a retenção de clientes.

---

## 🎯 Objetivos do Projeto

- 📉 Prever a **probabilidade de rotatividade** de cada cliente no próximo mês
- 👥 Construir **agrupamentos de clientes** com perfis semelhantes
- 📊 Identificar **fatores que influenciam o churn**
- 💡 Propor **recomendações práticas** para reduzir a evasão e melhorar o relacionamento com os clientes

---

## 🔍 Etapas do Projeto

1. 📊 **Análise exploratória de dados (EDA)**
2. 🧠 **Modelagem preditiva** para identificar clientes propensos ao churn
3. 🔎 **Clusterização de perfis de clientes**
4. 📌 **Conclusões e recomendações estratégicas**

---

## 📁 Sobre os Dados

O conjunto de dados chama-se `gym_churn_us.csv` foi dividido em três categorias principais:

### ✅ Perfil atual dos clientes:
- `gender`, `age`, `Near_Location`, `Partner`, `Promo_friends`, `Phone`, `Lifetime`

### 📆 Dados de frequência e uso:
- `Group_visits`, `Avg_class_frequency_total`, `Avg_class_frequency_current_month`

### 💳 Informações contratuais e gastos:
- `Contract_period`, `Month_to_end_contract`, `Avg_additional_charges_total`

> 🎯 **Target:**  
`Churn` — variável binária que indica se o cliente saiu ou permaneceu naquele mês.

---

## 🧰 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas)
![Seaborn](https://img.shields.io/badge/-Seaborn-6B6B6B?style=for-the-badge)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📌 Resultados Esperados

- Identificação dos **clientes com maior risco de evasão**
- Perfis de clientes mais engajados e mais propensos a permanecer
- Recomendações para:
  - 📍 Grupos-alvo estratégicos
  - 📈 Ações promocionais ou personalizadas
  - 🗓️ Ajustes nos contratos ou serviços oferecidos

---

## 📈 Métricas de Avaliação do Modelo

- Acurácia, Precisão, Recall e F1-Score
- Matriz de Confusão
- Análise de Importância das Variáveis

