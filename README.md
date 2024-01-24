# advanced_avax1

This is a Solidity smart contract that implements a basic vault to deposit and withdraw ERC-20 tokens.

## Overview

The contract includes the following functionalities:

- Deposit: Users can deposit ERC-20 tokens into the vault and receive shares in return.
- Withdraw: Users can withdraw their tokens by providing the corresponding shares.

## Smart Contract Details

### `IERC20` Interface

This contract relies on the ERC-20 interface for interaction with the token. The interface includes standard functions like `totalSupply`, `balanceOf`, `transfer`, `allowance`, `approve`, and `transferFrom`.

### `Vault` Contract

- `token`: An immutable variable storing the ERC-20 token address.
- `totalSupply`: Tracks the total supply of shares in the vault.
- `balanceOf`: Maps addresses to their corresponding share balances.
