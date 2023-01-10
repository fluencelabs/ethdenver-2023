# Fluence ETHDenver 2023 Hackathon

Welcome to what will undoubtedly amount  to yet another awesome EthDenver event. Fluence Labs' 2023 hackathon is all about keeping your dApps decentralized with decentralized RPC. To this end, Fluence is offering a total of USDC XXX in bounties.

## About Fluence

Evgeny: do you have the overview section we can copy-paste from  or link?

## Hacking On Fluence

Running blockchain nodes to support your dApps tends to be unreasonably resource intensive and not surprisingly, Web3 developers tend to gravitate toward using hosted blockchain gateways, aka RPC, solutions. Alas, "RPC as SaaS" introduces centralized bottlenecks challenging the availability, reliability and ethos of dApps.

With the Fluence's decentralized FaaS stack, which is comprised of an open, permissionless p2p network and supporting open source tooling, developers can easily create decentralized RPC solutions for their dApps.

## Bounties

For the hackathon, Fluence is providing an [fRPC](./fRPC-Starter) substrate ready to use in your dApps.

### Put the **d** back in dApp with fRPC -- 20 x USDC 250.00

Use the [fRPC-Starter](./fRPC-Starter/) code in your dAPP instead of using one centralized RPC SaaS and submit your repo, a dockerized demo of your dAPP and a 60 to 90 second video how fRPC has helped your dAPP to stay WEB3.

### Wallet Native fRPC -- USDC 15,000

The fRPC substrate provided is currently not integrated into the leading WEB3 frameworks. We want you to change that! Specifically, we want you to take the [fRPC substrate](./fRPC-Starter/) and integrate it into the (middleware of the) leading wallet sdks as a parameterizable API choice, e.g.:

```js
// setup your fRPC provider with the necessary urls, api keys and quorum parameters either in code or via env or config file(s)
const web3 = new Web3(Web3.fRPC);
// ...
// do something with the web3 response which now includes quorum information
```

to enable a seamless decentralized developer experience. Use [Fluence-JS](https://github.com/fluencelabs/fluence-js) to support your SDK integration.

USDC 3,0000 and USDC 2,000 are available for the best two integrations of fRPC with **each** of the following wallet SDKs:

* [web js](https://github.com/web3/web3.js)
* [ethers](https://github.com/ethers-io/ethers.js/)
* [wagmi](https://wagmi.sh/)

In addition to your forked and improved SDK code, please provide ample and generous documentation, a dockerized demo of your solution for the `eth_blockNumber` and `eth_sendRawTransaction` for an EVM testnet of your choice and a three to five minute video shilling your project.

### Rules

The official [ETHDenver rules](https://www.ethdenver.com/) apply.

## Workshop

An in-person [workshop](./Workshop/) is scheduled for March 1, 2023, 1 pm - 2:30 pm at the Vib Hotel Conference Room at 3560 Brighton Boulevard Denver, CO 80216. For updates, please subscribe to the [Fluence discord](https://fluence.chat) channel.

## Miscellaneous Resources

* [Fluence Documentation](https://doc.fluence.dev)
* [Fluence Examples](TBD)
* [Discord](https://fluence.chat)
* [Fluence Youtube](https://www.youtube.com/channel/UC3b5eFyKRFlEMwSJ1BTjpbw)