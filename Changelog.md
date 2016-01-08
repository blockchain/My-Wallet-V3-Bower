__Blockchain Wallet V3__

_Recent changes_

#   (2016-01-08)



---

## Bug Fixes

- **API:**
  - take advantage of content-type JSON
  ([0cb1647d](https://github.com/blockchain/My-Wallet-V3/commit/0cb1647dcafa70b954daa88dbf3136b2efdaad37))
  - credentials needs to be 'omit', not false, in Firefox
  ([37d23062](https://github.com/blockchain/My-Wallet-V3/commit/37d230628ff7d3ca8f31fc0a1aed4945cef27789))
  - allow cookie credentials with all authorized XHR domains
  ([954f5f0b](https://github.com/blockchain/My-Wallet-V3/commit/954f5f0b21f38d2bcc107862f41f9dc47f2e2f79))
- **Beta:** don't use ES6
  ([a8b6d4b0](https://github.com/blockchain/My-Wallet-V3/commit/a8b6d4b0160e70fa04d27b50263cf6088e2ff1c2))
- **api:** handle fetch errors better
  ([230c2791](https://github.com/blockchain/My-Wallet-V3/commit/230c27915fc89bf5b915f5d2c2798c3e94e8986d))
- **encoding:** set stream encoding to utf8 on request end
  ([466a560c](https://github.com/blockchain/My-Wallet-V3/commit/466a560c5c94e1d570daefd6631b221cef0eeb6e))
- **websocket:** try to reconnect when send
  ([0b67678e](https://github.com/blockchain/My-Wallet-V3/commit/0b67678ecbb1105e5d184b1f4238e2f6f4b9b652))


## Features

- **2FA:**
  - reset 2fa endpoint with email token
  ([93c47a2e](https://github.com/blockchain/My-Wallet-V3/commit/93c47a2e1bf86cc9782ee857b953625fd5f29335))
  - request 2FA reset
  ([558005d8](https://github.com/blockchain/My-Wallet-V3/commit/558005d8a5cbc87fa9fde5bd76f53fd12da40dc1))
- **API:**
  - authorize-approve- different browser
  ([5249a826](https://github.com/blockchain/My-Wallet-V3/commit/5249a8269b307c73aa94d54255b8629db5dccb8d))
  - authorize-approve- assuming same browser
  ([e1febc3e](https://github.com/blockchain/My-Wallet-V3/commit/e1febc3ec29a09bf706ec3616d776e82fe3d94c4))
  - unsubscribe
  ([183e055d](https://github.com/blockchain/My-Wallet-V3/commit/183e055d5aadd13ae78faf53906805760eacb3fb))
  - allow custom ROOT_URL, e.g. for development
  ([431ef410](https://github.com/blockchain/My-Wallet-V3/commit/431ef41030190b98d7408d5593540e16e038454a))
- **Deploy:** beta changes
  ([f48c13fb](https://github.com/blockchain/My-Wallet-V3/commit/f48c13fb7fcf252116e55fd16d635d8ca847f765))
- **Endpoint:**
  - verify-email-token processes result better
  ([3a1b30b6](https://github.com/blockchain/My-Wallet-V3/commit/3a1b30b6e3fe93fe14f0c1fdb4f8fe88c7200283))
  - verify-email with token via POST request
  ([83da5475](https://github.com/blockchain/My-Wallet-V3/commit/83da54751d8739facf42235d3ec21f0b69b54c10))
- **ForgotGuid:** use new endpoint to request guid reminder
  ([66d85607](https://github.com/blockchain/My-Wallet-V3/commit/66d856074e0191c43c613e0167941b5b67c4dd69))
- **WebSocket:** allow custom backend URL
  ([a8ae0e95](https://github.com/blockchain/My-Wallet-V3/commit/a8ae0e954560cb54ee758b0399cc067cde7f51fa))


## Refactor

- **WalletTokenEndpoints:** better code reuse
- **api:**
  - pass errors to wallet in correct format
  - remove unused event emitters
  - use fetch rather than hyperquest


## Test

- **WalletTokenEndpoints:** tests for verifyEmail()


## Chore

- **logging:** remove console logs that show messages when browser globals are undefined



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problem or suggestion, create an issue.* :) **Thanks** </sub></sup>