<h1 align="center">💰 Foundry Fund Me 💰</h1>

<p align="center">
  A decentralized crowdfunding smart contract built with 🧱 <a href="https://book.getfoundry.sh/">Foundry</a> and 🪙 <a href="https://chain.link/">Chainlink</a> price feeds.
  <br />
  <b>Fund with ETH ➕ Withdraw in ETH 💸 Or any other Native CryptoCurrency🪙</b>
  <br /><br />
  <img src="https://img.shields.io/badge/Build%20with-Foundry-4B275F?style=for-the-badge&logo=ethereum" />
  <img src="https://img.shields.io/badge/Smart%20Contract-Solidity-363636?style=for-the-badge&logo=solidity" />
</p>

---

## 📜 Overview

This project demonstrates a minimal, production-style funding smart contract using **Foundry**, where:

- 🌐 Users can fund the contract in ETH.
- 📉 A minimum USD value is enforced using **Chainlink** price feeds.
- 👑 Only the **owner** can withdraw funds.
- 🧾 All contributors and their amounts are recorded transparently on-chain.

---

## 🚀 Features

✨ Clean and powerful smart contract with:
- ✅ **Minimum USD funding enforcement**
- 🔐 **Owner-only withdrawal**
- 📊 **Trackable funders**
- ⛽️ **Gas-efficient logic**
- ⚙️ **Fully tested with Foundry**

---

## 🧰 Getting Started

### 🧾 Prerequisites

Make sure you have the following installed:

- 🟣 [Foundry](https://book.getfoundry.sh/getting-started/installation)
- 🟡 [Git](https://git-scm.com/downloads)

## Check your versions:

```bash
forge --version
git --version\
```
---
## 📦 Installation
Clone the project and install dependencies:
```
git clone https://github.com/krrish1611/Foundry-Fund-Me.git
cd Foundry-Fund-Me
forge install
```
---
 
## 🔧 Usage

### 🏗️ Build

```shell
$ forge build
```

### ✅ Test

```shell
$ forge test
```

### 🧹	Format

```shell
$ forge fmt
```

### ⛽️ Gas Snapshots

```shell
$ forge snapshot
```

### 🔨 Anvil

```shell
$ anvil
```

### 🚀 Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### 🎯 Cast

```shell
$ cast <subcommand>
```

### 🆘 Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```

## 📝 Replace 
```
<your_private_key> 
```
with your Anvil private key.

---
##  🗂️ Project Structure

### 📦 Foundry-Fund-Me
#### ├── 📁 lib/               → External dependencies
#### ├── 📁 script/            → Deployment & interaction scripts
#### ├── 📁 src/               → Core smart contracts
#### │   └── 📄 FundMe.sol     → Main contract
#### ├── 📁 test/              → Test cases
#### ├── 📄 foundry.toml       → Foundry config
#### └── 📄 README.md          → You're here! 
---
## 📜 License

#### 🧾 Licensed under the MIT License
---
## ✨ Author

### **Krrish Sah**  
Feel free to ⭐ the repo, open issues, or submit pull requests to contribute!
#### 💻 Developer | 🤖 AI Enthusiast | 🇮🇳 From India
---
