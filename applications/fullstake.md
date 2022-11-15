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
- **Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?** We have some competitors (and in Polkadot/Kusama ecosystem too, such as YieldScan, but hey don't seem to actively developing), and furthermore native Polkadot/Kusama staking is quite convenient, but we clearly understand that in future common DeFi user will need staking aggregator to stake different coins with different wallets.
  - **If so, how is your project different?** 

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
- **Website:** Your website

### Legal Structure

- **Registered Address:** N/A
- **Registered Legal Entity:** N/A

### Team's experience

- **Semenov Kirill** - 4+ years in product management & analytics and 3+ years in traditional entrepreneurship. Ex-Yandex.Taxi (GMV - $7.75Bn in 2021) Product manager, made products that positively affected millions of drivers and passengers. 
- **Daniel Kunis** - 
- **Artem Davletov** - 
- **Mark Grander** - 
Both are experienced blockchain developers who have successfully built from ground-up several projects together: 1) SDK Platform for launching Crypto payments and Rewards in games 2) Analytics of users NFT assets 


Please describe the team's relevant experience. If your project involves development work, we would appreciate it if you singled out a few interesting projects or contributions made by team members in the past. For research-related grants, references to past publications and projects in a related domain are helpful.

If anyone on your team has applied for a grant at the Web3 Foundation previously, please list the name of the project and legal entity here.

### Team Code Repos

- https://github.com/<your_organisation>/<project_1>
- https://github.com/<your_organisation>/<project_2>

Please also provide the GitHub accounts of all team members. If they contain no activity, references to projects hosted elsewhere or live are also fine.

- https://github.com/<team_member_1>
- https://github.com/<team_member_2>

### Team LinkedIn Profiles (if available)

- Semenov Kirill https://www.linkedin.com/in/kstrive/
- Daniel Kunis https://www.linkedin.com/in/dankunis/
- Artem Davletov https://www.linkedin.com/in/artem-davletov-3b8759205/
- Mark Grander https://www.linkedin.com/mwlite/in/mark-grander-a1ba3a210

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/w3f/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Web3 Foundation,
- previous interface iterations, such as mock-ups and wireframes.

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

> :exclamation: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 Example — Basic functionality

- **Estimated duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

> :exclamation: **The default deliverables 0a-0d below are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| **0b.** | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can (for example) spin up one of our Substrate nodes and send test transactions, which will show how the new functionality works. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Docker | We will provide a Dockerfile(s) that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.) |
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be implemented for the first milestone. You can refer to details provided in previous sections.) |
| 2. | Substrate module: Y | The Y Substrate module will... |
| 3. | Substrate module: Z | The Z Substrate module will... |
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |
| 5. | Library: ABC | We will deliver a JS library that will implement the functionality described under "ABC Library" |
| 6. | Smart contracts: ... | We will deliver a set of ink! smart contracts that will...


### Milestone 2 Example — Additional features

- **Estimated Duration:** 1 month
- **FTE:**  1,5
- **Costs:** 8,000 USD

...


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
