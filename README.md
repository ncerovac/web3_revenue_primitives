THIS is a living document!  See something you don't like? [File an issue!](https://github.com/FEMBusinessModelsRing/web3_revenue_primitives/issues/new)  Got something you want to see? [File an issue](https://github.com/FEMBusinessModelsRing/web3_revenue_primitives/issues/new)!

# Web 3 Revenue Primitives

<img src='imgs/coins.png'>

*Core primitives* are a set of concepts that are innately understood but cannot be expressed in simpler terms.

This repository is an attempt at list of *web3 revenue primitives*, created by, for, and at [ETHMagicians Prague 2018 by the business models ring](https://hackmd.io/DaJhrasLQteUk3IwX5bQAg?view#8-Business-Models-Ring).

[Notes from Business Models Ring at Eth Magicians, the first session which convened on 2018/10/29, are here](https://hackmd.io/W11KX6Y9R3idXXhN2tHFzA).

## TOC

- [Web 3 Revenue Primitives](#web-3-revenue-primitives)
  * [TOC](#toc)
  * [Marketplace Percentage Fee](#marketplace-percentage-fee)
  * [ICOS](#icos)
  * [Continous Funding Models](#continous-funding-models)
  * [Streaming Money](#streaming-money)
    + [Side Channels:](#side-channels-)
    + [State Channels:](#state-channels-)
  * [Non Fungible Tokens](#non-fungible-tokens)
  * [Subscriptions](#subscriptions)
  * [Self-Sovereign Identity](#self-sovereign-identity)
  * [Lending](#lending)
  * [Curating](#curating)
  * [Creating](#creating)
  * [Funding](#funding)
    + [Budgeting](#budgeting)
      - [Limitations of existing Open Source Budget template:](#limitations-of-existing-open-source-budget-template-)
      - [Treasury management:](#treasury-management-)
      - [Additional thoughts:](#additional-thoughts-)
  * [Advertising](#advertising)
  * [Personal Tokens](#personal-tokens)
  * [Stablecoins Business Models](#stablecoins-business-models)
    + [Fiat-Backed](#fiat-backed)
    + [Crypto-Backed](#crypto-backed)
    + [Algorithmic](#algorithmic)
  * [Questionable / Possible Ponzi Schemes](#questionable---possible-ponzi-schemes)
    + [Rent](#rent)
- [Revenue Models](#revenue-models)
  * [8(+1) types of revenue models](#8--1--types-of-revenue-models)
  * [Why is this important?](#why-is-this-important-)
  * [Examples of disruptive business / revenue models](#examples-of-disruptive-business---revenue-models)
  * [New revenue models](#new-revenue-models)
- [Web2 Revenue Models](#web2-revenue-models)
  * [Examples](#examples)
      - [Advertising Model](#advertising-model)
      - [Commerce Model](#commerce-model)
      - [Subscription Model](#subscription-model)
      - [Freemium Model](#freemium-model)
      - [Peer to Peer Model](#peer-to-peer-model)
      - [Transaction Processing Model](#transaction-processing-model)
      - [Licensing Model](#licensing-model)
      - [Data Model](#data-model)
- [What did we miss?](#what-did-we-miss-)



## Marketplace Percentage Fee

This model is where you take a % of each trsanction on your platform.  It is popular with exchanges.

## ICOS

Sell a bunch of ERC20 tokens at once, or during a window of time.

Some popular ICO models:

* [Security Token Offerings](https://blockgeeks.com/guides/security-tokens/)
* [Interactive ICO](https://medium.com/legal-block/interactive-coin-offering-a-token-distribution-alternative-model-or-the-new-face-of-the-ipos-61eee71e75ef)
* [Initial Supply Auction](https://medium.com/@MetronomeToken/metronomes-initial-supply-auction-quick-glance-price-chart-c9132595871e)
* [Simple Agreement for Future Tokens](https://medium.com/@argongroup/explaining-the-simple-agreement-for-future-tokens-framework-15d5e7543323)
* [Cryptocurrency Airdrop](https://en.wikipedia.org/wiki/Airdrop_(cryptocurrency))

Some popular ICOs:

* [Neo(China's Ethereum)](https://www.investinblockchain.com/what-is-neo/)
* [Stratis](https://www.investinblockchain.com/invest-in-stratis/)
* [Ark](https://www.investinblockchain.com/what-is-ark/)
* [Populous](https://www.investinblockchain.com/what-is-populous/)

Types of tokens:

* [Utility Token](https://medium.com/coinmonks/utility-tokens-a-general-understanding-f6a5f9699cc0)
* [Equity/Security Token](https://blockgeeks.com/guides/security-tokens/)
* [Currency Token](https://cryptocurrencyfacts.com/what-is-a-cryptocurrency-token/)
* [Reward Token](https://bitcoinexchangeguide.com/rewards-token-ico/)
* [Asset Token](https://medium.com/pecunio/the-rise-of-asset-backed-tokens-90570438261c)

## Continous Funding Models

Sell a bunch of ERC20 tokens *over time*.

* [Continuous Organizations](https://medium.com/@thibauld/introducing-continuous-organizations-22ad9d1f63b7?_branch_match_id=578515516036471346)
* [Curved Bonding](https://medium.com/@simondlr/tokens-2-0-curved-token-bonding-in-curation-markets-1764a2e0bee5)

## Streaming Money

### Side Channels:
A sidechain is a separate blockchain that is attached to its parent blockchain(mainchain) using a two-way peg. You can move assets to the sidechain and then back to the parent chain.
Sidechains need their own miners. These miners can be incentivized through ‘merged mining’, whereby two separate cryptocurrencies, based on the same algorithm, are mined simultaneously.
Here is a list of some of the Sidechain Projects:

* [Plasma](http://plasma.io/)
* [Loom](https://loomx.io/)
* [POA](https://poa.network/)
* [Truebit](https://truebit.io/)

### State Channels:
State channels are basically two-way pathways opened between two users that want to communicate with each other in the form of transactions. Here, only the final outcome needs to be included in the form of one single transaction on main chain. Other transaction's are done on off chain. Few know projects around it are:

* [Raiden Network](https://raiden.network/)
* [Machinomy](https://machinomy.com/)
* [FunFair](https://funfair.io/)
* [Liquidity](https://liquidity.network/)
* [Trinity](https://trinity.tech/#/)
* [Celer](https://www.celer.network/)
* [Spankchain](https://spankchain.com/)
* [Connext](https://connext.network/)
* [Counterfactual](https://counterfactual.com/)

## Non Fungible Tokens

Non fungible tokens are tokens that are unique from one another

Famous NFT projects:

* [CryptoKitties](https://medium.com/@codetractio/a-look-into-cryptokitties-revenue-model-6466b705a998)
* [OpenSea NFT marketplace](http://opensea.io)

## Subscriptions

Subscriptions are a recurring exchange of value over time.

* [EIP 1337](https://github.com/ethereum/EIPs/pull/1337)
* [1337 Alliance](https://1337alliance.com)

## Self-Sovereign Identity

Identity Standards Proposals:
* [EIP 725](https://github.com/ethereum/EIPs/issues/725)
* [EIP 725 Alliance](https://erc725alliance.org/)
* [EIP 1056](https://github.com/ethereum/EIPs/issues/1056) and [ERC 780](https://github.com/ethereum/EIPs/issues/780)
* [Identity Foundation](https://identity.foundation/)
* [Decentralized Identifiers (DID)](https://w3c-ccg.github.io/did-spec/)

Projects in the Identity space:
* [uPort](https://uport.me)
* [Civic](https://www.civic.com/)
* [BloomID](https://bloom.co/identity/)
* [TENZ-ID](https://tenzorum.org/tenz_id/)
* [Ethereum Name Service](https://ens.domains)

## Lending

Smart contracts that control credit scores, loan issuance, and interest payments will run on top of protocols like Ethereum. These debt contracts will be hashed into existence and generate hashflow for the lenders. This is a flow of hashflow above the base layer protocol.

* [Dharma Protocol](https://dharma.io/)
* [LoanScan](https://loanscan.io/)

## Curating

The job of a search engine like Google is to collect and curate data from the Internet. This is one of the most valuable curation projects in the world. The key with curation markets is to get all of the incentives aligned so that you can trust the underlying data. The term used in the industry is the Token Curated Registry.
It’s not just about creating a list. It’s about creating a list you can trust by incentivising curators to do the research for you.

* [Ocean Protocol](https://oceanprotocol.com/)
* [Messari](https://messari.io/)

## Creating

The creation of new things on chains will have value. Selling them to people who want them will generate hashflow. Making these unique tokens takes a lot of effort. You have to get a community of people to agree to their value.

* [Cryptokitties](https://www.cryptokitties.co/)

## Funding

Funding is the same whether it is at the ecosystem level or at the level of a single entity wanting to support funding. Grants are the main source of funding for projects in the Ethereum Community. Grants give a short time horizon for projects and don’t take into consideration the setup costs. Once a project has been set up, maintenance requires longer-term funding than grants provided. In many cases for an individual or small team, a business model of services can be considered on a project to project basis to find long term support. Operational costs hit projects with real-world budget and cash flow problems, and decentralized projects excel when they gather together for support. 

There is no one entity in charge of Ethereum, so the community must look at different funding bodies and revenue streams. For decentralized projects, it is a good idea to have different funding for different aspects of the ecosystem, such as stack, research, or community.  Obtaining multiple entities to fund a project is part of the shared ecosystem of Ethereum. Multiple entities of funding stop the community from defunding project Y, and instead disperse funding to both project X and Y. To get funding and sustainability of a project, it is best to collaborate with others who want to support the infrastructure, rather than waste time on putting together grant systems.

* [Funding Taxonomy](https://ethereum-magicians.org/t/funding-taxonomy-issues-for-ethereum-ecosystem/2014)
* [Funding Opportunities](https://github.com/fredexed/crypto-funding-ops)
* [Web3 Grants](https://hackmd.io/z5zFMTjiRJqs-4Wm43bJtQ)

### Budgeting
Closely associated to funding, budgeting and appropriating long-term cashflow is essential for the success of Ethereum projects, teams, and individuals. With an increasing focus on long-term sustainability, it is essential to outline a fundamental budget to track funds and plan for the foreseeable future. The [Open Source Budget](https://docs.google.com/spreadsheets/d/1CqaIu4ZupDWU0IedRXQw2coJptUhhyyMTu7ep6nNmIU/edit#gid=989402327) template by Boris Mann simplifies this concept into a simple, single currency spreadsheet for tracking expenses, basic payroll, and funding sources, in order to provide an outlook into long-term financial stability.

#### Limitations of existing Open Source Budget template:
  
  Identified limitations of the Open Source Budget template should be taken into consideration by Ethereum projects, teams, or individuals. These include:
  
  * The template assumes zero cost for an office or hardware.
  * The template does not factor in annual taxation or tax subsidization.
  * The template provides the "break-even" for a project, ignoring the potential need of a margin, or, buffer.

#### Treasury management:

  With projects being built on Ethereum, treasury management is also essential. Highlighted in a [Twitter thread](https://twitter.com/DeanEigenmann/status/1064723747582619648), it is generally recommended by Boris to keep upwards of six months of expenses for a team as a buffer. In addition, teams and projects should clarify their policies on payroll and payable expenses, to prevent market instability and variance from affecting their budgets (in the case that their budget is primarily in Ethereum or other non-fiat currencies).

#### Additional thoughts:

  With grants being main sources of funding for projects in the Ethereum Community, understanding their impact to long-term security & sustainability is essential. While one-off bounties and small grants may fund for the short-term, projects should look into additional sources of funding to ensure that they: (1) do not have to devote time and value to search for additional short-term funding, and (2) have a sustainable source of funding for their foreseeable project runway.

## Advertising

There are some options for doing advertising-based business models for open source projects, listed below.

* [CodeFund](http://codefund.app)

## Personal Tokens
Personal tokens are fixed-supply and -cost ERC20 tokens that derive their value from the performance of a human being. They are commonly used to tokenize either individual service offerings or a fixed-price hourly service.

* [DAppBoi](https://dappboi.com/)

  DAppBoi is an example of a personal token which tokenizes an hour of digital work by designer Matthew Vernon. By initiating the ERC20 token with a fixed supply of 100 $BOI tokens, purchasable directly from Matthew for 0.65ETH each, this personal token allows an individual to effectively purchase, trade, and invest in Matthew's design skillset.

  The tokens are redeemed by sending them to Matthew, who in exchange for 1 $BOI token provides 1 hour of design work. By using a personal token, not only does Matthew create demand for his skillset through a fixed token supply, but he also ensures that he will receive a minimum of 0.65ETH for each hour he works, since he is the primary supplier of the token and hence, regulates its price. In addition, using a personal token ensures that even if the market price for $BOI falls, Matthew will have already been compensated at his pre-determined hourly rate for the tokens in circulation.

  In the case that Matthew denies service to an individual who redeems $BOI, although the market valuation for the token may fall, Matthew has already been paid in advance for the initial purchase, thus, fulfilling his hourly rate.

## Stablecoins Business Models

The main component behind stablecoins capturing value in a market is seigniorage. This is profit made by issuing currency, which is generated from the difference of the face value of the currency and its production costs. The three major types of stablecoins are:

* Fiat-backed
* Crypto-backed
* Algorithmic

### Fiat-Backed

A fiat-backed stablecoin system will collateralize every stablecoin issued with fiat currency or some other non-crypto asset. The fiat currency is stored with some custodian, such as a bank or major institution. 

These stable coins can generate revenue from collecting fees on issuing/redeeming stablecoins, market-making, or short-term lending. The most popular fiat stablecoin systems today are:
* [Tether](https://tether.to/)
* [TrueUSD](https://www.trusttoken.com/trueusd/)

### Crypto-Backed

Crypto-backed systems provide decentralized ways to maintain claims on collateral. Reserves of collateral are kept in the form of crypto-assets (such as ETH) on smart contracts. All issued stablecoins are backed by these reserves of ‘volatility coin’ collateral.

Crypto-backed stablecoin systems focus more on the volatility coin put up as collateral to generate revenue. These systems can collect transaction fees created on-chain. Holders of the volatility coin are then paid proportionally.
In the case of Maker, they issue stablecoins as collateralized debt positions, which accumulate interest at an annual rate of 2.5%. The interest is again paid proportionally to those holding on the volatility coin. Other crypto-backed stablecoins have issued shares for collateral assets, which can be redeemed in exchange for stablecoins or another asset. Check out:
* [Maker](https://makerdao.com/en/)
* [Havven](https://www.synthetix.io/)

### Algorithmic

A newer business model, algorithmic stablecoins adjust supply to stabilize price without collateral requirements. These stablecoins may use a volatility coin to capitalize the system at first. This system is very lucrative due to the fact that all supply increases in the stablecoin are distributed to those holding on to the volatility coin.

These stablecoin systems can issue shares called seigniorage shares. When there is demand for more stablecoins, more are issued to offset demand and keep price level. If demand decreases and price of stablecoins fall, shares are put up for sale in exchange for stablecoins, which are then burnt from supply. Therefore, if the market cap of stable coins reaches a certain level, the value of all seigniorage shares will be at that same level.

Another revenue-generating tactic are variable interest rate deposits, where users can deposit stablecoins into smart contracts that pay out interest. When demand is low, interest rates are increased to incentivize depositing stablecoins, which lowers the circulating supply of stablecoins and price increases; and vice-versa.

## Questionable / Possible Ponzi Schemes

TODO - What else should live here?

* [Fomo3d](https://medium.com/@eetusro/i-note-this-is-fin-e-6646f4a1e55b)

### Rent

* [Determining a fair rent model of ENS](https://discuss.ens.domains/t/determining-a-fair-rent-model/603) = NOTE: At ENS, the purpose of the rent is to avoid squatters rather than making profit

# Revenue Models

This breaks down business revenue models into 8 types and provides examples of each. In addition, we reference Ben Wenmuller’s series of tweets with a potentially new business model for decentralized platforms - capital gains.

## 8(+1) types of revenue models

||Description|Examples|
|--- |--- |--- |
|Unit sales|Sell a product or service to customers|Daily necessities at local market|
|Advertising fees|Sell others opportunities to distribute their message on your space.|Billboards, banner ads, search engine ads|
|Franchise fees|Sell the right for others to invest and manage a version of your business.|Fast food restaurants, e-sports leagues|
|Utility fees|Sell goods and services on a metered basis.|Road tolls, electricity and water bills|
|Subscription fees|Charge a fixed price for access to services for a set period of time.|Video and music streaming, gym memberships|
|Transaction fees|Charge a fee for referring, enabling, or executing a transaction between parties.|Credit card merchant fees, online stock trades|
|Professional fees|Provide professional services on a time-and-materials contract.|Lawyers, accountants, real estate agents|
|License fees|Sell the rights to use intellectual property.|Physical toys based on movie characters|
|Capital gains*|Rises in asset value (i.e. tokens) will benefit both the decentralized platform and its users/hodlers|Decentralized startups|


[*As proposed by Ben Werdmuller’s tweets.](https://twitter.com/benwerd/status/1060209690808745985)

## Why is this important?
A company’s revenue model, very simply, is the way it makes money. New applications of revenue models against traditional revenue models can create disruptive new businesses.

## Examples of disruptive business / revenue models
Video Entertainment

Company A - retail stores, charge per rental (unit sales)

Company B - online “DVDs-by-mail”, monthly fee (subscription)

## New revenue models
How can decentralized platforms up-end the revenue models for businesses that seem to have their revenue model locked in?

For example, payments, which has been based on utility fees.

# Web2 Revenue Models

 The system designed by which a business monitizes its services
---
*"The ideal revenue model will be one that improves the user experience, or at least in no way harms it."*

| Model     |                                      Description                                      | Examples |
|:------------------------:|-------------------------------------------------------------------------------------|:----------:|
| Advertising            |       Service is free to use, marketers pay to reach your users via advertising       | [examples](#advertising-model) |
| Commerce               |             Sell something to your users, keep some or all of the proceeds            | [examples](#commerce-model) |
| Subscription           |     Charge your users monthly or annually for the opportunity to use your service     | [examples](#subscription-model) |
| Freemium          |     Sell a basic free product to as many customers as possible, but keep the premium features exclusively for paying customers     | [examples](#freemium-model) |
| Peer to Peer           |  Connect people together in a network, take a small piece of the activity that ensues | [examples](#peer-to-peer-model) |
| Transaction Processing |      Settle transactions, then take a small piece of the transaction for doing so     | [examples](#transaction-processing-model) |
| Licensing              |          Charge users once upfront for the opportunity to use your technology         | [examples](#licensing-model) |
| Data                   |                          Sell the data your service generates                         | [examples](#data-model) |
| Mobile                 | Not a revenue model but presents unique challenges and opportunities for monetization | [itunes app store](https://itunes.apple.com/us/genre/ios/id36?mt=8) |
| Gaming                 | Not a revenue model but presents unique challenges and opportunities for monetization | [steam](https://store.steampowered.com) |

These categories are not mutually exclusive. Many web/mobile services use multiple revenue models. Freemium for example is a combination of advertising & subscription.
---
## Examples

#### Advertising Model
* Search Ads - [Google](https://google.com)
* Video Ads - [Youtube](https://youtube.com)
* Location-based Ads - [Foursquare](https://foursquare.com)

#### Commerce Model
* Group buying - [Groupon](https://groupon.com)
* Digital goods/downloads - [Itunes](https://itunes.com)
* Auction commerce - [Ebay](https://ebay.com)

#### Subscription Model
* Software as a Service (SaaS) - [FreshDesk](https://freshdesk.com)
* Infrastructure as a Service (IaaS) - [AWS](https://aws.amazon.com/)
* Membership services - [Amazon Prime](https://www.amazon.com/gp/prime
)

#### Freemium Model
* [Dropbox](https://dropbox.com)
<img src='imgs/dropbox.jpg'>

* [Adobe](https://adobe.com)
* [LinkedIn](https://linkedin.com)

#### Peer to Peer Model
* [Airbnb](https://airbnb.com)
* [Uber](https://uber.com)
* [Match.com](https://match.com)

#### Transaction Processing Model
* [Paypal](https://paypal.com)
* [Stripe](https://stripe.com)
* [Google Pay](https://pay.google.com/)

#### Licensing Model
* Per Device/Server License – [Microsoft products](https://microsoft.com)
* Per Application instance – [Adobe Photoshop](https://adobe.com)
* Patent Licensing – [Qualcomm](https://qualcomm.com)

#### Data Model
* User data - [LinkedIn](https://linkedin.com)
* Search data - [Google](https://google.com)
* Benchmarking services – [Comscore](https://comscore.com)

# What did we miss?  

Coming to Prague this October? [Join us on the business model ring at ETHMagicians 2018](https://hackmd.io/DaJhrasLQteUk3IwX5bQAg?view#8-Business-Models-Ring)

Remote? [Open an issue and let us know](https://github.com/owocki/web3_revenue_primitives/issues/new), or, even better, [open up a PR](https://github.com/owocki/web3_revenue_primitives/compare).

<!-- Google Analytics -->
<img src='https://ga-beacon.appspot.com/UA-1014419-15/owocki/web3_revenue_primitives' style='width:1px; height:1px;' >
