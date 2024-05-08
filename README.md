# Decentralized Loan Lending App

## Overview

This project is a decentralized application (DApp) for loan lending, built with React JS, Redux Toolkit, and Material UI for the frontend, and utilizing blockchain technology with Binance Smart Chain (BSC), Hardhat, Solidity, ChainLink, and IPFS for the backend.

### Testnet transaction addr: https://testnet.bscscan.com/address/0xffD4D54e3968Ff98B64bdFBa7EEf06984952D75a
### Twitter post link: https://x.com/zelktrvx/status/1788136256989544878

## Features

- **LoginPage:** Users can log in to access the platform.
  
- **HomePage:** Displays the main interface and options available to users.
  
- **LendingPage:** Allows users to lend funds to others.
  
- **MortgageLendingPage:** Specific page for mortgage lending activities.
  
- **BorrowingPage:** Enables users to borrow funds from lenders.
  
- **PayOutPage:** Handles the payout process for loans.

## Tech Stack

- JavaScript (React JS)
- Redux Toolkit
- Material UI
- Blockchain (Binance Smart Chain)
- Hardhat
- Solidity
- ChainLink
- IPFS

## Project Setup

1. **Start Development Server:**
   ```bash
   npm start
   ```
   This command runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

2. **Compile Solidity Code:**
   ```bash
   npx hardhat compile
   ```
   Compiles the Solidity smart contract code.

3. **Deploy Smart Contract:**
   ```bash
   npx hardhat run scripts/deploy.js --network 
   ```

## Note

1. Create a `.env` file to store your private key and Alchemy API key URL.
   
2. Copy your ABI file and your deployed smart contract address and paste them in the `index.js` file on the frontend.

## Conclusion

This DApp provides a decentralized platform for loan lending activities, leveraging the security and transparency of blockchain technology on the Binance Smart Chain network.