__Blockchain Wallet V3__

#   (2016-09-26)



---

## Bug Fixes

- **quote:** return processed payment methods after fetching them
  ([a0247370](https://github.com/blockchain/My-Wallet-V3/commit/a0247370b519fce312c83afa2c142a18614216c9))
- **trade:** refresh() resolves with 'this'
  ([dc277c12](https://github.com/blockchain/My-Wallet-V3/commit/dc277c12586669f6e64855a6d85358c7b7f5e6b0))
- **trade expiration:** expire btc expected amount quote in one min
  ([ca06b8f5](https://github.com/blockchain/My-Wallet-V3/commit/ca06b8f5d7a2a1dd1f87f4ffc297900369cbebfc))


## Features

- **buysell:** debug logging, check that test trade isn't already matched
  ([799de233](https://github.com/blockchain/My-Wallet-V3/commit/799de23340ea687cf8cf24b357f1f452e0d3ce25))
- **coinify:** remove deprecated getPaymentMethods()
  ([af8c9edf](https://github.com/blockchain/My-Wallet-V3/commit/af8c9edfd529ee37eee93d470264e13657862eab))
- **helpers:** add maxTime arg to exponentialBackoff function (#282)
  ([357df563](https://github.com/blockchain/My-Wallet-V3/commit/357df563b1faca8241fc54eebc7677a7e6153cc4))
- **trade:** use trade.quoteExpireTime
  ([9d6699d0](https://github.com/blockchain/My-Wallet-V3/commit/9d6699d0a65740974748277f47ac3d9553d4afe8))


## Refactor

- **exchangedelegate:** requires trades array
  ([4b3c5218](https://github.com/blockchain/My-Wallet-V3/commit/4b3c5218d6f848e3561b349b0cbeeb121ce7f14d))
- **trade:** move save() to delegate
  ([e9a4c32e](https://github.com/blockchain/My-Wallet-V3/commit/e9a4c32e9d8f89034242c77c3f240fbd675aa2cd))


## Test

- **coinify:**
  - fixed KYC getters test, added unknown state warning test to Trade
  ([23359668](https://github.com/blockchain/My-Wallet-V3/commit/23359668300c913b053ee0e2d43839611a077077))
  - more for KYC, Quote, BankAccount, Helpers, Level, PaymentMethod, Quote, Coinify
  ([33de5461](https://github.com/blockchain/My-Wallet-V3/commit/33de5461b1c72064db64beef072ba86c7e602a78))
- **coinifyapi:** authenticated POST + PATCH
  ([f3edeab8](https://github.com/blockchain/My-Wallet-V3/commit/f3edeab875652c57a2668aeaecbf0d0e90db3c62))
- **coinifybankaccount:** use mock for Address
  ([44a61506](https://github.com/blockchain/My-Wallet-V3/commit/44a61506b6806164eeea47d3b6c1877dcc5b0164))
- **exchangedelegate:**
  - monitorAddress()
  ([59f065f3](https://github.com/blockchain/My-Wallet-V3/commit/59f065f399da4d6518a2606c48b706bd83d106b4))
  - add debug test, skip console.info for coverage
  ([b82c031b](https://github.com/blockchain/My-Wallet-V3/commit/b82c031b052d033d499ab63742f8c74871260d9f))
- **trade:** more tests
  ([610b6c90](https://github.com/blockchain/My-Wallet-V3/commit/610b6c909fd534a0bfde04f041fc16c22bb5f3ea))


## Chore

- **release:** bump version
  ([ec9928fc](https://github.com/blockchain/My-Wallet-V3/commit/ec9928fc09806cbefad4b2bf03e9db460b103b49))


## Pull requests merged

- Merge pull request #284 from blockchain/trade-dependencies
  ([8d4c87c5](https://github.com/blockchain/My-Wallet-V3/commit/8d4c87c58de923a67dc270f760d19ad935d701ca))
- Merge pull request #283 from blockchain/quote-expiration
  ([ad224997](https://github.com/blockchain/My-Wallet-V3/commit/ad224997e94c14a61ef8608a097eff8e4140b37f))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>