__Blockchain Wallet V3__

_Recent changes_

#   (2016-02-20)



---

## Bug Fixes

- **Cosmetic:** fixed indents in HDWallet tests
  ([98bc62da](https://github.com/blockchain/My-Wallet-V3/commit/98bc62daf048a6c7c75e4f35f823cff99994520a))
- **Helper:** TOR detection could send false positives
  ([b7e7bf25](https://github.com/blockchain/My-Wallet-V3/commit/b7e7bf258db41e91463b5ea89d0f7d384cd536f8))
- **Helpers:** replace endsWith with slice for browser compatibility
  ([52962766](https://github.com/blockchain/My-Wallet-V3/commit/52962766594f898f4d8bb902b5dc2d534c2a0405))
- **Transactions:** only call multiaddr with active addresses and xpubs
  ([d7d79f94](https://github.com/blockchain/My-Wallet-V3/commit/d7d79f9428395d23b366762e775fb9b3df968063))
- **key:** only 40-44 chars len base58 keys can be used.
  ([a1576618](https://github.com/blockchain/My-Wallet-V3/commit/a157661839cd80d3ad302be2e5150f829f5245f9))
- **keys:** keys shorter than 32 bytes are now usable
  ([2617c1f6](https://github.com/blockchain/My-Wallet-V3/commit/2617c1f6e2ad0193b24e0b82d5e8e98beb0d522a))


## Test

- **Address:**
  - Added more tests to Address
  - more tests for Address
  - added more tests to Address
- **HDAccount:** added more tests to HDAccount
- **Helper:** added tests for some helper functions
- **RNG:** RNG now covered at 100%
- **TransactionList:** two more small tests for TxList
- **WalletCrypto:** test cipherFunction behaviour with invalid parameters
- **blockchain-wallet:**
  - More tests for encryption, decryption and getPrivateKeyForAddress
  - added watch-omly and archived keys to the test wallet



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>