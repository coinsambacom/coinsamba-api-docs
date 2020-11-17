# Coinsamba API Docs

Coinsamba is the biggest platform in Brazil to compare cryptocurrencies prices in each exchange.

### Currently version
We only show newest version of the api in this doc root.
Actually API is in ``v1``

### Base URL

```sh
api.coinsamba.com/v1/
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
GET api.coinsamba.com/v1/forex
```

