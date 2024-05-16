# DegenToken

DegenToken is a token contract built on the Ethereum blockchain using Solidity. It is an ERC20 token with additional functionalities. 
The contract is written in Solidity and it uses the OpenZeppelin library for the ERC20 and Ownable contracts. The contract allows for the minting of new tokens, which can only be done by the owner of the contract. 
This is done through the mintDGN function which takes an address and an amount as parameters.

## Features

1. **Minting new tokens**: The platform can create new tokens and distribute them to players as rewards. Only the owner can mint tokens.
2. **Transferring tokens**: Players can transfer their tokens to others.
3. **Redeeming tokens**: Players can redeem their tokens for items in the in-game store.
4. **Checking token balance**: Players can check their token balance at any time.
5. **Burning tokens**: Anyone can burn tokens that they own and are no longer needed.

## Functions

- `mintDGN(address _to, uint256 _amount)`: This function allows the owner to mint new tokens.
- `transferDGN(address _to, uint256 _amount)`: This function allows players to transfer their tokens to others.
- `showShopItems()`: This function shows the items available in the in-game store.
- `redeemDGN(uint256 _item)`: This function allows players to redeem their tokens for items in the in-game store.
- `burnDGN(uint256 _amount)`: This function allows anyone to burn tokens that they own and are no longer needed.
- `getBalance()`: This function allows players to check their token balance at any time.

## Conclusion 

Overall, this contract provides a robust and flexible framework for a token that can be used in a game or similar platform. 
It provides all the necessary functions for managing the token and interacting with it in various ways. 
The use of the OpenZeppelin library ensures that the contract is secure and follows best practices. 
The contract is well-documented with comments explaining the purpose of each function, making it easy to understand and modify.

## Author 

https://academy.metacrafters.io/profile

## License

This project is licensed under the MIT License.
