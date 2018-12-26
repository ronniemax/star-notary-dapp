# Project 5 - Decentralized Star Notary

For this project, you will create a DApp by adding functionality to your smart contract and deploy it on the public testnet. To do so, you'll employ your blockchain identity to secure digital assets on the Ethereum platform using a smart contract. You will get to practice your knowledge of the basics of Solidity.

Previously, you learned to create your own private blockchain web service. In this course, you migrated your private blockchain functionality to a smart contract and created your own ERC721 non-fungible token contract!


## Getting Started

1. Run `npm install` to install dependencies from package.json

2. Run http-server and open browser and point to http://127.0.0.1:8080

3. This will load  index.html on your browser

4. Make sure metamask is up and running on the same browser and points to Rinkeby network.



## Prerequisites

- Your browser must have Metamask extension installed with rinkeby account active and having some ethers.


- NPM Modules:

```
- "truffle-hdwallet-provider": "0.0.6"

- "http-server": "0.11.1" (for local browser testing)
```



## Running the tests

1. Start a local ethereum client (ganache)

2. cd to `smart_contracts` directory

3. Run command:  `truffle test test/StarNotaryTest.js`



## Contract Deployed on Rinkeby Test Network

#### Smart Contract Deployed To Rinkeby

Transaction: https://rinkeby.etherscan.io/tx/0x2a71bbc33797fabdba0dd06d2df53d89212ded5cc15d910afca4fb34b941aba3

Transaction Hash: 0x2a71bbc33797fabdba0dd06d2df53d89212ded5cc15d910afca4fb34b941aba3

Contract Address: 0x44A10424daf039CCc4F2E795Fb3c6f5a3f7dbbB0


#### Execute createStar() function

- Transaction: https://rinkeby.etherscan.io/tx/0xa44eb0449e160adf0b47972c566f49efcb5684fe6cf7a4553c9cf0b0dbcff5ae

- Transaction Hash: 0xa44eb0449e160adf0b47972c566f49efcb5684fe6cf7a4553c9cf0b0dbcff5ae

- Contract Address: 0x44A10424daf039CCc4F2E795Fb3c6f5a3f7dbbB0


#### Place your star for sale using putStarUpForSale() function

- Transaction: https://rinkeby.etherscan.io/tx/0x83f9888f006caf7fb31e173deb2e8a80e774c255dea3ad7608019a3aaa3ecf64

- Transaction Hash: 0x83f9888f006caf7fb31e173deb2e8a80e774c255dea3ad7608019a3aaa3ecf64

- Contract Address: 0x44A10424daf039CCc4F2E795Fb3c6f5a3f7dbbB0
