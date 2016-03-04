__Blockchain Wallet V3__

_Recent changes_

#   (2016-03-04)



---

## Bug Fixes

- **2FA:** do not upcase Yubikey. Allow 2FA type to be specified.
  ([49926010](https://github.com/blockchain/My-Wallet-V3/commit/499260109972e1652551b91ffed5466d1d8cb7ed))
- **Address:** corrected bug in Address.factory
  ([81f87cb5](https://github.com/blockchain/My-Wallet-V3/commit/81f87cb56acdb4a7796cf20096f9b49ad7ab994f))
- **Payment:** pass error message after failed publish
  ([cc0304f9](https://github.com/blockchain/My-Wallet-V3/commit/cc0304f9e02e9e9b982b322620e35700b3c873ca))
- **WalletNetwork:** Added check on payload checksum for checkWalletChecksum
  ([8e4fd885](https://github.com/blockchain/My-Wallet-V3/commit/8e4fd88589c36091cba51c75ae9ffc90405f8a38))
- **payment:** update sweep fee and amount when fee-per-kb changes
  ([0201f91c](https://github.com/blockchain/My-Wallet-V3/commit/0201f91c063d26fee49d995bda5fafa20bfba972))
- **watchOnly:** remove cyclic dependency and return decrypted private key
  ([ef898213](https://github.com/blockchain/My-Wallet-V3/commit/ef898213cd54e6508197def1c2cbac6ca5ce9827))
- **webSocket:** ws msgs contructed correctly.
  ([d4ff4664](https://github.com/blockchain/My-Wallet-V3/commit/d4ff466495d325f38dbed4012e76d77a732554e6))
- **websocket:**
  - send valid json when subscribing to imported address
  ([e667f8ce](https://github.com/blockchain/My-Wallet-V3/commit/e667f8cea8c0c8cea3af7ef046a130e05dbd730e))
  - ws ping message.
  ([fa29d69b](https://github.com/blockchain/My-Wallet-V3/commit/fa29d69b4458cf1b13b416e11344ef29dbc9b15b))


## Features

- **Payment:** spend from watch only if available
  ([a14e96e6](https://github.com/blockchain/My-Wallet-V3/commit/a14e96e6880dbdc29dd850c93fa7c96989a8983f))
- **watchOnly:** check private keys address correspondence
  ([4cfcf364](https://github.com/blockchain/My-Wallet-V3/commit/4cfcf364316f956fde1da65a31743fad326e5521))


## Test

- **Address:** full test coverage for Address
- **BlockchainSocket:** msgWalletSub, msgBlockSub, msgAddrSub, msgXPUBSub, msgPing and msgOnOpen
- **Payment:**
  - fix broken tests
  - Add tests for Payment
- **WalletNetwork:** Added tests for checkWalletChecksum



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>