# Checkpoint 01: Data Science e Machine Learning com Python - SERS

Este repositório contém a resolução do **Checkpoint 01** da disciplina de **Soluções em Energias Renováveis e Sustentáveis**.  
O projeto aborda **análise exploratória, pré-processamento de dados, modelagem preditiva e clustering**, utilizando a linguagem **Python**.

---

## 📂 Estrutura do Projeto

O trabalho está dividido em três partes, cada uma explorando diferentes técnicas e datasets:

### Parte 1: Exercícios Iniciais (Questões 1-20)  
Análise exploratória e pré-processamento do dataset **Individual Household Electric Power Consumption**.  
Inclui manipulação de datas, cálculo de médias, visualização de dados e tratamento de valores ausentes.

### Parte 2: Exercícios Adicionais (Questões 21-25)  
Aprofundamento na análise do dataset com **séries temporais, autocorrelação, redução de dimensionalidade com PCA** e comparação entre modelos de regressão.

### Parte 3: Novo Dataset (Questões 26-35)  
Análise do dataset **Appliances Energy Prediction**, focando em **correlações, regressão linear múltipla, Random Forest** e criação de um **modelo de classificação binária**.

---

## 📊 Descrição dos Datasets

### 1. Individual Household Electric Power Consumption  
- **Período:** Dez/2006 a Nov/2010 (47 meses)  
- **Granularidade:** Leituras por minuto (~2 milhões de registros)  
- **Descrição geral:** Consumo de energia em uma residência na França, incluindo potência ativa, potência reativa, voltagem, intensidade de corrente e três sub-medidores.  
- **Principais variáveis:**  
  - `global_active_power`: Potência ativa global média por minuto (kW)  
  - `global_reactive_power`: Potência reativa global média por minuto (kVAr)  
  - `voltage`: Tensão média por minuto (V)  
  - `global_intensity`: Intensidade da corrente média (A)  
  - `sub_metering_1`: Cozinha → cargas menores (lava-louças, forno, micro-ondas)  
  - `sub_metering_2`: Lavanderia → cargas médias (máquina de lavar, secadora, geladeira)  
  - `sub_metering_3`: Aquecedor de água elétrico e ar-condicionado → cargas maiores  
- **Observação:** Possui ~1,25% de valores ausentes.  

---

### 2. Appliances Energy Prediction  
- **Período:** ~4,5 meses  
- **Granularidade:** Leituras a cada 10 minutos  
- **Descrição geral:** Consumo de energia de eletrodomésticos em uma residência, junto a variáveis ambientais internas (temperatura/umidade em diferentes cômodos) e externas (clima do aeroporto de Chievres, Bélgica).  
- **Principais variáveis:**  
  - `Appliances`: Energia consumida pelos eletrodomésticos (Wh)  
  - `lights`: Consumo das luzes da residência (Wh)  
  - `T1 ... T9`: Temperaturas em diferentes cômodos (°C)  
  - `RH_1 ... RH_9`: Umidades relativas em diferentes cômodos (%)  
  - `To`, `Pressure`, `RH_out`, `Wind speed`, `Visibility`, `Tdewpoint`: Variáveis externas do clima  
- **Observação:** Inclui dados climáticos horários interpolados a cada 10 minutos.  

---
