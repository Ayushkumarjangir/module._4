# Degen Gaming Token (DGT) Smart Contract

Degen Gaming Token (DGT) is an ERC20 token deployed on the Avalanche network for the Degen Gaming platform. The smart contract provides functionality for minting new tokens, transferring tokens, redeeming tokens for in-game prizes, checking token balance, and burning tokens.

## Prerequisites

Before deploying and using the Degen Gaming Token smart contract, ensure you have the following prerequisites:

1. An Avalanche wallet with AVAX tokens for deployment and transaction fees.
2. Basic understanding of smart contracts and the Ethereum Virtual Machine (EVM).
3. Development environment with Solidity compiler, such as Remix or Truffle.

## Deployment

Follow these steps to deploy the Degen Gaming Token smart contract on the Avalanche network:

1. Clone this repository or copy the smart contract code from [DegenGamingToken.sol](contracts/DegenGamingToken.sol).

2. Open the smart contract file and modify the constructor parameters:
   - `_name`: Token name.
   - `_symbol`: Token symbol.
   - `_initialSupply`: Initial supply of tokens to mint.

3. Deploy the smart contract using your chosen development environment (Remix, Truffle, etc.). Make sure to connect to the Avalanche network and provide the necessary gas for deployment.

4. After deployment, note down the contract address for interacting with the token.

## Usage

The Degen Gaming Token smart contract can be used as follows:

- **Minting Tokens**:
  - Only the owner of the contract can mint new tokens.
  - Use the `mint` function, providing the recipient's address and the amount of tokens to mint.

- **Transferring Tokens**:
  - Players can transfer tokens to each other using standard ERC20 transfer functions.

- **Redeeming Tokens**:
  - Players can redeem tokens for in-game prizes using the `redeem` function.
  - The cost of the prize is deducted from the player's balance and the total supply.
  
- **Checking Token Balance**:
  - Players can check their token balance using the standard ERC20 `balanceOf` function.

- **Burning Tokens**:
  - Any token holder can burn their own tokens using the `burn` function.

## Contract Address

The Degen Gaming Token smart contract is deployed at the following address on the Avalanche network:

[Contract Address]

## Contributing

Contributions to this smart contract are welcome. If you find any issues or want to suggest improvements, please open an issue or create a pull request in this repository.

## License

This smart contract is licensed under the [MIT License](LICENSE).
