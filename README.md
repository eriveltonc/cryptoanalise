# cryptoanalise
Este repositório contém um código em Python que utiliza a API da Binance para coletar dados históricos de todos os pares USDT disponíveis na exchange e analisá-los com o objetivo de identificar oportunidades de investimento em criptomoedas.

## Pré-requisitos

Antes de utilizar o código, é necessário criar uma conta na Binance e obter as chaves de API e secret key para acessar a API da exchange. Essas informações devem ser inseridas no código no trecho:

```
api_key = "INSIRA SUA API KEY DA BINANCE AQUI"
secret_key = "INSIRA SUA SECRETY KEY DA BINANCE AQUI"

```

Além disso, é necessário instalar as seguintes bibliotecas em Python:

- pandas
- matplotlib
- numpy
- binance
- sklearn
- talib
- yfinance
- plotly

## Como utilizar

Para utilizar o código, basta executar o arquivo `binance.py` em um ambiente de desenvolvimento Python, como o Jupyter Notebook ou o Google Colab.

O arquivo irá coletar os dados históricos de todos os pares USDT disponíveis na Binance e analisá-los para identificar oportunidades de investimento.

O resultado da análise será apresentado em gráficos, que podem ser interpretados para identificar as melhores oportunidades de investimento.
