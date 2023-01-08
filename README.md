<div id="top"></div>

<br />
<div align="center">

<h3 align="center">WeTube — Decentralised Video Streaming Platform</h3>

</div>

## About The Project

[![Wetube][product-screenshot]]

WeTube is a YouTube Clone built on top of Polygon network and The Graph, that allows users to create, share and watch videos, without worrying about their privacy.

### Built With

- Frontend framework: Next.js
- Smart contracts: Solidity
- Ethereum web client library: Ethers.js
- File storage: IPFS
- Querying data: The Graph
- CSS Framework: TailwindCSS
- Ethereum development environment: Hardhat
- Layer 2 blockchain: Polygon
- Video Infrastructure: Livepeer


<!-- GETTING STARTED -->

## Getting Started

To get this application up and and running on your local machine follow these simple steps.

### Prerequisites

You need to have Node.js, NPM and hardhat installed on your computer, before running this project.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/0xshikhar/WetubeApp
   ```
2. Install NPM packages

   ```sh
   npm install
   ```

   or

   ```sh
   yarn install
   ```
3. Create an `.env` file and get an API key from Livepeer studio, Web3 Storage and Imagekit. 
   ```sh
   PRIVATE_KEY=""
   NEXT_PUBLIC_LIVEPEER_KEY=""
   NEXT_PUBLIC_WEB3_STORAGE_KEY=""
   NEXT_PUBLIC_IMAGEKIT_ID=""
   ```
4. Compile the smart contract
   ```sh
   npx hardhat compile
   ```
5. Deploy the smart contract

6. Run the app

   ```sh
   npm start
   ```


### License

This project is an open source software licensed under the MIT License

