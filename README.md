# Checkpoint 01: Data Science e Machine Learning com Python -  SERS

Este repositório contém a resolução do **Checkpoint 01** da disciplina de Soluções em Energias Renováveis e Sustentáveis.  
O projeto aborda **análise exploratória, pré-processamento de dados, modelagem preditiva e clustering**, utilizando a linguagem **Python**.

---

## 📂 Estrutura do Projeto

O trabalho está dividido em quatro partes, cada uma explorando diferentes técnicas e datasets:

### Parte 1: Exercícios Iniciais (Questões 1-20)  
Análise exploratória e pré-processamento do dataset **Individual Household Electric Power Consumption**.  
As tarefas incluem manipulação de datas, cálculo de médias, visualização de dados e tratamento de valores ausentes.

### Parte 2: Exercícios Adicionais (Questões 21-25)  
Aprofundamento na análise de séries temporais, autocorrelação, redução de dimensionalidade com PCA e comparação entre modelos de regressão no mesmo dataset.

### Parte 3: Novo Dataset (Questões 26-35)
Análise do dataset **Appliances Energy Prediction**, focando em correlações, modelagem com Regressão Linear Múltipla, Random Forest e classificação binária.

---

## 📊 Descrição dos Datasets

Dois datasets foram utilizados para a realização dos exercícios:

### 1. Individual Household Electric Power Consumption  
- **Período:** Dez/2006 a Nov/2010 (47 meses)  
- **Granularidade:** Leituras por minuto (~2 milhões de registros)  
- **Descrição:** Consumo de energia em uma residência na França, incluindo potência ativa, reativa, voltagem, intensidade e três sub-medidores.  
- **Observação:** Possui ~1,25% de valores ausentes

### 2. Appliances Energy Prediction  
- **Período:** ~4,5 meses  
- **Granularidade:** Leituras a cada 10 minutos  
- **Descrição:** Consumo de energia de eletrodomésticos monitorado junto a variáveis ambientais (temperatura, umidade interna/externa e clima do aeroporto de Chievres, Bélgica).  
- **Observação:** Inclui duas variáveis aleatórias para testes de modelos e filtragem de atributos.  
