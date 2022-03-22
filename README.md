# Flight-Surety-Insurance-Dapp

FlightSurety
<br>
<b>FlightSurety is a DAPP that tracks insurance claims for passengers that have had their flights cancelled.</b>

Install
This repository contains Smart Contract code in Solidity (using Truffle), tests (also using Truffle), dApp scaffolding (using HTML, CSS and JS) and server app scaffolding.

To install, download or clone the repo, then:

npm install truffle compile

Develop Client
To run truffle tests:

truffle test ./test/flightSurety.js truffle test ./test/oracles.js

To use the dapp:

truffle migrate npm run dapp

To view dapp:

http://localhost:8000

Develop Server
npm run server truffle test ./test/oracles.js

Deploy
To build dapp for prod: npm run dapp:prod

Deploy the contents of the ./dapp folder

Resources
How does Ethereum work anyway?
BIP39 Mnemonic Generator
Truffle Framework
Ganache Local Blockchain
Remix Solidity IDE
Solidity Language Reference
Ethereum Blockchain Explorer
Web3Js Reference
