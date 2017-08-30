__Blockchain Wallet V3__

#   (2017-08-30)



---

## Bug Fixes

- **eth:**
  - give default account priority, instead of returning sum of balances
  ([f75b4e5a](https://github.com/blockchain/My-Wallet-V3/commit/f75b4e5a30060423f578c78bcabfcc5214526841))
  - update for keyed api response format
  ([a50bc267](https://github.com/blockchain/My-Wallet-V3/commit/a50bc267b52c44a9561e26a46a88de04a425e77a))
  - return fee from maxAvailable and use default gas price in price quote
  ([1dcfc61d](https://github.com/blockchain/My-Wallet-V3/commit/1dcfc61dfe33e867d71dea27687d0927bfe26fb8))
  - use correct account message property
  ([e37373f8](https://github.com/blockchain/My-Wallet-V3/commit/e37373f8be717049d72cf958947884ab8b5647d8))
  - correctly return create account promise
  ([2933a593](https://github.com/blockchain/My-Wallet-V3/commit/2933a5933be1d2f6ddb9b34bde29cf834447e833))
  - handle differences in balance and txs responses
  ([f7ec1f17](https://github.com/blockchain/My-Wallet-V3/commit/f7ec1f17deb49391364a8dda3cf706e2c1eb11cc))
  - do not allow transition if already done
  ([7a68d201](https://github.com/blockchain/My-Wallet-V3/commit/7a68d2019ff9d930f62be4076228dae9fbbe8dff))


## Features

- **eth:**
  - function to transition back to legacy eth
  ([ba542295](https://github.com/blockchain/My-Wallet-V3/commit/ba5422959f9f8ecabd7148310a6ae75b79f61fe3))
  - auto transition without sec pass
  ([42654dde](https://github.com/blockchain/My-Wallet-V3/commit/42654dde062b9b3416b1881fb171c6308c844ce6))
  - batch fetch eth account data
  ([4cdf568f](https://github.com/blockchain/My-Wallet-V3/commit/4cdf568f3cca6eb09222ed999c8d152925c6f157))
  - fetch history for legacy account as well
  ([2e8ae313](https://github.com/blockchain/My-Wallet-V3/commit/2e8ae313ede2141cfa1209839ac9bffd3aa22a1b))
  - legacy transition
  ([04efc2e4](https://github.com/blockchain/My-Wallet-V3/commit/04efc2e4e1da11450dce015b47fccccaae48edae))
  - debounce sync by 250ms
  ([6c825bc0](https://github.com/blockchain/My-Wallet-V3/commit/6c825bc0b8f5e7e766cab4376b347f50bad0bc42))
  - basic transition from legacy account to bip44 derived account
  ([f8f4cdfc](https://github.com/blockchain/My-Wallet-V3/commit/f8f4cdfc095556990e26f014c5342987e622c9bf))
- **helpers:** have asyncOnce return a promise
  ([c5d6a8fe](https://github.com/blockchain/My-Wallet-V3/commit/c5d6a8feb85feb3c60ecbae7b62c7e75a23999fa))


## Test

- **eth:**
  - fix create account tests
  ([4ad82976](https://github.com/blockchain/My-Wallet-V3/commit/4ad82976b398fec7821c75602dbf8bae2726d4da))
  - support correct flag in tests
  ([c55dac4f](https://github.com/blockchain/My-Wallet-V3/commit/c55dac4f63fd65078ecc052ed99b984035483d28))


## Chore

- **release:** v3.35.0
  ([165c6196](https://github.com/blockchain/My-Wallet-V3/commit/165c61968b61f5c90386ab2636ae0d6808e45515))


## Pull requests merged

- Merge pull request #431 from blockchain/beta-upgrade
  ([483e3593](https://github.com/blockchain/My-Wallet-V3/commit/483e35932d9a0586df5167a74738b3ef2d274f0a))
- Merge pull request #432 from blockchain/return-fee
  ([1fe150a1](https://github.com/blockchain/My-Wallet-V3/commit/1fe150a1a08f10360c1160a4c5b1d5c719b9a47c))
- Merge pull request #418 from blockchain/v3.34-release
  ([4dfe4443](https://github.com/blockchain/My-Wallet-V3/commit/4dfe444358653c5200efdf71eb04e2b3af8e86ac))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>