__Blockchain Wallet V3__

#   (2017-04-05)



---

## Bug Fixes

- test and safer function
  ([df589d58](https://github.com/blockchain/My-Wallet-V3/commit/df589d58546f1de499305dd9f93755dca5584fe9))
- max available amount
  ([494a661a](https://github.com/blockchain/My-Wallet-V3/commit/494a661a0be77e5d92ed7ffc738676a1d0ca484a))
- **api:** remove mock for charge_address request on testnet
  ([20f165ee](https://github.com/blockchain/My-Wallet-V3/commit/20f165eeafe337915da9e50c0ce3ee38537044a6))
- **external:**
  - init external metadata from correct hd node (#354)
  ([20ec8f42](https://github.com/blockchain/My-Wallet-V3/commit/20ec8f42209f70598f1df0757c65ae0bf152547a))
  - remove broken function call from wipe
  ([5f427cef](https://github.com/blockchain/My-Wallet-V3/commit/5f427cef925b06d94efe3b023b1fb826e8c64c7f))
- **hdaccount:**
  - use correct sort function
  ([d1223827](https://github.com/blockchain/My-Wallet-V3/commit/d1223827da868f6f1fe13c5683fc779fe8490bba))
  - set address_labels to empty array by default
  ([79b31c40](https://github.com/blockchain/My-Wallet-V3/commit/79b31c40e9c46e2513627d265bcd375b48ee1eb4))
- **helpers:**
  - semicolon
  ([0818a26c](https://github.com/blockchain/My-Wallet-V3/commit/0818a26ca340bfaacb7e2f7fc4d21258a2c0af3c))
  - hash guid to create group instead of relying on first char
  ([eaf79a77](https://github.com/blockchain/My-Wallet-V3/commit/eaf79a77b3c7cb7aff90ca7716e957c143b58cf9))
- **labels:**
  - fix length of .all
  ([e3901864](https://github.com/blockchain/My-Wallet-V3/commit/e39018641f37e95959568ab0daef2b28598f4e1d))
  - use correct Promise wrapper
  ([17ac0dc3](https://github.com/blockchain/My-Wallet-V3/commit/17ac0dc3a7df8ecc217fdab94d16229b2760bdbf))
- **metadata:** check for number before type id defaults to -1 (#352)
  ([f5ba7128](https://github.com/blockchain/My-Wallet-V3/commit/f5ba7128b39d4f9a9815408d82b14621dc6c279c))
- **payment:**
  - prevent state issues caused by mutability
  ([ea803054](https://github.com/blockchain/My-Wallet-V3/commit/ea80305437f1ef92da9641771877a94add2ce2f8))
  - correctly access last elem of amounts
  ([21ebe788](https://github.com/blockchain/My-Wallet-V3/commit/21ebe78845d3049b9d31ca8ed5a2aeefe974d872))
- **sell:** fixes (#362)
  ([31b4e995](https://github.com/blockchain/My-Wallet-V3/commit/31b4e9950afcfd103ad94dc2ddd934b1d66090e8))
- **wallet:** fix login from json functionality
  ([3c955e60](https://github.com/blockchain/My-Wallet-V3/commit/3c955e605fe8ac2ca76c728f35ab30e51cf6169a))


## Dependencies

- **coinify:** 0.4.1 for sell
  ([081fe081](https://github.com/blockchain/My-Wallet-V3/commit/081fe08103df4d3dfd651ee9739226f9ff884a1c))


## Features

- feat(fee experiment)
  ([840a344f](https://github.com/blockchain/My-Wallet-V3/commit/840a344fe77f63dc0842cb124d07f56354596d4e))
- **api:** flag to record advanced send in pushTxStats
  ([878d8a56](https://github.com/blockchain/My-Wallet-V3/commit/878d8a564efe0409ff00a2cd97fec3f4b9a98c86))
- **experiment:** groups a and b
  ([c47a4e3e](https://github.com/blockchain/My-Wallet-V3/commit/c47a4e3ed20c06357ad0b1a0b731fd1cf77f9362))
- **hdaccount:** sort _address_labels by index
  ([7d5c6b61](https://github.com/blockchain/My-Wallet-V3/commit/7d5c6b610f4ba116dacac2a93591e31455bb2e1d))


## Refactor

- **helpers:** less convoluted way of reading first bit
  ([5721c39a](https://github.com/blockchain/My-Wallet-V3/commit/5721c39a9420f47aad753fbd4f4542761c6a6625))
- **labels:**
  - duplicate without JSON
  ([2575b9a2](https://github.com/blockchain/My-Wallet-V3/commit/2575b9a2c14bd4da413ba06eeb660f49a67f3e15))
  - move some stuff back to HDAccount
  ([2c973a11](https://github.com/blockchain/My-Wallet-V3/commit/2c973a115f6f8a3554fb0c438f99ea930d0bf465))
  - _syncWallet is private
  ([ba86034d](https://github.com/blockchain/My-Wallet-V3/commit/ba86034d340e40e0dcb0c5b1bfba724ca43fafb8))
  - do not use KV store
  ([c99bedbc](https://github.com/blockchain/My-Wallet-V3/commit/c99bedbc58c5e90d50a93dbe5ac8d57aabd3b884))


## Chore

- **helpers:** clean helpers file
  ([c8211120](https://github.com/blockchain/My-Wallet-V3/commit/c8211120eb695c0f375449e77e4198da7ac27c08))
- **release:**
  - v3.30.9
  ([47b85d52](https://github.com/blockchain/My-Wallet-V3/commit/47b85d52c4b9d24c371e48bddbfa0e3ea58033af))
  - increase coinify client version
  ([d3cf11c7](https://github.com/blockchain/My-Wallet-V3/commit/d3cf11c76f5367c383986a19b9da2cd71162b051))
  - increase coinify client version
  ([45aa14ca](https://github.com/blockchain/My-Wallet-V3/commit/45aa14cacc8045fd4df3350a1f95d2471c7eb6a3))
  - correct package version
  ([c691cf03](https://github.com/blockchain/My-Wallet-V3/commit/c691cf035bca74b3c8d1254f265c342a2193453a))
  - increase coinify client version
  ([2e4ecc7f](https://github.com/blockchain/My-Wallet-V3/commit/2e4ecc7f04d404996d6c60c8cbfc0a2cd2c82933))
  - latest coinify client version
  ([05ce07f6](https://github.com/blockchain/My-Wallet-V3/commit/05ce07f671c2939d9ae0874248ae566e27358374))
  - bump version, coinify client dev version
  ([a1b70c6f](https://github.com/blockchain/My-Wallet-V3/commit/a1b70c6fd05462cb0fa55d699eba9fe294e20323))
  - v3.30.1
  ([75e0f1fe](https://github.com/blockchain/My-Wallet-V3/commit/75e0f1fe8bc54ec3e0d3b6a54eb9b6657669d1b3))
  - use sell version of coinify-client
  ([16646ea5](https://github.com/blockchain/My-Wallet-V3/commit/16646ea59c6177cc495657783dde8fa790e331cb))


## Branchs merged

- Merge branch 'master' into v3.30-release
  ([8532aa67](https://github.com/blockchain/My-Wallet-V3/commit/8532aa67d424aac53df5525f43709ef3ddbb4fed))
- Merge branch 'master' into v3.28-release
  ([8cf80765](https://github.com/blockchain/My-Wallet-V3/commit/8cf80765c05820de460d04afb81d38accd3387a2))
- Merge branch 'no-labels-kv-store' into v3.30-release
  ([c70eb130](https://github.com/blockchain/My-Wallet-V3/commit/c70eb130307f851be4466c748f3c6fb8a29c532a))
- Merge branch 'no-labels-kv-store' into v3.30-release
  ([8e70c5b0](https://github.com/blockchain/My-Wallet-V3/commit/8e70c5b00237aec08e035fbeb0d867718975a72f))


## Pull requests merged

- Merge pull request #358 from blockchain/v3.28-release
  ([e109ac13](https://github.com/blockchain/My-Wallet-V3/commit/e109ac13696c93d9ad5f09b586788dfe9d984220))
- Merge pull request #345 from blockchain/no-labels-kv-store
  ([6d8d9903](https://github.com/blockchain/My-Wallet-V3/commit/6d8d990383f7bfeaead0b2511296c23d2a2cf0a9))
- Merge pull request #353 from blockchain/max-available
  ([3fecba5a](https://github.com/blockchain/My-Wallet-V3/commit/3fecba5a5dbaa48abee0734574f2057f99010f96))
- Merge pull request #351 from blockchain/state-cleanup
  ([1643b4ad](https://github.com/blockchain/My-Wallet-V3/commit/1643b4ada40b35bf72dec7ceb5ebb89cef424874))
- Merge pull request #350 from blockchain/hash-guid
  ([c7cf2b48](https://github.com/blockchain/My-Wallet-V3/commit/c7cf2b4848d3e75aeb608758cbc7d8c68e84a112))
- Merge pull request #348 from blockchain/fee2
  ([4df76dcf](https://github.com/blockchain/My-Wallet-V3/commit/4df76dcfe4f97411a78641af151e30922628e3e2))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>