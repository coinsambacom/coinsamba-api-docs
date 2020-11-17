# Coinsamba API Docs

Coinsamba is the biggest platform in Brazil to compare cryptocurrencies prices in each exchange.

### Currently version
We only show newest version of the api in this doc root.
Actually API is in ``v1``

### Base URL

```sh
https://api.coinsamba.com
```

### Endpoints

We have some endpoints for you to use in your app.

| Endpoint | Description |
| ------ | ------ |
| [forex](#forex) | get rate for various currencys in BRL |
| [book](#book) | get orderbook or books |
| [ticker](#ticker) | get ticker or tickers |
| [index](#index) | get index for a currency |

# Forex

```
GET /v1/forex
```

Get forex conversions

**Parameters:**

Name | Type | Mandatory | Description
------------ | ------------ | ------------ | ------------
base | STRING | YES | base currency
quote | STRING | YES | quote currency

# Book

```
GET /v1/book
```

Get book of an exchange

**Parameters:**

Name | Type | Mandatory | Description
------------ | ------------ | ------------ | ------------
base | STRING | YES | base currency
quote | STRING | YES | quote currency
exchangeId | STRING | YES | exchange that you need book

# Ticker

```
GET /v1/ticker
```

Get ticker of an exchange pair

**Parameters:**

Name | Type | Mandatory | Description
------------ | ------------ | ------------ | ------------
base | STRING | YES | base currency
quote | STRING | YES | quote currency
exchangeId | STRING | YES | exchange that you need ticker

# Index

```
GET /v1/index
```

Get index of an pair

**Parameters:**

Name | Type | Mandatory | Description
------------ | ------------ | ------------ | ------------
base | STRING | YES | base currency
quote | STRING | YES | quote currency