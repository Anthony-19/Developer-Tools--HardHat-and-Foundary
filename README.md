# Developer-Tools--HardHat-and-Foundary
# Smart Contract Deployment – Arc & Lisk

This project contains a Solidity smart contract deployed using Foundry (Forge) and HardHat to:

🔵 Arc Testnet

🟣 Lisk Network

## Project Setup Using Forge
- Forge init . - To initialize 

- cd projectName

- forge build

- forge test

- forge script script/Owner.s.sol

## Project Setup Using Hardhat
- npm init -y
→ Initialize a Node.js project

- npm install --save-dev hardhat
→ Install Hardhat

- npx hardhat
→ Initialize a Hardhat project

- npm install
→ Install project dependencies

- npx hardhat compile
→ Compile smart contracts

- npx hardhat test
→ Run tests

- npx hardhat run scripts/deploy.js
→ Run deployment script locally

## Deploy to a Network (Example)
npx hardhat run scripts/deploy.js --network lisk

or

npx hardhat run scripts/deploy.js --network arc


## Contract Addresss For HardHat
- Lisk TestNet : 0x153EA741d11c74d09188EC1f854E0735c0e807a3
- Arc TestNet : 0x153EA741d11c74d09188EC1f854E0735c0e807a3

## Contract Addresss For Foundary
- Lisk TestNet : 0x4d6d19CB8137fCEFb936D90ECEeFFFfceDaA86D5
- Arc TestNet : 0x4d6d19CB8137fCEFb936D90ECEeFFFfceDaA86D5
