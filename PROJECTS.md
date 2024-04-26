# Projects:
> List of projects I have built.
> - Rust
>   - [Rpc massive requests](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#rpc-massive-requests-sender)
>   - [Multichain sniper bot with functionalities](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#multichain-sniper-bot-with-functionalities)
> - Python
>   - [ERC20 snipe with fast transfer](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#erc20-snipe-with-fast-transfer)
>   - [Arduino read data](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#arduino-read-data)
>   - [ERC20 buyers address collector](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#erc20-buyers-address-collector)
>   - [EVM sniper bot](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#evm-sniper-bot)
>   - [Starknet sniper bot](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#starknet-sniper-bot)
>   - [MEV sniper bot](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#mev-sniper-bot)
>   - [Gist generator](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#gist-creator)
>   - [Spam multi buy implementation](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#spam-multi-buy-implementation)
>   - [Spam ERC20 creation](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#spam-erc20-creation)
> - Solidity
>   - [Basic stacking rewards](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#basic-stacking-rewards)
>   - [Basic AVAX wallet](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#basic-avax-wallet)
>   - [Multi buy contract](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#multi-buy-contract)
> - Java
>   - [REST API for equipments management](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#rest-api-for-equipments-management)

<br>

---
## Rust
### Rpc massive requests sender
- Build time: 2 hours
- Repo(s): **Public**, https://github.com/0xHumban/rpc-ddos

A script using rust features to send a lot of requests to an HTTP RPC. Features used: ``async, Arc, Mutex, mpsc, thread``

<br>


### Multichain sniper bot with functionalities
- Build time: 3 months
- Repo(s): **Private**
- Resource: [DEXs implemented](https://github.com/0xHumban/0xHumban/blob/main/resources/rust-sniper-bot-impl.md)

Complex rust implementation of ``uniswap v2`` contract to perform onchain operations with ``ERC-20`` tokens.

A menu-based interface used by the user where he can perform these actions: 
- Check the potential token taxes
- Buy and sell a token for a wallet
- Snipe a token launch
- Check the price for a token on different ``DEXs``
- Simulate onchain transactions with a fork on the latest block
- Price tracking to check the price evolution
- Wallets tracking, to monitor performance and holdings.
- Auto-sell for a custom profit margin

The user can build his own custom ``startegy``, subscription method (Subscribe to new blocks, spam the latest block..),
to send custom transactions at the right time.

Technologies used: ``ether-rs``, ``foundry-rs`` (mainly for Anvil)

<br>
<br>

---
## Python

### ERC20 snipe with fast transfer
- Build time: 1 day
- Repo(s): **Public**, https://github.com/0xHumban/ERC20-token-snipe

Little project to train ```web3py``` library. Bot can rescue lost ERC20 tokens on a lost ethereum address.

<br>

### Arduino read data
- Build time: 2 hours
- Repo(s): **Private**, (might open)

Repository created to read and save data from Arduino RX port. First used to debug basic frames of an old machine.

<br>

### ERC20 buyers address collector
- Build time: 3 days
- Repo(s): **Private**, (might open)

A simple bot to collect address of buyers of a ERC20 tokens on a data time range. Collect address and write it in json file,
and used to retrieve and sort repeating address.

Goal: In automatic, get common buyers of different tokens, to track them.

<br>

### EVM sniper bot
- Build time: 2 months
- Repo(s): **Private**

Automatic sniping bot. Works on : ``Arbitrum / Optimism / Base / BSC``. Presale snipe, new tokens snipe, multi-wallets, auto-sell.

<br>


### Starknet sniper bot
- Build time: 8 hours
- Repo(s): **Private**

Automatic sniping bot. Works on : ``Starknet``. New token snipe, spam buy, auto sell, monitoring price in live, multi send wallets

<br>

### MEV sniper bot
- Build time: 07/2023 - 10/2023 (Discontinued)
- Repo(s): **Private**

Basic MEV sniper bot, used to snipe new ERC20 tokens on ``Ethereum``. Multi-wallets, first transaction mode, auto-sell, full configuration.
Beat public sniping bot like BananaGun and Maestro.

<br>

### Gist creator
- Build time: 4 hours
- Gist(s): **Public**, https://gist.github.com/0xHumban/bcd46eaf8ad1f0cb69d17081d814a430

Basic script to create a gist for a given file, with a simple command line 
Used to share code with collaborators easily

<br>


### Spam multi buy implementation
- Build time: 4 hours
- Repo(s): **Private**

An implementation for [Multi buy contract](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#multi-buy-contract), with basic interface to configure the contract
and start spamming buy transactions.

<br>


### Spam ERC20 creation
- Build time: 4 hours
- Repo(s): **Public**, https://github.com/0xHumban/spam-erc20-creation

The goal: share your social media links on Telegram groups that detect newly verified tokens, and attract new buyers.

<br>

___

## Solidity
### Basic stacking rewards
- Build time: 4 hours
- Contract(s): 1
- Tested: True
- Repo(s): **Public**, https://github.com/0xHumban/Staking-Rewards

A contract created, to simulate stake function on a DAPP, depending on the total supply and total token amount staked.

<br>

### Basic AVAX wallet
- Build time: 2 hours
- Contract(s): 1
- Tested: False
- Repo(s): **Public**, https://github.com/0xHumban/AVAX-Wallet-Solidity

A contract created, to simulate a basic wallet / bank with smart contracts. Deployed on Fuji testnet.

<br>

### Multi buy contract
- Build time: 5 days
- Contract(s): 2
- Tested: True
- Repo(s): **Private**

The goal was to create a contract that can perform multi buy in one transaction.
It can be used to spam transactions to buy tokens.

1 contract used as "basic" to instant reverted if already swapped or no liquidity.
And another one used as a template for custom token function (activeTrading ect...) 

<br>
<br>

---

## Java
### REST API for equipments management
- Build time: 2 months
- Tested: Unitary and integration test implemented
- Repo(s): **Private**

A Comprehensive API for Conference Equipment Management, built for a "fake" school client.

The goal was to create a REST API, that can be used in the software equipments management.

Some functionalities: users authentication and authorization, comprehensive interface with the database for different equipments, 
reservation management.

Technologies used: ``Spring boot``, ``Spring security``, ``JUnit 5``
