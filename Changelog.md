__Blockchain Wallet V3__

#   (2016-09-29)



---

## Bug Fixes

- **api:** request frombtc with uppercase currency code
  ([b6e8a7f0](https://github.com/blockchain/My-Wallet-V3/commit/b6e8a7f087108530485aa363f19e0edca9c7b0c5))
- **logout:** revert accidental change in ec9928fc
  ([04dfd78b](https://github.com/blockchain/My-Wallet-V3/commit/04dfd78b6e75dddf0634b0b6e33d6e6dd60b189f))
- **quote:**
  - constructror assert obj is present
  ([2a80db0b](https://github.com/blockchain/My-Wallet-V3/commit/2a80db0bbc92f38f88984df4b51aa1f84f6f728b))
  - pass outCurrency to getQuote
  ([33203565](https://github.com/blockchain/My-Wallet-V3/commit/332035653cf2667bc9333bba1a2cf15f1f71b4e1))
- **tx:** correctly mark change outputs for legacy address txs
  ([773ea521](https://github.com/blockchain/My-Wallet-V3/commit/773ea5217507f592eaafb0e73e165c29a76f2817))


## Refactor

- **coinifytrade:** apply filter in monitorPayments() instead of passing it on
  ([91980185](https://github.com/blockchain/My-Wallet-V3/commit/9198018577227da499fbcbf2d5cc798e232ecbf1))


## Test

- **coinifytrade:** monitorAddress()
  ([033349db](https://github.com/blockchain/My-Wallet-V3/commit/033349db42bbfda9c520c9faea5349fa3b792245))


## Chore

- **release:** v3.22.20
  ([3249fc33](https://github.com/blockchain/My-Wallet-V3/commit/3249fc3366ffd8b766cb7f200fc7633fc99b37ec))


## Pull requests merged

- Merge pull request #287 from blockchain/quote-curr
  ([df409f32](https://github.com/blockchain/My-Wallet-V3/commit/df409f32c057befdc4e9e26efdc43871e2422836))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>