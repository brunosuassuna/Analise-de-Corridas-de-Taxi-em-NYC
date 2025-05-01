# 🚖 Análise de Corridas de Táxi em NYC com PySpark no Databricks

Este projeto realiza uma análise exploratória sobre o comportamento de corridas de táxi na cidade de Nova York, utilizando o dataset público `samples.nyctaxi.trips` do Databricks. O foco está na identificação de padrões temporais, espaciais e econômicos, com ênfase no uso de processamento distribuído via PySpark.

---

## 🎯 Objetivos

- Analisar o volume de corridas por hora e por mês.
- Avaliar a receita média por região (ZIP Code).
- Identificar padrões sazonais e variações geográficas.
- Aplicar práticas de análise em larga escala com PySpark no ambiente Databricks.

---

## 🗂️ Fonte de Dados

- **Base:** `samples.nyctaxi.trips` (Databricks Public Datasets)
- **Cobertura:** Corridas de táxi na cidade de Nova York, com dados de localização, timestamps e valores financeiros.
- **Formato:** Tabela estruturada com bilhões de registros, ideal para análises com Spark SQL.

---

## ⚙️ Tecnologias e Ferramentas

- **Databricks** — Plataforma unificada para ciência e engenharia de dados
- **Apache Spark / PySpark** — Processamento distribuído e transformação de dados
- **Python 3.x** — Linguagem para análise e visualização
- **Matplotlib / Seaborn** — Visualizações customizadas em ambiente local
- **Spark SQL / display()** — Visualizações interativas em ambiente Databricks

---

## 📊 Análises Realizadas

- 📈 **Volume de Corridas por Hora do Dia**
- 📅 **Volume de Corridas por Mês**
- 💰 **Receita Média por Código Postal (ZIP Code)**
- 🗺️ **Distribuição Espacial de Corridas por Região**

Todas as visualizações foram geradas com `display()` (Databricks) e replicadas com `Matplotlib` e `Seaborn` para ambientes fora do Databricks.

---

## 🔍 Insights Relevantes

- **Horários de pico** entre 16h e 19h, consistentes com o tráfego urbano.
- **Sazonalidade evidente**, com aumento de corridas em meses como dezembro.
- **Distribuição desigual de receita e volume** entre regiões — possível relação com variáveis socioeconômicas.
- **Concentração de corridas** em ZIP Codes centrais, sugerindo hotspots urbanos.

---

## 📌 Conclusão

A análise demonstrou como é possível extrair insights significativos de um grande volume de dados utilizando PySpark em um ambiente escalável como o Databricks. A combinação de técnicas de agregação, filtragem e visualização permitiu identificar padrões urbanos consistentes e aplicáveis em contextos de mobilidade, planejamento urbano ou políticas públicas.

---

## 🚀 Como Executar

1. Acesse sua instância Databricks.
2. Importe o notebook `.dbc` ou `.ipynb`.
3. Conecte a um cluster Spark ativo.
4. Execute as células sequencialmente.
5. (Opcional) Para execução local, adapte a leitura do dataset para `.csv`.

Clone este repositório com:
```bash
git clone https://github.com/brunosuassuna/Analise-de-Corridas-de-Taxi-em-NYC.git
```

## ✉️ Contato
- **Email:** brunosuassuna.dev@gmail.com
- **LinkedIn:** www.linkedin.com/in/bruno-suassuna-698aa7235

