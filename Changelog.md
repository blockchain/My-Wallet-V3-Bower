__Blockchain Wallet V3__

#   (2017-09-13)



---

## Bug Fixes

- **socket:** only send messages on initial open
  ([4183c9b4](https://github.com/blockchain/My-Wallet-V3/commit/4183c9b42aff08d3b1d25a7b9f06d2e4ae59b204))


## Features

- **api:**
  - change endpoint name and params
  ([9e66b86e](https://github.com/blockchain/My-Wallet-V3/commit/9e66b86ece5ce9cd9eea8be9be923df452d340b1))
  - add method for price chart
  ([628d53fb](https://github.com/blockchain/My-Wallet-V3/commit/628d53fb2586d725176fe5f68f36493070cb7db4))


## Refactor

- **eth:** remove unnecessary check that latest block is the most recent
  ([606db650](https://github.com/blockchain/My-Wallet-V3/commit/606db650054ad30f8730b5d69a310b3638c9b06b))
- **socket:**
  - allow passing custom socket class to sockets
  ([d7ce9103](https://github.com/blockchain/My-Wallet-V3/commit/d7ce91034d6cca29d8b2963c348e211bdfb93de4))
  - add handlers before socket connect
  ([91f26b37](https://github.com/blockchain/My-Wallet-V3/commit/91f26b37d13e6813a3692aeba43a819dc0885477))
  - make sure socket lifecycle checks return a boolean
  ([c96ddc82](https://github.com/blockchain/My-Wallet-V3/commit/c96ddc82445daa0c3039132c55f402f765945f02))
  - use static methods, do not call .send externally
  ([4effd756](https://github.com/blockchain/My-Wallet-V3/commit/4effd756f661ed4d2319b8d3a41c536b002fbc63))
  - move pong handler into stable-socket
  ([f330fe72](https://github.com/blockchain/My-Wallet-V3/commit/f330fe722104cfb2b6b6d1d917628b50fb4637ac))
  - remove proxyquire in blockchain-socket spec
  ([3ad5f1ca](https://github.com/blockchain/My-Wallet-V3/commit/3ad5f1ca5fb0c6551bcfab6785a826acfe155844))
  - make base socket instance of EventListener
  ([3310765e](https://github.com/blockchain/My-Wallet-V3/commit/3310765e28b4794e78529bd0e8cbfe6258b07134))
  - share code between blockchain and eth sockets
  ([151c3024](https://github.com/blockchain/My-Wallet-V3/commit/151c3024c41c9ed2f01f6684066d431fe348d288))
- **test:**
  - rename spec files to match src counterparts
  ([6c460f74](https://github.com/blockchain/My-Wallet-V3/commit/6c460f74799c1162315bf83b0227896dede15cb7))
  - change tests to kebab-case to match src
  ([e3a8fc56](https://github.com/blockchain/My-Wallet-V3/commit/e3a8fc560a082a1de77352bee859c6f23866aa24))
  - _prepare -> __prepare
  ([c2543bfe](https://github.com/blockchain/My-Wallet-V3/commit/c2543bfeeb3e8240abf5b16694404d4a8d1fcdf2))
  - move data into __data__ dir
  ([c81dd047](https://github.com/blockchain/My-Wallet-V3/commit/c81dd0472dc15dbf53d99eebf0d5d03502a3df72))
  - remove unused spender mock
  ([be7c2716](https://github.com/blockchain/My-Wallet-V3/commit/be7c2716fd1cef2f998bacb40b78de43f03883d8))
  - move mocks into __mocks__ directory
  ([6c3d411e](https://github.com/blockchain/My-Wallet-V3/commit/6c3d411e185cefe9ad67e4a8bfab1c6fca0ab149))
  - standardize test extensions
  ([9850d7f9](https://github.com/blockchain/My-Wallet-V3/commit/9850d7f9febf7fa6a568dbaf9be4df25f707a227))


## Test

- **socket:**
  - move ws mock into common mock file
  ([775c3e8f](https://github.com/blockchain/My-Wallet-V3/commit/775c3e8f927179458075169f14c41baec7497ce9))
  - test spec for StableSocket
  ([bf9a2b08](https://github.com/blockchain/My-Wallet-V3/commit/bf9a2b0897fa1ff17e0da708510b1410c7938569))


## Chore

- **release:** bump version
  ([6845960b](https://github.com/blockchain/My-Wallet-V3/commit/6845960bb066b82c6a37c47a1969b4ef1335ccb1))
- **test:** add option to run in headless chrome, faster than phantomjs
  ([3046351d](https://github.com/blockchain/My-Wallet-V3/commit/3046351d275f1a0759db719ee0f27f09eba7482c))


## Branchs merged

- Merge branch 'v3.36-release' into improve-socket
  ([da9203ac](https://github.com/blockchain/My-Wallet-V3/commit/da9203ac6a086ba614545caf69ad9e4038521885))
- Merge branch 'v3.36-release' into chart
  ([21d8a522](https://github.com/blockchain/My-Wallet-V3/commit/21d8a522a8d7edd52dbb6e355366b13a5b003abc))


## Pull requests merged

- Merge pull request #439 from blockchain/refactor-tests
  ([edbb9e0e](https://github.com/blockchain/My-Wallet-V3/commit/edbb9e0ecfc47143defb8ac2f72077f71e42c416))
- Merge pull request #420 from blockchain/improve-socket
  ([1d5da2b3](https://github.com/blockchain/My-Wallet-V3/commit/1d5da2b34f95a8dc7ef1e2548d5de8fdb811fe96))
- Merge pull request #438 from blockchain/chart
  ([0adb74bb](https://github.com/blockchain/My-Wallet-V3/commit/0adb74bbc2bd8c11222d1a049e290eb821255bbc))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>