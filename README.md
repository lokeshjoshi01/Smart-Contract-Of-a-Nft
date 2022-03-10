# Smart-Contract-Of-a-Nft

Solidity Template
My favourite setup for writing Solidity smart contracts.

Hardhat: compile and run the smart contracts on a local development network
TypeChain: generate TypeScript types for smart contracts
Ethers: renowned Ethereum library and wallet implementation
Waffle: tooling for writing comprehensive smart contract tests
Solhint: linter
Solcover code coverage
Prettier Plugin Solidity: code formatter
This is a GitHub template, which means you can reuse it as many times as you want. You can do that by clicking the "Use this template" button at the top of the page.

Usage
Pre Requisites
Before running any command, make sure to install dependencies:

$ yarn install
Compile
Compile the smart contracts with Hardhat:

$ yarn compile
TypeChain
Compile the smart contracts and generate TypeChain artifacts:

$ yarn typechain
Lint Solidity
Lint the Solidity code:

$ yarn lint:sol
Lint TypeScript
Lint the TypeScript code:

$ yarn lint:ts
Test
Run the Mocha tests:

$ yarn test
Coverage
Generate the code coverage report:

$ yarn coverage
Clean
Delete the smart contract artifacts, the coverage reports and the Hardhat cache:

$ yarn clean
