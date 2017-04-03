__Blockchain Wallet V3__

#   (2017-04-03)



---

## Bug Fixes

- test and safer function
  ([df589d58](https://github.com/blockchain/My-Wallet-V3/commit/df589d58546f1de499305dd9f93755dca5584fe9))
- max available amount
  ([494a661a](https://github.com/blockchain/My-Wallet-V3/commit/494a661a0be77e5d92ed7ffc738676a1d0ca484a))
- **api:** remove mock for charge_address request on testnet
  ([20f165ee](https://github.com/blockchain/My-Wallet-V3/commit/20f165eeafe337915da9e50c0ce3ee38537044a6))
- **helpers:** hash guid to create group instead of relying on first char
  ([eaf79a77](https://github.com/blockchain/My-Wallet-V3/commit/eaf79a77b3c7cb7aff90ca7716e957c143b58cf9))
- **payment:**
  - prevent state issues caused by mutability
  ([ea803054](https://github.com/blockchain/My-Wallet-V3/commit/ea80305437f1ef92da9641771877a94add2ce2f8))
  - correctly access last elem of amounts
  ([21ebe788](https://github.com/blockchain/My-Wallet-V3/commit/21ebe78845d3049b9d31ca8ed5a2aeefe974d872))


## Features

- feat(fee experiment)
  ([840a344f](https://github.com/blockchain/My-Wallet-V3/commit/840a344fe77f63dc0842cb124d07f56354596d4e))
- **api:** flag to record advanced send in pushTxStats
  ([878d8a56](https://github.com/blockchain/My-Wallet-V3/commit/878d8a564efe0409ff00a2cd97fec3f4b9a98c86))
- **experiment:** groups a and b
  ([c47a4e3e](https://github.com/blockchain/My-Wallet-V3/commit/c47a4e3ed20c06357ad0b1a0b731fd1cf77f9362))


## Refactor

- **helpers:** less convoluted way of reading first bit
  ([5721c39a](https://github.com/blockchain/My-Wallet-V3/commit/5721c39a9420f47aad753fbd4f4542761c6a6625))


## Chore

- **helpers:** clean helpers file
  ([c8211120](https://github.com/blockchain/My-Wallet-V3/commit/c8211120eb695c0f375449e77e4198da7ac27c08))


## Pull requests merged

- Merge pull request #353 from blockchain/max-available
  ([3fecba5a](https://github.com/blockchain/My-Wallet-V3/commit/3fecba5a5dbaa48abee0734574f2057f99010f96))
- Merge pull request #351 from blockchain/state-cleanup
  ([1643b4ad](https://github.com/blockchain/My-Wallet-V3/commit/1643b4ada40b35bf72dec7ceb5ebb89cef424874))
- Merge pull request #350 from blockchain/hash-guid
  ([c7cf2b48](https://github.com/blockchain/My-Wallet-V3/commit/c7cf2b4848d3e75aeb608758cbc7d8c68e84a112))
- Merge pull request #348 from blockchain/fee2
  ([4df76dcf](https://github.com/blockchain/My-Wallet-V3/commit/4df76dcfe4f97411a78641af151e30922628e3e2))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>