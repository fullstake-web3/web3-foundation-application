# FullStake - all-chain staking aggregator

- **Team Name:** FullStake
- **Payment Address:** **TBD** BTC, Ethereum (USDT/USDC/DAI) or Polkadot/Kusama (aUSD) payment address. Please also specify the currency. (e.g. 0x8920... (DAI))
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2

> :exclamation: *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

### Overview

FullStake is a cross-chain staking aggregator that brings value to nominators, validators and blockchain itself. Concept of our product assumes integration of all popular PoS blockhains, especially Polkadot and Kusama. For nominators we provide a single-interface for staking/unstaking and reward collection for all of his possible portfolio assets. For validators we provide a tool that will help them acquire new users easier. We also believe that by making staking user-friendly and accessible we will increase amount of staked assets and adoption. 

From the user perspective our product solves the problem of native staking and analysing the whole portfolio within a single interface in DeFi. Based on our research, an average DeFi enthusiast owns at least 2-3 wallets and 4-5 different tokens. Every PoS chain has its own staking protocol which requires different actions in order to stake. Firstly, this makes staking more than 1 token inconvenient and hardly scalable for the end user. Secondly, having many different platforms for staking makes it impossible to analyse your portfolio’s profitability.

From the validator perspective our product solves the problem of nominator activation. Right now current staking solutions don't attach the user to the validator that initially acquired the user. Hence, it lowers marketing performance and efficiency. That's exactly what we try to solve. 

### Project Details

We began our work by researching our 2 users: nominators and validators. We 15 user interviews for each segment. This is our main conclusions: 
1. Nominators have problems with staking in new network and managing their diversified portfolio. They don't really want to know about choosing validators, their uptime and reputation, but they want to track 2 things: 
- How much I invest
- How much I will have in X period after comission 
And of course they want to maximize their profit with minimum risk. That's it, no more details, such as, how to bridge coins into another blockchains and then swap it to stake. 
2. Validators are too many clicks away from stakers to have effective marketing. That's why they need "click the link below" solution for fast and convenient staking. 

Then we made a [concept prototype](https://www.figma.com/proto/Fxsokt9nsc4tqqCVavKsLf/Mockups?page-id=24%3A2&node-id=875%3A712&viewport=335%2C-2155%2C0.47&scaling=scale-down&starting-point-node-id=875%3A712) based on these researches. We are constantly improving details and feature, though concept user flow and feature list are determined. 

We also have a [pitch deck](https://drive.google.com/file/d/1tkX9N1MPkBlO3Zi_7_oWb544peJ5r6yA/view?usp=sharing) that also covers market, monetization, product-market fit and go-to-market strategy. 

### Ecosystem Fit

- **Where and how does your project fit into the ecosystem?** We help nominators manage their staking and validators to attract new users. Also, we believe that we will increase security and decentralization of blockchain. 
- **Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?** Basically, we have 2 TAs: 
  - Nominators/stakers with diversified portfolio.
  - Validators. 
- **What need(s) does your project meet?**
  - For nominators we solve problem of staking on different wallets/sites. From this problem follows the need of cross-wallet/chain analytics. 
  - For validators we fix the last-step conversion by giving fast, simple and native solution - no more huge amount of instructions on how to stake through different platfrosm, just FullStake.
- **Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?** We have some competitors (and in Polkadot/Kusama ecosystem too, such as YieldScan), and furthermore native Polkadot/Kusama staking is quite convenient, but we clearly understand that in future common DeFi user will need staking aggregator to stake different coins with different wallets.
  - **If so, how is your project different?** 
    1. Our first differentiation from competitors is that we do product for conservative investors, that want to avoid additional risks and value transparency. We don't have our own token and we don't hold our users money.
    2. We aim to be cross-chain & cross-wallet and cover all PoS blockchains, because most of our users hold diversified portfolio.
    3. We also focus on bringing value to validators, so they could have a tool for more efficient customer acquisition.

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

Please include here

- how you intend to use, enhance, promote and support your project in the short term, and
- the team's long-term plans and intentions in relation to it.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.
