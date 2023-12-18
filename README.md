# Flow-NFT

## Project Objective
Creating an NFT contract and add a finction named borrowAuth NFT to the contract

## Description
In this project we are going to create a simple NFT contract in flow by using cadence as a programing language and we will also be add the function named borrowAuthNFT and we will authorize it using auth keyword in the contract. So for example if our NFT have some specific fields besides 'id', we should downcast it using 'as!' to be &NFT type, because &NonFungibleToken. WE will also be storing metadata as favousrite food, lucky number and name and retrive that metadata using address as refrence.

The cod for script and transaction is almost the same learned from the metcrafters flow learning modules.

## Execution
The project is executed on play.flow which is the flow test environment to run and test the contracts of flow we have done the following operatipns in the execution of the contract.
1. Deploy NonFungibleToken.cdc at 0x06
2. Deploy CryptoPoops.cdc at 0x05
3. We now create the collection by deploying Collection.cdc
4. Execute Mint.cdc transaction with address parameter with 0x05 and fill other parameters
5. Execute ReadScript.cdc with address parameter with the address where the NFT is stored

## Authors
Contributors Name

Omkar Kawadghare
