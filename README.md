# Genesis Token: A Solidity ERC20 Token Implementation
This Solidity contract implements the ERC20 token standard, creating a fungible token named "Genesis Token" (GNT) with the following characteristics:

### Symbol: GNT
### Name: Genesis Token
### Decimals: 9
### Total Supply: 6,000,005,000,000 (Fixed at deployment)
### Author: Khizar Bakhtiar
### License: MIT
This contract utilizes the SafeMath library for secure arithmetic operations on the token balance.



# Features:
### Transfer:
Allows users to transfer tokens to other addresses.
### Approve: 
Enables users to grant permission to a spender to transfer tokens on their behalf.
### TransferFrom:
Allows a spender to transfer tokens from an approved owner's account.
### Total Supply: 
Provides a public view function to retrieve the total supply of GNT tokens.
### Balance Of: 
Provides a public view function to retrieve the GNT token balance of a specific address.
### Allowance: 
Provides a public view function to retrieve the remaining allowance granted by an owner to a spender.



# Fallback Function:
The contract includes a fallback function that rejects any Ether sent directly to the contract's address. This ensures the contract only operates on GNT tokens.



# Deployment:
Compile the contract using a Solidity compiler (e.g., solc).
Deploy the contract to your preferred blockchain platform (e.g., Ethereum).
Usage:
Interact with the deployed contract functions using a web3 library or wallet that supports interacting with smart contracts.



# Security Considerations:
This is a basic ERC20 implementation and might require further security audits for production environments.
Always handle user input and external calls securely to prevent vulnerabilities.



# Further Development:
This contract can be extended to include additional functionalities like burning tokens, minting new tokens (if governance allows), or integrating with decentralized exchanges.
