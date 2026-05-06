# TokenMaster — Decentralized NFT Ticketing Platform

TokenMaster is a blockchain-based NFT ticketing platform designed to eliminate ticket fraud, counterfeiting, and scalping through decentralized smart contracts and NFT ownership verification.

The platform uses ERC-721 NFTs on the Polygon blockchain to provide secure, transparent, and tamper-proof digital event tickets with peer-to-peer transfer capabilities.

---

## Overview

Traditional ticketing systems face several challenges such as:

- Fake tickets
- Ticket duplication
- Scalping and unfair resale pricing
- Centralized control
- Lack of transparent ownership

TokenMaster solves these problems by leveraging blockchain technology and smart contracts to create verifiable NFT-based tickets.

---

## Key Features

- NFT-based event ticket generation
- ERC-721 smart contract implementation
- Secure blockchain verification
- Peer-to-peer ticket transfers
- Anti-counterfeit ticket validation
- Wallet authentication using MetaMask
- Decentralized ownership tracking
- Transparent and immutable transactions

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Solidity | Smart Contract Development |
| ERC-721 | NFT Token Standard |
| Polygon | Blockchain Network |
| Hardhat | Smart Contract Development Environment |
| React.js | Frontend Development |
| Web3.js | Blockchain Interaction |
| MetaMask | Wallet Integration |
| OpenZeppelin | Secure Smart Contract Libraries |

---

## System Workflow

1. Event organizers create events
2. Smart contracts mint NFT tickets
3. Users connect wallets through MetaMask
4. Tickets are purchased securely on-chain
5. Ownership is recorded on the blockchain
6. Tickets can be transferred or resold transparently

---

## Smart Contract Capabilities

- NFT minting for event tickets
- Ownership verification
- Secure ticket transfers
- Blockchain-based validation
- Immutable transaction records

---

## Installation and Setup

```bash
git clone https://github.com/your-username/tokenmaster.git

cd tokenmaster

npm install

npx hardhat node

npx hardhat run ./scripts/deploy.js --network localhost

npm start
