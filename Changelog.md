__Blockchain Wallet V3__

#   (2016-05-06)



---

## Bug Fixes

- **BlockchainWallet:** Test if legacy address exists before deleting it
  ([9ecac985](https://github.com/blockchain/My-Wallet-V3/commit/9ecac985e32ffafbd26b10e19be45a3e088af3d4))
- **Grunt:** Changelog task depends on node_modules
  ([671856a4](https://github.com/blockchain/My-Wallet-V3/commit/671856a4ba6716fb75df0d17f707e9a194650faf))
- **Recovery:** do not use temporary mnemonic + cleanup
  ([9df9a130](https://github.com/blockchain/My-Wallet-V3/commit/9df9a13065e71fad79d1b6164e680bbac327a9e6))
- **password-score:** any email must always score as bad.
  ([bf3bab74](https://github.com/blockchain/My-Wallet-V3/commit/bf3bab74620a893816a9bcc5df10ba5645d2d2fc))


## Refactor

- **ImportExport:** Moved crypt function to WalletCrypto
- **WebSocket:** upgrade ws to v 1.1.0


## Test

- **BlockchainWallet:**
  - More tests for Wallet
  - Tests on helper functions
- **Helpers:** Added tests for some functions
- **Transaction:** full coverage for transaction.js


## Chore

- **Package:** bump version and add authors



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>