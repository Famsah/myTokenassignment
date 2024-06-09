# MyToken Solidity Contract 

This contract provides a fundamental framework for managing a custom token, demonstrating essential conncepts in Solidity such as state variables, mappings, and basic function implementation.

## Description

My token is a simple Ethereum smart contract written in solidity. It allows you to create a custom token named "Famsah" with the abbreviation "FMSH". The contract include the functionality to mint (create) and burn (destroy) tokens.

### Features

Public variables to store token details.
Mapping to track balancess of addresses.
Mint function to create new tokens.
Burn function to destroy tokens with balance checks.

## How to Execute this program in Remix IDE
### Prerequisites

A web browser with accesss to internet.
MetaMask or another Ethereum wallet to interact with the contract on a test network.

## Steps
Open Remix IDE

Navigate to Remix IDE in your web browser.
Create a New File

In the File Explorer pane, click the "+" icon to create a new file.
Name your file MyToken.sol.
Copy and Paste the Contract Code from this link: 
https://github.com/Famsah/myTokenassignment/blob/main/myTokenassignment
Compile the Contract

Click on the "Solidity Compiler" tab in the left sidebar.
Select the Solidity version 0.8.18 from the dropdown menu.
Click the "Compile MyToken.sol" button.
Deploy the Contract

Click on the "Deploy & Run Transactions" tab in the left sidebar.
Ensure that "JavaScript VM" is selected in the Environment dropdown (for local testing).
Click the "Deploy" button.
Interact with the Contract

After deployment, the contract's functions (mint and burn) and public variables (tokenName, tokenAbbrv, totalSupply) will appear in the "Deployed Contracts" section.
You can now call these functions and view variables directly from the Remix IDE.

## Aurthor

Farhat Mbarak Saleh

## License

This project is licensed under the MIT license - see the LICENSE.md file for details.

