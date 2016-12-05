__Blockchain Wallet V3__

#   (2016-12-05)



---

## Bug Fixes

- **accountinfo:** setters for mobile and isMobileVerified
  ([f211ec8a](https://github.com/blockchain/My-Wallet-V3/commit/f211ec8a2f225ecd255e2e2c3af7692dea706eaa))
- **buysell:** don't downcase integer, fix token tests
  ([e746f0af](https://github.com/blockchain/My-Wallet-V3/commit/e746f0af8887d78096126eb899b8f2cb3f3997d1))
- **exchangedelegate:** use correct signed-token endpoint
  ([6a0e897b](https://github.com/blockchain/My-Wallet-V3/commit/6a0e897bb9119e6f4ec54ff6232d2737e279e93c))
- **paymentaccount:** getAll() returns accounts
  ([b4f95654](https://github.com/blockchain/My-Wallet-V3/commit/b4f9565455707ebdd002d785d7299747bad539f9))
- **sfox:**
  - do not include fee in sendAmount, the fee is part of the quote
  ([75c6b941](https://github.com/blockchain/My-Wallet-V3/commit/75c6b941c5e10fd652af447e9886d03f0663e537))
  - map pending state to processing
  ([8590de2a](https://github.com/blockchain/My-Wallet-V3/commit/8590de2a7c5ace1b4e6e5acc79a79cb015de3494))
  - set trade after updating with QA tools
  ([c2cf50e0](https://github.com/blockchain/My-Wallet-V3/commit/c2cf50e00c52138324a6bdc8a3a63ca1d5adac87))
  - correctly assign base_amount and quote_amount
  ([527e47b2](https://github.com/blockchain/My-Wallet-V3/commit/527e47b2430bbca2d2d38b9f98aa76fb07fd14c8))
  - set verification status to full object
  ([f15fb87b](https://github.com/blockchain/My-Wallet-V3/commit/f15fb87bba00950a72a145c2bad48aa7b5ece433))
  - fix trade refresh function
  ([5bd47ce2](https://github.com/blockchain/My-Wallet-V3/commit/5bd47ce22c99ee10e2203e331123e7961e06ccf9))
  - since paymentMethods is now an object it will not iterate
  ([6851a6e0](https://github.com/blockchain/My-Wallet-V3/commit/6851a6e0d6b9d53bf42e327a07120a8d26fba3d6))
  - minor fixes
  ([4d149e6e](https://github.com/blockchain/My-Wallet-V3/commit/4d149e6e296f4929d337f64667f56d95959ac328))
  - save trade id in lower case
  ([2a87369b](https://github.com/blockchain/My-Wallet-V3/commit/2a87369b7704dc5c26fceb8dacdcff5585b6d9ee))
  - tested with real API
  ([b093fb28](https://github.com/blockchain/My-Wallet-V3/commit/b093fb284347fffadc80f55b8287de01d1be5546))
  - use correct token endpoint with params
  ([d94a93e6](https://github.com/blockchain/My-Wallet-V3/commit/d94a93e6ed6f50806aa880a21dc04fd46a385fb4))
  - use API key rather than partner id
  ([722bd023](https://github.com/blockchain/My-Wallet-V3/commit/722bd0235f9e17482292313ed6ffdc700158b81e))


## Features

- **buysell:** buy is triggered by PaymentMethod
  ([89fb08e2](https://github.com/blockchain/My-Wallet-V3/commit/89fb08e2958a2d1a84ae52e4a6b7ba24c8932184))
- **exchange:** buy() straight from the PaymentMedium object
  ([ca6d8dd3](https://github.com/blockchain/My-Wallet-V3/commit/ca6d8dd355c57e312b97202f7dcf5eee047f6c10))
- **exchangedelegate:**
  - labelBase is configurable (falls back to 'Exchange order')
  ([8c167552](https://github.com/blockchain/My-Wallet-V3/commit/8c1675521bf6bdbda176d03c25f291213ac5b1cc))
  - mobile
  ([16c450de](https://github.com/blockchain/My-Wallet-V3/commit/16c450defe01d39c520ef81cc5f35e129f479c99))
  - obtain token for both email and mobile
  ([750a4f30](https://github.com/blockchain/My-Wallet-V3/commit/750a4f304c2cb722dda21d63f5ead77a676be9be))
- **helpers:** add option to cancel asyncOnce call
  ([246c0080](https://github.com/blockchain/My-Wallet-V3/commit/246c00802b40317a5636821fe1099a315b1bb6a9))
- **quote:** expose fee amount and fee currency in quote
  ([dea09e01](https://github.com/blockchain/My-Wallet-V3/commit/dea09e01ea6b52859da85f64a8bc91c530592188))
- **sfox:**
  - add production domain
  ([f48af1c4](https://github.com/blockchain/My-Wallet-V3/commit/f48af1c40250d2cbe7797d49e872f880e545ab47))
  - leave setting API key to frontend
  ([c0430a44](https://github.com/blockchain/My-Wallet-V3/commit/c0430a440f466ec8f944a5649a1ac1599ff18ed7))
  - set profile settings after verification
  ([b0c462b8](https://github.com/blockchain/My-Wallet-V3/commit/b0c462b84fa4e90918d7d0daced67123c1a3399b))
  - add calculated rate to quote class
  ([f1496767](https://github.com/blockchain/My-Wallet-V3/commit/f149676776ead09bd9c30f28fb3c015f42e83dab))
  - include filename
  ([9992f268](https://github.com/blockchain/My-Wallet-V3/commit/9992f26853e6490b267623f2852d7d5da28938b0))
  - get signed url from sfox to upload docs to s3
  ([ecbea54e](https://github.com/blockchain/My-Wallet-V3/commit/ecbea54e8a1bb2160398c8cc8db66431fc1e7edb))
  - simulate ACH success / fail
  ([53df686f](https://github.com/blockchain/My-Wallet-V3/commit/53df686f04d7d76f4ce42e69533e977209b5ced6))
  - add and verify ACH
  ([b84c4b6d](https://github.com/blockchain/My-Wallet-V3/commit/b84c4b6d92d7bede8bb68e6a7f2d96759989d80b))
  - verify profile
  ([f457fa58](https://github.com/blockchain/My-Wallet-V3/commit/f457fa58011e75f5e8764acf7bd054d0bde4a8c6))
  - place order (partially tested, pending API change)
  ([c7b34d92](https://github.com/blockchain/My-Wallet-V3/commit/c7b34d9226ba9455a011c4a88c55ddd03425517d))
  - get registered payment methods
  ([3ddad8d6](https://github.com/blockchain/My-Wallet-V3/commit/3ddad8d6ca6484cb047a35858e890a488b25906a))
  - get quote
  ([023eb648](https://github.com/blockchain/My-Wallet-V3/commit/023eb6486867cbad01f9a95d9f7c805c2a43c728))
  - reuse address watch code
  ([974b6ff0](https://github.com/blockchain/My-Wallet-V3/commit/974b6ff02c72f1561cecd1b8ba1220df00de68e0))
  - get and refresh trades
  ([6241ca3e](https://github.com/blockchain/My-Wallet-V3/commit/6241ca3ea9d43152faf22db4768ff207a12ba3ab))
  - fetchProfile() gets verification status and limits
  ([dce8c5ed](https://github.com/blockchain/My-Wallet-V3/commit/dce8c5ede709714ce60e04a9e0ce547a7a184193))
  - signup and serialize
  ([e519ef78](https://github.com/blockchain/My-Wallet-V3/commit/e519ef78cb7e7bcae36f2b4d9500a6b19692c917))


## Refactor

- **buysell:**
  - move Exchange classes to their own module.
  ([0792b7fa](https://github.com/blockchain/My-Wallet-V3/commit/0792b7fafd571d2f0d616b5f60255692ba4a607a))
  - repair tests
  ([c68760c0](https://github.com/blockchain/My-Wallet-V3/commit/c68760c0dd51717a871be4c3b06d0f9586d2758c))
  - split PaymentMethod into type and account (work in progress)
  ([8b4ebd5b](https://github.com/blockchain/My-Wallet-V3/commit/8b4ebd5b00e4473e64c3c6927987f50d9432af6f))
  - API class with Coinify & SFOX subclass
  ([490b62c9](https://github.com/blockchain/My-Wallet-V3/commit/490b62c9cc7d7d3eaaeafcce188f1e0c0e2aed7b))
- **es6:**
  - Quote class
  ([8350a6de](https://github.com/blockchain/My-Wallet-V3/commit/8350a6de354f77fbaa3166190787e33aa8dfed15))
  - class for Exchange, Coinify and SFOX
  ([d8212cbd](https://github.com/blockchain/My-Wallet-V3/commit/d8212cbd9277164578ef7a933736693e255aee19))
  - apply to Exchange and SFOX files
  ([4416dc55](https://github.com/blockchain/My-Wallet-V3/commit/4416dc55395004d5b71dfd5b1f4ee18db973dc93))
  - exchange.getTrades()
  ([566a7f1a](https://github.com/blockchain/My-Wallet-V3/commit/566a7f1a74d6a1f3e0663a4a78e85c689b14c12b))
  - configured as opt-in, applied to coinify/helpers.js
  ([2628f1e8](https://github.com/blockchain/My-Wallet-V3/commit/2628f1e8760871ac1749c230c33bc38edfeff80f))
- **external:** addCoinify / addSFOX no longer needed
  ([b8a71871](https://github.com/blockchain/My-Wallet-V3/commit/b8a71871397fb4f314fd736b1d20304413414aba))
- **paymentmedium:** getAccounts() uses PaymentAccount.getAll, add test
  ([ce177b61](https://github.com/blockchain/My-Wallet-V3/commit/ce177b61cb9d61c39950c713aa6d08ab71c157fb))
- **paymentmethod:** turn into class and seperate Coinify specific stuff
  ([eff5d8b0](https://github.com/blockchain/My-Wallet-V3/commit/eff5d8b07ede7abf0ab874d3103c36cd416b0b54))
- **sfox:**
  - remove nickname from exchange payment account
  ([e75bd076](https://github.com/blockchain/My-Wallet-V3/commit/e75bd076933a348b90fd189a494904ccca3968b3))
  - improve clarity of quote vs base amount in quote class
  ([8602b28b](https://github.com/blockchain/My-Wallet-V3/commit/8602b28b3841bc46306c217e6304a509fbb7c290))


## Test

- **api:** increase coverage (Exchange and SFOX)
  ([da74917c](https://github.com/blockchain/My-Wallet-V3/commit/da74917cf9ab90ac67b7ecfe462b4dcb6ccc2086))
- **buysell:** fix broken tests, semistandard fix
  ([09e523b8](https://github.com/blockchain/My-Wallet-V3/commit/09e523b827b13f42dd945aecf4cc804ce1470d2c))
- **es6:** Istanbul needs to go before Babelify. HTML reports work again
  ([b8e5ae21](https://github.com/blockchain/My-Wallet-V3/commit/b8e5ae21777c9da31f624a506cd4ae497ff7cac1))
- **paymentaccount:** more tests
  ([f566f365](https://github.com/blockchain/My-Wallet-V3/commit/f566f365f18b11a6c687c1b2e9d03ff4c89d79ec))
- **paymentmedium:** more tests
  ([230b180e](https://github.com/blockchain/My-Wallet-V3/commit/230b180e1d92638fab5f985ea006a99ff7159a08))


## Chore

- **release:** v3.25.0
  ([298dbe6f](https://github.com/blockchain/My-Wallet-V3/commit/298dbe6f32676008e220f4a84ce3e682e637627a))


## Branchs merged

- Merge branch 'master' into usa
  ([9e515124](https://github.com/blockchain/My-Wallet-V3/commit/9e515124e4f52704a6d08ccd7a8f74ac1b3ffe1b))


## Pull requests merged

- Merge pull request #28 from blockchain/send-amount
  ([c56919a0](https://github.com/blockchain/My-Wallet-V3/commit/c56919a053c40a5fe5c6e4f42c3db8b0e59766f9))



---
<sub><sup>*Generated with [git-changelog](https://github.com/rafinskipg/git-changelog). If you have any problems or suggestions, create an issue.* :) **Thanks** </sub></sup>