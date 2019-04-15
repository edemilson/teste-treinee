# CRIPTOSITE

Requisitos:

Criar uma lista com todas as moedas virtuais, nessa lista eu preciso pesquisar uma moeda pelo nome, ordenar por nome (Ordem alfabética), pelo ranking e pelo seu valor em dólares.
Salvar moedas como favoritas e mostrar elas no inicio da lista.

Criar uma página para cada moeda onde terá suas informações. Um gráfico dos últimos valores da moeda em dólares, um gráfico com a previsão de qual valor a moeda vai atingir em x meses, uma calculadora que irá converter criptomoeda para outra criptomoeda (ex. Tenho 15 BTC quantos ETH eu posso comprar com esses 15 BTC), criptomoeda para dólar (ex. 15 BTC valem X dolares) e usando a previsão uma calculadora que irá mostrar se eu investir X baseado nas previsões quanto eu terei daqui X meses.


**Lista Moedas**
```sh
Endpoint: https://coinbin.org/coins
```
**Converte criptomoeda para criptomoeda**
```sh
Endpoint: https://coinbin.org/btc/to/eth
```
**Previsão de valor**
```sh
Endpoint: https://coinbin.org/btc/forecast
```
**Converte um X de moeda Y para dólar**
```sh
Endpoint: https://coinbin.org/lbc/<total-moeda>
```
**Informações específicas de uma determinada moeda**
```sh
Endpoint: https://coinbin.org/lbc
```
**Histórico de preço da moeda**
```sh
Endpoint: https://coinbin.org/btc/history
```
**Baseado os ips dos usuários que acessam uma moeda especifica, exibir no mapa suas localizações**
```sh
Endpoint: http://ip-api.com/json/<endereco-ip>
```

# Alternativa de API
```sh
https://min-api.cryptocompare.com/documentation
```