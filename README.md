# 📦 Digital Asset Management using Blockchain

This project is a decentralized marketplace built on the **Ethereum blockchain** using **Solidity smart contracts**, the **Truffle framework**, and a **React frontend**. It allows users to **buy and sell digital assets** securely on the blockchain.

## 🌐 Live Demo

**Coming soon...** (Add link here if hosted on IPFS, Fleek, or localhost demo video)

---

## 🛠 Tech Stack

- **Smart Contracts:** Solidity  
- **Blockchain Dev Framework:** Truffle  
- **Test Network:** Ganache  
- **Frontend:** React.js  
- **Blockchain Interface:** Web3.js  
- **Wallet:** MetaMask

---

## 🚀 Getting Started

### ✅ Prerequisites

- Node.js & npm
- Truffle (`npm install -g truffle`)
- Ganache (GUI or CLI)
- MetaMask extension in your browser

---

### 🔧 Installation Steps

1. **Clone the Repository:**

```bash
git clone https://github.com/THEBHARAT08/Digital-Asset-Management-by-using-Blockchain-.git
cd Digital-Asset-Management-by-using-Blockchain-
```

2. **Install Dependencies:**

```bash
npm install
```

3. **Start Ganache:**

- Open Ganache and start a workspace (default: `http://127.0.0.1:7545`).

4. **Compile Smart Contracts:**

```bash
truffle compile
```

5. **Deploy Contracts to Ganache:**

```bash
truffle migrate
```

6. **Run the React Frontend:**

```bash
npm start
```

---

## 🔗 MetaMask Configuration

- Switch MetaMask to **Localhost 7545**
- Import one of the accounts from Ganache using its private key

---

## 💡 Features

- 🪙 List digital assets for sale  
- 💼 Buy assets using ETH  
- 🔒 Fully decentralized using Ethereum smart contracts  
- 🔗 MetaMask wallet integration

---

## 📂 Project Structure

```
contracts/
│  ├── Marketplace.sol        # Main smart contract
│  └── Migrations.sol         # For managing deployments
migrations/
│  ├── 1_initial_migration.js
│  └── 2_deploy_contracts.js
truffle-config.js             # Truffle settings
package.json                  # Node dependencies and scripts
```

---

## 🧪 Run Tests

```bash
truffle test
```

---

## 📚 Data Source

This app does not use an external dataset. All data is stored on the Ethereum blockchain (via Ganache test network).

---

## 👨‍💻 Author

Developed by [Bharat Lohar](https://github.com/THEBHARAT08)

---

## 📄 License

This project is licensed under the MIT License.
