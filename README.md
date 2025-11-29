# Projeto de Análise de Dados – Fórmula 1 (MBA)

Este projeto foi desenvolvido como parte do **MBA em Engenharia e Ciências de Dados**, com o objetivo de construir um fluxo completo de análise de dados utilizando **Pentaho Data Integration (Kettle)**, **Python** e **Power BI**.

A solução final consolida dados de pilotos da Fórmula 1 em um processo de **ETL + modelagem + visualização analítica**, demonstrando domínio das principais ferramentas utilizadas em ambientes corporativos de dados.

---

## 🎯 Objetivo do Projeto

Criar um pipeline de dados completo envolvendo:

- **Junção e tratamento inicial dos dados no Pentaho**
- **Limpezas, padronizações e análises em Python**
- **Construção de Dashboard interativo no Power BI**

O objetivo final é gerar uma análise clara e visual do desempenho e características dos pilotos de Fórmula 1 ao longo dos anos.

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Função |
|------------|--------|
| **Pentaho Data Integration (Kettle)** | Junção de datasets, limpeza inicial e preparação dos dados |
| **Python (Pandas, NumPy)** | Limpeza avançada, padronização e análise exploratória |
| **Jupyter Notebook** | Desenvolvimento e documentação do processo analítico |
| **Power BI** | Criação do dashboard final com métricas e visualizações |

---

## 📂 Estrutura do Repositório

```
📁 f1-data-project/
├── data/
│   ├── F1_base_eventos.csv
│   ├── F1_base_fatais.csv
│   ├── F1_base_pilotos.csv
│   ├── F1_base_temporadas.csv
│   ├── F1DriversDataset.csv
│   ├── F1DriversTratados.csv
│   └── fatal_accidents_drivers.csv
│
├── pentaho/
│   └── f1driverstransformation.ktr
│
├── dashboardF1.pbix
└── f1drivers.ipynb
```

---

## 🔧 Pipeline de Dados

### **1. ETL no Pentaho**
A transformação `f1driverstransformation.ktr` realiza:

- Junção dos dois datasets fornecidos  
- Limpeza inicial e padronização de colunas  
- Ajuste de tipos e correções básicas  
- Preparação dos dados para processamento posterior em Python  

### **2. Limpeza e Análise em Python**
O notebook `f1drivers.ipynb` inclui:

- Remoção de inconsistências restantes  
- Padronização de campos e normalização  
- Criação de novas variáveis
- Análise exploratória:
  - Pilotos por país
  - Faixa etária
  - Experiência e performance
  - Comparações entre equipes

### **3. Dashboard no Power BI**
O arquivo `dashboardF1.pbix` apresenta visualizações como:

- Top pilotos por pontuação  
- Ranking por nacionalidade  
- Distribuição de idade  
- Indicadores por equipe  
- Filtros dinâmicos e storytelling visual  

---

## 📊 Resultados e Insights

Exemplos de insights gerados no dashboard:

- Quais pilotos acumularam mais títulos, vitórias, pódios e poles na F1?
- Como os pilotos campeões se comparam em termos de **taxa de vitória** e **taxa de pódio** por largada?
- Qual é o desempenho dos pilotos brasileiros na categoria em participações e pódios?
- Quais equipes e circuitos aparecem com mais acidentes na história?
- Em que tipo de evento (corrida, treino, teste, classificação, demonstração) ocorreram mais acidentes?

---

## ▶️ Como Executar o Projeto

### 🔄 1. Rodar a transformação no Pentaho
Abra no Spoon:
```
f1driverstransformation.ktr
```

### 🧪 2. Executar o notebook
```bash
jupyter notebook f1drivers.ipynb
```

### 📊 3. Abrir o dashboard no Power BI
Abra:
```
dashboardF1.pbix
```

---

## ✅ Conclusão

Este projeto integra todo o fluxo de trabalho de dados:

- ETL inicial no Pentaho  
- Limpeza e análise em Python  
- Visualização e tomada de decisão no Power BI  

Representa uma solução completa end-to-end, reforçando habilidades essenciais de um profissional de **Data Analytics e Engenharia de Dados**.

---

## 👨‍💻 Autor

Projeto desenvolvido por **Eduardo Sigarini**  
🔗 LinkedIn: https://linkedin.com/in/eduardosigarini  
🐙 GitHub: https://github.com/eduardosigarini

