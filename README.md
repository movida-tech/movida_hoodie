# Hoodie Defi Project

Hoodie is a decentralized capital efficient option protocol that enables sellers to create spreads. 
Hoodie protocol enables any user to create arbitrary option tokens, that represent the right to buy or sell a certain asset in a predefined price (strike price) at or before expiry. 
As the option seller in Hoodie, you can reduce the amount of capital locked in the system by creating spreads. (e.g Instead of putting down 100 USDC and mint 1 ETH-USDC-100 Put, you can buy a ETH-USDC-50 Put, and only deposit 50 USDC as collateral)
The oTokens created by Hoodie are cash settled European option, means all the options will automatically be exercised at expiry. A holder can redeem the proceeds by sending the oTokens back, the system will pay the holder the cash value based on strike price and underlying spot price at expiry, instead of actually exchanging the underlying asset and the strike asset.

## Local Development Setup

For local development it is recommended to use ganache to run a local development chain. Using the ganache simulator no full Ethereum node is required.

As a pre-requisite, you need:

- Node.js (v10.18.0)
- NPM

Clone the project and install all dependencies:

```sh
$ git clone https://github.com/movida-tech/movida_hoodie.git

# install project dependencies
$ npm i
```

Run the project:

```sh
$ npm start
```

**_DeFi and Tokenomics on WAX:_**

_WAX has created a new tokenomic model that marries the explosive growth of NFTs with the superior monetization capabilities of DeFi. The core element of the new WAX tokenomics system is its inter-blockchain design._

_Below are the details of the implementation including a summary of the new tokens, token mechanics, distribution, governance, and more. **This is a technical document.** For a summary of the steps required to participate in the WAX DeFi model, click [here](https://wax.io/blog/wax-tokenomics-defi-is-now-live-heres-how-to-participate)._

**_Definitions:_**



*   **_WAX Blockchain: a purpose-built blockchain that uses Delegated Proof of Stake (DPoS) as its consensus mechanism, designed to make NFT transactions faster, easier, and safer for all participants_**
*   **_WAX NFT: a [non-fungible token](https://medium.com/wax-io/the-beginners-guide-to-nfts-and-how-to-get-them-on-wax-8c377f008f0e) that trades on the WAX Blockchain_**
*   **_WAX Cloud Wallet: the WAX Blockchain’s native wallet that stores WAXP Tokens and WAX NFTs. Accounts can be created in just two clicks_**
*   **_WAX Network Fees: 2% fees collected by [WAX-powered secondary markets](https://www.dapp.com/dapps/wax-marketplace?sort=0&time=0&type=0) on sales of NFTs_**
*   **_WAXP to Ethereum bridge: a new bridge that will enable WAXP token holders to convert their tokens into WAXE._**
*   **_WAXE: a new Ethereum ERC20 utility token. A WAX Token holder wanting to participate in the WAX tokenomics will burn their WAXP tokens to receive WAXE (using the Ethereum bridge) and then deposit WAXE and ETH into WAXE-ETH Liquidity Pool._**
*   **_WAXE-ETH Liquidity Pool: a liquidity pool for the WAXE-ETH trading pair. Those who deposit a combination of WAXE and ETH into the liquidity pool will earn the WAXE-ETH Liquidity Pool token._**
*   **_WAXE-ETH Liquidity Pool token: the ERC20 token that’s received when depositing WAXE and ETH into the Liquidity Pool. The Liquidity Pool token can be staked in the WAX Economic Activity Pool to earn two types of rewards: WAXG and ETH._**
*   **_WAXG: a new Ethereum ERC20 Governance Token. WAXG will be given to those who stake their WAXE-ETH in the WAX Economic Activity Pool. You can then do one of two things with your WAXG: burn WAXG and receive ETH from the PiggyBank pool in exchange, or vote with them to adjust Governance parameters._**
*   **_WAX Economic Activity Pool smart contract on Ethereum (WEAP): this smart contract will govern two different economic activity pools, PiggyBank and Distribution Pools, as well as, rewards distributions and WAX DeFi Governance._**

## DeFi and Tokenomics on the WAX Blockchain: WAXE & WAXG Token Mechanics

**We want all Worldwide Asset eXchange™ participants to benefit from the economic activity taking place on the WAX Blockchain.**

The WAX Blockchain is the “King of NFTs” and **we want to share the success of NFT activity and future economic activity growth on WAX with WAX Token holders.** To do this, we feel that the success of WAX Blockchain economic activity **will be best captured and expressed on the [best blockchain monetary system - Ethereum](https://medium.com/wax-io/coming-to-wax-a-new-wax-tokenomic-model-cd0616a069e9).**



![alt_text](https://waxplorer.com/image1.png "image_tooltip")


Not all blockchains are created equal, which is advantageous to the space since it creates diversity and enables different blockchains to excel based on their different use cases. The WAX Blockchain is purpose-built for NFT transactions and is the top performing blockchain in the NFT space, while Ethereum is the de facto best monetary blockchain system. Therefore in order to allow all WAX participants to benefit from the economic activity generated from NFT transactions on the WAX Blockchain, WAX is creating additional token instruments to allow WAX's economic activity to be expressed on the Ethereum monetary system. This will be applied to future and past NFT transaction activity (including secondary market sales for Topps GPK, William Shatner, and all other participating NFT sales that occur prior to the implementation of this model).

**So how will the WAX Blockchain's economic activity leverage the Ethereum blockchain?**

 

Until now the WAXP Protocol Token, which is transacted on the WAX Blockchain, expressed only the utility value of the WAX Blockchain. As new business lines develop and economic activity expands and diversifies on WAX, there is a need to express WAX’s economic activity via Ethereum-based (ERC20) tokens. This will be accomplished through the creation of three new Ethereum based (ERC20) tokens: 



1. **WAXE** ERC20 Token. The WAXP token will be convertible into the WAXE token at a **ratio of 1000:1.** That is, 1,000 WAXP tokens can be converted into 1 WAXE token.
2. **WAXG** ERC20 Token. This governance token will be used to vote on the distribution and allocation of the WAX Blockchain's economic activity.
3. **WAXE-ETH Liquidity Pool** ERC20 Token. This is received when depositing WAXE and ETH into the Liquidity Pool. The Liquidity Pool token can be staked in the WAX Economic Activity Pool to earn two types of rewards: WAXG and ETH.


## 1. What is the purpose of WAXE, WAXG, and WAXE-ETH Liquidity Pool Tokens?

The WAX Blockchain's economic model is based on the buying, selling, and trading of NFTs that are created and transacted on the WAX Blockchain. In order to conduct most of these NFT transactions, participants need WAXP Tokens. One way to acquire WAXP is to purchase them on exchanges. 

**The WAXE and WAXG Token mechanisms will ensure that existing and future WAX NFT participants have access to the leading exchanges on the best monetary blockchain system - Ethereum.**


### WAXE Token Details

Name: WAX Economic Token

Symbol: WAXE

Decimals: 8

Token Contract Address: [0x7a2Bc711E19ba6aff6cE8246C546E8c4B4944DFD](https://etherscan.io/token/0x7a2bc711e19ba6aff6ce8246c546e8c4b4944dfd)

Maximum supply: 3,700,000 WAXE (3.7 million)

Initial Supply: 3,700,000 WAXE

Inflationary (mintable)? No

Deflationary (burnable)? No


### WAXG Token Details

Name: WAX Governance Token

Symbol: WAXG

Decimals: 8

Token Contract Address: [0xb140A429c342083E97Daf42d5D82634bd7Ade7d4](https://etherscan.io/token/0xb140a429c342083e97daf42d5d82634bd7ade7d4)

Maximum supply: 10,000,000 WAXG (10 million)

Initial supply: 10,000,000 WAXG

Inflationary (mintable)? No

Deflationary (burnable)? Yes


### WAXE-ETH Token Details

Name: Uniswap Liquidity Pool WAXE-ETH Token

Symbol: UNI-V2 WAXE-ETH

Decimals: 18

Token Contract Address: [0x0ee0cb563a52ae1170ac34fbb94c50e89adde4bd](https://etherscan.io/token/0x0ee0cb563a52ae1170ac34fbb94c50e89adde4bd)


## 2. How are WAXE, WAXG, and WAXE-ETH Tokens created?

**_How are WAXE Tokens created?_**

WAXE Tokens are created in two ways:



1. **Economic Activity Swap:** When WAX NFTs are bought and sold on WAX-powered secondary markets, these transactions collect network fees of 2% in the form of WAXP Tokens. Of the total number of WAXP Tokens collected for Economic Activity Fees:
*   20% of the WAXP Tokens will be burned creating a **deflationary tokenomics mechanism** on the WAX Blockchain.
*   80% of the WAXP Tokens will be swapped for WAXE Tokens at a ratio of 1000 WAXP to 1 WAXE. These WAXE Tokens are then funneled into the **WAX Economic Activity Pool (WEAP)**. 

![alt_text](https://waxplorer.com/image2.png "image_tooltip")

2. **Token Holder Swap:** WAXP Token Holders will be able to obtain WAXE tokens by swapping their WAXP tokens for WAXE tokens or purchasing them on an Ethereum exchange. **The WAXP tokens that get swapped for WAXE tokens will be burned**, creating an additional **deflationary tokenomics mechanism** on the WAX Blockchain.

![alt_text](https://waxplorer.com/image3.png "image_tooltip")

**_How are WAXE-ETH Tokens created?_**

WAXE-ETH Tokens are created when WAXE and ETH are deposited into the WAXE-ETH Liquidity Pool.

**_How are WAXG Tokens created?_**

WAXE-ETH Token holders who stake their tokens in the WEAP will receive a drop of WAXG Tokens every two weeks.

**_Gas fees using the WAX to Ethereum Bridge_**

Operations on Ethereum require gas fees. Users will pay the gas fees required to complete the following operations, based on the quoted Ethereum gas fee at that time:

*   Claiming WAXE after using the ETH Bridge to burn WAXP
*   Depositing WAXE and ETH into the WAXE-ETH Liquidity Pool 
*   Staking WAXE-ETH into the WAX Economic Activity Pool
*   Claiming rewards 

## 3. How is WAX Blockchain economic activity fee distributed?
WAX Blockchain economic activity fee, captured as WAXP in the Economic Activity Accumulator, is converted to WAXE Tokens (drawn from the total supply) and will be distributed in the form of Ethereum to WEAP participants. Within the WEAP, there will be two different smart contracts:

*   **Distribution Contract:** the percentage of the WAXE Tokens in the WEAP (initially 50%) that will be converted to ETH for distribution to Liquidity Pool WAXE-ETH Token Holders who stake their WAXE-ETH Tokens in the WEAP. 
*   **PiggyBank Contract:** the percentage of the WAXE Tokens in the WEAP PiggyBank Pool (initially 50%) that will be perpetually converted to ETH for distribution to WAXG Token holders who choose to burn their WAXG Tokens in the WEAP Smart Contract.

WAXG Token holders will be able to cast votes to govern the allocation and distribution of the WEAP.

WAXG Token holders will be able to vote on the following parameters of the WEAP:

*   **Burn %** is the percentage of Economic Activity Fees (WAXP) that gets burned before the remainder is transferred to the WEAP. Initially, this is 20%.
*   **Distribution %** is the percentage of WAXE Tokens from the Economic Activity Fees that get deposited into the WEAP’s Distribution Contract. Initially, this is 50%.
*   **PiggyBank %** is the percentage of WAXE Tokens from the Economic Activity Fees that get deposited into the WEAP’s PiggyBank Contract. Initially, this is 50%.
*   There may be additional governance parameters as the system is developed (ie: implementation of different liquidity pools, or the length of staking periods)