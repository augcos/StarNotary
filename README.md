# Decentralized Star Notary Service Project
## Introduction
This code is part of the Decentralized Star Notary Service Project for the Blockchain Developer Nanodegree by Udacity. The goal of this project is to implement a notary sistem to create, track and exchange ERC721 tokens on the ethereum network. For this project, an ERC-721 token was created 

## Development
The project vas developed using the following software:
```
Node.js         v10.19.0
npm             v8.1.1
Truffle         v5.4.14
OpenZeppelin    v2.3.0
Solidity        v0.5.16
```

## How to install?
Before running this project in your local system, you will need to have Node.js, npm and Truffle preinstalled. After cloning this repository, run the following command to install all the necessary dependencies:
```
npm install
```

## Run the project
# Deploy to a local blockchain
First start the Truiffle development enviroment. Run the following command, which will launch a local ethereum blockchain on 127.0.0.1:9454 as well as the development enviroment:
```
truffle develop
```
Next, compile the code and deploy from the Truiffle development enviroment using the following commands:
```
compile
migrate --reset
```

## Deploy to the Rinkeby testnet
First start the Truiffle development enviroment. Run the following commands to compile the code and deploy to the Rinkeby testnet (deployment make take a few minutes):
```
compile
migrate --reset --network rinkeby
```
In order for this deployment to be successfull, you will need to do two changes to the project. First, create a file in the same directory as truffle-config.js named .secret with the mnemonic to you ethereum account. Next, add your Infura endpoint address to the infuraKey

**PROJECT for the Blockchain Developer Nanodegree by Udacity**
1. Truffle Version: 5.4.14 - OpenZeppelin Version: 2.3.0
2. ERC-721 Token Name: 'The Coolest Token'
3. ERC-721 Token Symbol: 'TCT'
4. Smart Contract Address: https://rinkeby.etherscan.io/address/0xa3bf4F8A3B5c3B6ee74aB018ecCFf5a1b89D1c04
