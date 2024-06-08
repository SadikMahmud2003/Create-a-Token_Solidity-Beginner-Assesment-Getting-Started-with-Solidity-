# Metacrafters Project: Create a Token (Getting Started with Solidity)

## Overview

This is a simple "Token" program written in solidity that shows the practical steps to those new to Solidity and interested in understanding its basic syntax and functionality. It demonstrates the creation of a basic Ethereum token named "Igbani" with the symbol "IGN." The contract allows for the minting (creation) and burning (destruction) of tokens, while also keeping track of token balances for Ethereum addresses. The initial total supply of tokens is set to 0.

## Getting Started

To run and interact with this program, you can use Remix, an online Solidity Integrated Development Environment (IDE). Here are the steps to get started:

### Execution Instructions
Step-by-step instructions for deploying and interacting with a Solidity contract on Remix are clear and comprehensive. Here's a refined version with some minor tweaks for clarity:

1. **Go to the Remix website**:
   - Open [https://remix.ethereum.org/](https://remix.ethereum.org/).

2. **Create a new file**:
   - Click on the "+" icon in the left-hand sidebar.
   - Save the file with a `.sol` extension (e.g., `BifrostToken.sol`).

3. **Copy and paste the provided Solidity code**:
   - Go to the provided link: [https://github.com/SadikMahmud2003/Create-a-Token_Solidity-Beginner-Assesment-Getting-Started-with-Solidity-](https://github.com/SadikMahmud2003/Create-a-Token_Solidity-Beginner-Assesment-Getting-Started-with-Solidity-)
   - Copy the Solidity code from the GitHub page.
   - Paste the copied code into the newly created file in Remix.

4. **Compile the code**:
   - Click on the "Solidity Compiler" tab in the left-hand sidebar.
   - Ensure the "Compiler" option is set to "0.8.18" (or another compatible version).
   - Click on the "Compile BifrostToken.sol" button.

5. **Deploy the contract**:
   - Click on the "Deploy & Run Transactions" tab in the left-hand sidebar.
   - Select the "BifrostToken" contract from the dropdown menu.
   - Click on the "Deploy" button.

6. **Interact with the contract**:
   - **Mint Tokens**:
     - In the deployed contract section, click on the "BifrostToken" contract to expand it.
     - Click on the down caret icon on the "mint" function button.
     - Input the required variables (`_to` address and `_value` amount).
     - Click on the "transact" button to execute the minting function.

   - **Burn Tokens**:
     - Repeat the process above for the "burn" function.

   - **Read Balances and Public Variables**:
     - To check the balance of a specific Ethereum address, paste the address into the text field next to the `balances` function and click on the "balances" button to retrieve the balance.
     - To view the `tokenName`, `tokenAbbrv`, and `totalSupply`, click on their respective buttons to display their values.
   

## Author

- Sadik Mahmud
  - GitHub: https://github.com/SadikMahmud2003
  - LinkedIn: www.linkedin.com/in/sadik-mahmud-873635256

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---
