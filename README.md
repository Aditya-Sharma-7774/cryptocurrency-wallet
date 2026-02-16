# cryptocurrency-wallet
Developed a decentralized Cryptocurrency Wallet to store, send, and receive Ethereum (ETH) on the Ethereum Blockchain.
# 💰 Ethereum Cryptocurrency Wallet

A decentralized Cryptocurrency Wallet built on the Ethereum blockchain that allows users to securely store, send, and receive ETH. The project demonstrates smart contract development, blockchain interaction, and secure transaction handling using Solidity and Ethereum development tools.

---

## 🚀 Features

- Store, send, and receive Ethereum (ETH)
- Smart contract-based transaction management
- Secure transaction validation using require() statements
- MetaMask wallet integration for authentication and transaction signing
- Local blockchain testing using Ganache
- Smart contract deployment and testing via Remix IDE

---

## 🛠️ Technologies Used

- Solidity
- Ethereum Blockchain
- Remix IDE
- Ganache
- MetaMask
- Web3.js (if used for frontend interaction)

---

## 📂 Project Structure

Crypto-Wallet/
│── contracts/
│ └── Wallet.sol
│── migrations/ (if applicable)
│── test/ (if applicable)
│── README.md
## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/crypto-wallet.git
cd crypto-wallet
2️⃣ Setup Ganache
Install and open Ganache.

Create a new workspace.

Copy RPC Server URL.

3️⃣ Deploy Smart Contract
Open Remix IDE.

Paste the Wallet.sol code.

Compile using Solidity compiler.

Connect Remix to Ganache (Injected Provider / Web3).

Deploy the contract.

4️⃣ Connect MetaMask
Connect MetaMask to Ganache network.

Import test account using private key from Ganache.

Interact with the deployed contract.

🔐 Security Features
Input validation using require()

Transaction verification before execution

Controlled fund transfer logic

Protection against unauthorized access

🧪 Testing
Tested ETH transfer functionality on Ganache local blockchain.

Verified transaction logs and balances after each operation.

Ensured proper error handling for invalid transactions.

📌 Future Improvements
Add frontend UI (React.js)

Implement event logging

Improve gas optimization

Add multi-user support

Deploy on Ethereum testnet (Goerli / Sepolia)
👨‍💻 Author
Aditya Sharma
