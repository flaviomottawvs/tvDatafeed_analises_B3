# Análise de Dados Financeiros com Jupyter Notebook

Este projeto consiste em três scripts Jupyter Notebook projetados para realizar análises financeiras detalhadas de ativos listados na BM&FBOVESPA. Cada script utiliza a API TvDatafeed para obter dados em tempo real e analisar diferentes aspectos do mercado financeiro.

## Scripts Inclusos

### 1. Comparação de Desempenho de Ativos
Este notebook compara o desempenho de vários ativos do setor de varejo ao longo do tempo. Utiliza gráficos para visualizar a variação percentual normalizada de preços de fechamento desde uma data de início especificada.

- **Bibliotecas Utilizadas:**
  - `TvDatafeed`: Para acessar dados de mercado via TradingView.
  - `pandas`: Para manipulação de dados.
  - `matplotlib`: Para visualização de dados.

### 2. Rastreamento de Tendência usando ADX
Este script analisa a tendência de um ativo específico usando o indicador ADX, junto com DI+ e DI-. É útil para identificar se um ativo está em uma tendência forte ou fraca e a direção dessa tendência.

- **Bibliotecas Utilizadas:**
  - `TvDatafeed`
  - `pandas`
  - `pandas_ta`: Para cálculo de indicadores técnicos.
  - `mplfinance`: Para gráficos de candlestick.
  - `matplotlib`

### 3. Backtesting da Estratégia de Bandas de Bollinger
Este notebook realiza um backtesting de uma estratégia de trading baseada em Bandas de Bollinger. O script inclui cálculos para pontos de compra e venda baseados na intersecção do preço com as bandas e avalia o desempenho da estratégia.

- **Bibliotecas Utilizadas:**
  - `TvDatafeed`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `plotly`: Para gráficos interativos e análises visuais detalhadas.

## Configuração e Uso
Para executar os notebooks, você precisará das credenciais de acesso ao TvDatafeed, que devem ser configuradas como variáveis de ambiente ou diretamente inseridas nos scripts. Além disso, é necessário instalar as bibliotecas Python mencionadas, o que pode ser feito via pip:

```bash
pip install pandas pandas_ta matplotlib mplfinance plotly openpyxl
```

## Visualização e Análise 

Cada script oferece visualizações gráficas dos dados analisados, facilitando a interpretação e a tomada de decisões baseadas nos resultados das análises.

## Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.


### Notas
- Certifique-se de substituir `"USERNAME"` e `"PASSWORD"` com suas credenciais reais onde necessário ou configurá-las de maneira segura.
- Adaptar conforme necessário para alinhar com a estrutura e regras específicas de seu projeto ou repositório.



