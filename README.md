# Talent Management plaform on Blockchain
This is a project application and therefore cannot be used in a real life. 

## Dependencies
This project used a collection of technologies and tools, to run the application, you need to install the following dependencies:

1. [Node Package Manager](https://nodejs.org/en/) that comes with Node.js
2. [Truffle Framework](https://www.trufflesuite.com/) : it will allow us to build decentralized applications on the Ethereum blockchain, it comes with a suite of tools that allow writing smart contracts with Solidity programming language, test smart contracts and deploy them to the blockchain, develop client-side application.
3. [Ganache](http://truffleframework.com/ganache) : a local in-memoryblockchain. it come with 10 external accounts with addresses on the local Ethereum blockchain, each account with 100 fake ether.
4. [Metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en) : a chrome extension, allow us to connect to the blockchain with local accounts.
5. [React](https://reactjs.org/docs/getting-started.html): React is a JavaScript library for building user interfaces.


## Project structure

* **contracts directory**: contains smart contracts, plus a Migration contract that handles migrations 
* **migrations directory**: contains migration files. migrations are similar to other web development frameworks that require migrations to change the state of a database. whenever a smart contract is deployed, we update the blockchain's state and therefore need a migration.
* **node_modules directory**: all the node dependecies.
* **test directory**: tests for smart contracts
* **truffle.js file**: main configuration file for the truffle project.
* **clients.js drirectory** Frontend

## Run Project
 * Clone the project
 ```
 git clone https://github.com/aymaraya/talentchain_code.git
 ```
 * Install dependencies
  ```
  $ cd votingSystem
  $ npm install
  ```
