# Intro to Binance Chain

This is a work-in-progress by Daniel Onggunhao (@onggunhao) to create a technical workshop series on Binance Chain.

It is inspired by the excellent [Serverless Stack](https://serverless-stack.com/), and aims to teach through building real-life projects.

For more information on Binance Chain, please visit the official [Binance Chain Docs](https://docs.binance.org/)

## Workshops

This is a tentative list of workshops. Please add an issue if you have any suggestions.

### The Basics

**[Workshop: Practical Intro to Binance Chain](practical-guide-binance-chain.md)**

-   Before we dive into the technicals, let's use the technology from the perspective of the end user
-   We'll create a wallet and load it with BNB
-   We'll use the BNB to trade for BUSD
-   We'll explain why it's difficult to build a Decentralized Exchange, and why Binance Chain has chosen to take this route of creating our own chain
-   Binance Chain doesn't have smart contracts, how we support the ecosystem rather than compete with it

### Listing on Binance DEX

**[Workshop: Launching an e-money Stablecoin on Binance Chain](launch-stablecoin.md)**

-   We'll create a BEP-2 stablecoin on the Binance Chain testnet, using the command line interface
-   We'll go through the minting process

**[Workshop: Listing an e-money Stablecoin on Binance Chain](list-stablecoin.md)**

-   We'll list the e-money Stablecoin on Binance Chain

**[Workshop: Listing an Ethereum ERC-20 token on Binance DEX](list-bep3-token.md)**

-   We use Hashed Timelocked Contracts and Atomic Swaps to list an ethereum ERC-20 token on Binance Chain
-   This uses BEP-3 tokens
-   For this, we'll list the popular stablecoin Dai on Binance DEX

### Payment Network

**[Workshop: Programmable Money and your first transaction](programmable-money-transaction.md)**

-   We'll use the stablecoin we created in the last workshop, this time programmatically send it to people
-   We'll use multi-send, a cheap way to send it to a large group of people with small transaction costs

### Advanced

**[Workshop 5: Building a simple block explorer for Binance Chain](building-block-explorer.md)**

-   We'll learn how to use go and amino to retrieve data from Binance Chain
-   We'll learn about the AVL tree data structure that Binance Chain uses

**[Workshop: Building a simple wallet](build-simple-wallet.md)**

**[Workshop: Running a Binance Chain node](running-binance-chain-node.md)**

**[Workshop: How it works](how-it-works.md)**
