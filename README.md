# SOLIDITY_PROJECT
Overview
This Solidity smart contract represents a simple coin token with the ability to mint and burn tokens.

Requirements
The contract includes public variables to store essential details about the coin, such as Token Name, Token Abbreviation, and Total Supply.

Utilizes a mapping of addresses to balances (mapping(address => uint)).

Features a mint function that increases the total supply and the balance of the sender's address by a specified value.

Implements a burn function to destroy tokens by deducting the value from both the total supply and the balance of the sender's address.

The burn function includes conditionals to ensure that the balance of the sender is greater than or equal to the specified amount to be burned.

Solidity Version
This contract is written in Solidity version 0.8.18.

Usage
Minting Tokens
To mint new tokens, call the mint function with the recipient's address and the desired value as parameters.

Credits
Special thanks to METACRAFTERS.

