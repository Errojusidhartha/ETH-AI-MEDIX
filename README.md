# ETH-AI-MEDIX

Ethmedix - Health Record Management System

Ethmedix is a decentralized Health Record Management System that allows users to upload and manage health records securely on the Ethereum blockchain. It provides an interface for uploading, accessing, and sharing health records with authorized parties, including hospitals and doctors.

Features

Upload health records in various formats such as PDFs,images and other formats too .
Store health records securely on the Ethereum blockchain using smart contracts.
Grant access to health records for authorized users, including hospitals and doctors.
Display health records in a grid view for easy browsing.
Share health records with hospitals and doctors for collaboration and consultation.
Technologies Used

React.js: Front-end JavaScript library for building user interfaces.
Ethereum: Blockchain platform for storing health records using smart contracts.
Solidity: Smart contract programming language for Ethereum.
Hardhat: Ethereum development environment for building and testing smart contracts.
Pinata: It is a decentralised storage used for pinning files to IPFS.
Getting Started

Clone the repository:

git clone https://github.com/your-username/ethmedix.git

Install dependencies:

cd ethmedix npm install npm install axios // installing dependencies is important such that no errors are occured during the execution of the project..

Set up the Ethereum development environment:

Install Hardhat globally:

npm install -g hardhat

Start a local Ethereum network:

npx hardhat node

Deploy the smart contracts: in another terminal

npx hardhat run --network localhost scripts/deploy.js

Update the contract address and ABI in the App.js file to match your deployed smart contract.

Then following commands in another terminal cd Dise
python3 code1234.py
Then start the server in another terminal cd web5 npm start
