# 🚀 Foundry-FundMe

## 📌 Overview
Foundry-FundMe is a Solidity smart contract project built with [Foundry](https://book.getfoundry.sh/), a fast and portable toolkit for Ethereum development. This project implements a simple crowdfunding contract where users can fund a contract, and the owner can withdraw funds.

## ✨ Features
- 💰 Allows users to fund the contract.
- 🔑 Owner can withdraw collected funds.
- 🛠 Uses Foundry for testing and deployment.
- 📜 Includes scripts for automation.

## 🔧 Prerequisites
Ensure you have the following installed:
- ⚡ [Foundry](https://book.getfoundry.sh/getting-started/installation.html)
- 🖥 Node.js & npm (for additional tooling, if needed)
- 💳 A wallet with test ETH (for deployment and interaction)

## 📥 Installation
Clone the repository and install dependencies:
```sh
git clone https://github.com/hiteshdhanik/Foundry-FundMe.git
cd Foundry-FundMe
forge install
``` 

## Usage
### 🏗  Build the project
```
forge build
```

## ✅ Run tests
```
forge test

```

## 🚢 Deploy contract

```
forge script script/DeployFundMe.s.sol --rpc-url <your_rpc_url> --private-key <your_private_key>
```


## 🔗 Interact with the contract
You can use Foundry's `cast` tool to interact with deployed contracts.
```
cast send <contract_address> --rpc-url <your_rpc_url> --private-key <your_private_key> --value 1ether
```

## 📂 Directory Structure
```
Foundry-FundMe/
│── 📁 src/            # Solidity contracts
│── 📁 script/         # Deployment and interaction scripts
│── 📁 test/           # Test cases for contracts
│── 📁 lib/            # External dependencies
│── 📝 foundry.toml    # Foundry configuration
│── 🛠 Makefile        # Build and test commands
```

## 📜 License
This project is licensed under the MIT License.

## 🙌 Acknowledgments
📖 Foundry
💡 Solidity Community

## 🚀 Happy Building! 🎉