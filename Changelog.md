__Blockchain Wallet V3__

_Recent changes_

#   (2016-01-15)



---

## Bug Fixes

- **Address:** avoid circular dependency
  ([508feb59](https://github.com/blockchain/My-Wallet-V3/commit/508feb59a471e37ed3d6937e1048d1ca35f478eb))
- **test:** mock Address in BlockchainWallet specs
  ([a7d2a19d](https://github.com/blockchain/My-Wallet-V3/commit/a7d2a19dd6fbc68fda96523c5a2701e7408acc2b))


## Refactor

- **WalletNetwork:** move methods out of MyWallet and add tests
- **promises:**
  - remove dependency on Q
  - remove dependency on RSVP


## Test

- **Promise:** make sure tests can fail & use jasmine-s6-promise-matchers
- **WalletNetwork:** move to top of Karma because of global variable issue


## Chore

- **Release:** 3.6.0



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>