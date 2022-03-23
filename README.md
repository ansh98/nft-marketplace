
# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```



The stack
In this guide, we will build out a full stack application using:

Web application framework - Next.js
Solidity development environment - Hardhat
File Storage - IPFS
Ethereum Web Client Library - Ethers.js

Though it will not be part of this guide (coming in a separate post), we will look at how to build a more robust API layer using The Graph Protocol to get around limitations in the data access patterns provided by the native blockchain layer.

About the project
The project that we will be building will be Metaverse Marketplace - an NFT marketplace.



NFT Marketplace Contract - this contract allows users to mint NFTs and list them in a marketplace.

I believe this is a good project because the tools, techniques, and ideas we will be working with lay the foundation for many other types of applications on this stack – dealing with things like payments, commissions, and transfers of ownership on the contract level as well as how a client-side application would use this smart contract to build a performant and nice-looking user interface.

In addition to the smart contract, I'll also show you how to build a subgraph to make the querying of data from the smart contract more flexible and efficient. As you will see, creating views on data sets and enabling various and performant data access patterns is hard to do directly from a smart contract. The Graph makes this much easier.

