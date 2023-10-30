<!-- @format -->
<img width =100%  src = "https://raw.githubusercontent.com/wuddz-devs/wuddz-dapp/main/assets/dapp.png">
<h1 align ="center">WUDDZ-DAPP</h1>
<br>

## Description
 - Wuddz-Dapp Is An Awesomely Coded Web3 (Infura Apikey Required) Decentralized Application In Python, For Everyday Cryptocurrency Needs.
   
 - Create Accounts, Get All Token Balances & Usd Value For An Account/Wallet, Make Transactions
 
 - Deploy Verify & Interact With Smart Contracts, Swap ERC20 Tokens Using 0x Api Quotes (Apikey Required), Get Crypto Value In Other Currencies
 
 - Get Token Prices In USD, Interact With An Exchange (Via Api Authentication) Using Ccxt Api (The Best Trading API On The Planet)
 
 - Decode Base64 Encoded Strings.
 
 - I Wrote This Application At The Height Of The Web3 Craze, 
 
 - I've Seen Way Too Many People Being Scammed & Taken Advantage Of
 
 - All From Visiting Shady Websites Or Using Circumspect Software, Namely Web Browsers
 
 - Wuddz-Dapp Is Safe And It Gets The Job Done Period.
 
 - Fully Updated & Good To Go.

## Requirements
 - python
 - ccxt
 - pycoingecko
 - requests
 - setuptools
 - web3

## Installation
Install using [PyPI](https://pypi.org/project/wuddz-dapp):
```
$ pip install wuddz-dapp
```
Install locally by cloning or downloading and extracting the repo, then cd into 'dist' directory and execute:
```
$ pip install wuddz_dapp-1.0.4.tar.gz
```
Then to launch Wuddz-Dapp, execute the following in the terminal:
```
$ wudz-dapp
```
Then to launch Wuddz-Dapp Exchange_API, execute the following in the terminal:
```
$ wudz-eapi
```

### Library
Get Current Price Of Ethereum In USD.
```
>>> from wuddz_dapp import dapp
>>> dp=dapp.Dapp()
>>> dp.get_price('ethereum')
1782.58
```
Get Ethereum Balance On Ethereum Mainnet.
```
>>> from wuddz_dapp import dapp
>>> dp=dapp.Dapp()
>>> dp.block_network(nc='mainnet')
>>> dp.eth_value('0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045')
Decimal('935.143444994707078128')
```
Get Ethereum Address/Ens Name On Ethereum Mainnet.
```
>>> from wuddz_dapp import dapp
>>> dp=dapp.Dapp()
>>> dp.block_network(nc='mainnet')
>>> dp.ens_addr('0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045')
'vitalik.eth'
```
Get USDT(Tether) Contract Address On Ethereum Mainnet.
```
>>> from wuddz_dapp import dapp
>>> dp=dapp.Dapp()
>>> dp.block_network(nc='mainnet')
>>> dp.tkn_address('USDT', n='mainnet')
'0xdac17f958d2ee523a2206206994597c13d831ec7'
```
Authenticate To Bybit Testnet Exchange With Required API Credentials & Print 'BTC/USD:BTC' Token Info Result Dictionary.
```
>>> from wuddz_dapp import exchange_api
>>> eapi=exchange_api.Exchange()
>>> exd={
...     'enableRateLimit': True,
...     'options': {'adjustForTimeDifference': True},
...     'apiKey': 'exchangeapikeyhere',
...     'secret': 'exchangesecrethere'
...     }
>>> eapi._exchange('bybit', exd, tn='t')
>>> eapi.token_info('BTC/USD:BTC')
{'symbol': 'BTC/USD:BTC', 'timestamp': None, 'datetime': None, 'high': 34294.0, 'low': 33000.0, 'bid': 33643.5, 'bidVolume': 115966.0, 'ask': 33647.0, 'askVolume': 102616.0, 'vwap': 2.9425371718953e-05, 'open': 33982.5, 'close': 33647.0, 'last': 33647.0, 'previousClose': None, 'change': -335.5, 'percentage': -0.9872, 'average': 33814.75, 'baseVolume': 1017340443.0, 'quoteVolume': 29935.6207, 'info': {'symbol': 'BTCUSD', 'lastPrice': '33647.00', 'indexPrice': '33638.12', 'markPrice': '33642.01', 'prevPrice24h': '33982.50', 'price24hPcnt': '-0.009872', 'highPrice24h': '34294.00', 'lowPrice24h': '33000.00', 'prevPrice1h': '33515.00', 'openInterest': '43895114', 'openInterestValue': '1304.77', 'turnover24h': '29935.6207', 'volume24h': '1017340443', 'fundingRate': '0.0001', 'nextFundingTime': '1698451200000', 'predictedDeliveryPrice': '', 'basisRate': '', 'deliveryFeeRate': '', 'deliveryTime': '0', 'ask1Size': '102616', 'bid1Price': '33643.50', 'ask1Price': '33647.00', 'bid1Size': '115966', 'basis': ''}}
```

## Video:
- https://youtu.be/SjESwOpwh7w

## Contact Info:
 - Email:     wuddz_devs@protonmail.com
 - Github:    https://github.com/wuddz-devs
 - Telegram:  https://t.me/wuddz_devs
 - Youtube:   https://youtube.com/@wuddz-devs
 - Reddit:    https://reddit.com/user/wuddz-devs

### Buy Me A Coffee!!
![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-dapp/main/assets/eth.png)
 - ERC20:    0xbF4d5309Bc633d95B6a8fe60E6AF490F11ed2Dd1

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-dapp/main/assets/btc.png)
 - BTC:    bc1qa7ssx0e4l6lytqawrnceu6hf5990x4r2uwuead

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-dapp/main/assets/ltc.png)
 - LTC:      LdbcFiQVUMTfc9eJdc5Gw2nZgyo6WjKCj7

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-dapp/main/assets/doge.png)
 - DOGE:     DFwLwtcam7n2JreSpq1r2rtkA48Vos5Hgm

![Alt Text](https://raw.githubusercontent.com/wuddz-devs/wuddz-dapp/main/assets/tron.png)
 - TRON:     TY6e3dWGpqyn2wUgnA5q63c88PJzfDmQAD

#### Enjoy my awesome creativity!!
#### Peace & Love Always!!
