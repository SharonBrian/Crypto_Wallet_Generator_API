#### **update log:**

 2021-07-16 : Add Symbol: BTC、ETH、ETC、TRX、HECO、BSC、OKT、USDT(ERC20/TRC20/OMNI)、BCH、LTC、MATIC、DASH、DOGE、QTUM

# Crypto Wallet Generator API Document

**Supported Crypto Wallet：**BTC、ETH、ETC、TRX、HuobiEcoChain(HECO)、Binance Smart Chain(BSC)、OKex Chain（OKT）、USDT-ERC20、USDT-TRC20、USDT-OMNI、MATIC、BCH、LTC、DASH、DOGE、QTUM


**For learning and test only, please do not use for commercial purposes**

## Request Domain

 https://www.tokenwallet.one

## Generate Crypto Wallet Address And Private Key

### Generate Wallet

```
GET   /create/<symbol>
```
**symbol options :  btc、eth、etc、trx、heco、bsc、okt、usdt_erc20、usdt_trc20、usdt_omni、matic、bch、ltc、dash、doge、qtum**

### Request Example

```
GET   /create/btc
```
### Return Parameters

```
Parameter Name	  Parameter Type	Description
state     		  String			state value: success 、error
symbol			  String			symbol
addr			    String			wallet address
privateKey		  String			wallet private key
```



## Donations
**BTC Address:** 15AEAHyMjFGqKvSgsbmUBD1M7xVXJaBsHz			
**ETH Address:**	0x3d61db050fc4810c64012ac260dc9c73b902f641		
**DOGE Address:**	D8BAJrtK4W3jZ8XNQAyjxiEQgogCbboyZb	

