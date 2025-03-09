# Ballot-Dapp

This Decentralized Ballot Voting DApp is a blockchain-based voting system that ensures secure, transparent, and tamper-proof elections. Built with Ethereum, Solidity, Web3.js, and Bootstrap, this application allows users to register, vote, and declare winners in a decentralized manner.

🔥 Features
✅ Secure & Transparent – Votes are stored on the blockchain, preventing fraud.
✅ Decentralized – Eliminates central authority, ensuring trust in the voting process.
✅ Easy-to-Use UI – Clean and intuitive interface for seamless voting.
✅ Smart Contracts – Solidity-based contracts handle the voting logic.
✅ Web3 Integration – Connect with Ethereum wallets for authentication.

🏗️ Tech Stack
Smart Contracts: Solidity
Frontend: HTML, CSS, Bootstrap
Blockchain Interaction: Web3.js, Truffle
Backend: Ethereum Blockchain

Here’s the updated **Getting Started** section with Truffle deployment and MetaMask setup:  

---

## 🚀 Getting Started  

### 1️⃣ Prerequisites  
Ensure you have the following installed:  
- **Node.js** (Download from [nodejs.org](https://nodejs.org/))  
- **Truffle** (Install via npm: `npm install -g truffle`)  
- **Ganache** (For local Ethereum blockchain: [Download Ganache](https://trufflesuite.com/ganache/))  
- **MetaMask Extension** (Install from [metamask.io](https://metamask.io/))  

### 2️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/ballot-dapp.git
cd ballot-dapp
```

### 3️⃣ Install Dependencies  
```bash
npm install
```

### 4️⃣ Start a Local Blockchain with Ganache  
- Open **Ganache** and create a new workspace.  
- Copy the **RPC Server URL** (e.g., `http://127.0.0.1:7545`).  

### 5️⃣ Deploy Smart Contracts  
```bash
truffle migrate --network development
```
- Ensure `truffle-config.js` is configured to use Ganache.  
- If using a test network (Ropsten, Goerli, Sepolia), configure Infura and add your MetaMask wallet private key.  

### 6️⃣ Connect MetaMask to the Local Blockchain  
- Open **MetaMask** and switch to "Localhost 7545".  
- Import accounts from Ganache using their private keys.  

### 7️⃣ Start the DApp  
```bash
npm start
```
- Open **http://localhost:3000** in your browser.  
- Register an address, vote for a candidate, and declare the winner!  

---
