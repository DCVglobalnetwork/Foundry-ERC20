## Foundry ERC20 

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

## Getting Started

Requirements

git
You'll know you did it right if you can run 

```shell
git --version
```
 and you see a response like 
 ```shell
git version x.x.x
```
foundry

You'll know you did it right if you can run 

```shell
forge --version
```

and you see a response like

```shell
forge 0.2.0 (816e00b 2023-03-16T00:05:26.396218Z)
```

### Quickstart

```shell
git clone https://github.com/DCVglobalnetwork/Foundry-ERC20.git
cd foundry-erc20
forge install 
forge build

## Usage

OpenZeppelin

OpenZeppelin Contracts Docs
https://docs.openzeppelin.com/contracts/4.x/

OpenZeppelin GitHub Repo
https://github.com/OpenZeppelin/openzeppelin-contracts

### Installing OpenZeppelin Contracts Package

```shell
forge install OpenZeppelin/openzeppelin-contracts --no-commit
```

### Start a local node

```shell
make anvil
```
![Screenshot 2024-04-26 142403](https://github.com/DCVglobalnetwork/Foundry-ERC20/assets/105791829/a764acc5-3c1a-4de9-afff-699fd5c9b5d4)


### Deploy

This will default to your local node. You need to have it running in another terminal in order for it to deploy.

```shell
make deploy
```

![Screenshot 2024-04-26 142547](https://github.com/DCVglobalnetwork/Foundry-ERC20/assets/105791829/da1475f0-6821-4e8c-b821-f5a207635f9e)

```shell
$ forge --help
$ anvil --help
$ cast --help
```
