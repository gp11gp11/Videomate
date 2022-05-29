#Videomate

Most of the video platform like tiktok are centralised. The central authorithy has the right to remove videos even without a prior notice, result in loss of work done by content creator. This companies can be banned which result in loss of data of content creators. Videos on this platform are mostly filled with ads, and the search result can be biased. They can put fourth the content that they want us to watch. Content creators get paid by the central authority after taking commision.
Videomate comes with a solution to all the problems mentioned above. Anyone can upload to Videomate and anyone can view in videomate. No data is lost and tampered since it is deployed in blockchain, which is immutable. we use filecoin to store the data, and the hash is stored in mumbai(polygon testnet)which runs on ethereum evm. Viewer if they wise can pay tip to content creator or they can buy the content from the content creator.

## Tech Stack Used

- Solidity
- Truffle Suite
- ethereum
- web3.storage - IPFS and Filecoin
- Openzeppelin contracts
- ReactJS
- react-bootstrap
- polygon
- mumbai testnet


## Run Locally

### Pre-Requisites

- Truffle Suite
- Ganache CLI

```
$ npm install -g truffle
$ npm install -g ganache-cli
```  
Clone the project

```
$ git clone https://https://github.com/gp11gp11/Videomate.git
$ cd videomate
```
### Setting up a local Blockchain
Install dependencies

```
$ npm install
```

Compile Smart Contracts

```
$ truffle compile
```

Run ganache

```
$ ganache-cli
```  

Run migrations to deploy the smart contracts

```
$ truffle migrate
```  

### Setting up the client

Start the App

```
$ npm start
```

Visit https://localhost:3000/ to view the app


## Running Tests

To run tests, run

```
  truffle test
```
