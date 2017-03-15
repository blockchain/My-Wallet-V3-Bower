__Blockchain Wallet V3__

#   (2017-03-15)



---

## Bug Fixes

- **api:** Linters are overrated?
  ([f61d8ae8](https://github.com/blockchain/My-Wallet-V3/commit/f61d8ae8ea189d7ab44311cb76ef9fb53938c13b))
- **crypto:** do not convert salt to binary string before pbkdf2, fixes nodejs issue
  ([ddea287d](https://github.com/blockchain/My-Wallet-V3/commit/ddea287deaf241807f52631f7ea04b37e5e92ea0))
- **hdaccount:** receiveIndex falls back to labels backup
  ([2a69a1c7](https://github.com/blockchain/My-Wallet-V3/commit/2a69a1c780dabdc8b55e357613c1785285edf29e))
- **labels:**
  - setLabel() checks address argument type
  ([d15907c0](https://github.com/blockchain/My-Wallet-V3/commit/d15907c06145dde543a749688542343192996de6))
  - also check for undefined in toJSON
  ([328ca08a](https://github.com/blockchain/My-Wallet-V3/commit/328ca08a46603613c3167df3899826e6108197a7))
  - don't delete from wallet payload until safe to KV is confirmed
  ([e5d69a22](https://github.com/blockchain/My-Wallet-V3/commit/e5d69a22c1a1bdac6863b65acfd856266e88db4c))
- **login:** make exchange json optional
  ([67cfbe15](https://github.com/blockchain/My-Wallet-V3/commit/67cfbe15f1374e01a2b20cd5423198506d80c1dc))
- **metadata:** use correct derivation after 2nd password entry
  ([a315b6dd](https://github.com/blockchain/My-Wallet-V3/commit/a315b6dd1e601b2c0fad941523e748250a0e5596))


## Features

- **address:** migrate to KV store, version management
  ([1d53288c](https://github.com/blockchain/My-Wallet-V3/commit/1d53288ce8fc9efd5b955cf3c2ad96587ae7b7de))
- **blockchainwallet:** remove getNotePlaceholder()
  ([41baa380](https://github.com/blockchain/My-Wallet-V3/commit/41baa380a4011a77c90a631dead2fec5906d4209))
- **labels:** use version from object
  ([def9b748](https://github.com/blockchain/My-Wallet-V3/commit/def9b74842fe48c5c9d0fab7e109779a1204fa69))
- **metadata:**
  - use isMetadataReady instead of isdoubleencrypted
  ([52989974](https://github.com/blockchain/My-Wallet-V3/commit/52989974ec05ada612300474988585b85234c709))
  - load from payload
  ([66b2cfde](https://github.com/blockchain/My-Wallet-V3/commit/66b2cfded795fcf0eeb7cec0ba997c1cf8411792))
- **transaction:** add account and receive index
  ([b580c461](https://github.com/blockchain/My-Wallet-V3/commit/b580c461df3f13edf15f0eef17047aa4720722cc))
- **wallet:** move address labels to metadata service
  ([e4b39cfa](https://github.com/blockchain/My-Wallet-V3/commit/e4b39cfa216eb54f0ade928396b6f1b9b94bc3b5))


## Refactor

- **account:** get last labeled address from wallet.labels
  ([a7579005](https://github.com/blockchain/My-Wallet-V3/commit/a75790059034861bcaa51ebadd421d2aadd6b8fe))
- **addresses:** make this._accounts serializable, add and remove label
  ([c3690a6f](https://github.com/blockchain/My-Wallet-V3/commit/c3690a6f4653ddf88490c2fa9b127d3122e42c20))
- **addresshd:** new class, fetch balance
  ([dd0cccfe](https://github.com/blockchain/My-Wallet-V3/commit/dd0cccfe5c5afb1a00dc0330d4bbde6dc8cb451d))
- **exchangedelegate:** use Label methods
  ([7d5edf97](https://github.com/blockchain/My-Wallet-V3/commit/7d5edf97f1d178d72d594b3613b681a30b43b262))
- **labels:** addLabel requires maxGap argument
  ([b0266174](https://github.com/blockchain/My-Wallet-V3/commit/b0266174b16917ef9a72f8f0b83c95883516b4a5))


## Test

- **addresshd:** 100% coverage
  ([f31fe3bc](https://github.com/blockchain/My-Wallet-V3/commit/f31fe3bcd2834d800f777efa817efcf5be12f736))
- **blockchainwallet:** repair and add more
  ([b19beb05](https://github.com/blockchain/My-Wallet-V3/commit/b19beb056f27200d57ddbcb7e086b430c5431c62))
- **exchangedelegate:** disable tests, will fix before merge
  ([6f9055b9](https://github.com/blockchain/My-Wallet-V3/commit/6f9055b9ec1c17d4f97d971930d48600cb6c3acb))
- **external:**
  - remove blank line
  ([50828ad5](https://github.com/blockchain/My-Wallet-V3/commit/50828ad5836260a01626d878188b47eed3b3d407))
  - repair and add more
  ([45ac7bdf](https://github.com/blockchain/My-Wallet-V3/commit/45ac7bdfa7c230758344131d18b77b64bc21b7e5))
- **hdaccount:** repair and add more
  ([3a3bccdc](https://github.com/blockchain/My-Wallet-V3/commit/3a3bccdc537cd8ae15d44bce1432e2081ae75817))
- **labels:** renamed spec file, added/repaired 9 tests
  ([2aa773af](https://github.com/blockchain/My-Wallet-V3/commit/2aa773afe434ecef0bf6907191f3c1f9e2d8ddb2))
- **wallet:** use loadMetadata in mock
  ([67b54233](https://github.com/blockchain/My-Wallet-V3/commit/67b542333bac28384d3e18880c29ad2efc8020c2))


## Chore

- **release:** v3.29.0 - address-labels branch
  ([053aacc3](https://github.com/blockchain/My-Wallet-V3/commit/053aacc3af4949eb25bf386e22313c76daad695e))


## Branchs merged

- Merge branch 'master' into address-labels
  ([81aec2be](https://github.com/blockchain/My-Wallet-V3/commit/81aec2beff8006a49f2dc64d3dbfc17ddaa79f85))


## Pull requests merged

- Merge pull request #339 from blockchain/pbkdf2-fix
  ([93b47ad9](https://github.com/blockchain/My-Wallet-V3/commit/93b47ad99b4994e87e91c7117d2a6042ee1e3b9e))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>