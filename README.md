# MyToken Project

A simple ERC20 token implemented using Solidity and the OpenZeppelin library.

## Description

This project demonstrates the creation of an ERC20 token with basic minting, burning, and transferring functionalities. The token is implemented using Solidity and leverages the OpenZeppelin library for secure and community-reviewed code. This project is intended to serve as a foundational example for anyone interested in creating their own ERC20 token on the Ethereum blockchain.

## Getting Started

### Installing

1. **Copy the Smart Contract:**
   - Copy the ERC20 token smart contract code into the Remix IDE.

2. **Compile:**
   - Open the Remix IDE and paste your smart contract code.
   - Ensure that you have the correct Solidity compiler version selected.
   - Click on the "Compile" button to compile the contract.

3. **Deploy:**
   - Switch to the "Deploy & Run Transactions" tab in Remix.
   - Select the appropriate environment (e.g., Injected Web3, JavaScript VM, or a specific network like Ropsten).
   - Deploy the contract by clicking the "Deploy" button.

### Executing Program

1. **Minting Tokens:**
   - Call the `mint` function with the desired amount of tokens to create.

2. **Burning Tokens:**
   - Call the `burn` function with the amount of tokens to be destroyed.

3. **Transferring Tokens:**
   - Use the `transfer` function to send tokens to another address.

### Installing

* Copy the Smart Contact content into the remix
* Compile and Deploy 

### Code Example

```solidity
// Example of minting tokens
myToken.mint(1000);

// Example of burning tokens
myToken.burn(500);

// Example of transferring tokens
myToken.transfer(recipientAddress, 200);
```

### Help
For common problems or issues, check the following:

Ensure you have the correct Solidity version specified in your hardhat.config.js file.
Ensure your Ethereum client (like Ganache or Infura) runs and configures correctly.

### Troubleshooting Commands
npx hardhat help

### Author
Jose Roberto Kam

