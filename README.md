# awesome-ethmergedata
All things ethereum data related to PoS, MEV, PBS and other tasty things

*A list of resources for tracking Ethereum data dashboards and tools for monitoring. We take no responsibility for the accuracy of the data published. Be aware of different biases and definitions used across dashboards.*

## Intro

With the Merge going through successfully, Ethereum has changed permanently. If you are not familiar with the details, [here’s a good primer](https://coinmetrics.io/special-insights/ethereum-merge/). The new process for adding transactions to the chain has significant trade-offs with respect to [economics](http://ultrasound.money), [energy usage](https://ethereum.org/en/energy-consumption/), [MEV](https://github.com/flashbots/eth2-research), [censorship](https://notes.ethereum.org/@vbuterin/pbs_censorship_resistance)-[resistance](https://github.com/flashbots/mev-boost/issues/215), security and [centralization](https://noxx.substack.com/p/order-flows-kingmaker-of-the-block).

The data is crucial to monitor, track and interpret progress of these dimensions. This post intends to provide a coherent library of twitter accounts, dashboards, data tools and other lists. We will do our best to keep it up to date, although this space moves very quickly.

If you have feedback, additions or questions, [feel free to reach out](mailto:contact@inflection.xyz).

## Glossary

### Types

There are five types of resources:

1. **Twitter accounts** to follow to understand the space (excl. accounts of the dashboards), e.g., @blink_labs_xyz
2. **Dashboards** of live data, e.g., [ultrasound.money](http://ultrasound.money) 
3. **Repos** of tools you can use to extract data yourself
4. **Meta-lists** which are lists in themselves
5. **Raw-data** which are API's or published raw data

### Coverage

The resources cover different data points, for ease of use, the resources are classified according to what they are focused on.

Blocks: blocks built, proposed and finalized

Builder: proposes blocks to validators, through relays

Burn: Eth reduction of supply through fee burn due to EIP-1559

MEV: Maximal extractable value

MEV-Boost: Intermediate design towards full PBS, proposed by Flashbots

Validator: Consensus participant 

Relay: Relays blocks from builders to validators

Rewards: Eth earned of different participants

Supply: Amount of eth in circulation and staked

## Twitter-accounts
| Description | URL | Coverage | Interesting because | Affiliation |
|:--|:--|:--|:--|:--|
EthStakerBot tweeting high proposer payments to validators | https://twitter.com/mevproposerbot?s=21&t=xgb8KRm9heGyFERearZuKQ | MEV-boost, Rewards | In the last week (28.09-05.10) the highest payment to validator was 30.896 ETH | Personal |
Tweets big MEV rewards|https://twitter.com/MevBoostBot | MEV, Rewards | 8ETH paid out in miner rewards in one bundle | 
EF guy and definer of relay monitor specs|https://twitter.com/ralexstokes|Twitter account|MEV-boost, Relay|https://twitter.com/ralexstokes/status/1573314707586686976| EF |
BloXroute COO | https://twitter.com/eyalmarkov |  Builder, Relay, Rewards, Validator | https://twitter.com/eyalmarkov/status/1572616363054612486| BloXroute |
Co-founder of Prysm labs and builder of Eth client|https://twitter.com/terencechain |  Blocks, Validator | https://github.com/rated-network/eth2REKT | Prysmatic labs
Data analysts highlighting  findings on block builders and others| https://twitter.com/blink_labs_xyz |  Builder, Relay, Validator | https://twitter.com/blink_labs_xyz/status/1572687125136678912/photo/1 | Blink Labs
