# FishnetNFT
### (AI NFT Generator)

### Demo UI 
![fishnetNFTui2](https://github.com/cole319/FishnetNFT/assets/108489425/fdce062b-ceec-46f1-b79b-a683b9e62edc)

## Tech Stack

- Writing Smart Contracts & Tests : Solidity
- Client Side Development : Javascript
- Development Framework : Hardhat
- Blockchain Interaction with Blockchain : Ethers.js
- Frontend Framework used for Frontend : React.js
- Connection to IPFS : NFT.Storage
- AI Models : Hugging Face

## Requirements For Initial Setup
- NodeJS is required to run this app

## Setting Up
### 1. Clone/Download the Repository


### 2. Install Dependencies:
`$ npm install`

### 3. Setup .env file with required APIs

### Get Read access token from
[Hugging Face](https://huggingface.co/) 

### Get API key
[NFT.Storage](https://nft.storage/)

### 4. Run tests
`$ npx hardhat test`

### 5. Start Hardhat node
`$ npx hardhat node`

### 6. Run deployment script
In a separate terminal execute:
`$ npx hardhat run ./scripts/deploy.js --network localhost`

### 7. Start frontend
`$ npm run start`
