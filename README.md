# Resellio - Smart Contract ERC-721 on BSC

Resellio is a decentralized platform that uses blockchain technology to enable buying and selling of digital assets such as game consoles, digital tickets, and collectibles. This repository contains the code for the Resellio smart contract, built on the Binance Smart Chain using the ERC-721 standard for non-fungible tokens (NFTs).

## Prerequisites

- Node.js
- Truffle
- Ganache

## Installation

1. Clone the repository
2. Run `npm install` to install dependencies
3. Run Ganache to set up a local blockchain
4. Compile the contract by running `truffle compile`
5. Migrate the contract to the blockchain by running `truffle migrate`

## Usage

The smart contract includes the following functions:

- `createNFT`: Allows a user to create a new NFT representing a digital asset.
- `buyNFT`: Allows a user to buy an NFT from another user.
- `sellNFT`: Allows a user to sell an NFT they own.
- `bidOnNFT`: Allows a user to place a bid on an NFT.
- `acceptBid`: Allows a user to accept a bid on an NFT and sell it to the bidder.

## Testing

Run `truffle test` to run the tests for the contract.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact the Resellio team at littleplantstudio@gmail.com.
