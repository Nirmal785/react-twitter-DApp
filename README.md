
# Twitter DApp

## Overview

Twitter DApp is a decentralized application that integrates with the Twitter API to provide blockchain-based functionalities. This project aims to enhance the Twitter experience by utilizing the benefits of decentralized technology, such as increased security, transparency, and user control over data.

## Features

-  Decentralized Authentication : Log in with your decentralized wallet.
-  Tweet from Blockchain : Post tweets directly from your DApp.
-  On-Chain Data Storage : Store tweets and user data securely on the blockchain.

-  Real-Time Updates : Get real-time updates and notifications from the blockchain.

## Prerequisites

Before you begin, ensure you have met the following requirements:

-  Node.js  (version 14.x or later)
-  npm  (version 6.x or later)
-  Truffle  (version 5.x or later)
-  Ganache  (for local Ethereum testing)
-  MetaMask  (for interacting with the DApp)

## Installation

To install and run this project locally, follow these steps:

1.  Clone the repository: 

   ```bash
   git clone https://github.com/your-username/twitter-dapp.git
   ```

2.  Navigate to the project directory: 

   ```bash
   cd twitter-dapp
   ```

3.  Install dependencies: 

   ```bash
   npm install
   ```

4.  Start the local blockchain (Ganache): 

   ```bash
   ganache-cli
   ```

5.  Deploy the smart contracts: 

   ```bash
   truffle migrate --network development
   ```

6.  Run the DApp: 

   ```bash
   npm start
   ```

7.  Open the DApp: 

   Open your browser and go to `http://localhost:3000`.

## Usage

1.  Connect your wallet : Use MetaMask or any other Ethereum wallet to connect to the DApp.
2.  Authenticate : Authenticate yourself using the decentralized login option.
3.  Tweet : Post tweets from the DApp, which will be recorded on the blockchain.
4.  View Tweets : See tweets that are stored on the blockchain.
5.  Engage : Earn tokens by engaging with the content.

## Smart Contracts

The smart contracts are located in the `contracts` directory. Key contracts include:

-  Twitter.sol : The main contract for handling tweets.


## Technologies Used

- Solidity: For writing smart contracts.
- Web3.js: For interacting with the Ethereum blockchain.
- React.js: For building the frontend.
- Truffle: For smart contract development and testing.
- Ganache: For local blockchain testing.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.


## Contact

For more information, reach out to:

-  Name : nirmal darji
-  Email : nirmaldarji2412@gmail.com
-  Twitter : [@Nirmaldarji16](https://twitter.com/Nirmaldarji16)

