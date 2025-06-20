# Get Started With Web3: 发送第一笔 Web3 交易

---

自学入门 `Web3` 不是一件容易的事，作为一个刚刚入门 Web3 的新人，梳理一下最简单直观的 `Web3` 小白入门教程。整合开源社区优质资源，为大家从入门到精通 Web3 指路。每周更新 1-3 讲。

欢迎关注我的推特：[@bhbtc1337](https://twitter.com/bhbtc1337)

北航区块链协会 DAO 推特：[@BHBA_DAO](https://twitter.com/BHBA_DAO)

进入微信交流群请填表：[表格链接](https://forms.gle/QMBwL6LwZyQew1tX8)

文章开源在 GitHub：[Get-Started-with-Web3](https://github.com/beihaili/Get-Started-with-Web3)

购买BTC/ETH/USDT 等加密货币推荐 [币安](https://www.binance.com/zh-CN)[注册链接](https://accounts.marketwebb.me/register?ref=39797374)

---

## 交易是什么

交易是一种在区块链上执行的动作，它可以是一次转账，也可以是一次合约调用。交易的执行需要消耗一定的 gas，gas 是用户为了执行交易向矿工或验证节点发送的一定数量的代币，gas 的多少是由网络的实时情况决定的，通常矿工或验证节点会优先打包高 gas 的交易上链。交易的执行结果会被写入区块链中，所有人都可以通过区块链查询到交易的执行结果。

## 0 成本在测试网上发出第一笔交易

### 1. 选择测试网络

首先我们要选择一个合适的测试网络方便发送交易，由于测试网络可以免费领取代币，又不会占用主网宝贵的资源所以我们选择测试网络进行第一笔交易的发送。打开小狐狸钱包，点击右上角的网络信息。

<div align="center"> <img src="./img/01.jpg" width = 600 /> </div>

选择测试网络，如果跳转到设置页面就在设置页面中打开测试网络选项。

<div align="center"> <img src="./img/02.jpg" width = 600 /> </div>

选择 Goerli 测试网络。

### 2. 领取测试代币

下一步我们去 [Goerli 水龙头](https://goerlifaucet.com/) 领取测试代币。登录网站，填入我们的的钱包地址，点击 Send me ETH 按钮，等待一会就可以收到测试代币了。

<div align="center"> <img src="./img/03.jpg" width = 600 /> </div>

点击后可以看到水龙头发送代币的交易信息。

<div align="center"> <img src="./img/04.jpg" width = 600 /> </div>

回到钱包中我们可以看到代币余额变化了。

<div align="center"> <img src="./img/05.jpg" width = 600 /> </div>

### 3. 发送交易

点击小狐狸钱包的 发送 按钮可以看到发送交易的页面，填入接收地址，这里我们方便起见写入发送地址。

<div align="center"> <img src="./img/07.jpg" width = 600 /> </div>

点击确定后来到发送界面，选择发送资产类型，数额，gas 费用。

<div align="center"> <img src="./img/06.jpg" width = 600 /> </div>

gas 费用可以根据需要选择低中高三种类型，也可以自定义 gas 费用，gas 费用越高交易被打包的优先级越高，但是 gas 费用越高，交易的执行成本也越高。

<div align="center"> <img src="./img/08.jpg" width = 600 /> </div>

<div align="center"> <img src="./img/09.jpg" width = 600 /> </div>

最后点击发送按钮，发送交易。

### 4. 查询交易

发送交易后点击活动即可查询发出的交易。

<div align="center"> <img src="./img/10.jpg" width = 600 /> </div>

目前交易显示待处理说明交易已经发送出去但是还没有被验证节点打包上链。

<div align="center"> <img src="./img/11.jpg" width = 600 /> </div>

点击交易可以查看交易详情，交易详情中点击在区块链浏览器上查看可以看到更多信息。

<div align="center"> <img src="./img/12.jpg" width = 600 /> </div>

在浏览器中可以看到：
- 交易哈希
- 交易状态
- 上链区块
- 时间戳
- 发送交易地址
- 接收交易地址
- 交易金额
- 交易费用

点击显示详细信息可以看到更多信息包括：

- gas price
- gas limit
- gas fees
- burnt & Txn Savings fees
- other attributes
- input data

<div align="center"> <img src="./img/13.jpg" width = 600 /> </div>

## （选做）在主网上发出第一笔交易

### 1. 获取主网代币

和测试网上发送交易的情况一样，在主网上发送交易同样需要一定的代币作为 gas。

我们可以通过交易所或者其他途径获取代币。小额的代币获取可以尝试加入我们的群聊在群里找群友私下交易一下（建议 50 元以下的可以找群友勾兑，有风险大额不建议）这里还需要双方查询当前的资产价格，可以通过 [Coinmarketcap](https://coinmarketcap.com/) 或者 [CoinGecko](https://www.coingecko.com/zh) 查询，Coinmarketcap 和 CoinGecko 是两个常用的查询数字资产价格的网站，上面提供大部分数字资产的价格信息。

通过交易所途径获得代币这里我们以行业内的头部 OKX 交易所为例进行介绍，打开 OKX 交易所，注册账号，完成实名认证，然后通过 C2C 交易获得数字资产。C2C 交易就是用户之间的交易，用户可以在 OKX 上发布自己的交易信息，然后其他用户可以看到这个信息，然后进行交易。交易由 OKX 提供中间担保，这个方案比较安全。一般是先用法定货币购买 USDT，然后在交易所内用 USDT 购买其他数字资产（例如用 USDT 换 ETH）。这里我们以 ETH 为例，C2C 交易后等待 24 小时冷冻期，购买 ETH，然后点击提币，选择 ETH 主网，粘贴自己的钱包地址，输入密码点击确认提币，等待一会儿后交易所会将代币从交易所地址转到你的地址，然后就可以在钱包中看到自己的 ETH 余额了。

P.S. 可以通过推荐链接注册 OKX 账号，有手续费优惠 [OKX 注册](https://cnouyi.studio/join/7133496)

## 总结

本文介绍了如何使用小狐狸钱包发送一笔最简单的转账交易。交易是我们接触区块链最直接的方式，通常交易的参数和调用方法都在区块链项目的前端中写好，用户只需签署交易即可，非常简单。恭喜你完成了第一笔交易，你现在可以在 10 分钟内给国外的朋友转账了😄下一节我们将介绍如何与 Dapp 交互。
