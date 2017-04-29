# TiKV-for-DLT

TiKV 是一个开源分布式Key-Value型数据库. 代码地址(https://github.com/pingcap/tikv).  TiKV-for-DLT 是面向区块链和分布式账本技术平台的开源可插拔分布式Key-Value型数据库.

## 支持的DLT平台目录

- [TiKV for Hyperledger/Fabric](https://github.com/CBD-Forum/TiKV-for-DLT/blob/master/for-fabric/tikv-for-fabric.md)
- [TiKV for Hyperledger/Sawtooth](#TiKV-for-Hyperledger/Sawtooth)
- [TiKV for Hyperledger/Iroha](#TiKV-for-Hyperledger/Iroha)
- [TiKV for Ethereum](#TiKV-for-Ethereum)

## TiKV for Hyperledger/Fabric

Hyperledger Fabric 是区块链技术的一种实现，它通过模块化的架构允许组件的“插入-运行”来实现这份协议规范。它具有强大的容器技术，因此可支持任何主流的语言来开发智能合约。Fabric 基于工业化、商业化的需求来设计的，并引入了可扩展性。它是典型的许可制区块链解决方案。Fabric 1.0版本支持 leveldb/couchdb 作为持久化存储数据库.我们通过 [TiKV-For-Fabric集成步骤](https://github.com/CBD-Forum/TiKV-for-DLT/blob/master/for-fabric/tikv-for-fabric.md), 实现Fabric区块链平台与分布式TiKV数据库的集成、使用.

## TiKV for Hyperledger/Sawtooth

TODO

## TiKV for Hyperledger/Iroha

TODO

## TiKV for 以太坊（Ethereum）

TODO

## 代码贡献

欢迎各种形式的开源代码贡献. 本项目提供绝大多数DLT平台的可插拔集成，还有很多集成工作没有实现! 

## 许可

TiKV-for-DLT 项目使用 Apache License Version 2.0 软件许可.
