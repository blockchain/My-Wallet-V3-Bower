__Blockchain Wallet V3__

#   (2016-09-16)



---

## Bug Fixes

- **kyc:** return self after setting internal properties
  ([5ab08bec](https://github.com/blockchain/My-Wallet-V3/commit/5ab08bec590d60030d27dab26040fc5358aea7d1))


## Features

- **blockchainwallet:** add function to get note placeholder (#275)
  ([937f8fc3](https://github.com/blockchain/My-Wallet-V3/commit/937f8fc38a66c67cc56aab004938253f11c45399))
- **coinify:** store buy & sell currency list after fetching
  ([36f3bc33](https://github.com/blockchain/My-Wallet-V3/commit/36f3bc33a1cd1302d373a65b4e73b095dcd5292f))
- **trade:** card declined()
  ([4f4dbab3](https://github.com/blockchain/My-Wallet-V3/commit/4f4dbab3c982f844736ddc374d73feda26c814de))


## Refactor

- **coinify:**
  - API class, fewer circular dependencies
  ([d62a9447](https://github.com/blockchain/My-Wallet-V3/commit/d62a94476343b5ff399770c4fada393e8af6573b))
  - reuse Trade & KYC list management
  ([64d585ae](https://github.com/blockchain/My-Wallet-V3/commit/64d585ae82e612eb432da17bdff4c4abb644a48d))
- **trade:** move currency functions into helpers (#276)
  ([ab863403](https://github.com/blockchain/My-Wallet-V3/commit/ab8634033f0f665e6970f58c25d5aff9cd274ede))


## Test

- **coinify:**
  - buy()
  ([207b0e40](https://github.com/blockchain/My-Wallet-V3/commit/207b0e40eb98192903fa1b4f524ae058bfd4dd87))
  - use .kycs accessor
  ([7af539ba](https://github.com/blockchain/My-Wallet-V3/commit/7af539ba382e7f4797661de52728ae1482dd889f))
  - triggerKYC test fixed
  ([2e88a8a8](https://github.com/blockchain/My-Wallet-V3/commit/2e88a8a84ae14d6f7e49bbf519f9bab8988e8738))
  - hasAccount, isLoggedIn
  ([eaa63ec5](https://github.com/blockchain/My-Wallet-V3/commit/eaa63ec510d394d91ea8723e24aa53ae2cdd0db8))
  - fetch profile
  ([7e6157ac](https://github.com/blockchain/My-Wallet-V3/commit/7e6157ace080307a75d9542651935e8284c8842d))
  - deserialize trades
  ([8c1cf7f9](https://github.com/blockchain/My-Wallet-V3/commit/8c1cf7f99be7b1568484d348b60eee116d62a9f7))
- **coinifyapi:** tests and add fetch-mock
  ([4bebc1fb](https://github.com/blockchain/My-Wallet-V3/commit/4bebc1fb22cea6989d5dab95b181694b2bfb6bd1))
- **coinifytrade:** refresh() saves
  ([c19dd18e](https://github.com/blockchain/My-Wallet-V3/commit/c19dd18e60b5f9cd53279a798134737bc8bb2df6))


## Pull requests merged

- Merge pull request #278 from blockchain/coinify-api
  ([f50556a1](https://github.com/blockchain/My-Wallet-V3/commit/f50556a1252ede7f4e9cf9ace0f436965ae1672e))
- Merge pull request #277 from blockchain/declined
  ([5a380a85](https://github.com/blockchain/My-Wallet-V3/commit/5a380a85b6fcc58d356d51a108c229ef5fc29895))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>