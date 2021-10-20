
# DeFi Smart Accounts

This repository contains the core contracts for Instadapp DeFi Smart Accounts (DSAs).
  

## Installation

1. Install NPM Packages

```javascript
npm i
```

2. Create a `.env` file in the root directory and use the below format for .`env` file.

```javascript
ALCHEMY_ID="<Replace with your Alchemy ID>" //For deploying
```  

## Commands:

Compile contracts

```
npm run compile
```

Run the testcases

```
npm test
```

Get the test coverage

```
npm run coverage
```

Contract verify

```
npx hardhat run verify [address] --network [Network]
```

Run Scripts

```
npx hardhat run [script-path]
```

