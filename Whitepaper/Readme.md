
**Canswap: A Cross-Chain Swap Platform**
v1.1

swappertoshi 

swappertoshi@protonmail.com

www.canswap.org | www.canswap.com

**Abstract** Canswap is a decentralized cross-chain swap platform that allows for the seamless trading of fungible tokens across multiple blockchains. Our solution addresses the current pain point faced by users who have to navigate through multiple chains and bridges in order to trade, incurring high gas fees and facing delays due to network congestion.

Our platform utilizes a multi-chain protocol that allows for the execution of trades on multiple blockchains simultaneously, through the use of stable coin pools and a mechanism that triggers trades in both blockchains. This reduces gas costs by trading from highly congested networks such as Ethereum to less congested networks like Solana, BNBChain, Polygon, etc. This approach will make the trading process more efficient and cost-effective for users.

Our goal is to empower users to trade freely across the borders of different blockchains without any complications, making it a seamless experience on the backend and front end. With Canswap, users can easily and efficiently trade their assets without the hassle of navigating multiple networks.



## 1. **Introduction**

The world of blockchain finance and collectibles is rapidly evolving, with more and more assets being tokenized and traded on various networks. However, one limitation of this ecosystem is the siloed nature of different blockchains, which can make it difficult for users to access and trade a wide range of assets. Canswap, an idea first conceptualized in 2021, is here to change that. Our platform enables the swapping of different assets across multiple blockchains, providing users with greater flexibility and freedom in managing their assets. 

With our extensible set of smart contracts that can be deployed on any blockchain which developers can leverage to build truly native cross-chain applications and user-friendly interface, we're breaking down the barriers between multiple blockchains and opening up a whole new world of possibilities for the multichain future



## 2. **Transactions**

Transactions on Canswap are made simple and seamless through the platform's smart contract integration with multiple blockchains . 

To facilitate these swaps, Canswap employs a smart contract-based system to manage the interactions between different blockchains and handle the exchange of tokens and trade data. The system also uses a network of stablecoin pools to ensure that trades are executed accurately and securely.

With Canswap, users can easily trade one asset for another, regardless of which blockchains they are on. This allows for greater flexibility and freedom in managing assets, breaking down the barriers between blockchains and easing the way for DeFi

To further enhance the efficiency of trades, Canswap uses  off-chain order books to match trades and reduce the number of transactions required on the blockchain. This approach helps to minimize gas fees and speeds up the trade process. Additionally, the platform is designed with security in mind, employing various measures to protect users' assets and ensure the safety of their trades.

The backend architecture of Canswap is designed to provide fast, secure, and cost-effective trading for users. With smart contracts diversified across multiple blockchains and other advanced techniques, Canswap aims to provide a seamless experience of exploring the potential of the multichains



* **Stablecoin Pool**: This component will hold the stablecoins (e.g. USDC, DAI) from different chains. The stablecoin pools will be used for swapping between the different chains.
* **Order Management System**: This component will manage the orders placed by users for the swaps. It will handle the matching of orders, executing the swaps, and ensuring the transfers of the assets between the chains.
* **Cross-chain Interoperability Layer**: This component will provide the infrastructure to transfer assets between the chains. This layer will take care of converting the assets between the chains and ensuring the correct transfer of the assets to the correct pool.
* **Price Oracle**: This component will provide the real-time pricing information of the assets in different chains. The price oracle will be used to determine the amount of stablecoin required to buy a certain amount of an asset in a specific chain.
* **Liquidity Management**: This component will manage the liquidity of the pools. It will keep track of the assets in the pools, ensure the smooth functioning of the swaps, and manage the incentives for the liquidity providers.
* **Security Layer**: This component will provide the security of the platform by implementing best practices in terms of security, smart contract security, and protecting user's assets.
* **User Interface**: This component will provide the user-facing interface to interact with the platform. The user interface will allow users to place orders, view the status of their orders, and access the different pools and assets available for swapping.

This architecture will allow for seamless cross-chain swaps, with the use of stablecoin pools as the intermediaries for the swaps. The platform will be able to handle the transfer of assets between different chains in a secure, efficient, and user-friendly manner.



## 3. **Swaps**

The swap interface on Canswap's front end is designed to be user-friendly and intuitive for users of all experience levels. Here is an example of how the swap process might work from a user's perspective:

1. The user navigates to the Canswap platform and connects to their web3 wallet.
2. The user selects the assets they want to trade from the available options on the platform and enters the desired trade details, including the number of assets they want to trade and the assets they want to swap
3. The platform calculates the current exchange rate for the assets being traded based on the Price Oracle data.
4. The user confirms the trade details and submits the transaction. The smart contract-based trading system then executes the exchange of assets and manages the trade data through Stablecoin Pool and the Order Management System which works on the Cross-chain Interoperability Layer.
5. The user receives the assets which they wanted to swap with and can view the transaction details in the trade history section of their account.

    Throughout the entire process, the user experience is the same, regardless of which blockchain the assets are on. The user can trade different assets across multiple blockchains seamlessly, with no need to navigate through multiple blockchains and bridges.

## 4. **Incentives**

There are several different types of stakeholders in the Canswap ecosystem, and each one has its own set of incentives for participating in the platform. Here are a few examples:

**→ Users**: Users are the primary stakeholders in Canswap, and they stand to benefit from the platform's ability to facilitate seamless trading of assets across multiple blockchains. They can trade different assets across multiple blockchains seamlessly, with no need to navigate through multiple blockchains and bridges, they can also benefit from the lower gas fees and faster transactions that the platform offers.

**→ Liquidity providers**: Liquidity providers are users who provide assets to the Canswap's liquidity pools, they are incentivized to do so by earning a percentage of the trading fees generated by the pool. The more assets they provide in various chains, the more they earn in trading fees.

**→ Developers**: Developers are incentivized to build and improve the Canswap platform. They can earn rewards for contributing to the platform's development, bug bounty and for building dApps that use the Canswap protocol.

**→ Investors**: Investors in Canswap are incentivized by the potential for the platform to increase in value as more users adopt it. They can also earn a return on their investment by participating in trading and liquidity provisions on the platform.

**→ Token holders**: Token holders of Canswap are incentivized to hold the token, as they can use it to vote on proposals to improve the platform, and to participate in staking & farming pools. 



## 5. **Supported Chains**

Our platform is built on the Ethereum network and is compatible with all top EVM-compatible blockchains.

Canswap eliminates users' need to navigate multiple blockchains and bridges, providing a more user-friendly experience.

We will support the following blockchains:



* Ethereum 
* Polygon 
* Arbitrum
* Gnosis
* Avalanche
* Solana 
* Phantom 
* BNBChain
* Aptos
* Sui
* and more

By supporting these chains, we are providing our users with access to a wide range of assets and the ability to swap them with ease. Our platform will continue to support new blockchains as they come online, providing users with even more options and flexibility.

In addition, our smart contract-based trading system is designed to handle the interactions between different blockchains, making the trading process smooth and seamless. 



## 6. **Zk Research For Implementation**

  Research and Development of Zero-Knowledge Proofs: At Canswap, we understand the importance of privacy and security in cross-chain swaps. That's why we are actively researching and exploring the implementation of zero-knowledge proofs (ZKPs) to enhance the privacy and security of our platform. ZKPs allow users to prove the validity of a statement without revealing any underlying information, making it a valuable addition to the Canswap platform. We are committed to staying at the forefront of innovation and incorporating cutting-edge technologies to provide a secure and user-friendly platform for cross-chain swaps.

## 7. **Calculation**

→ **Liquidity Pool & Asset’s Value Calculation**:

Let's say the value of Asset A is represented by "$A", and the value of Asset B is represented by "$B". The price oracle provides the current exchange rate between Asset A and Asset B, represented as "$R_{A,B} = A / B".

The amount of Asset A in the liquidity pool is represented as "Qα", and the amount of Asset B in the liquidity pool is represented as "Qβ". The total value of the liquidity pool can then be represented as:

V_{pool} = Qα * $A + Qβ * $B

By substituting the exchange rate into the equation, we can express the value of the liquidity pool in terms of either Asset A or Asset B:

V_{pool} = Qα * $A + Qβ * ($A / $R_{A,B}) = Qα * ($B / $R_{A,B}) + Qβ * $B

This equation can be used to calculate the value of the liquidity pool.

 \
→ **Maintaining the liquidity pool**

In the context of liquidity pools, the value of a pool can be modeled using differential equations. One common approach is to use a system of ordinary differential equations (ODEs) to model the dynamics of the liquidity pool. The value of the pool is then represented by a function, typically denoted as V(t), which represents the value of the pool at time t.

Let's consider a simple example of a liquidity pool with two assets, A and B. The change in the value of the pool over time can be modeled as a function of the supply and demand for the two assets in the pool.

The supply of asset A can be represented by the function S_A(t), while the demand for asset A can be represented by the function D_A(t). Similarly, the supply of asset B can be represented by the function S_B(t), and the demand for asset B can be represented by the function D_B(t).

The change in the value of the pool over time can then be modeled as a differential equation:

dV/dt = k_A * (D_A(t) - S_A(t)) + k_B * (D_B(t) - S_B(t))

where k_A and k_B are constants that represent the impact of the supply and demand for assets A and B on the value of the pool.

This differential equation represents the balance between the supply and demand for assets A and B in the liquidity pool, and the value of the pool is updated in real-time based on the supply and demand dynamics of the assets.

Solving this differential equation for V(t) provides a mathematical representation of the value of the liquidity pool over time, taking into account the supply and demand dynamics of the two assets.

→ **Exchange rate calculation**:

 \
The calculation of the value of Asset A on blockchain 1 compared to Asset B on blockchain 2 can be represented by the following mathematical equation:

$A = P_O * Qα

Where:

$A is the value of Asset A

P_O is the price oracle data obtained 

Qα is the quantity of Asset A

Similarly, the value of Asset B on blockchain 2 can be calculated as:

$B = P_O * Qβ

Where:

$B is the value of Asset B

P_O is the price oracle data obtained  \
Qβ is the quantity of Asset B

The price oracle data, P_O, can be obtained from a reliable third-party data provider, such as Chainlink, which aggregates data from multiple sources to provide accurate and tamper-proof price data.

The ratio of $A to $B can then be calculated as (exchange rate):

R = $A / $B



* The Canswap platform uses a real-time price feed to gather the current market prices of the assets being traded.
* The platform calculates the exchange rate using the equation provided earlier: Exchange rate = ratio of $A to $B (R)
* This rate is updated in real-time as the prices change to ensure that the user is getting the most up-to-date and accurate rates for their trades.

## 8. **Fees**

   → (For platform) Trading Fees: Users will be charged a small percentage fee for each trade executed on the platform. The exact fee percentage will be set based on community feedback and be updated dynamically based on the current market conditions to ensure healthy liquidity on the platform.  


   -> (For community) Liquidity Provision Fees: Users providing liquidity to the pools on the platform will earn a percentage of the trading fees generated by the pool. The percentage will be set dynamically and adjusted to ensure healthy liquidity on the platform.

## 9. **Roadmap**

**2021**

Q1: Idea conceptualization for Canswap

Q2: canswap.com and canswap.org domain registration

Q3: Market & competitor research

Q4: Early documentation begin 

**2022**

Q1: First draft of litepaper 

Q2: Team building

Q3: Research and development of the smart contract-based trading system and cross-chain communication via stablecoin pools

Q4: Development of cross-chain communication functionality

**2023**

Q1: Website & Final Documentation Live, Waitlist, Fair launch & fundraising, TGE & Uniswap Listing

Q2: Integrating Ethereum & EVM compatible chains to the app, completing front-end, testing and bug fixing of the platform

Q3: Release of the MVP (minimum viable product) for community testing

Q4: Integration of more blockchains

**2024**:

Q1: Launch of the Canswap platform's beta version for public use

Q2: Introduction of a governance model and decentralized decision-making

Q3: Integration of more blockchains 

Q4: Zk proofs integration testing

**2025**: 

Q1: Implementation of privacy features and support for privacy-focused assets, zero-knowledge proofs

Q2:  Continuous improvement and development of new features based on community feedback



# 10. **Business Model**

Canswap will charge a transaction fee on the platform. The exact percentage of the fees will be published later based on community feedback. 

The fees generated on the platform will be utilised as follows: 

→ **Buyback & Burn**: 30% of the fees generated will be used to buy back and burn $CAN tokens, this will decrease the total supply of $CAN and increase the value of the remaining tokens in circulation.

→ **Operation cost**: 20% of the fees generated will be used for platform operations, including development, maintenance, and marketing.

→ **Safu Fund**: 10% of the fees generated will be used for a "safu" fund, which will be used to cover any potential losses or unexpected expenses.

→ **Staking Rewards**: 5% of the fees generated will be used for staking rewards, encouraging users to hold and stake $CAN tokens to support the network.

→ **Treasury**: 35% of the fees generated will be kept in the treasury, mainly for liquidity, to make it easier for users to trade and attract more users to the platform.

The business model is self-sustaining and creates a positive feedback loop where the value of the exchange and token increases as the platform becomes more successful.

The platform will also explore the use of Zero-knowledge technology to enhance privacy and security, this includes privacy-preserving swaps and liquidity provision, staking, governance model, privacy



# 11. **Tokenomics**

**$CAN token**

**Network**: Ethereum

**Standard**: ERC20

**Token Type**: Utility

**Total supply**: 1.000.000.000

**Public Sale**: 500.000.000 (50%)

**Liquidity & Exchanges**: 150.000.000 (15%)

**Marketing**: 100.000.000 (10%)

**Platform Incentives, Staking & Farming**: 50.000.000 (5%)

**Treasury**: 150.000.000 (15%)

**Team**: 50.000.000 (5%)

We will raise a total of $500.000 at an FDV of $1.000.000 and lock 60% ($300.000) in liquidity

1 $CAN in public sale = $0.001

1 ETH (at $1500) = 1.500.000 $CAN

We’re raising a total of 333 $ETH for 500M $CAN tokens \




1. **Governance**: $CAN token holders will be able to vote on proposed changes to the platform and have a say in the direction of the project.
2. **Staking**: $CAN token holders will be able to earn rewards for staking their tokens on the platform.
3. **Liquidity provision**: $CAN token holders will be able to earn rewards for providing liquidity to the pools on the platform.

**$CAN** **Burn**: 30% of the revenue made from the platform will be used to buy back and burn $CAN tokens, which helps to maintain a healthy token economy

**$CAN** **Liquidity**: 35% of the revenue made from the platform will be added to liquidity pools

# 12. **Disclaimer**
This litepaper is a technical description of the Canswap platform and is not a formal offer to sell securities or a solicitation of an offer to buy securities. This document is provided for informational purposes only and does not constitute an offer or a recommendation to buy or sell any securities. The information contained in this document is not intended to be a complete description of the risks associated with investing in the Canswap platform. Any investment decision should be based on appropriate due diligence and research, and investment in the Canswap platform should only be made by individuals who understand the risks associated with such investments. The Canswap platform and its components are still in the development phase and are subject to change. The Canswap platform does not guarantee the performance or success of its services, and the information contained in this document is subject to change without notice.


# References 

 - “An overview on cross-chain: Mechanism, platforms, challenges and
   advances” by Wei Ou, Shiying Huang, Jingjing Zheng, Qionglu Zhang,
   Guang Zeng, Wenbao Han
   (https://www.sciencedirect.com/science/article/pii/S1389128622004121)
   
  - “​​Research on Cross-chain Technology of Blockchain” by Shaofeng Lin,
   Yihan Kong, Shaotao Nie, Wenjia Xie, Jia Du
   (https://ieeexplore.ieee.org/document/9470331)
   
  - “SoK: Communication Across Distributed Ledgers” by Alexei Zamyatin,
   Mustafa Al-Bassam3, Dionysis Zindros, Eleftherios Kokoris-Kogias5,9,
   Pedro Moreno-Sanchez, and Aggelos Kiayias and William J. Knottenbelt1
   (https://eprint.iacr.org/2019/1128.pdf)
   
  - “Uniswap v2 Core” by Hayden Adams, Noah Zinsmeister, Dan Robinson
   (https://uniswap.org/whitepaper.pdf)








