Markdown
# 🍷 Winemag: Machine Learning & Predictive Analytics for Wine Reviews

Este projeto aplica técnicas avançadas de **Data Science, Processamento de Linguagem Natural (NLP) e Machine Learning** sobre o famoso ecossistema de dados da *Wine Enthusiast* (Winemag). O objetivo principal é extrair padrões mercadológicos, analisar o sentimento das avaliações e construir modelos preditivos robustos para estimar a qualidade (pontuação) e a precificação de vinhos globalmente.

Combinando o rigor analítico e a modelagem matemática da física com o ecossistema de dados do Python, o projeto aborda desde a limpeza de dados esparsos até a colocação de modelos supervisionados em produção.

---

## 🎯 Objetivos do Projeto

* **📊 Análise Exploratória de Dados (EDA):** Mapear a distribuição geográfica, variedades de uva e a correlação macroeconômica entre preço e qualidade dos vinhos.
* **🧠 Modelagem Preditiva (Regressão/Classificação):** Desenvolver algoritmos capazes de prever a nota de um vinho com base em suas características sensoriais e preço.
* **🗣️ Processamento de Linguagem Natural (NLP):** Minerar o texto das avaliações (*reviews*) para identificar termos mais associados a vinhos de alta qualidade através de TF-IDF e embeddings de texto.

---

## 📂 Estrutura do Repositório
```
winemag/
│
├── data/
│   ├── raw/                 # Dataset original (winemag-data-130k-v2.csv)
│   └── processed/           # Dados limpos, tratados e com engenharia de features
│
├── notebooks/
│   ├── 1_eda.ipynb          # Análise exploratória e visualização estatística
│   ├── 2_nlp_analysis.ipynb # Processamento de texto e análise de sentimentos
│   └── 3_modeling.ipynb     # Treinamento e avaliação dos modelos de ML
│
├── src/
│   ├── __init__.py
│   ├── data_cleaning.py     # Pipeline de tratamento de valores nulos e outliers
│   └── features.py          # Vetorização de texto e codificação de variáveis categóricas
│
├── .gitignore               # Isolamento de datasets gigantes e caches locais
└── README.md                # Documentação técnica do projeto
```
---
## 🛠️ Tecnologias & Bibliotecas Utilizadas
* Manipulação & Estatística: Python, Pandas, NumPy, SciPy.

* Visualização Analítica: Matplotlib, Seaborn.

* Machine Learning & NLP: Scikit-Learn, NLTK / Spacy (para processamento de texto).

## 📈 Principais Insights Extraídos (Exemplo)
A Regra dos Rendimentos Decrescentes: A relação entre preço e pontuação não é linear. Vinhos acima de uma determinada faixa de preço apresentam ganho marginal de pontuação estatisticamente irrelevante.

Engenharia de Features Textuais: A presença de adjetivos específicos na descrição textual possui uma correlação mais forte com a nota final do que a própria vinícola de origem.

## 🚀 Como Executar o Projeto
Clone o repositório:
```
Bash

   git clone [https://github.com/DaviFPassos/winemag.git](https://github.com/DaviFPassos/winemag.git)
```
### Instale as dependências:
```
Bash
   pip install -r requirements.txt
```
Execute os notebooks na pasta notebooks/ para visualizar o pipeline completo.

---

Caso esse código já esteja no seu GitHub e você queira extrair o texto exato que escreveu lá no p