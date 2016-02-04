__Blockchain Wallet V3__

_Recent changes_

#   (2016-02-04)



---

## Bug Fixes

- **Dependencies:** update whitelist and cleanup script
  ([6426c864](https://github.com/blockchain/My-Wallet-V3/commit/6426c86421d25335a102bba25e91234c8c604a05))
- **RNG:** remove src/index.js
  ([10dd1038](https://github.com/blockchain/My-Wallet-V3/commit/10dd1038497daa1bdb0c90342a61ff700a92cc79))
- **TransactionList:** remove es6 arrow function
  ([f80c889a](https://github.com/blockchain/My-Wallet-V3/commit/f80c889a1c2797d340dca2f965e35689523430c6))
- **TxList:** compatibility with front end
  ([ce539d4d](https://github.com/blockchain/My-Wallet-V3/commit/ce539d4d0b84dad4984a3f5ee8acb46fba8ae7c0))
- **address.fromString:** write the expected error message.
  ([2c9cc8a2](https://github.com/blockchain/My-Wallet-V3/commit/2c9cc8a2bcfb802e575edb630cc1481490705ce8))
- **websocket:** catch error if websocket fails to connect
  ([c2ae19e8](https://github.com/blockchain/My-Wallet-V3/commit/c2ae19e80c38a82e6db9b11153e338c47e519ddc))


## Features

- **RNG class:**
  - added some checks on entropy
  ([f1fe52ae](https://github.com/blockchain/My-Wallet-V3/commit/f1fe52ae2c657bb8f8805688321638baf0ef94b4))
  - add and mnemo gen uses new rng
  ([dd8aaecb](https://github.com/blockchain/My-Wallet-V3/commit/dd8aaecb09896db79ebe390557c3678eef14bb84))
  - combine local and server ent
  ([a7b43062](https://github.com/blockchain/My-Wallet-V3/commit/a7b43062d94bebb619db089c139e94412c8d44ea))
  - added server side entropy.
  ([81a49738](https://github.com/blockchain/My-Wallet-V3/commit/81a49738261db6521210fd7be768a0a687a17a3f))
- **TxList:**
  - use all xpubs and addresses, find tx by hash prop
  ([de5d3ea2](https://github.com/blockchain/My-Wallet-V3/commit/de5d3ea2bfa77152bf2672765f2508a9e3bdbf27))
  - use events api to emit updates
  ([e93f01a9](https://github.com/blockchain/My-Wallet-V3/commit/e93f01a96a7ad9d55b9a0cc0d1fa1a0179fa935c))
  - allow subscribing to tx changes
  ([6bb947e7](https://github.com/blockchain/My-Wallet-V3/commit/6bb947e73ad8f50e6a7c270314602b1ece85289c))
  - add TransactionList class for storing txs
  ([f4b9b068](https://github.com/blockchain/My-Wallet-V3/commit/f4b9b06883d2d640470ce8916c2a6c3d4c7c4596))
- **add-key:** add private key to watch only.
  ([f4fd92db](https://github.com/blockchain/My-Wallet-V3/commit/f4fd92db7826a2eb7a054ee09a21bbba4ea5bd70))
- **tests:** added Blockchain-wallet tests for wallet creation in case of rng failure.
  ([99035ccf](https://github.com/blockchain/My-Wallet-V3/commit/99035ccf2a0b2c8795a77e2cbe79e933466088d1))


## Refactor

- **crypto:** remove deprecated CryptoJS dependency
- **tests:** delete old files.


## Test

- **Address:**
  - RNG tests
  - Address.new() tests
- **BlockchainWallet:** newHDWallet and more tests for Wallet.new
- **RNG:**
  - XOR length, run() and getServerEntropy()
  - added xor test
- **TransactionList:** add tests for TransactionList class
- **Travis:** use modern Chrome
- **hdwallet.new:** fix rng mock.


## Chore

- **Release:** 3.7.0



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>