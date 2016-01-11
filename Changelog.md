__Blockchain Wallet V3__

_Recent changes_

#   (2016-01-11)



---

## Bug Fixes

- **API:**
  - take advantage of content-type JSON
  ([c7b40645](https://github.com/blockchain/My-Wallet-V3/commit/c7b4064587f5bfa83c696698dd75fe12e1296852))
  - credentials needs to be 'omit', not false, in Firefox
  ([37d23062](https://github.com/blockchain/My-Wallet-V3/commit/37d230628ff7d3ca8f31fc0a1aed4945cef27789))
  - allow cookie credentials with all authorized XHR domains
  ([954f5f0b](https://github.com/blockchain/My-Wallet-V3/commit/954f5f0b21f38d2bcc107862f41f9dc47f2e2f79))
- **Beta:** don't use ES6
  ([84bbdafd](https://github.com/blockchain/My-Wallet-V3/commit/84bbdafdb44e0aed4e54033aa1e94fd9bfb3fc7a))
- **api:** handle fetch errors better
  ([230c2791](https://github.com/blockchain/My-Wallet-V3/commit/230c27915fc89bf5b915f5d2c2798c3e94e8986d))
- **encoding:** set stream encoding to utf8 on request end
  ([466a560c](https://github.com/blockchain/My-Wallet-V3/commit/466a560c5c94e1d570daefd6631b221cef0eeb6e))
- **websocket:** try to reconnect when send
  ([0b67678e](https://github.com/blockchain/My-Wallet-V3/commit/0b67678ecbb1105e5d184b1f4238e2f6f4b9b652))


## Features

- **2FA:**
  - reset 2fa endpoint with email token
  ([c136ec39](https://github.com/blockchain/My-Wallet-V3/commit/c136ec39475127f16050271b465c3028e9beb9af))
  - request 2FA reset
  ([2adf8be2](https://github.com/blockchain/My-Wallet-V3/commit/2adf8be2ddd6c874b8d51c09900be5c1acf6264a))
- **API:**
  - authorize-approve- different browser
  ([64f42b98](https://github.com/blockchain/My-Wallet-V3/commit/64f42b98b9c0f22263b36507e6b199875ad2cd97))
  - authorize-approve- assuming same browser
  ([f3691296](https://github.com/blockchain/My-Wallet-V3/commit/f369129625c081a75555e6fb508e0f074e7ec5bb))
  - unsubscribe
  ([7c6eb577](https://github.com/blockchain/My-Wallet-V3/commit/7c6eb5775aa25047bbfbfbc3059dd606bc8aeb15))
  - allow custom ROOT_URL, e.g. for development
  ([d8cd54fa](https://github.com/blockchain/My-Wallet-V3/commit/d8cd54faf1855340cb9c6846065ff93fc3081034))
- **Deploy:** beta changes
  ([692cc2c2](https://github.com/blockchain/My-Wallet-V3/commit/692cc2c29af8bbc695998c875dabaf21a4ad23a8))
- **Endpoint:**
  - verify-email-token processes result better
  ([c5b113e8](https://github.com/blockchain/My-Wallet-V3/commit/c5b113e8d0384df3646afc24505b4173167816b8))
  - verify-email with token via POST request
  ([e4577f70](https://github.com/blockchain/My-Wallet-V3/commit/e4577f7075f5c724990b05a3ec43d56a06ae71ca))
- **ForgotGuid:** use new endpoint to request guid reminder
  ([03497e44](https://github.com/blockchain/My-Wallet-V3/commit/03497e446eb480c01f30a4e7d1894f5747dad88b))
- **WebSocket:** allow custom backend URL
  ([b7b848e2](https://github.com/blockchain/My-Wallet-V3/commit/b7b848e232bf39db36ef7e5e4db6239e5c092f36))
- **derive-pk:** exposed a way to generate a specific private-key.
  ([137f9c80](https://github.com/blockchain/My-Wallet-V3/commit/137f9c808f099d34992bb066d5b35d52b6d80e0c))


## Refactor

- **API:**
  - use promises for new endpoints
  - no need for root url setter
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