# Foundry-FundMe

This repository is a project built with Foundry, a fast and modular toolkit for Ethereum application development. It integrates key features from Foundry tools like Forge for Ethereum testing, Cast for interacting with smart contracts, Anvil for a local Ethereum node, and Chisel for a Solidity REPL.

## Features
- Fund transfer and withdrawal functionalities.
- Written in Solidity, with tests and deployment scripts.
- **Forge**: Ethereum testing framework.
- **Cast**: A tool for smart contract interaction.
- **Anvil**: Local Ethereum node.
- **Chisel**: A Solidity REPL.


# Getting Started
  
## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [foundry](https://getfoundry.sh/)
  - You'll know you did it right if you can run `forge --version` and you see a response like `forge 0.2.0 (816e00b 2023-03-16T00:05:26.396218Z)`

    

# Usage

## Deploy

```
forge script script/DeployFundMe.s.sol
```


## Testing

1. Unit
2. Integration
3. Forked
4. Staging

This repo covers #1 and #3. 

```
forge test
```

or 

```
// Only run test functions matching the specified regex pattern.

"forge test -m testFunctionName" is deprecated. Please use 

forge test --match-test testFunctionName
```

or

```
forge test --fork-url $SEPOLIA_RPC_URL
```

### Test Coverage

```
forge coverage
```

## Format

```shell
$ forge fmt
```

## Gas Snapshots

```shell
$ forge snapshot
```

## Anvil

```shell
$ anvil
```