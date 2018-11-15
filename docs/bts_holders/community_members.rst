
**********************
Community Memberships
**********************


.. contents:: Table of Contents
   :local:
   
About BitShares Members  
============================== 

BitShares 2.0 separates responsibilities and incentives activities that are beneficial to the network, thus acknowledging different skill sets and interested community members to have incentives to contribute in the most appropriate way.

* Witnesses are paid for maintaining the back-bone of the network.
* Committee members are unpaid volunteers that organize the community and propose changes to the network.
* Marketers are paid in referral fees.
* Workers are paid for whatever they propose and do.
* BTS Holders are people holding BTS. They can cast a vote and influence the DAC's businesses

Each of the above (except Marketers) requires users to vote for the people, proposals, and/or changes. Those with sufficient approval will be compensated.

Workers are the "catch all" group where if you have an idea for something that could improve the network, you can get "paid" by the network to do it. Organizing meet-ups, developing a new tool or feature for the community, and maintaining websites and infrastructure (e.g. the mumble server team or linux distribution) are all examples of things workers may do.
   
   
BTS Holders
========================

In contrast to most crypto-currencies, BitShares does not claim to be a currency but rather an *equity* in a decentral autonomous company (DAC). As a result, the market valuation of BitShares is free floating and may be as volatile as any other equity (e.g. of traditional companies).

Every entity hold the core token (BTS) is considered a BTS Holder of the BitShares decentralized company.

Nonetheless, BTS tokens can be used as *collateral* in financial smart contracts such as market pegged assets and thus back every existing smartcoin such as the bitUSD.


Committees
========================

Since Bitcoin struggled to reach a consensus about the size of their blocks, the people in the cryptocurrency space realized that the governance of a DAC should not be ignored. Hence, BitShares offers a tools to reach on-chain consensus about business management decisions.

The BitShares blockchain has a set of parameters available that are subject of BTS Holder approval. BTS Holders can define their preferred set of parameters and thereby create a so called *committee member* or alternatively vote for an existing committee member. The BitShares committee consists of several *active* committee members.

The BitShares ecosystem has a set of parameters available that are subject of BTS Holder approval. Initially, BitShares has the following blockchain parameters:

* **fee structure**:         *fess that have to be paid by customers for individual transactions*
* **block interval**:        *i.e. block interval, max size of block/transaction*
* **expiration parameters**: *i.e. maximum expiration interval*
* **witness parameters**:    *i.e. maximum amount of witnesses (block producers)*
* **committee parameters**:  *i.e. maximum amount of committee members*
* **witness pay**:           *payment for each witnesses per signed block*
* **worker budget**:         *available budget available for budget items (e.g. development)*

Please note that the given set of parameters serves as an example and that the network's parameters are subject to change over time.

Additionally to defining the parameters any active witness can propose a protocol or business upgrade (i.e. hard fork) which can be voted on (or against) by BTS Holders. When the total votes for the hard fork are greater than the median witness weight `w` then the hard fork takes effect.


Witnesses
========================

In BitShares, the witnesses' job is to collect transactions, bundle them into a block, sign the block and broadcast it to the network. They essentially are the block producers for the underlying consensus mechanism.

For each successfully constructed block, a witness is payed in shares that are taken from the limited reserves pool at a rate that is defined by the BTS Holders by means of approval voting.


Workers / Budget Items
========================
Thanks to the funds stored in the reserve pool, BitShares can offer to not only pay for its own development and protocol improvement but also support and encourage growth of an ecosystem.


Payouts
--------------

A blockchain parameter (defined by BTS Holders through the committee) defines the daily available budget. No more than that can be paid at any time to all workers combined.

The daily budget is distributed as follows:

* The available budget is taken out of reserves pool.
* The budget items are sorted according to their approval rate (``Pro - Con``) in a descending order.
* Starting at the worker with the highest approval rate, the requested daily pay is payed until the daily budget is depleted.
* The worker with the least approval rate that was paid may receive less than the requested pay

Hence, in order to be successfully funded by the BitShares ecosystem, the BTS Holders approval for your budget item needs to be highly ranked.

Since the payments for workers from the non-liquid reserve pool result in an increased supply of BTS, these payments are vesting over a period of time defined by BTS Holders.

Working for BitShares
---------------------------------

In order to be get paid by BitShares, a proposal containing

* the date of work begin,
* the date of work end,
* a daily pay (denoted in BTS),
* the worker's name, and
* an internet address.

has to be publish on the blockchain and approved by BTS Holders.

A worker can also choose on of the following properties:

* **vesting**: *pay to the worker's account*
* **refund**:  *return the pay back to the reserve pool to be used for future projects*
* **burn**:    *destroys the pay thus reducing share supply, equivalent to share buy-back of a company stock.*

Pseudo Workers
---------------------------------

Three types of pseudo workers exist that are not primarily used to for salary.

Polling Workers
^^^^^^^^^^^^^^^^^^^^

A worker proposal can be used to poll the BTS Holders for an opinion. Those workers usually have no or very small pay. Additionally, they come with a *proposal*, *recommendation* or other topic on which BTS Holders can publish a binary opinion (pro, or contra).

Refund Worker
^^^^^^^^^^^^^^^^

This worker is used to set an approval limit for worker proposals and their payment by simply refunding his payment/salary to the reserve pool. If its amount of daily pay is as large as the daily available funds, and the worker has highest approval among all worker proposals, all funds will be returned to the reserves and no one will be payed. If, however, an other worker proposal has
more votes than the refund worker, the proposal gets paid its salary, and the rest is return.

Burn Worker
^^^^^^^^^^^^^^

This type of worker is similar to the *Refund Worker* above but **burns** his pay.



|

|

|