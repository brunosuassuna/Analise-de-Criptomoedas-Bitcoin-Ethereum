# 📊 **Análise de Mercado de Criptomoedas - Bitcoin e Ethereum**

## 🚀 **Visão Geral**
Este projeto realiza uma análise de mercado avançada focada em **Bitcoin (BTC)** e **Ethereum (ETH)**, utilizando dados coletados de forma automatizada via **API CoinGecko**. A análise é feita em uma plataforma de **Databricks** e abrange:

- Coleta automatizada de dados em tempo real
- Processamento de dados e engenharia de features
- Análise técnica avançada, incluindo médias móveis e volatilidade
- Visualizações interativas e gráficos comparativos
- Modelagem de séries temporais para previsão de preços futuros

## 🔍 **Principais Funcionalidades**
### ✅ **Coleta Automatizada de Dados**
- Integração com a **API CoinGecko** para dados em tempo real
- Fallback para dados simulados caso a API falhe
- Tratamento de erros robusto e controle de rate limits

### 📈 **Análise Técnica Completa**
- **Médias Móveis:** Cálculo de médias móveis de 7 e 30 dias para análise de tendências
- **Indicadores de Volatilidade:** Medição da volatilidade dos ativos
- **Correlação entre Ativos:** Análise da correlação entre **BTC** e **ETH** e outros fatores externos

### 📊 **Visualizações Profissionais**
- **Gráficos Comparativos de Desempenho:** Comparação entre **BTC** e **ETH**
- **Heatmaps de Correlação:** Visualização das correlações entre diferentes variáveis
- **Análise de Tendências e Sazonalidade:** Gráficos interativos para explorar tendências no mercado

### 🔮 **Modelagem de Séries Temporais**
- **ARIMA e Prophet:** Modelos preditivos para projeção de preços futuros
- **Análise de Cenários:** Estudo de diferentes cenários de mercado com base em dados históricos

## 🛠 **Tecnologias Utilizadas**
- **Python:** Utilizado para processamento de dados e visualizações
- **Pandas e NumPy:** Processamento de dados
- **Matplotlib, Seaborn, Plotly:** Visualizações gráficas e interativas
- **PySpark:** Processamento distribuído de grandes volumes de dados
- **Databricks:** Plataforma de execução
- **Delta Lake:** Armazenamento de dados
- **Git:** Controle de versão

## 📂 **Estrutura do Projeto**
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

## 🏁 **Como Executar**
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
- **LinkedIn:** www.linkedin.com/in/brunosuassuna
