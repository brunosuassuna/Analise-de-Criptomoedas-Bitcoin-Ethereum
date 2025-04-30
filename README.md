# 📊 Análise de Mercado de Criptomoedas - Bitcoin e Ethereum

## 🚀 Visão Geral
Projeto profissional de análise de mercado de criptomoedas, focado em Bitcoin (BTC) e Ethereum (ETH), desenvolvido no ambiente Databricks. Este repositório contém um pipeline completo de:

- Coleta de dados via API CoinGecko
- Processamento e engenharia de features
- Análise técnica avançada
- Visualizações interativas
- Modelagem de séries temporais

## 🔍 Principais Funcionalidades
### ✅ Coleta Automatizada de Dados

- Integração com API CoinGecko
- Fallback para dados simulados caso a API falhe
- Tratamento robusto de erros e rate limits

## 📈 Análise Técnica Completa

- Cálculo de médias móveis (7, 30 dias)
- Indicadores de volatilidade
- Correlação entre ativos

## 📊 Visualizações Profissionais

- Gráficos comparativos de desempenho
- Heatmaps de correlação
- Análise de tendências e sazonalidade
- Versões estáticas (Matplotlib) e interativas (Plotly)

## 🛠 Tecnologias Utilizadas
- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- PySpark para processamento distribuído
- Databricks como plataforma de execução
- Delta Lake para armazenamento de dados
- Git para controle de versão

## 📂 Estrutura do Projeto
```bash
├── 📂 notebooks/                           # Notebooks organizados por etapa
│   ├── 📂 data_ingestion/                  # Coleta e preparação de dados
│   ├── 📂 technical_analysis/              # Análise e indicadores técnicos
│   ├── 📂 visualizations/                  # Códigos de visualização
│   └── 📂 models/                          # Modelos preditivos (ARIMA, Prophet)
├── 📂 data/                                # Diretório de dados
│   ├── 📂 raw/                             # Dados brutos da API
│   ├── 📂 processed/                       # Dados tratados
│   └── 📂 output/                          # Resultados e relatórios finais
└── 📂 docs/                                # Documentação complementar
```

 ## 🏁 Como Executar
**Clone o repositório:** 
```bash
git clone https://github.com/brunosuassuna/Analise-de-Criptomoedas-Bitcoin-Ethereum.git
```
- Importe os notebooks no Databricks
- Execute em ordem

 ## 📜 Licença
- **Licença:** [MIT](https://opensource.org/license/MIT)

## ✉️ Contato
- **Email:** brunosuassuna.dev@gmail.com
- **LinkedIn:** www.linkedin.com/in/bruno-suassuna-698aa7235
