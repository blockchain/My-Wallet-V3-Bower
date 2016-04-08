__Blockchain Wallet V3__

#   (2016-04-08)



---

## Bug Fixes

- **RNG:** don't hard-code URL
  ([86665fe8](https://github.com/blockchain/My-Wallet-V3/commit/86665fe8f62f735871616e1676ae09b64768cf87))
- **SignMessage:**
  - allow message signing with uncompressed addresses
  ([6be77fef](https://github.com/blockchain/My-Wallet-V3/commit/6be77fef8e78df2a4000c3eed98794f0c0b1e042))
  - encode message as base64
  ([9d2afde9](https://github.com/blockchain/My-Wallet-V3/commit/9d2afde9a85baa104d5088cc5178bc00f9afd95e))


## Features

- **SignMessage:** implement signMessage in Address class
  ([33ac7bbe](https://github.com/blockchain/My-Wallet-V3/commit/33ac7bbefb65be6ca6e06bac64ea6a4241f50b9f))


## Refactor

- **WalletStore:** remove logout timer logic


## Test

- **Address:** test that signMessage outputs base64 and tries uncomp format
- **RNG:** fix failing test in rng module



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>