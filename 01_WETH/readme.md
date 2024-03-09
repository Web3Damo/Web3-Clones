# WETH (Wrapped Ethereum)

WETH (Wrapped Ethereum) 是以太坊上与 ETH 价格 1:1 挂钩的 ERC-20 代币。

## 部署指南

### 1. `WETH.sol`

#### 1.1 编译选项(Compiler Settings)

| Setting              | Value                        |
| -------------------- | ---------------------------- |
| Contract Name        | **WETH**        |
| Optimization Enabled | **No** with **200** runs |
| Compiler Version     | **0.8.19+commit.7dd6d404**   |
| Evm Version          | default                      |

## 核心函数

- `deposit()` 或 `直接向合约地址转账ETH`

- `withdraw(uint wad)` 

## 测试

| 测试内容              | 链上记录                        |
| -------------------- | ---------------------------- |
| 部署       | [0xfA22cD2014576457b308CC82915AD64A11eE59E5](https://testnet.bscscan.com/address/0xfa22cd2014576457b308cc82915ad64a11ee59e5)        |
| Deposit | [0x75094fb787707b08959415037a42c389b619d4540b219fc4501bab0b35b9a89f](https://testnet.bscscan.com/tx/0x75094fb787707b08959415037a42c389b619d4540b219fc4501bab0b35b9a89f) |
| Withdraw     | [0xa9ca7cbb16be749485ef922b878aed98ea618e8bf4e6ae62d5c4003125f42638](https://testnet.bscscan.com/tx/0xa9ca7cbb16be749485ef922b878aed98ea618e8bf4e6ae62d5c4003125f42638)  |


## 参考

### 合约

- [WETH9](https://etherscan.io/address/0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2) - 💡 以太主网WETH
- [WBNB](https://bscscan.com/address/0xbb4CdB9CBd36B01bD1cBaEBF2De08d9173bc095c) - BSC主网WBNB

### 文章

- [WTF IS WETH?](https://weth.io/)
- [WETH与ETH：有什么区别？](https://www.biyuandi.com/biyuandi/1011.html)