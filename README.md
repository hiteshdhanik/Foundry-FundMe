# Foundry-FundMe

This repository is a project built with Foundry, a fast and modular toolkit for Ethereum application development. It integrates key features from Foundry tools like Forge for Ethereum testing, Cast for interacting with smart contracts, Anvil for a local Ethereum node, and Chisel for a Solidity REPL.

## Features
- Fund transfer and withdrawal functionalities.
- Written in Solidity, with tests and deployment scripts.
- **Forge**: Ethereum testing framework.
- **Cast**: A tool for smart contract interaction.
- **Anvil**: Local Ethereum node.
- **Chisel**: A Solidity REPL.

## Setup
To get started with the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/hiteshdhanik/Foundry-FundMe.git
   cd Foundry-FundMe
   ```

2. Install dependencies:
    ```bash
    forge install
    ```
    

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
