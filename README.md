# 🍦 Prevendo Vendas de Sorvete com Machine Learning (Azure)

Este projeto foi desenvolvido como parte de um desafio da DIO para aplicar conceitos de **Machine Learning** na predição de vendas de sorvete com base na temperatura. O objetivo é ajudar sorveterias a prever a demanda e, com isso, **reduzir desperdícios e aumentar os lucros**.

## 📊 Objetivo

Construir um modelo de regressão que:
- Preveja o número de vendas de sorvete com base na temperatura.
- Seja gerenciado via MLflow.
- Possa ser implantado na nuvem (Azure) para uso em tempo real.
- Tenha reprodutibilidade por meio de um pipeline estruturado.

---

## 🧪 Tecnologias Utilizadas

- Python
- Pandas / Numpy
- Scikit-learn
- Matplotlib / Seaborn
- MLflow
- Azure Machine Learning (Studio)

---

## 📁 Estrutura do Projeto
/users
│
├── temperatura_vendas.csv # Dados com temperatura e vendas
├── icecream_sales_predict.ipynb # Notebook com todo o código do projeto
├── model.pkl # Modelo treinado salvo
└── README.md # Este documento

---

## 🚀 Etapas do Projeto

### 1. Criação do workspace
![dio1](https://github.com/user-attachments/assets/d219ae4c-ec71-47b8-b888-2dee071b910a)

### 2. Carregamento dos Dados
Os dados foram carregados a partir do arquivo `temperatura_vendas.csv`, contendo duas colunas:
- `Temperatura` (em °C)
- `Vendas` (número de sorvetes vendidos)
![dio5](https://github.com/user-attachments/assets/42dae5ca-4df2-48ff-9d6a-83fc5ee16d8a)

### 3. Treinamento do modelo
![dio7](https://github.com/user-attachments/assets/34f3dba8-413c-4418-a7bf-add185271bb7)

### 4. Salvando o modelo
![dio8](https://github.com/user-attachments/assets/0a2393aa-2dc4-44bd-b407-ef60fcb01f80)

### 5. Deploy
![dio9](https://github.com/user-attachments/assets/3be91c92-f80b-4564-8e56-b9325e451c42)

