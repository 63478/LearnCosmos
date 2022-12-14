## 一、选择题（多选）
#### 1 Cosmos Network 是指什么？
1. Cosmos Hub 主网
2. 区块链的互联网
3. ATOM 区块链网络
4. 多个区块链网络组成的超级网络
答：4
#### 2 以下哪些不是跨链基金会的议程（Program）
1. 促进发展负责任的监管环境
2. 提升 ATOM 代币的价格
3. 为全球 Builders 提供全方位支持
4. 提供 Cosmos 技术栈相关的在线培训
答：2
#### 3 以下哪些不是应用专有链的特性
1. 可升级性
2. 可扩展性
3. 高可用性
4. 独立自主性
5. 可互操作性
答：1、3
#### 4 以下哪些不是 Cosmos 技术栈的核心产品
1. Tendermint
2. Substrate
3. Cosmos SDK
4. IBC 跨链协议
5. Ignite CLI
答：2、5
#### 5 以下哪些说法是正确的
1. Cosmos SDK 被全球超过 200 个 PoS 区块链项目采用
2. Tendermint 是支持拜占庭容错的 PoW 共识引擎
3. IBC 是基于哈希锁机制的跨链协议
4. Tendermint 被全球超过 40% 的 PoS 区块链网络采用
答：1、4
#### 6 以下哪些 ABCI 方法不是用于执行交易的
1. BeginBlock
2. CheckTx
3. EndBlock
4. DeliverTx
答：1、2、3
#### 7 以下哪些是 Cosmos 链节点的功能分层
1. 共识层
2. 连接层
3. 会话层
4. 网络层
5. 应用层
答：2、3
#### 8 Tendermint Core 与应用层之间的通讯接口是
1. REST API
2. ABCI
3. Socket
4. GRPC
5. ABCI++
答：2、5
#### 9 以下哪些是 Tendermint Core 的特性
1. 交易的概率最终性
2. 拜占庭容错 BFT
3. 交易的快速最终性
4. 基于工作量证明 PoW
5. 交易的绝对最终性
答：2、3、5
#### 10 以下哪些说法是正确的
1. 通过向网络增加节点可提高网络的吞吐能力
2. ABCI++ 是对区块链网络的水平扩展
3. 应用专有链可对链上治理机制做定制化设计
4. IBC 是区块链之间的互操作协议
答：3、4

## 二、填空题
#### 1 Cosmos 的愿景是构建 __（区块链互联网）__
#### 2 Cosmos Hub 的主网代号是 __(Cosmos Hub)__, 主通证是 __（ATOM）__
#### 3 Tendermint 是 __(Jae Kwon)__ 发明的？ 
#### 4 Tendermint Core 正确运行需要至少占__（2/3）__投票权的验证人不作恶？
#### 5 如果你想授权他人代管你的链账户通证资产，你会使用 __(authz)__ 模块功能
#### 6 如果你想替他人支付交易手续费，你会使用 __(feegrant)__ 模块功能
#### 7 如果你想修改一个链上系统参数，你需要使用 __(upgrade)__ 模块功能
#### 8 如果你需要使用 Rust 语言编写智能合约，你会加载 __(CosmWasm)__ 合约模块
#### 9 如果你需要把以太坊上的通证跨链转移到 Cosmos 生态，你可以使用 __(Axelar)__ 或 __(Gravity Bridge)__ 网络
#### 10 如果你需要查看一笔跨链交易的分阶段详情，你可以使用 __(Mintscan)__ 或 __(IOBScan)__ 跨链浏览器

## 三、问答题
#### 1 IBC 数据包为什么会超时？
答：中继器下线或者没发送给目标链
#### 2 来自中国的技术团队为 IBC 协议贡献了哪些标准？
答：ICS-20，ICS-721，ICS-10，ICS-110，ICS-101
#### 3 跨链 NFT 转移协议（ICS-721）的 Go 语言实现代码库在哪儿？
答：https://github.com/bianjieai/ibc-go/tree/develop/modules/apps/nft-transfer
#### 4 同时支持 Web, Android, iOS 平台的 Cosmos 生态钱包有哪些（不少于两个）？
答：Keplr，MathWallet，Cosmostation
#### 5 Cosmos 中文技术社区翻译的关于 ABCI++ 的最近一篇微信公众号文章链接是什么？
答：https://mp.weixin.qq.com/s/fC3d1vqcdpvGLeorNIpDUQ