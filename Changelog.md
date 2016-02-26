__Blockchain Wallet V3__

_Recent changes_

#   (2016-02-26)



---

## Bug Fixes

- **API:**
  - update-block-tor-ips insists on 1 or 0, not a boolean
  ([e5d5d6c2](https://github.com/blockchain/My-Wallet-V3/commit/e5d5d6c2488c0c31d58d9527851d9c97d8ca7b61))
  - API.securePost callbacks version.
  ([5b1d8f3b](https://github.com/blockchain/My-Wallet-V3/commit/5b1d8f3baa0b0da2b69effe31a07636090bc20a4))
  - Added missing dependency
  ([99e1aa2c](https://github.com/blockchain/My-Wallet-V3/commit/99e1aa2cccb0b173c6bef43d30c230169d277612))
- **HDAccount:** assertions now use Helpers functions instead of custom conditions
  ([c20785f6](https://github.com/blockchain/My-Wallet-V3/commit/c20785f68475924aef5a50f99d9e7c2e533a8f9d))
- **HDWallet:**
  - stronger check on seedHex during mnemonic decryption
  ([23fcbe31](https://github.com/blockchain/My-Wallet-V3/commit/23fcbe31ef98254d2221f57f47ef1d1ae3573d2c))
  - removed useless ternary expression
  ([9d2652ef](https://github.com/blockchain/My-Wallet-V3/commit/9d2652efd6c4745cb8ada32f1ee77e651a497f33))
  - stronger seed hex verification on restore
  ([0fec144d](https://github.com/blockchain/My-Wallet-V3/commit/0fec144da6ac4c98d8d84ce014c78fc4394ca31c))
- **Helpers:**
  - Made use of isInstanceOf
  ([e4fe33fd](https://github.com/blockchain/My-Wallet-V3/commit/e4fe33fd61274fdd1bf968dfe9cb49c592eb9499))
  - replace endsWith with slice for browser compatibility
  ([9fd1a87f](https://github.com/blockchain/My-Wallet-V3/commit/9fd1a87f451eea3bc5c7855b0607954dbfffcafe))
- **MyWallet:**
  - don't use ES6 yet
  ([3ca63345](https://github.com/blockchain/My-Wallet-V3/commit/3ca633453033856ee517757abe9d88a74031c1a4))
  - Fixed unreachable console.log
  ([b08cb5bc](https://github.com/blockchain/My-Wallet-V3/commit/b08cb5bc0ffbda77ed7fad097fb251464cd193d0))
- **Payment:**
  - only allow setting feePerKb to a positive integer
  ([e2d5ee3a](https://github.com/blockchain/My-Wallet-V3/commit/e2d5ee3abdde4e8aa774d8b02db668f7602088ed))
  - removed unused parameter `amount` for sweep
  ([ec818486](https://github.com/blockchain/My-Wallet-V3/commit/ec8184869479b13b39231fb8827435a1fdae1111))
- **Signup:** save guessed language and currency
  ([2e11d00f](https://github.com/blockchain/My-Wallet-V3/commit/2e11d00fc0d57cce4c64dbb6fede0f058ea21f4b))
- **Transactions:** only call multiaddr with active addresses and xpubs
  ([d5862dff](https://github.com/blockchain/My-Wallet-V3/commit/d5862dff537c78ff4e2110ec9ce3665526cb8335))
- **Tx:**
  - coinbase transactions pay no fees
  ([af4c2801](https://github.com/blockchain/My-Wallet-V3/commit/af4c2801b8fc37f5252224f69fd54a1a14a09c4b))
  - Simplified conditional expression
  ([cbbac978](https://github.com/blockchain/My-Wallet-V3/commit/cbbac97833fd682c54ff45caab508876ce3fd43b))
- **Wallet:**
  - base58 key detection now uses existing Helpers function
  ([573f241e](https://github.com/blockchain/My-Wallet-V3/commit/573f241eeaf71e0f249b45c11498b2b252fea690))
  - updated getBaseFee description
  ([5cb1cd68](https://github.com/blockchain/My-Wallet-V3/commit/5cb1cd6832b47da185722dee9437efe30b04c46d))
  - updated generateNewKey description
  ([17e3a1d7](https://github.com/blockchain/My-Wallet-V3/commit/17e3a1d780bc8c911e05e8a99e2e00720221561a))
- **WalletCrypto:** undefined variable in an error message
  ([9cde95aa](https://github.com/blockchain/My-Wallet-V3/commit/9cde95aacffde7affa3782b379b051804e605ae7))
- **WalletNetWork:** Fixed Promise workflow + 1 forgotten require
  ([7bbc1d75](https://github.com/blockchain/My-Wallet-V3/commit/7bbc1d750cfb75e7011d9c84ed311b9ba1773c2d))
- **WalletNetwork:** removed check on decryptWalletProgress
  ([b01bdc09](https://github.com/blockchain/My-Wallet-V3/commit/b01bdc097cbe6e796e250cce73e0f2d16026be8b))
- **blockchain-settings-api:**
  - More exported function for test
  ([f8072a6e](https://github.com/blockchain/My-Wallet-V3/commit/f8072a6eb7bb5bf05227d8879ce84987cf93544b))
  - Fixed copy paste error
  ([84a40838](https://github.com/blockchain/My-Wallet-V3/commit/84a408384b1ec3e60273a4b62bc4b7655c1b5193))
  - Added sendEvent call to verifyEmail
  ([95dee9d6](https://github.com/blockchain/My-Wallet-V3/commit/95dee9d672c8a7439b7ccf7c85206d01d2cfa086))
  - Fixed calls to apiSecurePostCallbacks
  ([5c8ac031](https://github.com/blockchain/My-Wallet-V3/commit/5c8ac031a0ae1eaac04bb2de13b1824c193b4919))
  - Uniformized boolean conversion for settings update
  ([29080796](https://github.com/blockchain/My-Wallet-V3/commit/29080796074e998b06ee71b2c640eedb7d29c8fb))
  - Simplified error handling
  ([24e244e1](https://github.com/blockchain/My-Wallet-V3/commit/24e244e18094a6ef44e08898f0a1fd968caa9e90))
  - Refactored password hint checking
  ([c0192a04](https://github.com/blockchain/My-Wallet-V3/commit/c0192a04c61eecc2c4f7ac25c6988abe8c5bfc76))
  - Better callback checking
  ([d5f9a612](https://github.com/blockchain/My-Wallet-V3/commit/d5f9a612bec547d7263b00208e357b6025b62260))
  - Removed unused parameter txt from updateKV
  ([c18d8ee3](https://github.com/blockchain/My-Wallet-V3/commit/c18d8ee388b2574a8222bd4f5fef1c1e698c188c))
- **fee:** fee is reset when setting new origin or amount.
  ([4594f71c](https://github.com/blockchain/My-Wallet-V3/commit/4594f71c0ee39364b3a0b6345f7cec8fddbb2111))
- **key:** only 40-44 chars len base58 keys can be used.
  ([be3fe06a](https://github.com/blockchain/My-Wallet-V3/commit/be3fe06a120b2ac62720ec768116644f4a695455))
- **keys:** keys shorter than 32 bytes are now usable
  ([22eac2db](https://github.com/blockchain/My-Wallet-V3/commit/22eac2db143f747395e50904a8276345d6a12558))
- **timeout:** AJAX_TIMEOUT is back.
  ([24de0dab](https://github.com/blockchain/My-Wallet-V3/commit/24de0dab22daea4ce02f3fa2ccd4bf1e616dec1d))


## Features

- **2FA:** convert code to upper case
  ([e462ead7](https://github.com/blockchain/My-Wallet-V3/commit/e462ead75fa953db4050e3140f25f3078ee563d5))
- **API:** remove unused update_API_access
  ([1549a0c1](https://github.com/blockchain/My-Wallet-V3/commit/1549a0c16e5bf5e8a708e0febbb4a23f3a55824b))
- **FeePerKB:** set fee per kb through payment class
  ([af98d816](https://github.com/blockchain/My-Wallet-V3/commit/af98d816190cbe9dd0bd83f6cb37f3c3b29f5053))
- **Helpers:** Uniformized number range checking across the codebase with new helpers: isPositiveNumber and isPositiveInteger
  ([66856025](https://github.com/blockchain/My-Wallet-V3/commit/66856025822b02247e8a54385620012e661655d6))
- **WalletTransaction:** add watch-only flags for iOS
  ([350af2b5](https://github.com/blockchain/My-Wallet-V3/commit/350af2b55aba62bf7fb0633c1ddef42c74bc2861))
- **blockchain-settings-api:** Exported some functions for tests
  ([fb11ab64](https://github.com/blockchain/My-Wallet-V3/commit/fb11ab640c3070e251dbfc74882626a31febe749))
- **tx list:** coinbase tx are shown properly.
  ([43c6b351](https://github.com/blockchain/My-Wallet-V3/commit/43c6b3510eee10ae6b529be2601149e0d99a5dad))


## Refactor

- **WalletSignup:** Moved some functionality to WalletNetwork, use of promise
- **getBalanceForRedeemCode:** moved to API
- **helpers:** some functions moved from MyWallet to Helpers.
- **latest block:** Latest block moved from walletstore.


## Test

- **Address:**
  - fixed wrong testing of promises
  - Added more tests to Address
- **HDAccount:** 100% coverage (lines, functions and branches) for HDAccount
- **HDWallet:** full coverage for HDWallet
- **Helpers:**
  - More tests for Helpers
  - isPositiveInteger and isPositiveNumber
- **KeyChain:** 100% coverage for KeyChain
- **KeyRing:** 100% coverage for KeyRing
- **Payment:** add test spec for payment.js
- **RNG:** all branches are covered in RNG
- **SettingsAPI:** fixed broken tests
- **Transaction:**
  - More tests for Transaction
  - add coinbase test and move test vectors to file
- **TransactionList:**
  - full coverage for TransactionList
  - two more small tests for TxList
- **Tx:** Near full coverage for wallet_transaction
- **WalletCrypto:**
  - 100% line coverage for WalletCrypto
  - test cipherFunction behaviour with invalid parameters
- **WalletNetwork:** All lines covered for WalletNetwork
- **WalletSignup:** full coverage for WalletSignup
- **blockchain-settings-api:** Full coverage for blockchain-settings-api
- **blockchain-wallet:**
  - More tests for encryption, decryption and getPrivateKeyForAddress
  - added watch-omly and archived keys to the test wallet


## Chore

- **Release:** 3.10.0
- **Whitelist:** bump patch version of sha.js



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>