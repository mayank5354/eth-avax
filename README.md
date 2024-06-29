# Solidity Smart Contract Example

## Overview

This project demonstrates the use of Solidity's `require()`, `assert()`, and `revert()` statements in a smart contract. The contract allows users to deposit and withdraw funds while ensuring safe operations.

## Smart Contract Functions

- **deposit(uint256 amount)**: Allows users to deposit a specified amount. Requires the amount to be greater than zero.
- **withdraw(uint256 amount)**: Allows users to withdraw a specified amount. Requires that the balance is sufficient.
- **checkBalance(uint256 expectedBalance)**: Asserts that the input value equals the current balance.
- **safeWithdraw(uint256 amount)**: Attempts to withdraw an amount and reverts if the amount exceeds the balance.

## How to Use

1. Clone the repository.
2. Deploy the smart contract using a Solidity-compatible environment (e.g., Remix, Hardhat).
3. Interact with the contract using the provided functions..

## Purpose

This project is designed to help developers understand how to use error handling statements in Solidity to ensure smart contract security.
