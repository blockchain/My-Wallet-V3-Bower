__Blockchain Wallet V3__

#   (2016-09-09)



---

## Bug Fixes

- fix(metadata):do not create metadata entry on login. (#267)
  ([32789ad7](https://github.com/blockchain/My-Wallet-V3/commit/32789ad78e038252b71fdc29b3cf81fe4044b7dd))
- **coinify:** use Math.round instead of Math.trunc
  ([b100567b](https://github.com/blockchain/My-Wallet-V3/commit/b100567b660f8c4721ad3fbfc8e4ca0e04f4cbc3))
- **cream:** this._wallet.external doesn't exist with 2nd password (#269)
  ([657a6912](https://github.com/blockchain/My-Wallet-V3/commit/657a6912b45c19480bd0c781b555ad2ce52105d8))
- **external:** check if metadata entry has been created
  ([e989a6d3](https://github.com/blockchain/My-Wallet-V3/commit/e989a6d34cf71f1ae379eb184f8b754fb8d27cd2))
- **metadata:** make requests in sequence to prevent wrong checksum error (#273)
  ([4ff6a32a](https://github.com/blockchain/My-Wallet-V3/commit/4ff6a32af2e14892825428ffc478899a81a361ef))
- **quote:**
  - process anonymous quote, profile no longer needed
  ([b3d73048](https://github.com/blockchain/My-Wallet-V3/commit/b3d73048b9dc5a06f5e9852ef892dc26c1b2a98a))
  - remove unused feeForMedium and totalForMedium
  ([21718fcc](https://github.com/blockchain/My-Wallet-V3/commit/21718fcccc4ba4ebea381cdec800d074cb3a8ece))
- **trade:**
  - check hash instead of just address
  ([e9b35122](https://github.com/blockchain/My-Wallet-V3/commit/e9b35122c879314b5dd63d5d3fc049364f6cd95a))
  - more NaN issues
  ([6e38fbac](https://github.com/blockchain/My-Wallet-V3/commit/6e38fbacdd0fed5b002cd863ea9c23825f1365d9))
  - outAmount NaN
  ([6bee8ccb](https://github.com/blockchain/My-Wallet-V3/commit/6bee8ccbeea51c9504ef84b3e449689bb1e6220f))
  - use outAmount when applicable (#268)
  ([c473846d](https://github.com/blockchain/My-Wallet-V3/commit/c473846d341c0c044149a900fd04c2ef19b43cd7))
- **v1-wallets:** second password iterations are set correctly (#271)
  ([42bc4de2](https://github.com/blockchain/My-Wallet-V3/commit/42bc4de20378fbf38723d426e544ed95dfd8dd8c))


## Features

- **quote:** calculate fee for each payment method
  ([7bb0c318](https://github.com/blockchain/My-Wallet-V3/commit/7bb0c318f99e10e30df6c836efbb7cd9a889921a))
- **wallettransaction:** compute To and From (#260)
  ([32e0070e](https://github.com/blockchain/My-Wallet-V3/commit/32e0070ee6b0aa96e444cab5504512b90f71e377))


## Refactor

- **coinify:** Level and Limits objects
  ([7dcebabe](https://github.com/blockchain/My-Wallet-V3/commit/7dcebabe5616a804dd932ffed8a24887be02106c))
- **paymentmethod:** use cent and satoshi
  ([293eedb3](https://github.com/blockchain/My-Wallet-V3/commit/293eedb3a10769d264382359f56ece0fd58ba8d6))
- **quote:**
  - store base and quote amount as integers
  ([e365455d](https://github.com/blockchain/My-Wallet-V3/commit/e365455d3a41fa9cd5ee05888f0052be3e549ae0))
  - require integer cents or satoshi
  ([fee397ae](https://github.com/blockchain/My-Wallet-V3/commit/fee397aed04dba5f4162b632f56fad02ef5fa9bd))
- **trade:** use cent and satoshi
  ([99c59273](https://github.com/blockchain/My-Wallet-V3/commit/99c59273bd0c0b8345c1cad0a38b7767460796ed))


## Test

- **coinify:**
  - getBuyQuote()sets _lastQuote
  ([9572541f](https://github.com/blockchain/My-Wallet-V3/commit/9572541f4816de007e385c617b7446e2ba3e437d))
  - getBuyQuote()
  ([b30aac2d](https://github.com/blockchain/My-Wallet-V3/commit/b30aac2d23f1125036691fbeaa97d7160ddb03a5))
- **quote:** getQuote()
  ([f8f68aaa](https://github.com/blockchain/My-Wallet-V3/commit/f8f68aaa54aef80cfc576bacdaacde6fa8a3b1a2))


## Chore

- **release:**
  - v3.22.14
  ([c1aa7414](https://github.com/blockchain/My-Wallet-V3/commit/c1aa7414da2d8048dbd32fb5302e0e609efcb568))
  - update version to v3.22.12, this is not the actual release
  ([4534eea9](https://github.com/blockchain/My-Wallet-V3/commit/4534eea905706e795c19a1641bdc6c87d13fc5c6))


## Branchs merged

- Merge branch 'master' into precision
  ([ee044923](https://github.com/blockchain/My-Wallet-V3/commit/ee04492354c43e618eac52a6fc9af0b7fab2d6f7))
- Merge branch 'master' into precision
  ([b67e9ddf](https://github.com/blockchain/My-Wallet-V3/commit/b67e9ddf26aab4debfd82f50731ca8bd377444a1))


## Pull requests merged

- Merge pull request #265 from blockchain/precision
  ([856a3084](https://github.com/blockchain/My-Wallet-V3/commit/856a30840cd44dac65702b052fbc067c29e9b782))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>