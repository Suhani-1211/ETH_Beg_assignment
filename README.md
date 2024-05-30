# ETH_Beg_assignment
Creating a token
# MyToken Contract
This Solidity contract implements a basic token system with functionalities to mint and burn tokens.
## Requirements
1. The contract has public variables storing details about the token, including its name, abbreviation, and total supply.
2. It includes a mapping of addresses to token balances.
3. Provides a `mint` function that increases the total supply by a specified value and increases the balance of a given address by that amount.
4. Implements a `burn` function that decreases the total supply and the balance of a given address by a specified value, with appropriate checks to ensure the sender has enough balance to burn.
5. The `burn` function includes conditionals to check if the sender's balance is sufficient for burning.
## Usage
1. Deploy the contract to a supported Ethereum Virtual Machine (EVM) environment.
2. Interact with the contract through transactions to mint or burn tokens.
3. Use the provided functions to manage token supply and balances.
## Solidity Version
This contract is written in Solidity version 0.8.18.
## SPDX-License-Identifier
This contract is licensed under the MIT License. See the SPDX-License-Identifier at the top of the Solidity file for more details.
## Contract Address
Once deployed, the contract will have a unique address on the Ethereum blockchain, allowing users to interact with its functions.
