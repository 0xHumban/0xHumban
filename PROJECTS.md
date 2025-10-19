# Projects:
> Projects I'm currently working on
> - IA 
>   - [Computer Vision on pebbles](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#computer-vision-on-pebbles)

---

> List of projects I have built.
> - IA 
>   - [RAG implementation for a startup POC](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#ai-startup-poc)
>   - [Computer Vision on pebbles](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#computer-vision-on-pebbles)
> - Go
>   - [Marmot Reduce (Distributed system for calculations)](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#marmot-reduce)
>   - [Ants chat (a chat on the same network)](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#ants-chat)
> - Rust
>   - [Rpc massive requests](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#rpc-massive-requests-sender)
>   - [Multichain sniper bot with functionalities](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#multichain-sniper-bot-with-functionalities)
>   - [Terminal interface emergency withdraw](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#terminal-interface-emergency-withdraw)
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
>   - [FLT tokens claims](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#flt-tokens-claim)
> - Solidity
>   - [Basic stacking rewards](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#basic-stacking-rewards)
>   - [Basic AVAX wallet](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#basic-avax-wallet)
>   - [Multi buy contract](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#multi-buy-contract)
> - Java
>   - [REST API for equipments management](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#rest-api-for-equipments-management)
>   - [J2EE Application for parking management](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#j2ee-application-for-parking-management)
> - WEB
>   - [Progressive Web App for basketball association](https://github.com/0xHumban/0xHumban/blob/main/PROJECTS.md#progressive-web-app-for-basketball-association)


<br>

---

## Artificial Intelligence
### AI Startup POC 
- Build time: 6 months (2024-2025)
- Technologies: ``Python``, ``LlamaIndex``, ``Flask``, ``React``, ``Docker``, ``GIT``
- Concepts: ``AI``, ``Machine Learning``, ``Retrieval-Augmented Generation``, ``Reinforcement Learning``
- Repo(s): **Private**

Developed a Proof of Concept (RAG system) integrating a chatbot trained on technical documentation.

Designed and deployed a web application using a Retrieval-Augmented Generation (RAG) architecture.

Deployed to production with Docker, managing and indexing dozens of technical documents.

<br>

### Computer Vision on pebbles
- Build time: 2025-Present
- Technologies: ``OpenCV``, ``Python``
- Concepts: ``Image Segmentation`` ,``Deep Learning``
- Repo(s): **Private**

Developed tools for automatic detection of pebbles in geological datasets using differents algorithms.

Implemented image segmentation to recognize pebble contours and trained machine learning models to classify lithological types.

<br>

---



## Go

### Marmot reduce
- Build time: 2 week
- Repo(s): **Public**, https://github.com/0xHumban/marmot-reduce

A simplified distributed system inspired by the MapReduce programming model. It allows you to perform distributed computations across multiple clients connected to a server.

####  Features

##### Server

- **Interactive menu** to manage operations.
- **Display connected clients** in real time.
- **Ping clients** to check their availability.
- **Update Distant client**, sending new version of client
- **Proper connection management**, preventing resource leaks.
- **Distributed execution of calculations**:
  - Letter counting in a text.
  - Checking if a number is prime.
  - PI estimation using Monte Carlo algorithm
  - Free fall simulation

#####  Client

- **Persistent connection**:
  - If the connection is lost, the client automatically attempts to reconnect.
  - It continues until the server sends an exit message.
  - It can self update himself with new version sent by server


<br>
<br>


### Ants chat
- Build time: 1 week
- Repo(s): **Public**, https://github.com/0xHumban/ants-chat

A local network chat where clients can connect to server, send / receive message to others clients. 
![Ants chat schema](https://github.com/0xHumban/ants-chat/blob/main/assets/ants-chat-schem.png)

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

### Terminal interface emergency withdraw
- Build time: 15 hours
- Repo(s): **Public**, https://github.com/0xHumban/emergency-withdraw

Terminal app created to help you to keep your $ETH if your pass phrase is compromised.

Features:

Enter your seed phrase en select wallets, and transfer ``$ETH`` to another address.
- View the ``$ETH`` balance for your wallets (generated with your pass phrase)
- Select one by one or select all wallets you want to send ``$ETH``
- View the total ``$ETH`` value to send
- Transfer ``$ETH`` to the address you want
- Refresh in live the wallets balance

Technologies used: ``ratatui``

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


### FLT tokens claim
- Build time: 2 hours
- Repo(s): **Public**, https://github.com/0xHumban/flt-tokens-claim

The goal: enter your private key and see if when you can claim your $FLT token, and you can send the transaction to claim. 
<br>

$FLT are community tokens airdrop by Fluence Network for developers, to claim it you have to claim $FLT-DROP and wait 
2 months.


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

Technologies used: ``Spring boot``, ``Spring security``, ``JUnit 5``, ``SQL``

### J2EE Application for parking management
- Build time: 1 week (2025)
- Repo(s): **Private**
- Technologies: ``J2EE``, ``WildFly``, ``Hybernate``, ``SQL``
- Concepts: ``JPA``, ``EJB``, ``Servlet``, ``Persistence``

Application to simulate parking management.




<br>
<br>

---

## Web
### Progressive Web App for basketball association
- Build time: 2 months
- Technologies: ``ReactJS``, ``REST API``, ``Firebase``, ``Gitlab``, ``PWA``
- Repo(s): **Private**

Requirements gathering and analysis: Identified client needs focused on improving communication between coaches and players within sports teams.

Design and development: Built a Progressive Web App (PWA) using React, ensuring responsiveness and cross-platform compatibility.

API integration: Utilized and customized a REST API to manage data exchange between the front end and the server.

Backend services: Integrated Firebase services for chats management and real-time notifications.

Team collaboration: Worked closely with the project manager to maintain smooth communication and efficient project tracking throughout development.