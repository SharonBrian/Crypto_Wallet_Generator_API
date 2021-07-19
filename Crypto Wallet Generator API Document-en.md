#### **update log:**
 2021-07-18 : Added Symbols: BNB、NEO、ONT、Steller(XLM)、POTE、CLUB

2021-01-11 : Added Symbols: LTC、DASH、DOGE、Cosmos(ATOM）、Monero(XMR)、Waves、Ripple(XRP)

2020-07-16 : Added Symbols: BTC、ETH、ETC、HuobiEcoChain(HECO)、BinanceSmartChain(BSC)、OKexChain(OKT)、TRX、USDT(ERC20/TRC20/OMNI)、EOS、BCH、QTUM、Filecoin(FIL)、BSV、VeChain(VET)、Polygon(MATIC)


# Crypto Wallet Generator API Document

**Supported Crypto Wallet：**BTC、ETH、ETC、HuobiEcoChain(HECO)、BinanceSmartChain(BSC)、OKexChain(OKT)、TRX、USDT(ERC20/TRC20/OMNI)、EOS、BCH、QTUM、Filecoin(FIL)、BSV、VeChain(VET)、Polygon(MATIC)、LTC、DASH、DOGE、Cosmos(ATOM）、Monero(XMR)、Waves、Ripple(XRP)、BNB、NEO、ONT、Steller(XLM)、POTE、CLUB


**For learning and test only, please do not use for commercial purposes**

## Request Domain

 https://www.tokenwallet.one

## Generate Crypto Wallet Address And Private Key

### Generate Wallet

```
GET   /create/<symbol>
```
**symbol options :  btc、eth、etc、heco、bsc、okt、trx、usdt_erc20、usdt_trc20、usdt_omni、eos、bch、qtum、fil、bsv、vet、matic、ltc、dash、doge、atom、xmr、waves、xrp、bnb、neo、ont、xlm、pote、club **

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

