# 🚨 Detecção de Anomalias em Transações Financeiras com Linguagem R e Power BI

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de identificar possíveis **anomalias em transações financeiras** utilizando técnicas de **Machine Learning** implementadas em **Linguagem R** e apresentar os resultados em um dashboard interativo desenvolvido no **Microsoft Power BI**.

Foi utilizado o algoritmo **Isolation Forest** para detectar registros com comportamento fora do padrão, gerando um **Anomaly Score** para cada transação e classificando automaticamente os registros como **Normal** ou **Anomalia**.

Após a execução do modelo em R, os resultados foram importados para o Power BI, onde foram criados indicadores, gráficos e visualizações que permitem analisar rapidamente o comportamento das transações e identificar possíveis fraudes ou registros suspeitos.

---

# 🤖 Tecnologias Utilizadas

- Microsoft Power BI
- Linguagem R
- Isolation Forest
- Machine Learning
- Power Query
- DAX
- Business Intelligence
- Visualização de Dados

---

# 📊 Funcionalidades do Dashboard

O dashboard apresenta os seguintes recursos:

- 🚨 Média do Score de Anomalia
- 📈 Maior Score de Anomalia encontrado
- 📊 Distribuição de registros classificados como Normal e Anomalia
- 📦 Boxplot comparando os Scores por Status (gerado em Linguagem R)
- 📉 Distribuição da quantidade de registros por Score
- 📋 Indicadores para análise do comportamento das transações

---

# 🧠 Machine Learning

A detecção de anomalias foi realizada utilizando o algoritmo **Isolation Forest**, implementado em **Linguagem R**.

Fluxo desenvolvido:

1. Carregamento dos dados.
2. Treinamento do modelo Isolation Forest.
3. Cálculo do **Anomaly Score** para cada registro.
4. Definição do critério de classificação.
5. Classificação dos registros em:
   - Normal
   - Anomalia
6. Exportação dos resultados para utilização no Power BI.

---

# 📂 Modelagem dos Dados

O modelo de dados é composto pela tabela **previsoes_novos_dados**, gerada após a execução do algoritmo **Isolation Forest** em Linguagem R.

Campos utilizados:

- **id** → Identificador único de cada registro.
- **anomaly_score** → Score de anomalia calculado pelo algoritmo.
- **average_depth** → Profundidade média calculada pelo Isolation Forest.
- **status** → Classificação do registro (*Normal* ou *Anomalia*).

Após o processamento em Linguagem R, os dados foram exportados e importados para o Power BI para construção dos indicadores e visualizações.

---

# 📈 Principais Análises

Com este dashboard é possível:

- Identificar registros classificados como anomalias;
- Comparar os scores entre registros normais e anômalos;
- Avaliar a distribuição das classificações geradas pelo modelo;
- Analisar a dispersão dos scores através do Boxplot;
- Monitorar o comportamento dos registros com base no Anomaly Score;
- Apoiar processos de monitoramento e identificação de possíveis fraudes.

---

# 📷 Prévia do Dashboard

## Dashboard Principal

[screenshots/dashboard.png]

## Modelo de Dados

[screenshots/modelagem.png]

---

# 🎯 Competências Demonstradas

Este projeto demonstra conhecimentos em:

- Machine Learning
- Linguagem R
- Isolation Forest
- Detecção de Anomalias
- Microsoft Power BI
- Power Query
- DAX
- Modelagem de Dados
- Business Intelligence
- Storytelling com Dados
- Visualização de Dados

---

# 📁 Estrutura do Repositório

```text
📂 Financial-Anomaly-Detection
│
├── Dashboard.pbix
├── Script_IsolationForest.R
├── README.md
├── imagens
│   ├── dashboard.png
│   └── modelagem.png
└── dataset
```

---

# 🚀 Como visualizar

1. Faça o download do arquivo **Dashboard.pbix**.
2. Abra utilizando o **Microsoft Power BI Desktop**.
3. Navegue pelas visualizações do relatório.
4. Consulte o script em **Linguagem R** para compreender a implementação do algoritmo Isolation Forest e o processo de detecção de anomalias.

---

# 👨‍💻 Autor

**José Rafael Santos Pereira**

Desenvolvendo projetos práticos com **Power BI | SQL | Python | Business Intelligence**

📌 GitHub: https://github.com/ZeRafaSp/

💼 LinkedIn: https://www.linkedin.com/in/rafaelsantospereirarsp/
