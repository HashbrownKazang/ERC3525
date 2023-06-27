# ERC3525 Deployment Tutorial

English | [简体中文](./README-zh_CN.md)

[ERC-3525](https://eips.ethereum.org/EIPS/eip-3525), proposed by [Solv Protocol](https://solv.finance), is a standard for the Semi-Fungible Token (or SFT) approved by the Ethereum community.

It defines a new type of digital asset characterized by the following key features:

* Unique ID and expressivity of ERC-721 non-fungible tokens. Compatibility with the ERC-721 token standard.
* It is fractionalizable, combinable, and computable.
* It can work like an account and nest other digital assets, including ERC-20 fungible tokens and NFTs, with support for token-to-token transfer.
* Programmable appearance, functionality, lockup, transfer, etc. Metadata is optimized to support dynamic inputs and more complex financial logic.

This is a starter kit for developers to creating and deploying a simple ERC-3525 smart contract using ChainIDE, MetaMask, and Solidity.

### 1. Setting up a Wallet

#### 1.1. Install MetaMask

When we deploy a smart contract to the blockchain or make a transaction to the deployed smart contract,
we need to pay the gas fee, and for that, we need to have a Web3 wallet, which is MetaMask. 
So, first of all, we'll install MetaMask. Please click [here](https://metamask.io/) to install MetaMask.

#### 1.2. Add the Mumbai Test Network to MetaMask
Click on the "Connect wallet" in the upper right corner, select the "Injected Web3 Provider" button, and then select on MetaMask to connect to the MetaMask wallet (Polygon Mainnet is the main network, and Mumbai is the test network - connect to Mumbai).

![image-20230114120433122](https://d3gvnlbntpm4ho.cloudfront.net/ERC721_Deployment_on_Mumbai_Polygon/image-20230114120433122.png)


#### 1.3. Obtaining Testnet Matic
Once Mumbai has been added to MetaMask, navigate to the [Polygon Faucet](https://faucet.polygon.technology/) to receive test tokens. On the faucet page, choose Mumbai as the network, MATIC as the token, and paste your MetaMask wallet address. Then, click submit, and the faucet will send you some test MATIC within a minute.

<img src="https://d3gvnlbntpm4ho.cloudfront.net/ERC+721+Deployment+on++Mumbai/Polygon_PR_get_tokens.png" width="100%" height="100%" />


### 2. Write down an ERC-3525 Smart Contract

The [ERC-3525 Reference Implementation](https://github.com/solv-finance/erc-3525) provides — in the form of an open-source code library and an NPM module package — a great way to learn and innovate around the ERC-3525 technology. 

You only need write down a few codes to get your own ERC-3525 application for using the ERC-3525 Reference Implementation.


The ChainIDE team has prepared the complete ERC-3525 showcase including all the required functions, you may use that built-in template and add/delete functions according to your requirements.

### 3. Compile, deploy and verify
These steps are the same as the ERC-721 Showcase.

### Learn more

[ERC-3525](https://eips.ethereum.org/EIPS/eip-3525)

[ERC-3525 White Paper](https://whitepaper.sftlabs.io/SFT%20Whitepaper.pdf)

[ERC-3525 Reference Implementation](https://github.com/solv-finance/erc-3525)

[ERC-3525 Starter Kit: Developer Edition](https://medium.com/solv-blog/erc-3525-starter-kit-developer-edition-9d734ca62bd0)

Find us on following:

[Telegram](https://t.me/EIP3525_DEV)

[Twitter](https://twitter.com/SFTLabsHQ)

[Website](https://sftlabs.io/)