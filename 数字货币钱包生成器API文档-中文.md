#### **更新日志:**
 2021-07-17 ：新增币种： EOS、Cosmos(ATOM)、Filecoin(FIL)、BSV、VeChain(VET)、Steller(XLM)
 
 2021-07-16 : 新增币种: BTC、ETH、ETC、TRX、HECO、BSC、OKT、USDT(ERC20/TRC20/OMNI)、BCH、LTC、Polygon(MATIC)、DASH、DOGE、QTUM

# 数字货币钱包地址生成器 API 使用文档

支持币种列表：BTC、ETH、ETC、TRX、HuobiEcoChain(HECO)、Binance Smart Chain(BSC)、OKex Chain（OKT）、USDT-ERC20、USDT-TRC20、USDT-OMNI、Polygon(MATIC)、BCH、LTC、DASH、DOGE、QTUM、EOS、ATOM、FIL、BSV、VeChain(VET)、Steller(XLM)


仅供学习,请勿用于商业用途

## 用户请求域名

 https://www.tokenwallet.one

## 生成币种钱包地址和私钥

### 生成币种钱包地址和私钥

```
GET   /create/<symbol>
```

**symbol可选项为: btc、eth、etc、trx、heco、bsc、okt、usdt_erc20、usdt_trc20、usdt_omni、matic、bch、ltc、dash、doge、qtum、eos、atom、fil、bsv、vet、xlm**

### 请求示例

```
GET   /create/btc
```

### 返回参数

```
参数名			   参数类型		   描述
state     		  String			状态值: success 、error
symbol			  String			币种简称
addr			    String			钱包地址
privateKey		  String			钱包私钥
```



## 捐赠

**BTC地址:** 	15AEAHyMjFGqKvSgsbmUBD1M7xVXJaBsHz		

**ETH地址:**	0x3d61db050fc4810c64012ac260dc9c73b902f641		

**DOGE地址:**	D8BAJrtK4W3jZ8XNQAyjxiEQgogCbboyZb		
