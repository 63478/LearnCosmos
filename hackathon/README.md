# 一个去中心化连载小说写作与阅读平台

## 背景
中心化的平台最大的问题是垄断，这导致了以下问题：
1. 审查原因，有些类型的小说作者无法上传。
2. 审查原因，有些小说会被突然下架。 
3. 公平问题，是否所有作者的小说都能被公平的披露给读者，而不是暗箱操作，限流。
4. 所有权问题，作者写的小说的所有权如何无法得到保障。
5. 经济模型问题，粉丝按照字数订阅文章，会引导作者写水文。同时，粉丝消费到底有多少是自己喜欢的作者手里，不透明。
6. 形成垄断后，大平台完全掌控流量，作者没有其他投稿平台，容易被平台剥削。
7. 亲人的账号无法共享，还要再次消费。
8. 用户评论不需要付费，导致公地悲剧，太多毫无价值甚至恶意攻击诋毁、水军等评论信息。

## 解决方案
使用区块链和去中心化存储技术，保障作者对其文章的所有权。中心化的平台为用户提供舒适的阅读体验、方便的交互过程、对文章的索引、作者与粉丝的关系的建立与维系，作者与用户完全可以不通过平台进行写作与阅读。

## 大致的架构图
![architecture](/assets/hackathon/architecture.png)

## 经济模型
恒定每个块32个币，没有最大限量，保证节点一直有动力维护这个链，通削弱先发优势，币子尽量公平分配给用户。但通胀率会逐渐减小，变成微通胀模式，所以早期区块链节点维护者还是有一定优势的。

## 疑问
1. 作者是否应该有权删除其作品？还是说应该培养用户的思维模式，习惯无法删除的这个特点。
2. 盗版问题能通过技术解决吗？无论怎么加密，链下人的环节始终不可控，只要还想给人看，就需要解密，所以，强制付费模式行不通。盗版问题也只能通过法律途径解决，技术可以证明所有权，法律取证就变得很容易。
