# The Smart Contract

This repository contains a lottery game implemented using a smart contract. The smart contract is written in Solidity, a contract-oriented, high-level language for implementing smart contracts.

## Features
- Players can enter the lottery by sending a transaction to the smart contract with a certain amount of funds.
- The contract maintains a list of all players who have entered the lottery.
- The owner can choose to randomly select a winner, who will receive all of the funds that have been entered into the lottery.

## Tools and Libraries
- Truffle is a popular development framework for Ethereum.
- Ganache is a local blockchain for testing and development.
- Remix IDE is a web-based Solidity compiler and IDE.
- Metamask is a browser extension for interacting with the Ethereum blockchain.

The page is built with HTML, CSS, and JavaScript. The JavaScript code uses the Web3.js library to interact with the Ethereum blockchain and the deployed smart contract.

## How it works

- Unlimited amount of users can participate in the lottery, however the minimum amount is 2.
- Every user has to connect their Metamask wallet to the lottery website.
- The price to enter the lottery is 1 Ether.
- The winner takes it all.
- User can see the amount of Ether currently in the prize pool.
- Only the owner can end the lottery and randomly pick a winner.

## Ganache local Ethereum net.

![image](https://user-images.githubusercontent.com/43725384/207672207-d8da3cfa-4007-47de-b101-50ffc7e085b7.png)

## Ganache transaction logs.

![image](https://user-images.githubusercontent.com/43725384/207672296-d11c50f4-2d9c-44ca-b40c-4da6294770cf.png)

## Minimalistic UI implementation.

![image](https://user-images.githubusercontent.com/43725384/207672461-8914d3bb-7c94-4137-b71d-4f48080f48d1.png)
