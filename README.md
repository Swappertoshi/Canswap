# Litepaper
Canswap: A P2P Cross-Chain AMM Swap

V1.0

swappertoshi 

swappertoshi@protonmail.com

www.canswap.org | www.canswap.com


**Abstract**. Canswap is a decentralized peer-to-peer swap platform that allows for the seamless trading of fungible tokens across multiple blockchains. Our solution addresses the current pain point faced by users who have to navigate through multiple chains and bridges in order to trade, incurring high gas fees and facing delays due to network congestion.

Our platform utilizes a multichain protocol that allows for the execution of trades on multiple blockchains simultaneously, through the use of "common blocks". This reduces gas costs by trading from highly congested networks such as Ethereum to less congested networks like Solana, BSC, Polygon, etc. This approach will make the trading process more efficient and cost-effective for users.

Canswap gives power to average users to trade freely between the borders of blockchains without any complications, it will be seamless on the backend but also on the front end and user’s experience.

Our platform aims to empower users to easily trade between different blockchains and increase the overall liquidity and accessibility of the crypto market.


# Introduction 
The world of blockchain finance and collectibles is rapidly evolving, with more and more assets being tokenized and traded on various networks. However, one limitation of this ecosystem is the siloed nature of different blockchains, which can make it difficult for users to access and trade a wide range of assets. Canswap, an idea first conceptualized in 2021, is here to change that. Our platform enables the swapping of different cryptocurrencies across multiple blockchains, providing users with greater flexibility and freedom in managing their assets. Whether you're looking to trade a popular ERC-20 token for a newer Binance Smart Chain asset or swap an NFT from one blockchain for another, Canswap makes it easy. With our cutting-edge multichain protocol and user-friendly interface, we're breaking down the barriers between blockchains and opening up a whole new world of possibilities for crypto enthusiasts and collectors alike.

# Transactions
Canswap uses a multichain protocol to execute trades across multiple blockchains simultaneously. This approach allows for the efficient and cost-effective swapping of different cryptocurrencies.

The core component of this protocol is the use of "common blocks". A common block is a block that is mined and added to multiple chains at the same time. These blocks contain a batch of transactions that are intended to be executed on multiple chains. This allows for the execution of trades on multiple blockchains in a single transaction, reducing the number of transactions and gas costs required.

To facilitate these trades, Canswap employs a smart contract-based system that is designed to manage the interactions between different blockchains. The smart contract serves as an intermediary between the different chains, handling the exchange of tokens and the management of trade data.

The system also uses a technique called "atomic swaps" to ensure that trades are executed atomically and securely. Atomic swaps involve creating a smart contract that holds the assets being traded, and then executing the trade only if certain conditions are met. This ensures that the assets are only transferred if both parties agree to the terms of the trade.

In addition to the smart contract-based trading system, Canswap also employs a number of other techniques to ensure the security and efficiency of trades. These include off-chain order books, which are used to match trades and reduce the number of transactions on the blockchain, and on-chain state channels, which are used to reduce the need for on-chain transactions.

The backend architecture of Canswap is designed to provide fast, secure, and cost-effective trading for users. With its multichain protocol, smart contract-based system, and other advanced techniques, Canswap aims to provide a seamless trading experience for users across multiple blockchains.

The architecture is composed of several key components:

-> Multichain protocol: The backbone of Canswap's system, responsible for executing trades across multiple blockchains simultaneously by using common blocks. These blocks contain a batch of transactions that are intended to be executed on multiple chains, allowing for the execution of trades on multiple blockchains in a single transaction, reducing the number of transactions and gas costs required.

-> Smart contract-based trading system: Handles the interactions between different blockchains, serving as an intermediary between the different chains, handling the exchange of tokens and the management of trade data. It also uses atomic swaps to ensure that trades are executed atomically and securely.

-> Off-chain order book: Matches trades and reduces the number of transactions on the blockchain. This database contains information about the available trades and the assets being traded and is updated in real-time, allowing users to quickly find and execute trades.

-> State channel: Reduces the need for on-chain transactions by allowing off-chain transactions to be settled on-chain, reducing the number of transactions and gas costs required.

-> Event log: Logs all events that occur on the platform, used for auditing and debugging purposes.

-> API server: Interacts with the smart contract and other backend components, providing a way for users to interact with the platform and execute trades.


# Swaps
The swap interface on Canswap's front end is designed to be user-friendly and intuitive for users of all experience levels. Here is an example of how the swap process might work from a user's perspective:

The user navigates to the Canswap platform and connects their web3 wallet

The user selects the assets they want to trade from the available options on the platform. They can choose to swap between different cryptocurrencies, regardless of which blockchain they are on.

The user enters the desired trade details, including the amount of assets they want to trade and the assets they want to receive in return.

The platform uses the multichain protocol to match the user's trade with another user who is looking to trade the same assets. The platform also calculates the current exchange rate for the assets being traded.

The user confirms the trade details and submits the transaction. The smart contract-based trading system then handles the exchange of assets and the management of trade data.

The platform uses an off-chain order book and state channels to execute the trade and update the user's account balance.

The user receives the assets they requested in the trade and can view the transaction details in the trade history section of their account.

Throughout the entire process, the user experience is the same, regardless of which blockchain the assets are on. The user can trade different assets across multiple blockchains seamlessly, with no need to navigate through multiple blockchains and bridges.

Incentives 
There are several different types of stakeholders in the Canswap ecosystem, and each one has its own set of incentives for participating in the platform. Here are a few examples:

→ Users: Users are the primary stakeholders in Canswap, and they stand to benefit from the platform's ability to facilitate seamless trading of assets across multiple blockchains. They can trade different assets across multiple blockchains seamlessly, with no need to navigate through multiple blockchains and bridges, they can also benefit from the lower gas fees and faster transactions that the platform offers.

→ Liquidity providers: Liquidity providers are users who provide assets to the Canswap's liquidity pools, they are incentivized to do so by earning a percentage of the trading fees generated by the pool. The more assets they provide, the more they earn in trading fees.

→ Developers: Developers are incentivized to build and improve the Canswap platform. They can earn rewards for contributing to the platform's development and for building dApps that use the Canswap protocol.

→ Investors: Investors in Canswap are incentivized by the potential for the platform to increase in value as more users adopt it. They can also earn a return on their investment by participating in trading and liquidity provision on the platform.

→ Token holders: Token holders of Canswap are incentivized to hold the token, as they can use it to vote on proposals to improve the platform and also they can get discounts on trading fees.

Supported Chains

Our platform is built on the Ethereum network and is compatible with all top EVM-compatible blockchains.

The multichain protocol that we use enables the execution of trades across multiple blockchains simultaneously, allowing users to trade assets seamlessly between different chains. This eliminates users' need to navigate multiple blockchains and bridges, providing a more user-friendly experience.

We support the following blockchains:

Ethereum 
Polygon 
Arbitrum
Gnosis
Avalanche
Solana 
Phantom 
BNBChain
and more

By supporting these blockchains, we are providing our users with access to a wide range of assets and the ability to trade them with ease. Our platform will continue to support new blockchains as they come online, providing users with even more options and flexibility.

In addition, our smart contract-based trading system is designed to handle the interactions between different blockchains, making the trading process smooth and seamless. The platform also uses off-chain order books and state channels to reduce the number of on-chain transactions and gas costs, making trades faster and more cost-effective.

In summary, Canswap's multichain protocol and smart contract-based trading system allow for the seamless and efficient trading of assets across multiple blockchains, including Ethereum, Polygon, Arbitrum, Gnosis, Avalanche, Solana, Phantom, and more.

Zk Research For Implementation 
Canswap is actively researching on Zero-knowledge proofs like ZkEVM by Polygon, etc. to explore the potential use cases of zk technology and enhance privacy and security for the users of the platform. 

→ implementation of privacy-preserving atomic swaps: With zk-atomic swaps, users can trade assets without revealing their identities or the details of the trade to the network. This can help to protect users' privacy and prevent front-running.

→ implementation of privacy-preserving liquidity provision: With zk-liquidity provision, liquidity providers can provide liquidity to pools without revealing their identities or the details of the liquidity they are providing. This can help to protect liquidity providers' privacy and prevent front-running.

# Calculation 

→ Exchange rate calculation:
Canswap's platform calculates the exchange rate for the assets being traded in real time. The following equation can be used to calculate the exchange rate:

Exchange rate = (Asset A price on blockchain 1) / (Asset B price on blockchain 2)

The Canswap platform uses a real-time price feed to gather the current market prices of the assets being traded.
The prices are gathered from multiple decentralized exchanges and centralized exchanges that support the assets.
The platform calculates the exchange rate using the equation provided earlier: Exchange rate = (Asset A price on blockchain 1) / (Asset B price on blockchain 2)
The exchange rate is then used to determine the trade details, such as the number of assets to be traded and the assets to be received in return.
This rate is updated in real-time as the prices change to ensure that the user is getting the most up-to-date and accurate rates for their trades.



→ Atomic swap calculation:

Canswap uses atomic swaps to ensure that trades are executed atomically and securely. The following equation can be used to calculate the number of atomic swaps required to execute a trade:

Number of atomic swaps = (Number of assets involved in trade) / (Number of assets per atomic swap)

The Canswap platform uses atomic swaps to ensure that trades are executed atomically and securely.
The platform creates a smart contract for each atomic swap, which holds the assets being traded.
The smart contract is programmed to execute the trade only if certain conditions are met, such as the expiration of a time lock or the receipt of a secret key.
The platform uses the number of assets involved in the trade and the number of assets per atomic swap to calculate the number of atomic swaps required using the equation provided earlier: Number of atomic swaps = (Number of assets involved in trade) / (Number of assets per atomic swap)
Once the number of atomic swaps is determined, the platform executes the atomic swaps and updates the user's account balance accordingly.


# Fees

→ (For platform) Trading Fees: Users will be charged a small percentage fee for each trade executed on the platform. The exact fee percentage will be set based on community feedback and be updated dynamically based on the current market conditions to ensure healthy liquidity on the platform. 

-> (For community) Liquidity Provision Fees: Users providing liquidity to the pools on the platform will earn a percentage of the trading fees generated by the pool. The percentage will be set dynamically and adjusted to ensure healthy liquidity on the platform.



# Roadmap

2021
Q1: Idea conceptualization for Canswap
Q2: canswap.com and canswap.org domain registration
Q3: Market & competitor research
Q4: Early documentation begin 

2022
Q1: First draft of litepaper 
Q2: Team building
Q3: Research and development of the multichain protocol and smart contract-based trading system 
Q4: Development of the off-chain order book and state channel functionality

2023
Q1: Website & Final Documentation Live, Waitlist, Fair launch & fundraising, TGE & Uniswap Listing
Q2: Testing and bug fixing of the platform
Q3: Release of the MVP (minimum viable product) for community testing
Q4: Integration of more blockchains

2024:
Q1: Development of the user interface and user experience,  Launch of the Canswap platform's beta version for public use
Q2: Introduction of a governance model and decentralized decision-making
Q3: Integration of more blockchains 
Q4: Zk proofs integration testing

2025: 
Q1: Implementation of privacy features and support for privacy-focused assets, zero-knowledge proofs
Q2:  Continuous improvement and development of new features based on community feedback

# Business Model 

Canswap will charge a transaction fee on the platform. The exact percentage of the fees will be published later based on community feedback. 

The fees generated on the platform will be utilised as follows: 

→ Buyback & Burn: 30% of the fees generated will be used to buy back and burn $CAN token, this will decrease the total supply of $CAN and increase the value of the remaining tokens in circulation.

→ Operation cost: 20% of the fees generated will be used for platform operations, including development, maintenance, and marketing.

→ Safu Fund: 10% of the fees generated will be used for a "safu" fund, which will be used to cover any potential losses or unexpected expenses.

→ Staking Rewards: 5% of the fees generated will be used for staking rewards, encouraging users to hold and stake $CAN tokens to support the network.

→ Treasury: 35% of the fees generated will be kept in the treasury, mainly for liquidity, to make it easier for users to trade and attract more users to the platform.

The business model is self-sustaining and creates a positive feedback loop where the value of the exchange and token increases as the platform becomes more successful.

The platform will also explore the use of Zero-knowledge technology to enhance privacy and security, this includes privacy-preserving atomic swaps and liquidity provision, staking, NFT trading, governance model, privacy


# Tokenomics

**$CAN token**
Network: Ethereum
Standard: ERC20
Token Type: Utility
Total supply: 1.000.000.000
Public Sale: 500.000.000 (50%)
Liquidity & Exchanges: 150.000.000 (15%)
Marketing: 100.000.000 (10%)
Platform Incentives, Staking & Farming: 50.000.000 (5%)
Treasury: 150.000.000 (15%)
Team: 50.000.000 (5%)


We will raise a total of $500.000 at an FDV of $1.000.000 and lock 60% ($300.000) in liquidity
1 $CAN in public sale = $0.001
1 ETH (at $1500) = 1.500.000 $CAN

We’re raising a total of 333 $ETH for 500M $CAN tokens


# References

"Cross-chain atomic swaps" by Tierion (https://medium.com/tierion/cross-chain-atomic-swaps-b9a6b17a6e7e)

A survey of cross-chain atomic swap protocols" by The Ocean (https://theoceanx.com/blog/survey-cross-chain-atomic-swap-protocols/)

"A beginner's guide to multichain architectures" by Blockgeeks (https://blockgeeks.com/guides/multichain-architectures/)

Gas savings in multichain systems" by ChainGuardian (https://chainguardian.com/blog/gas-savings-in-multichain-systems/)

"Off-chain order books" by ChainGuardian (https://chainguardian.com/blog/off-chain-order-books/)

"Decentralized exchange protocols" by ConsenSys (https://consensys.net/resources/decentralized-exchange-protocols/)

"Cross-chain communication" by ChainGuardian (https://chainguardian.com/blog/cross-chain-communication/)

"A survey of cross-chain communication solutions" by ChainGuardian (https://chainguardian.com/blog/cross-chain-communication-solutions/)

