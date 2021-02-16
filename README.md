# Contribute to MEV-Explore

Hey! Thanks for your interest in contributing to MEV-Explore. MEV-Explore v0 exists thanks to the many community contributors who have participated to it, join us!

For starters, we recommend you to join the [#MEV-Explore channel](link) of our Discord and to check out MEV-Explore's [Metholodogy](https://explore.flashbots.net/methodology) page for an explanation of how we've arrived at this dashboard and our data collection process.

## Relevant repos to MEV-Explore
The repos in the Flashbots organization connected to MEV-Explore are the following:

* [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs)
* [mev-inspect-logs](https://github.com/flashbots/mev-inspect-logs)

## Ways to contribute

### Help us expand our protocol coverage by writing inspectors

Requirements: 
* proficiency in Rust or Javascript
* understanding of smart contract logic

Inspectors currently missing include:
* Swerve arbitrage
* Bancor arbitrage
* Kyber Network arbitrage
* DyDx liquidations - existing work by @brockelmore [here](https://github.com/flashbots/mev-inspect-logs/blob/main/scripts/getDydxLiqs.js)
* Mooniswap arbitrage
* DODO arbitrage
* ESD/DSD incentivized clipper inspectors - existing work by @austin-williams [here](https://github.com/flashbots/mev-inspect-logs/issues/1)


### Help us improve the quality of our data

Requirements:
* no specific coding skill required
* an understanding of value flow within an Ethereum transaction

Our data collection approach is far from perfect and we need as much help we can get in spotting misclassified transactions. You can see some individual transactions we classify in the [Leaderboard](https://explore.flashbots.net/leaderboard) page of the dashboard.

There are several kinds of misclassified transactions:
* a transaction we've classified as MEV but that isn't
* a transaction that has a different revenue and/or tx_fee than the one we're showing for it

For any misclassified transaction you find, please open an issue on here for us to look at it, prune it from our db and add a filter to our crawlers to ignore similar transactions in the future or correct the calculation error.

### General feedback 

Requirements:
* be kind

As a user of MEV-Explore, help us improve it by suggesting new visualizations and metrics that would be useful to you, your project or your research group. You can do that in the ['Discussions'](link) tab of this repository so that others can join in.


## Resources

* [MEV-Explore dashboard](https://explore.flashbots.net)
* [MEV-Explore blogpost](link)
* [MEV-Inspect codebase](https://github.com/flashbots/mev-inspect-rs)
* [Flashbots PM repo](https://github.com/flashbots/pm)
* [Flashbots Discord](https://discord.gg/7hvTycdNcK)


⚡️🤖
