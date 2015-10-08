# MyWallet Bower package

Please file any bugs / issues / questions on the [original repository](https://github.com/blockchain/My-Wallet-V3/).

## Usage

```sh
bower install blockchain-wallet
```

See README in original repository.

## Verification

You can verify that the files in `/dist` are correct.

Follow the instructions in the README of [My-Wallet-V3](https://github.com/blockchain/My-Wallet-V3/) on how to build the distribution version.  
  
Now compare:

```sh
git diff my-wallet-v3/dist/my-wallet.js my-wallet-v3-bower/dist/my-wallet.js 
git diff my-wallet-v3/dist/my-wallet.min.js my-wallet-v3-bower/dist/my-wallet.min.js 
```

In addition you can check the GPG signature of the release tag:

```sh
git tag -v v3.0.0
```

Valid developer keys: CC301009 (Sjors), 36E3D143 (Jaume).

