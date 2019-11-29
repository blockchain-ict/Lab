# 概述
本平台是ICT区块链实验室公共平台，主要用于：

* 共享公共学习资源。包括论文、笔记、有价值的文章博客等。
* 协同开发项目。用于实现多人协同工作时，代码管理，文档管理；便于新加入成员快速熟悉项目，能够快速入手；
* 展示实验室成果，公布相关博客，提升实验室影响力。

# 加入及文档规范

1. 欢迎大家积极共享相关文献资源，编辑、完善相应的内容。
2. 尽量使用Markdown文档进行编辑，Markdown文档基础教程可参考[Markdown基础教程]( https://juejin.im/post/5ad6e09e518825557b4d451c )；推荐使用typora-Markdown编辑阅读器：[ https://typora.io/ ]( https://typora.io/ )。
3. 每位同学在`commit`相关文档或项目时，附加信息请添加有个人标识，可以是姓名拼音或者是拼音简写，并采用简要的语句概述相关改动。如：`git commit -m "Zhangsan: fix a bug"`。
4. 善用`.gitignore`文件，禁止将过程文件、个人配置文件等杂乱文件上传到共享库中。除必要外，应保证上传到库中只有文档类文件及源码类文件。
5. 处于实验室开发中的项目及未公开的项目，必须建立私有仓库，禁止使用公有仓库。涉及一定机密的项目，禁止在该平台进行协助开发。

# 项目协作开发规范

通过Github平台进行协同开发，有利于资源共享、版本控制，便于新人加入着手项目，能够极大的提高项目开发效率。对于协同开发，每个项目需遵循以下规范：

1. 除开源项目外，必须创建私有库进行开发。
2. 每个项目需要有一个主负责人，负责管理该公共账号，并创建相应的私有库；负责合并代码，合并项目资料；其他成员由主负责人邀请，加入到私有库开发中，共同进行开发。
3. 对于每个项目的库，建议使用以下结构：

```
project
|__README.md
|__doc
|__src
|__test
```

其中，`README.md`文档应包含有项目的一个概况及相关的一些信息，如[示例](./ProjectRMDemo.md)所示。`doc`主要包含一些开发中的文档。`src`主要包含相关代码，`test`是项目的测试入口。

4. 对于每个项目必须包含相关的说明文档，包括但不限于：项目概述文档（包含项目的整体状况）、开发环境的搭建说明（可以是一些博客链接，帮助他人快速入手）、相关资料整理等。

# 区块链入门推荐

* 区块链技术脱胎于比特币应用，因此先可以看看[《精通比特币》]( https://github.com/tianmingyun/MasterBitcoin2CN )对区块链实现有一个初步的认识。
* 以太坊(Ethereum)是目前区块链技术较为成功的一个应用，也是开发者较多的一个开源项目，其一般被认为区块链2.0的代表，可以看看[以太坊黄皮书]( https://ethereum.github.io/yellowpaper/paper.pdf )，对以太坊有个初步的了解。
* 初步了解下[智能合约]( https://solidity.readthedocs.io/en/v0.5.13/ )，能够编写简单的合约。
* 学会使用[web3]( https://web3py.readthedocs.io/en/stable/web3.main.html )或者[JSON RPC]( https://github.com/ethereum/wiki/wiki/JSON-RPC )，与以太坊节点进行交互。掌握DAPP开发基本知识。
* 了解POW、POS、POA、PBFT等分布式共识算法。

# 相关论文推荐

具体请查看[论文相关文档](./paper/README.md)。

# 相关博客推荐

* [李康师兄的博客]( https://ethereum.iethpay.com/smart-contract-battle1.html )，详细介绍了以太坊私链的搭建及合约的部署，以及一些笔记
* [以太坊爱好者]( https://ethfans.org/ )
* [深入浅出区块链]( https://learnblockchain.cn/ )
* ...

# 相关开源项目推荐

* [Bitcoin]( https://github.com/bitcoin/bitcoin )
* [Ethereum]( https://github.com/ethereum/go-ethereum )

* [以太坊源码分析]( https://github.com/ZtesoftCS/go-ethereum-code-analysis )



