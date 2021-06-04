# learn-solidity

```
  /$$$$$$            /$$ /$$       /$$ /$$   /$$
 /$$__  $$          | $$|__/      | $$|__/  | $$
| $$  \__/  /$$$$$$ | $$ /$$  /$$$$$$$ /$$ /$$$$$$   /$$   /$$
|  $$$$$$  /$$__  $$| $$| $$ /$$__  $$| $$|_  $$_/  | $$  | $$
 \____  $$| $$  \ $$| $$| $$| $$  | $$| $$  | $$    | $$  | $$
 /$$  \ $$| $$  | $$| $$| $$| $$  | $$| $$  | $$ /$$| $$  | $$
|  $$$$$$/|  $$$$$$/| $$| $$|  $$$$$$$| $$  |  $$$$/|  $$$$$$$
 \______/  \______/ |__/|__/ \_______/|__/   \___/   \____  $$
                                                     /$$  | $$
                                                    |  $$$$$$/
                                                     \______/
```

本课程致力于推广面对财富编程的以太坊智能合约语言 Solidity

- 对于有代码基础的小伙伴, 可以通过此教程入门
- 对于没有代码基础的小伙伴, 可以通过此教程了解部分以太坊的工作原理以及智能合约是什么, 甚至可以看懂比较简单的智能合约

# 目录

1.  [第一课](./courses/1.md#第一课)

    1. [简介](./courses/1.md#简介)
       - [什么是以太坊智能合约?](./courses/1.md#什么是以太坊智能合约)
       - [什么是 Solidity?](./courses/1.md#什么是-solidity)
       - [以太坊账户模型](./courses/1.md#以太坊账户模型)
       - [以太坊交易](./courses/1.md#以太坊交易)
    1. [准备工作](./courses/1.md#准备工作)
    1. [Solidity](./courses/1.md#Solidity)
       - [文件结构](./courses/1.md#文件结构)
       - [常用类型](./courses/1.md#常用类型)
       - [全局变量和函数](./courses/1.md#全局变量和函数)
       - [使用例子](./courses/1.md#使用例子)
    1. [Transaction 和 Call 的区别](./courses/1.md#transaction-和-call-的区别)
    1. [第一个智能合约(ERC20)](./courses/1.md#第一个智能合约)
    1. [课堂作业](./courses/1.md#课堂作业)

1.  [第二课](./courses/2.md#第二课)

    1. [Remix](./courses/2.md#Remix)
       - [编译智能合约](./courses/2.md#编译智能合约)
       - [部署、调试智能合约](./courses/2.md#部署、调试智能合约)
       - [手动认证智能合约](./courses/2.md#手动认证智能合约)
    1. [Hardhat](./courses/2.md#Hardhat)
       - [Hardhat 项目构建](./courses/2.md#hardhat-项目构建)
       - [Hardhat 的使用](./courses/2.md#hardhat-的使用)
       - [自动认证智能合约](./courses/2.md#自动认证智能合约)
    1. 示例代码讲解(OpenZepplin)
       - [SafeMath](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v3.2.0/contracts/math/SafeMath.sol)
       - [AccessControl](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/release-v3.2.0/contracts/access/AccessControl.sol)
       - [ERC20](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/release-v3.2.0/contracts/token/ERC20)
       - [ERC721](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/release-v3.2.0/contracts/token/ERC721)
    1. [课堂作业](./courses/2.md#课堂作业)

1.  第三课

    1. UniswapV2 智能合约分析
    1. MasterChef, SwapMining 智能合约分析

1.  第四课

    1. 智能合约常见漏洞
       - 重入攻击
       - 溢出攻击
       - 未初始化的存储指针
       - ...
    1. 智能合约原理
       - merkle-patricia-trie
       - 智能合约运行原理
       - 一个简单的例子
