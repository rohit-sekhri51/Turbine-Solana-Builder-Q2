# Turbine Solana Builder Cohort Q2 2025

This repository serves as an umbrella collection of modular Solana programs built using the Anchor framework. Each submodule represents a focused, composable on-chain application ranging from DeFi primitives to DAO governance.

## 📦 Submodules Overview

### 1. [`amm-rs`](https://github.com/rohit-sekhri51/amm)
> Automated Market Maker (AMM) implementation using constant product formula — swap, pool, and liquidity management on-chain.

### 2. [`capstone-dao-notebox`](https://github.com/rohit-sekhri51/capstone-dao-notebox)
> DAO-governed on-chain publishing dApp. Includes CPI flow from a DAO voting module to update platform configuration in NoteBox.

### 3. [`escrow-rs`](https://github.com/rohit-sekhri51/escrow)
> Secure escrow contract supporting conditional asset transfers between buyer and seller on Solana.

### 4. [`marketplace-rs`](https://github.com/rohit-sekhri51/marketplace)
> NFT or token marketplace with listing, bidding, and sale logic, leveraging Anchor PDAs for trade validation.

### 5. [`nft-staking-rs`](https://github.com/rohit-sekhri51/nft-staking)
> Stake NFTs to earn on-chain rewards, using time-based or metadata-driven reward logic.

### 6. [`quadfund-dao`](https://github.com/rohit-sekhri51/quadfund-dao)
> DAO platform implementing quadratic funding logic for community project support and democratic fund distribution.

### 7. [`solana-starter`](https://github.com/rohit-sekhri51/solana-starter)
> Beginner-friendly TypeScript starter project for Solana client-side development and RPC interactions (Week 1).

### 8. [`vault-rs`](https://github.com/rohit-sekhri51/vault)
> On-chain token vault with time-locked withdrawal or conditional release mechanism.

## 🛠 Getting Started
Clone the repo and initialize all submodules:

```bash
git clone --recurse-submodules https://github.com/your-org/solana-anchor-collection.git
cd solana-anchor-collection
git submodule update --init --recursive
```

## 📚 Tech Stack
- Solana Runtime
- Anchor Framework
- TypeScript (for client)
- Mermaid (for diagrams)

## 📄 License
MIT

