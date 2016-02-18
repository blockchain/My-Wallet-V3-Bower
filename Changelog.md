__Blockchain Wallet V3__

_Recent changes_

#   (2016-02-18)



---

## Bug Fixes

- **Transactions:**
  - prevent duplicate transactions in txlist
  ([23d174fe](https://github.com/blockchain/My-Wallet-V3/commit/23d174fec1dcefc20c548e2e4ef6a5733b624417))
  - check for duplicates
  ([dbe8036c](https://github.com/blockchain/My-Wallet-V3/commit/dbe8036c56459f5615aede7a4e1f60b4f2ca5565))
- **getTransaction:** idiomatic change.
  ([fb9227d2](https://github.com/blockchain/My-Wallet-V3/commit/fb9227d2bf84574ab8f30419eeef765514bf1537))
- **import:**
  - right key imported.
  ([6c3b86ba](https://github.com/blockchain/My-Wallet-V3/commit/6c3b86ba646b59008b4481b3ca769265b344024c))
  - add key when already exists and it is watchonly.
  ([dfda7ba3](https://github.com/blockchain/My-Wallet-V3/commit/dfda7ba361b669fa7953f1df36385aa5a320e32a))


## Features

- **TxList:** enable tx list refresh
  ([25ff401b](https://github.com/blockchain/My-Wallet-V3/commit/25ff401bd37fc72f7965277010626fe2aba280c4))
- **WatchOnly:**
  - maintain label when adding private key to watch only address
  ([39e9c91f](https://github.com/blockchain/My-Wallet-V3/commit/39e9c91fcce4ce25f5cff7f294e1e224c4f3b51b))
  - Add private key to watch only address in importLegacyAddress
  ([fcaef625](https://github.com/blockchain/My-Wallet-V3/commit/fcaef625ef9d5bd348ccbc05259bcd01cc0f21c5))


## Test

- **TransactionList:** test that duplication transactions are prevented in 23d174fec1
- **WalletStore:** added tests and removed unneeded fix from dbe8036c5645



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>