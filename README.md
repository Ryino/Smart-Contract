  SimpleStorage Smart Contract
This repository contains a simple Ethereum smart contract named SimpleStorage. The contract allows you to store and retrieve an unsigned integer value on the Ethereum blockchain.

The contract is like a digital safe deposit box that lets you store and retrieve a single number whenever you need it.

  Contract Details
Contract Name: SimpleStorage
Solidity Version: ^0.8.26
License: MIT License (SPDX-License-Identifier)
  Functions
          set
Description: Sets the stored value to a specified unsigned integer.
Visibility: Public
Parameters: uint256 x (unsigned integer value)
Usage: set(uint256 x)
          get
Description: Retrieves the currently stored unsigned integer value.
Visibility: Public
Returns: uint256 (unsigned integer value)
Usage: get()
