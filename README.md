# 🗳️ Decentralized Voting System Using Blockchain

This project implements a **secure, transparent, and tamper-proof voting system** using **Ethereum Blockchain**, **Solidity**, **Truffle**, **Ganache**, and **MetaMask**. It replaces centralized voting with a decentralized, immutable, and fully verifiable smart-contract–based process.

---

## 🚀 Overview

Traditional voting systems suffer from:
- Centralized databases (single point of failure)
- Vulnerability to tampering & unauthorized access
- Lack of transparency & public trust
- Manual, slow verification processes
- Difficulty ensuring both anonymity & security

This blockchain-based system solves all of the above through:
- **Transparency** – All votes are verifiable
- **Security** – Cryptographic protection prevents manipulation
- **Immutability** – Votes cannot be edited or deleted
- **Decentralization** – No central authority controls results
- **Auditability** – Real-time and trustless verification

---

## 🧱 System Architecture

- **User (Voter)** signs transactions via MetaMask  
- **Frontend DApp** interacts with the smart contract  
- **Truffle** compiles & migrates the contract  
- **Ganache** acts as a local Ethereum blockchain  
- **Voting.sol Smart Contract** manages candidates, votes & results  

---

## 👥 Stakeholders

| Stakeholder | Responsibility |
|------------|----------------|
| Election Commission | Deploy contract, set voting dates, add candidates |
| Voters | Authenticate & cast secure votes using MetaMask |
| Candidates | Participate in the election; vote count updated automatically |
| Auditors | Verify results via blockchain ledger |

---

## ⚙️ Installation & Setup

### 1️⃣ Install Prerequisites
- Node.js and npm  
- Truffle  
  ```bash
  npm install -g truffle
  ```
- Ganache (GUI or CLI)  
- MetaMask browser extension  

---

### 2️⃣ Clone the Repository
```bash
git clone <your-repository-url>
cd decentralized-voting-system
```

---

### 3️⃣ Install Dependencies
```bash
npm install
```

---

### 4️⃣ Start Ganache
Open Ganache GUI  
**OR**
```bash
ganache-cli
```

---

### 5️⃣ Configure Truffle
Edit `truffle-config.js`:
```js
development: {
  host: "127.0.0.1",
  port: 7545,
  network_id: "*"
}
```

---

### 6️⃣ Compile & Deploy Smart Contracts
```bash
truffle compile
truffle migrate --reset
```

---

### 7️⃣ Connect MetaMask
- Add a Custom RPC matching Ganache  
- Import Ganache accounts using private keys  
- Approve transaction requests during voting  

---

### 8️⃣ Start the Frontend
For plain HTML/JS:
```bash
Open index.html with Live Server
```

For React setups:
```bash
npm start
```

---

## 🎯 Features

- Add candidates  
- Cast votes securely  
- Prevent double voting  
- Set voting start and end dates  
- Live vote count display  
- Winner announced via `getWinner()`  
- Full MetaMask transaction flow  
- Ganache-backed local blockchain ledger  

---

## 🧪 Experimental Demonstrations

- Contract deployment with MetaMask  
- Adding candidates  
- Casting votes  
- Viewing candidate vote counts  
- Displaying final winner  
- Working DApp interface for real-time voting  

---

## 🏁 Conclusion

This project:
- Implements a **secure blockchain-based voting mechanism**  
- Ensures **immutability, decentralization, and transparency**  
- Uses **MetaMask authentication** for trustless participation  
- Removes intermediaries for a **tamper-proof voting process**  
- Demonstrates the potential of blockchain for **future e-governance**  

---

## 🔗 Developer
**Jatin Navani**  
🌐 https://jatinnavani.in
