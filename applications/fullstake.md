# FullStake - all-chain staking aggregator

- **Team Name:** FullStake
- **Payment Address:** **TBD** BTC, Ethereum (USDT/USDC/DAI) or Polkadot/Kusama (aUSD) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2

> :exclamation: *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

### Overview

Staking flows are mostly complicated and time-consuming. Most users/stakers want a transparent and risk-free 1-click solution for staking and an easy way to analyze a diversified portfolio (the average DeFi investor has 3-4 coins and 2-3 wallets). It is caused by a fast-growing amount of PoS blockchains (right now it is around 100 networks).

From the validator perspective, our product solves the problem of stakers activation. All validators have to provide big text instructions on how to stake. Also, right now it is not guaranteed that the user will stake through the validator that acquired him. 

### Project Details
Currently we are at a stage when we already conducted user research, designed an MVP for our product and are ready for development. We are also actively fundraising (VCs, angels and accelerators). 

These are our main conclusions of user researches: 

**Users/stakers insights**
1. Staking flows are usually very complicated and time-consuming and vary between networks. All users want a “1-click” solution for staking 
2. Almost all native staking platforms provide poor analytics (transaction history, income visualization, normalization per USD, etc.). Because of that, they struggle to analyze their investments, only rough calculations
3. It is very uncomfortable if network doesn’t have auto-claim or auto-compound of rewards - users often forget to claim rewards in order to reinvest it 
4. Users have trust issues about signing transactions in wallets, that’s why some of them are afraid of using financial instruments like staking, liquidity pools etc.
5. Not all networks provide an interface for a fast diversification of validators. Users can spend extra hours making a diversified staking portfolio. It is also very inconvenient to unstake from each validator separately.  
6. CEXs stakers are really angry when they face limits for staking amount, less APR than in native staking 

**Validators insights**
1. Validators are always ready for delegations, so they are ready for revenue-share model if it is transparently visible that the additional stake came from our product
2. Right now validators have to put a huge list of different methods on how to stake (e.g. https://everstake.one/). They are losing potential customers on this step. 
3. Sometimes they have a negative economy (e.g. when the price of the coin is dumping), at such moments they are ready to pay more
4. They are also ready to pay more, when they need extra stake to be evaluated to the active validator pool


This is our [concept prototype](https://www.figma.com/proto/Fxsokt9nsc4tqqCVavKsLf/Mockups?page-id=24%3A2&node-id=875%3A712&viewport=335%2C-2155%2C0.47&scaling=scale-down&starting-point-node-id=875%3A712) based on these researches. We are constantly revising it, though general user flow and feature list are determined. 

We have a [pitch deck](https://drive.google.com/file/d/1tkX9N1MPkBlO3Zi_7_oWb544peJ5r6yA/view?usp=sharing) that also covers market, monetization, product-market fit and go-to-market strategy. 

### Ecosystem Fit

- **Where and how does your project fit into the ecosystem?** We help nominators stake easily and fast and validators to attract new users. Also, we believe that we will increase security and decentralization of blockchain. 
- **Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?** Basically, we have 2 target audiences: 
  - Nominators/stakers with diversified portfolio.
  - Validators. 
- **What need(s) does your project meet?**
  - For nominators we give fast and easy 1-click staking instrument with cross-wallet/chain analytics.
  - For validators we fix the last-step conversion by giving fast, simple and native solution - no more huge amount of instructions on how to stake through different platfrosm, just FullStake.
  - For Polkadot / Kusama we make staking more accessible that will result in increased total staking capilization and network decentralization
- **Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?** We have some competitors (and in Polkadot/Kusama ecosystem too, such as YieldScan), and furthermore native Polkadot/Kusama staking is quite convenient, but we clearly understand that in the future 1-click staking will become a commodity and we want to hasten that day.
  - **If so, how is your project different?** 
    1. Our secret sauce is that we provide unified 1-click staking in top PoS blockchains by wrapping native staking into our own smart contract.  
    3. We do product for conservative investors that want to avoid additional risks and value transparency. We don't have our own token and we don't hold our users money.
    4. We aim to be cross-chain & cross-wallet and cover all PoS blockchains, because most of our users hold diversified portfolio.
    5. We also focus on bringing value to validators, so they could have a tool for more efficient customer acquisition.

## Team :busts_in_silhouette:

### Team members

Our business and product part: 
- Semenov Kirill
- Daniel Kunis

Our dev part:
- Artem Davletov
- Mark Grander

### Contact

- **Contact Name:** Kirill Semenov
- **Contact Email:** stakefull@gmail.com

### Legal Structure


- **Registered Address:** N/A
- **Registered Legal Entity:** N/A

### Team's experience

- **Semenov Kirill** - 4+ years in product management & analytics and 3+ years in traditional entrepreneurship. Ex-Yandex.Taxi (GMV - $7.75Bn in 2021) Product manager, made products that positively affected millions of drivers and passengers. 
- **Daniel Kunis** - 2+ years in iOS development & 1,5 year as PM in Yandex and Jetbrains Kotlin Team. 
- **Artem Davletov & Mark Grander** - both are experienced blockchain developers who have successfully built from ground-up several projects together: 1) SDK Platform for launching Crypto payments and Rewards in games 2) Analytics of users NFT assets 

### Team Code Repos

Source codes will reside in:
- https://github.com/fullstake-web3

GitHub accounts of team members:
- https://github.com/dankunis
- https://github.com/ArtemDavletov

### Team LinkedIn Profiles

- Semenov Kirill https://www.linkedin.com/in/kstrive/
- Daniel Kunis https://www.linkedin.com/in/dankunis/
- Artem Davletov https://www.linkedin.com/in/artem-davletov-3b8759205/
- Mark Grander https://www.linkedin.com/mwlite/in/mark-grander-a1ba3a210

## Development Roadmap :nut_and_bolt:

We want to focus on unifying all the staking processes into simple and fast flow. In order to do that, we want to implement only staking pools in Polkadot/Kusama chains.  

### Overview

- **Total Estimated Duration:** 3 months
- **Full-Time Equivalent (FTE):**  4 FTE
- **Total Costs:** 30,000 USD

### Milestone 1 — Backend part

- **Estimated duration:** 1,5 month
- **FTE:**  3
- **Costs:** 15,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 |
| **0b.** | Documentation | We will provide **inline documentation.** in our Github repisitory. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an article on our Medium that explains our backend structure |
| 1. | Wallet integration | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 3. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 4. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will...


### Milestone 2  — Frontend part

- **Estimated Duration:** 1,5 month
- **FTE:**  3
- **Costs:** 15,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 |
| **0b.** | Documentation | We will record a video tutorial on how to use our platform from the nominators perspective. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate module: Y | The Y Substrate module will... |
| 3. | Substrate module: Z | The Z Substrate module will... |
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 5. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 6. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will...

## Future Plans

We are fully-commited to this project, we even left our 9-5 jobs becase we believe in our unique product insights and each other. We're seeking fundraising to eventually become a sustainable business. 

Our go to market strategy is to partner with validators so they would use FullStake to attract new stakers. There are around 500,000 validators across all chains and all of them lack a good user activation solution (see how a top validator company explains how to stake through them https://everstake.one/near). We will distribute our product providing a “click the link to stake through us” solution for validators which will increase validators last-step conversion.

However we see staking as step 1 where we build a profitable business and, most importantly, gain a user base. Our big vision is to create a mobile-first WeChat-alike SuperApp for DeFi. Just like Web2, we believe Web3 will definitely become mobile-first and currently there is no widely adopted solution that would let Polkadot dApps communicate seamlessly between each other like they do via browser extensions on desktop. From the user perspective we plan to become an entry point into DeFi and we will achieve this by providing a platform-native infrastructure and SDK for app development that would ease web-to-mobile transition.
To sum up, we start with staking to gain trust, users and technical base and then proceed to build a mobile-first ecosystem for developers and users. 

## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website
