# FlashBots

Flashbots is a research and development organization working on mitigating the negative externalities of current Maximal Extractable Value (from now on MEV) extraction techniques and avoiding the existential risks MEV could cause to state-rich blockchains like Ethereum.

# What is MEV?

In a nutshell, it's the concept of extracting value (profit) by making certain types of transactions on chain that are not block rewards themselves. Originally, it started happening because miners had control over which transactions they'd like to include in a block, and in which order. Since when creating a block, miners can include, exclude and change the transactions of the block as they wish, this means they can favor some transactions as compared to others and gain some additional profits by doing so. Note that we are talking about miners right now but things will change after the merge.

Typically, MEV happens when a certain transaction must be included in a certain block (usually the current block) to actually be profitable. Additionally, it sometimes may also need to be in a specific place in the block - for example buying a highly contested NFT drop right after the contract gets deployed, within the same block the contract was deployed, unlike us normies who wait at least until the next block so Metamask recognizes the contract as having been deployed before it sends a transaction out by which time gas price may have gone up significantly.


## Resource to learn more about MEV
[Flashbots Docs](https://docs.flashbots.net/)

