# Architect a Supply Chain: Fair Trade Coffee
This repository contains an ethereum blockchain solution for Fair Trade Coffee.  The appication is designed to record the creation of coffee product from raw materials through to the consumer.  The consumer is able to verify their coffee's authenticity through validation of the blockchain.

## Content
In the /diagrams/ folder you will find the following UML diagrams:

Activity diagram (mapping out the activities of each participant)
Sequence diagram (mapping out the functions that will be used and the sequence of them)
State diagram (mapping out the state changes to the item(s) being tracked)
Data diagram (mapping out the structure of our smart contract and their inheritance)

## Libraries
The Roles library is used which allows simple creation and management of different roles, and then provides access controls for these.

## IPFS 
Not used in this project.

#### Contract Address: 
https://rinkeby.etherscan.io/address/0xb92473d300ede5a626bdf66516e5ca189cce5950
#### Contract Hash: 
0x2994e50af441c7b341c56355fec312f470037393c8551fb8ad94d2bdd4da79e2
#### Transaction Hash: 
0x2994e50af441c7b341c56355fec312f470037393c8551fb8ad94d2bdd4da79e2

## Versions
Truffle v4.1.13 (core: 4.1.13)
Solidity v0.4.24 (solc-js)

## Instructions for Running Test Cases for the Smart Contract
1.  truffle compile
2.  truffle test

## Instruction for Running the Smart Contract and Front End App in local development environment
1.  truffle compile
2.  truffle migrate --reset (deploy the contract to ganache)
3.  npm run dev (to start the front end app)
4.  http://localhost:3000/

## Instruction for Deploying the Smart Contract to Rinkeby Testnet
1.  Connect to the Rinkeby testnet with Metamask
2.  In Metamask, select an account with Ether
3.  truffle migrate --network rinkeby
4.  npm run dev
5.  http://localhost:3000/