# Design Goals
**Factom Creates a Faster, Cheaper, Bloat-free Way to Develop Blockchain Based Applications**

When Satoshi Nakamoto launched the Bitcoin blockchain he revolutionized the way transactions were recorded. There had never before existed a permanent, decentralized, and trustless ledger of records. Developers have rushed to create applications built on top of this ledger. Unfortunately, they have been running into a few core constraints intrinsic to the original design tradeoffs of Bitcoin.

1) Speed – because of the design of the decentralized, proof-of-work consensus method used by Bitcoin, difficulty requirements are adjusted to maintain roughly 10 minute confirmation times. For applications that wish greater security, multiple confirmations may be required. A common requirement is to wait for 6 confirmations, which can lead to wait times over an hour.

2) Cost – the default transaction cost is around .01 mBTC (roughly $0.003 USD in November 2014). The exchange price of BTC has been volatile throughout its history. If the price of BTC rises, then the cost of transactions can go up. This can prove to be a serious cost barrier to applications that need to manage very large numbers of transactions. Additionally, many factors including constraints on block size and reward halving could act to increase transaction fees.

3) Bloat – with the Bitcoin blockchain size limit of 1 MB per block, transaction throughput is capped at 7 transactions per second. Any application that wants to write and store information using the blockchain will add to the traffic. This problem has become politically charged as various parties seek to increase the block size limit.

Factom is a protocol designed to address these three core constraints. Factom creates a protocol for Applications that provide functions and features beyond currency transactions. Factom constructs a standard, effective, and secure foundation for these Applications to run faster, cheaper, and without bloating Bitcoin.
