Análise de Fatores da Desigualdade de Gênero 📊👩‍🔬
Este projeto de Ciência de Dados tem como objetivo investigar e identificar quais fatores melhor explicam os resultados de desigualdade de gênero ao redor do mundo. A análise busca responder o que realmente impulsiona a equidade: seriam fatores econômicos (como o PIB), investimentos públicos (saúde/educação) ou a estrutura legislativa e social?

🎯 Objetivos do Projeto
Pergunta Central: O que impulsiona a equidade de gênero?

Análise Comparativa: Entender as divergências entre os principais índices globais. Um país pode ser bem avaliado em um índice e mal em outro?

Fatores Explicativos: Correlacionar indicadores socioeconômicos do Banco Mundial com índices de desigualdade para encontrar padrões.

📂 Dados Utilizados
O projeto integra dados de múltiplas fontes internacionais para criar uma visão holística do problema:

World Development Indicators (World Bank):

Dataset principal contendo indicadores massivos sobre saúde, educação, economia e desenvolvimento social (ex: acesso a eletricidade, taxas de alfabetização, etc.).

Índices de Desigualdade (Bases Extras):

Global Gender Gap Index (GGGI): Focado em participação econômica, educação, saúde e empoderamento político.

Social Institutions and Gender Index (SIGI): Mede instituições sociais discriminatórias (foco nas causas não econômicas da desigualdade).

Gender Inequality Index (GII - UNDP): Mede a perda de desenvolvimento humano devido à desigualdade.

Gender Development Index (GDI - UNDP): Razão entre o IDH feminino e masculino.

🛠️ Metodologia e Etapas
O notebook Analise_data_quest.ipynb cobre as seguintes etapas:

Coleta e Ingestão: Carregamento de arquivos CSV e Excel via Google Drive.

Limpeza e Transformação (ETL):

Normalização dos dados do World Bank (transformação de formato wide para long com a função melt).

Padronização de códigos de países (ISO Codes) para permitir o cruzamento das bases.

Análise Exploratória (EDA):

Comparação entre os conceitos de desigualdade de cada base.

Criação de matrizes de correlação entre os índices (GII, GDI, GGI, SIGI) e seus subíndices.

🚀 Tecnologias Utilizadas
Linguagem: Python 🐍

Bibliotecas:

pandas (Manipulação e agregação de dados)

numpy (Cálculos numéricos)

matplotlib & seaborn (Visualização de dados)

glob & os (Gerenciamento de arquivos)

📦 Como Executar
Clone este repositório.

Garanta que você possui as bases de dados (ou ajuste o caminho para os arquivos CSV/Excel locais).

Instale as dependências:

Bash

pip install pandas numpy seaborn matplotlib openpyxl
Execute o Jupyter Notebook:

Bash

jupyter notebook Analise_data_quest.ipynb
