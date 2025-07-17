# 🚗 Peer-to-Peer Carpooling using Blockchain

## 📄 Overview
This project decentralizes the traditional carpooling system by leveraging **blockchain technology**.  
It uses **Ethereum** for transactions, ensuring **security, transparency, and immutability**.

Users can book and offer rides directly without intermediaries through **smart contracts**, making the system trustworthy and transparent.

---

## ✨ Features

- 🔗 **Decentralized Carpooling System**  
- 🛡️ **Secure & Transparent Transactions via Ethereum**  
- 📃 **Smart Contracts for Managing Carpool Data**  
- 🌐 **Web3.js Integration** for Blockchain Interaction  
- 🧰 **Ganache Setup** for Local Blockchain Testing  
- 🔑 **User Authentication** with Login & Registration Panels  
- 📊 **User Dashboard** for Ride Management  

---

## 🛠️ Technologies Used

| Technology    | Purpose                          |
|---------------|----------------------------------|
| **Solidity**  | Smart Contract Programming       |
| **Ethereum**  | Blockchain Platform              |
| **Ganache**   | Local Blockchain for Testing     |
| **Remix IDE** | Smart Contract Development       |
| **Web3.js**   | Ethereum Blockchain Interaction  |
| **HTML/CSS/JS** | Frontend Development           |

---

## 🚀 How to Run the Project

### 1️⃣ Smart Contract Deployment (Remix IDE)

- Open **[Remix IDE](https://remix.ethereum.org/)** in your browser.
- Create a new workspace named **`CAR`**.
- In **Contracts**, create two files:
  - `DataBank.sol`
  - `CarpoolingContract.sol`
- Copy and paste the smart contract code from this repository.
- Compile using **Solidity Compiler**:
  - Select **Advanced Configuration**.
  - Set **EVM Version** to **Paris**.
  - Click **Compile**.

---

### 2️⃣ Ganache Setup

- Download **Ganache**: [Ganache Download](https://trufflesuite.com/ganache/)
- After installation, click **Quick Start**.
- Ganache will run on **port 7545**.

---

### 3️⃣ Project Setup Locally

- Create a folder named **`CARPOOLING`**.
- Open the terminal in the project folder:

```bash
npm install --save web3
npm install web3.js-browser
```
- Download all code files from this repository into your project folder.

### 4️⃣ Deploy Smart Contracts

- In **Remix IDE**, go to **DEPLOY & RUN TRANSACTIONS**.
- Set **ENVIRONMENT** to **Custom-External Http Provider**.
- Change the port from **8545** to **7545** (to match Ganache).
- Click **Deploy** to deploy the contracts to your local blockchain.

---

### 5️⃣ Connect Web3.js

- From **Remix IDE > Solidity Compiler**, copy the **ABI** code.
- Paste the ABI into `web3connection.js`.
- From **DEPLOY & RUN TRANSACTIONS**, copy the **Deployed Contract Address**.
- Paste the contract address into `web3connection.js`.

---

### 6️⃣ Run the Web Application

- Open the project in **VS Code**.
- Use the **Live Server** extension and click on **Go Live**.
- Open your browser and go to:
```bash
http://localhost:5500
```

## 📂 Project Structure
```bash
CARPOOLING/
├── contracts/
│ ├── DataBank.sol
│ └── CarpoolingContract.sol
├── web/
│ ├── index.html
│ ├── login.html
│ ├── dashboard.html
│ └── web3connection.js
├── README.md
└── package.json
```

---

## 📸 Screenshots

| Feature | Screenshot |
|----------|-----------|
| **Login Panel** | ![Login](./screenshots/login.png) |
| **New User Registration** | ![New User](./screenshots/new_user.png) |
| **User Dashboard** | ![Dashboard](./screenshots/dashboard.png) |

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🤝 Contributing

Pull requests are welcome.  
For major changes, please open an issue first to discuss what you would like to change.

---

## 💬 Contact

For queries or collaboration:  
**Aishwarya** - [aishwarya.anand1125@gmail.com]  


