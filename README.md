# NFT-Auction

This project provides a ERC721 smart contract that allows you to mint unique NFTs. It also provides an auction contract that allows users to auction of their NFTs.

Getting Started
To deploy the smart contract follow the steps below.

Install Node.js
cd NFT-Auction/minty
npm link
npm install
Install IPFS Command Line
ipfs daemon
In a new terimal window npx hardhat node
Run minty deploy
Minting Tokens
Once the smart contract is deployed and IPFS is running you can mint new NFTs by running the following command.

minty mint ./asset-path --name "Name" --description "description"
Using the Frontend
Install the Liveserver Extension in VSCode.
Open base.html
Click the button that says "Go Live" in the bottom right hand corner of your VSCode.
Import any accounts you need into MetaMask and change your MetaMask network to "Hardhat".
Interact with the contract!
