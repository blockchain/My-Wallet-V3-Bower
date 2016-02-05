__Blockchain Wallet V3__

_Recent changes_

#   (2016-02-05)



---

## Bug Fixes

- **WalletCrypto:** use correct key block size when padding with Iso10126
  ([1b97b5c7](https://github.com/blockchain/My-Wallet-V3/commit/1b97b5c7ff17289779639e4b5f6fdc60c46178a5))
- **WalletTransaction:** use some instead of map/reduce
  ([91d84044](https://github.com/blockchain/My-Wallet-V3/commit/91d84044f24749593e864cca2efd17d657ae35a3))


## Features

- **Analytics:** remove
  ([f957a8e6](https://github.com/blockchain/My-Wallet-V3/commit/f957a8e6bb7e230d65773ef6e309fb018af0ec95))
- **TOR:** don't use web sockets
  ([e0347d5e](https://github.com/blockchain/My-Wallet-V3/commit/e0347d5e54cd21e5b527b628fa2625b6bdf31ede))
- **WalletTransaction:** detect sent to/from watch-only
  ([cd68349f](https://github.com/blockchain/My-Wallet-V3/commit/cd68349f0ef7ba711811120ee3a593b0ec6fecb8))


## Refactor

- **rng:**
  - clean up getServerEntropy function
  - use crypto-browserify implementation of xor
  - move entropy code to top of function
  - remove unused callback and unnecessary assert


## Test

- **BlockchainSocket:** basic tests



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>