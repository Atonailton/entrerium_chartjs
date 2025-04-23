# Entrerium - Robô de Cripto

Um robô de análise de criptomoedas que exibe gráficos interativos de candlestick (15 minutos), indicadores técnicos (RSI, MACD, Média Móvel, Oscilador Estocástico, Order Blocks, Point of Control) e sinais de trading. Construído com **Chart.js** e **CoinGecko API**, é otimizado para dispositivos como o Samsung M23 e hospedado no **GitHub Pages**.

## Funcionalidades
- **Gráfico de Candlestick**: Candles de 15 minutos com Order Blocks (retângulos) e Point of Control (linha).
- **Indicadores Técnicos**:
  - RSI, MACD, Média Móvel, Oscilador Estocástico.
  - Order Blocks (suporte/resistência) e Point of Control (PoC).
- **Sinais de Trading**: Probabilidades de compra/venda baseadas em indicadores, com entrada, saída, stop-loss e risco-retorno.
- **Análise de Volume**: Simulada (devido à limitação da CoinGecko).
- **Sentimento de Mercado**: Índice Fear & Greed via Alternative.me API.
- **Responsivo**: Otimizado para telas pequenas (ex.: Samsung M23).
- **Hospedagem**: Funciona no GitHub Pages, eliminando erros de CORS.

## Tecnologias
- **Chart.js**: Gráficos de candlestick com plugins `chartjs-chart-financial` e `chartjs-plugin-annotation`.
- **CoinGecko API**: Dados OHLC de 15 minutos (Bitcoin, Ethereum, Dogecoin).
- **Tailwind CSS**: Estilização da interface.
- **Moment.js**: Manipulação de datas no gráfico.
- **GitHub Pages**: Hospedagem gratuita.

## Como Executar

### Pré-requisitos
- Conexão à internet (Wi-Fi recomendado para estabilidade).
- Navegador moderno (Chrome, Firefox, Samsung Internet).
- Conta no GitHub para hospedagem.

### Passos
1. **Clone ou baixe o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/entrerium-robo-cripto.git
