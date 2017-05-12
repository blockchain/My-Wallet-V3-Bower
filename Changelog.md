__Blockchain Wallet V3__

#   (2017-05-12)



---

## Bug Fixes

- **build:** es5 compatible Object.assign
  ([da3ad6ae](https://github.com/blockchain/My-Wallet-V3/commit/da3ad6ae4e1385c8e90bdd2f6b2374fc9c7210e6))
- **buy:**
  - save external after checking trades
  ([3f86fbe9](https://github.com/blockchain/My-Wallet-V3/commit/3f86fbe98017924d7b1bc1534ae1b5d8257a43c1))
  - only watch trades that have not received bitcoin yet
  ([47877e59](https://github.com/blockchain/My-Wallet-V3/commit/47877e59347171efc25eef704be786c486c63688))
- **misc:** polyfill for environments without symbol
  ([994b9de6](https://github.com/blockchain/My-Wallet-V3/commit/994b9de676376903045710e8c2fd3f3bc91c4134))
- **package:** lock fetch version to 2.0.3
  ([d89f8fad](https://github.com/blockchain/My-Wallet-V3/commit/d89f8fad382f473ee31b3ad719fd79c14d4db825))
- **sync:** reload external metadata after a sync
  ([58a222e6](https://github.com/blockchain/My-Wallet-V3/commit/58a222e65c82e42fd3c7daa4fb86e3c50777f6c2))


## Features

- **account:** add can buy method to account info
  ([76a7c432](https://github.com/blockchain/My-Wallet-V3/commit/76a7c432de118074718f5668634f619ab801f522))
- **dev:** use yarn
  ([d174e392](https://github.com/blockchain/My-Wallet-V3/commit/d174e3928733efa8dbae60a4335b0eebeb83e813))
- **metadata:**
  - handle metadata hd node on payload
  ([e2f4e5ba](https://github.com/blockchain/My-Wallet-V3/commit/e2f4e5ba50a5b3f538957c1264aa5902640acd2b))
  - expose function for deriving metadata node
  ([ebd75341](https://github.com/blockchain/My-Wallet-V3/commit/ebd7534135cb2eaf3724ab41296439a1f81afb23))


## Chore

- **make:** ignore engine restrictions when installing with yarn
  ([275d54ce](https://github.com/blockchain/My-Wallet-V3/commit/275d54ced6978ad7a7c60d077cb85feee0c561fc))
- **release:** v3.31.2
  ([ae453d6c](https://github.com/blockchain/My-Wallet-V3/commit/ae453d6c19135062ebea6293326cfe96eedcaf58))
- **standard:** fix code style error in gruntfile
  ([2c1a4242](https://github.com/blockchain/My-Wallet-V3/commit/2c1a424253706d2a00274283114b02d91a66a1ad))


## Branchs merged

- Merge branch 'ios' into v3.31-release
  ([6ef0679a](https://github.com/blockchain/My-Wallet-V3/commit/6ef0679a40f1d893d4229fe4b9e37b472dfeea61))


## Pull requests merged

- Merge pull request #381 from blockchain/check-completed
  ([9a188b4f](https://github.com/blockchain/My-Wallet-V3/commit/9a188b4fdd7f15ba5d7c51700c9640a18587e646))
- Merge pull request #361 from blockchain/reload-external
  ([c43155aa](https://github.com/blockchain/My-Wallet-V3/commit/c43155aa71cd1375f8f0f8e2b54de3b76ed8c93c))
- Merge pull request #355 from blockchain/symbol-polyfill
  ([d5f57cb5](https://github.com/blockchain/My-Wallet-V3/commit/d5f57cb516e2550a21436014c462b8bfb73ed719))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>