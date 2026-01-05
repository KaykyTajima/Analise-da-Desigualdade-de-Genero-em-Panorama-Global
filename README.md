# Análise de Fatores da Desigualdade de Gênero 📊👩‍🔬

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)

Este projeto de Ciência de Dados tem como objetivo investigar e identificar quais fatores melhor explicam os resultados de desigualdade de gênero ao redor do mundo. A análise busca responder o que realmente impulsiona a equidade: seriam fatores econômicos (como o PIB), investimentos públicos (saúde/educação) ou a estrutura legislativa e social?

## 🎯 Objetivos do Projeto

* **Pergunta Central:** O que impulsiona a equidade de gênero?
* **Análise Comparativa:** Entender as divergências entre os principais índices globais. Um país pode ser bem avaliado em um índice e mal em outro?
* **Fatores Explicativos:** Correlacionar indicadores socioeconômicos do Banco Mundial com índices de desigualdade para encontrar padrões.

## 📂 Dados Utilizados

O projeto integra dados de múltiplas fontes internacionais para criar uma visão holística do problema:

1. **World Development Indicators (World Bank):**
   * Dataset principal contendo indicadores massivos sobre saúde, educação, economia e desenvolvimento social (ex: acesso a eletricidade, taxas de alfabetização).
2. **Índices de Desigualdade (Bases Extras):**
   * **Global Gender Gap Index (GGGI):** Focado em participação econômica, educação, saúde e empoderamento político.
   * **Social Institutions and Gender Index (SIGI):** Mede instituições sociais discriminatórias.
   * **Gender Inequality Index (GII - UNDP):** Mede a perda de desenvolvimento humano devido à desigualdade.
   * **Gender Development Index (GDI - UNDP):** Razão entre o IDH feminino e masculino.

## 🛠️ Metodologia

O notebook realiza as seguintes etapas de processamento de dados:

* **Coleta e Ingestão:** Carregamento de arquivos CSV e Excel.
* **ETL (Extração, Transformação e Carga):**
    * Normalização dos dados do World Bank (transformação *wide* para *long*).
    * Padronização de códigos de países (ISO Codes) para cruzamento de bases.
* **Análise Exploratória (EDA):**
    * Comparação conceitual entre os índices.
    * Matrizes de correlação entre GII, GDI, GGI, SIGI e subíndices.

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Python
* **Bibliotecas:**
    * `pandas` & `numpy` (Manipulação de dados)
    * `matplotlib` & `seaborn` (Visualização)
    * `openpyxl` (Leitura de arquivos Excel)
