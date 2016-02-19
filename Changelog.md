__Blockchain Wallet V3__

_Recent changes_

#   (2016-02-19)



---

## Bug Fixes

- **confirmations:**
  - tx conf are now static.
  ([44a0efbd](https://github.com/blockchain/My-Wallet-V3/commit/44a0efbdd5960275ad2894c70f157208dc86b777))
  - conf are computed on ask based on latest-block.
  ([7898adb0](https://github.com/blockchain/My-Wallet-V3/commit/7898adb0a671052f9477382598ec083850de7ec6))
- **transactions:** wipe transactions after call to get history
  ([9cd832db](https://github.com/blockchain/My-Wallet-V3/commit/9cd832db68964c02da19619c8c9386f0d5ee217f))
- **utx:** added on_tx_received event for ios request.
  ([cc2f15b7](https://github.com/blockchain/My-Wallet-V3/commit/cc2f15b7d8841485e64343bb640b99e72da26fda))
- **ws:**
  - send on_tx and on_block messages after getHistory
  ([53bb39b7](https://github.com/blockchain/My-Wallet-V3/commit/53bb39b76ffe84e6b87790f6ed49558ad488ed89))
  - send ping op instead of ping_block
  ([510bd875](https://github.com/blockchain/My-Wallet-V3/commit/510bd875d9b93c24b9e57e29b78bf5bb90afabd6))


## Features

- **txlist:** added a digested txlist for iOS.
  ([0cfe53e5](https://github.com/blockchain/My-Wallet-V3/commit/0cfe53e5752f242509a6e9c25e5f6ba7ee8f9ff6))


## Refactor

- **txlist:** clean some code.


## Test

- removed tests for removed code.


## Chore

- **Whitelist:** bump es6-promise



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>