---
title: Blockchain Beginner Track
date: 2025-01-08
categories:
  - Blockchain
  - Learning
tags:
  - Binance Academy
  - Blockchain
  - Cryptocurrency
  - DeFi
  - Web3
---


Resource link: <https://academy.binance.com/en/track/beginner-track>

This course encompasses a series of modules focusing on the basics of **blockchain** technology, **cryptocurrencies**, decentralized **finance** (DeFi), **Web3**, and trading and investing strategies.

## Blockchain

- blockchain is  a distributed ledger technology.
- specific type of database.
  - data can be add
  - data cannot be removed
  - each block data is linked to the previous block data
  - each block contains a hash for it identification, and the hash based on the previous block.
- no central authority, each node has a copy of the blockchain.

### History of Blockchain

- 1991: Stuart Haber and W. Scott Stornetta described for time-stamping digital documents.
- 2004: Hal Finney introduced a system called reusable **proof of work** (RPOW). issue of the **double-spending problem**.
- 2008: Satoshi Nakamoto published a whitepaper called "Bitcoin: A Peer-to-Peer Electronic Cash System".
- 2009: Bitcoin network was launched.
- 2013: Vitalik Buterin proposed **Ethereum**, a blockchain platform that supports **smart contracts**, which is a programs on the blockchain that automatically execute when certain conditions are met. DApps (decentralized applications) can be built on top of Ethereum.

### How Does Blockchain Work

- authentication message: digital signature by the asymmetric encryption algorithm. To auth who is the sender.
- transform message on the peer-to-peer network.

#### Double-spending Problem

Double-spending is a potential issue in a digital cash system where the same funds are sent to two recipients at the same time.

- The centralized approach: blind sign a message to a bank, and the bank will check the balance and sign the transaction.
- The decentralized approach: blockchain, the network will check the balance and sign the transaction.

### Blockchain consensus mechanisms

#### Proof of Work (PoW)

- PoW is a consensus algorithm that requires nodes to solve complex mathematical problems to validate transactions. (i.e, called mining, miner)
  - expensive to produce but easy for others to verify.
  - note: when the network more larger, the difficulty of the problem will increase.

#### Proof of Stake (PoS) - 2011

- PoS is a consensus algorithm that requires nodes to stake a certain amount of cryptocurrency to validate transactions.
  - the more coins you hold, the more likely you are to be chosen to validate a block.

### nodes and forks

- nodes: a device that connects to a blockchain network.
  - full nodes: download the entire blockchain and validate every transaction. (i.e Bitcoin Core over 400GB as of min-2022)
  - light nodes: only download block headers and verify transactions. (i.e, SPV wallets)
- forks: a split in the blockchain network that occurs when two or more miners find a block at the same time.
  - hard fork: a permanent divergence in the blockchain.
  - soft fork: a temporary divergence in the blockchain.
