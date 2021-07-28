#### **更新日志:**
2021-07-28 ：限制访问频率，每个IP每秒访问接口次数限制为2次，超过则会报访问频率超过限制的错误；

2021-07-18 : 新增币种 BNB、NEO、ONT、Steller(XLM)、POTE、CLUB

2021-01-11 : 新增币种 LTC、DASH、DOGE、Cosmos(ATOM）、Monero(XMR)、Waves、Ripple(XRP)

2020-07-16 : 新增币种: BTC、ETH、ETC、HuobiEcoChain(HECO)、BinanceSmartChain(BSC)、OKexChain(OKT)、TRX、USDT(ERC20/TRC20/OMNI)、EOS、BCH、Filecoin(FIL)、BSV、VeChain(VET)、Polygon(MATIC)

# 数字货币钱包地址生成器 API 使用文档

支持币种列表：BTC、ETH、ETC、HuobiEcoChain(HECO)、BinanceSmartChain(BSC)、OKexChain(OKT)、TRX、USDT(ERC20/TRC20/OMNI)、EOS、BCH、Filecoin(FIL)、BSV、VeChain(VET)、Polygon(MATIC)、LTC、DASH、DOGE、Cosmos(ATOM）、Monero(XMR)、Waves、Ripple(XRP)、BNB、NEO、ONT、Steller(XLM)、POTE、CLUB


仅供学习,请勿用于商业用途

## 用户请求域名

 https://www.tokenwallet.one

## 生成币种钱包地址和私钥

### 生成币种钱包地址和私钥

```
GET   /create/<symbol>
```

**symbol可选项为: btc、eth、etc、heco、bsc、okt、trx、usdt_erc20、usdt_trc20、usdt_omni、eos、bch、fil、bsv、vet、matic、ltc、dash、doge、atom、xmr、waves、xrp、bnb、neo、ont、xlm、pote、club **

### 请求示例

```
GET   /create/btc
```

### 返回参数

```
参数名			   参数类型		   描述
state     		  String			状态值: success 、error
 code         String   状态码: 1000(success)、1001(request_exceed_limit)、1002(symbol_not_supported)、1003（service_error）
symbol			  String			币种简称
addr			    String			钱包地址
privateKey		  String			钱包私钥
```



## 捐赠

**BTC地址:** 	15AEAHyMjFGqKvSgsbmUBD1M7xVXJaBsHz		

**ETH地址:**	0x3d61db050fc4810c64012ac260dc9c73b902f641		

**DOGE地址:**	D8BAJrtK4W3jZ8XNQAyjxiEQgogCbboyZb		
