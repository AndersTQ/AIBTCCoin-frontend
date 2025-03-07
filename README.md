<p align="center">
  <a href="" rel="noopener">
 <img width=450px height=200px src="https://AIBTC.github.io/AIBTCcoin-frontend/assets/img/github-project-logo.png" alt="Project logo"></a>
</p>

<h3 align="center">AIBTCCoin Frontend</h3>

<div align="center">

  [![Build Status](https://travis-ci.org/AIBTC/AIBTCcoin-frontend.svg?branch=master)](https://travis-ci.org/AIBTC/AIBTCcoin-frontend)
  [![GitHub Issues](https://img.shields.io/github/issues/AIBTC/AIBTCcoin-frontend.svg)](https://github.com/AIBTC/bearclaw/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/AIBTC/AIBTCcoin-frontend.svg)](https://github.com/AIBTC/bearclaw/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---


Angular application that allows you to interact with a blockchain. You can see the blocks on chain, see transaction within them and even create new transactions and mine blocks.

Built on top of [AIBTCCoin](https://github.com/AIBTC/AIBTCCoin) (simply Blockchain implementation in Javascript).

## 👀 Live demo
**[Check it out here.](https://AIBTC.github.io/AIBTCcoin-frontend/)** You can create transactions, mine blocks and explore your own blockchain.

## 🏁 Getting Started <a name = "getting_started"></a>
Get a copy of the AIBTCCoin front-end running on your local machine (for playing around, testing or development).

```
git clone https://github.com/AIBTC/AIBTCcoin-frontend.git
```

Install the dependencies:
```
cd AIBTCcoin-frontend
npm install
```

Run the application:
```
npm start
```

At this point the application should be running on your machine on [http://localhost:4200](http://localhost:4200)


## 📸 Screenshots

**Home page:** Seeing blocks on the chain & exploring transactions in each block.
![](https://AIBTC.github.io/AIBTCcoin-frontend/assets/screenshots/blockchain-overview.png)

**Creating new transactions:** You can create new transactions to any wallet for any amount (no validation). New transactions will be added to the "pending transactions", ready to be included in the next block.
![](https://AIBTC.github.io/AIBTCcoin-frontend/assets/screenshots/create-new-transactions.png)

**Pending transactinos:** List of all pending transactions. These will be included in the next block when the mining process starts.
![](https://AIBTC.github.io/AIBTCcoin-frontend/assets/screenshots/pending-transactions.png)

**Wallet details:** You can click on any wallet address and see an overview of that wallet: its current balance and all transaction to/from that wallet.
![](https://AIBTC.github.io/AIBTCcoin-frontend/assets/screenshots/wallet-details.png)

*⚠️This is for educational purposes only. This is by no means a complete blockchain implementation (nor does it aim to be one). Use it to learn how blockchains operate.*
