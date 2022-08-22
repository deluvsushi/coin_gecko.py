# coin_gecko.py
Web-API for [coingecko.com](https://www.coingecko.com) website that provides a fundamental analysis of the crypto market. In addition to tracking price, volume and market capitalisation

## Example
```python
import coin_gecko
coin_gecko = coin_gecko.CoinGecko()
global_crypto_data = coin_gecko.get_global_crypto_data()
print(global_crypto_data)
```
