E# HelloWorld Smart Contract

This Solidity smart contract, named `HelloWorld`, showcases the use of `require()`, `assert()`, and `revert()` statements to add two to a given input.

## License

This code is released under the MIT License. See [LICENSE](LICENSE) for more information.

## Smart Contract Details

- Solidity Version: 0.8.17
- SPDX-License-Identifier: MIT

## Description

The `HelloWorld` smart contract has three functions, each demonstrating a different way to handle conditions:

1. **`addTwoRequire(uint x)`**

   - Description: Uses the `require()` statement to ensure that the input `x` must be equal to 2. If the condition is not met, the function reverts with the specified error message.
   - Returns: The sum of `x` and 2.

2. **`addTwoAssert(uint x)`**

   - Description: Uses the `assert()` statement to check if the input `x` is equal to 2. If the condition is not met, the function reverts.
   - Returns: The sum of `x` and 2.

3. **`addTwoRevert(uint x)`**

   - Description: Uses the `revert()` statement to revert the transaction if the input `x` is not equal to 2.
   - Returns: The sum of `x` and 2.

4. Deploy this smart contract to the Ethereum blockchain using a development environment like Remix or Truffle.

5. Call the `addTwoRequire(uint x)`, `addTwoAssert(uint x)`, and `addTwoRevert(uint x)` functions with different values of `x` to observe the behavior of `require()`, `assert()`, and `revert()`.

Here is an example of how to interact with the contract using the Remix IDE:

1. Deploy the contract.

2. Call the `addTwoRequire(uint x)` function with different values of `x`. Observe how it reverts if `x` is not equal to 2.

3. Call the `addTwoAssert(uint x)` function with different values of `x`. Observe how it reverts if `x` is not equal to 2.
