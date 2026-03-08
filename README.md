# ETH Layer 3 & Layer 2 Experiments

This repository contains various smart contract and application experiments conducted on Ethereum Layer 2 (zkEVM, zkSync) and potential Layer 3 architectures. The project includes diverse modules ranging from DeFi games to network metric tracking and L1-L2 communication protocols.

## 🚀 Project Structure

### 1. [CasinoGame](./CasinoGame)
A decentralized gambling game that operates using ERC20 tokens (MockDAI, MockUSDC).
- **Technologies:** Solidity, Hardhat, OpenZeppelin.
- **Features:** Token-based betting mechanics, mock token contracts.

### 2. [zkevm_metrics](./zkevm_metrics)
A data monitoring tool that tracks important metrics (versions, gas prices, etc.) on the Polygon zkEVM network.
- **Technologies:** Express.js, Cheerio, Node-fetch.
- **Features:** Fetching and serving zkEVM Gas Station data via web scraping.

### 3. [zkEVM-custom-token](./zkEVM-custom-token)
A project developed for the deployment and management of a custom token (MultiplyToken) on zkEVM.
- **Technologies:** Solidity, Hardhat.
- **Features:** Custom token economics and deployment scripts.

### 4. [zksync_l1_to_l2](./zksync_l1_to_l2)
Studies on token transfer and message sending from the Ethereum (L1) network to the zkSync (L2) network.
- **Technologies:** Solidity, Matter Labs zkSync Contracts, zksync-ethers.
- **Features:** L1-L2 bridging, message transmission, L1TokenSender contract.

## 🛠 Installation and Usage

Each sub-directory is an independent project managing its own dependencies. To run a specific project:

1. Navigate to the project folder:
   ```bash
   cd [folder-name]
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. For Hardhat projects, run compilation or tests:
   ```bash
   npx hardhat compile
   npx hardhat test
   ```
4. For the metrics server (zkevm_metrics):
   ```bash
   node server.mjs
   ```

## 🔒 Security Note
The projects in this repository are for experimental purposes. Never share your `.env` files and carefully review the contracts before deploying to mainnet environments.

---
*Developed by: [Your Name/Username]*
