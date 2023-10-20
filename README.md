# Smart Contract with require(), assert(), and revert() Statements

This repository contains a simple Ethereum smart contract written in Solidity that demonstrates the usage of `require()`, `assert()`, and `revert()` statements.

## Contract Details

### Functionsanderrorscontract

- The `Functionsanderrorscontract` is a basic smart contract that showcases the functionality of `require()`, `assert()`, and `revert()` statements.

- It includes the following functions:

    - `setOwner(address newOwner)`: Allows the owner to change the contract owner.

    - `assertExample(uint256 x, uint256 y)`: Demonstrates the usage of `assert()`. It checks if `x` is greater than `y`.

    - `requireExample(uint256 x, uint256 y)`: Demonstrates the usage of `require()`. It checks if `x` is greater than `y`.

    - `revertExample(uint256 x, uint256 y)`: Demonstrates the usage of `revert()`. It explicitly reverts the transaction if `x` is not greater than `y`.
