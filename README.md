# Vue + Truffle + Webpack [vtw]

This simple script combines truffle with a [custom Vue webpack template](https://github.com/wilfreddenton/vue-truffle-webpack) to generate a boilerplate that can be built on top of to create complex distributed apps on the Ethereum blockchain.

## Install

vtw requires that you have [truffle](https://github.com/trufflesuite/truffle) and the [vue-cli](https://github.com/vuejs/vue-cli) installed.

`npm install -g truffle`

`npm install -g vue-cli`

After obtaining the dependencies simply run the following command. This will fetch the `vtw` script file and move it into `/usr/local/bin` so it can be used globally as a command.

```
curl -O https://raw.githubusercontent.com/wilfreddenton/vue-truffle-webpack/master/vtw ; chmod +x vtw ; mv vtw /usr/local/bin
```

## Usage

1. `mkdir dapp`
2. `cd dapp`
3. `vtw`
4. Answer the prompts to setup the Vue app
5. `cd app`
6. `npm install`
7. `npm run dev`
