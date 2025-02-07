# assignment4.

**Team Members: Kabylkhanova Nuray, Tlegenova Kamilya, Baibossyn Arlen**

## Overview

This project implements an ERC20 token **AIMarketplace** named **AITU_SE2315_AlmenAlnur** using Solidity. It includes key features such as:
- **User Authentication and Wallet Integration**
- **Token Balance Display**
- **AI Model Listings**
- **Purchase Flow**

The smart contract is developed and tested using Solidity, Hardhat, VS Code, and Remix IDE (to obtain the ABI and contract address).

## Features
- **User Authentication and Wallet Integration**
- **Token Balance Display**
- **AI Model Listings**
- **Purchase Flow**

## Project Structure
```plaintext
📦 AITU_SE2315_AlmenAlnur
 ┣ 📂 contracts
 ┃ ┣ 📜 AITU_SE2315_AlmenAlnur.sol  # ERC20 Token Contract
 ┃ ┣ 📜 AIMarketplace.sol  # Marketplace Contract
 ┣ 📂 test
 ┃ ┣ 📜 AITU_SE2315_AlmenAlnur.js  # Tests for Initial Contract
 ┃ ┣ 📜 AITU_SE2315_AlmenAlnur_Modified.js  # Tests for Modified Contract
 ┣ 📂 frontend
 ┃ ┣ 📜 app.js
 ┃ ┣ 📜 index.html
 ┃ ┣ 📜 style.css
 ┣ 📜 hardhat.config.js  # Hardhat Configuration
 ┣ 📜 package.json  # Dependencies
 ┣ 📜 README.md  # Project Documentation
 ┗ 📜 LICENSE  # MIT License
```

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repo-url>
   cd AITU_SE2315_AlmenAlnur
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Install web3**:
   ```bash
   npm install web3
   ```

4. **Compile the Smart Contract**:
   ```bash
   npx hardhat compile
   ```

5. **Run test cases**:
   ```bash
   npx hardhat test
   ```

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## References
1. [Connecting to Metamask with Vanilla JS](https://docs.web3js.org/guides/dapps/metamask-vanilla/)
2. [OpenZeppelin Wizard](https://wizard.openzeppelin.com/)

