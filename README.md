# Ayush Token Smart Contract

Ayush Token (AJ) is an ERC-20 token built on the Ethereum blockchain. It provides functionalities for managing token transfers, prizes, and burning tokens.

## Features

- Minting: The owner of the contract can mint new tokens.
- Transfers: Users can transfer tokens to other addresses.
- Prize System: Users can redeem prizes using their tokens.
- Burning: Users can burn their tokens to reduce the total supply.

## Prizes

The contract supports a prize system with different prize levels. Each prize has a specific cost in tokens associated with it. Users can redeem prizes by spending the required amount of tokens.

Prize Costs:
- Prize 1: 1000 AJ
- Prize 2: 500 AJ
- Prize 3: 200 AJ
- Prize 4: 100 AJ

## Usage

1. Deploy the contract to the Ethereum blockchain.
2. The contract owner can mint new tokens using the `mint` function.
3. Users can transfer tokens to other addresses using the `TransferToken` function.
4. Users can redeem prizes using the `RedeemPrize` function by specifying the prize ID.
5. Users can burn their tokens using the `burnToken` function.
6. The `getTokenBalance` function allows users to check their token balance.

## Deployment

1. Make sure you have the required versions of Solidity and dependencies installed.
2. Deploy the contract to the Ethereum network of your choice.
3. After deployment, the contract owner can add prize costs using the `AddPrizeCost` function.

## Disclaimer

This smart contract is provided as-is and may not have undergone a thorough security audit. Use it at your own risk. Always exercise caution when working with smart contracts and handling tokens.

## License

This smart contract is licensed under the MIT License.
