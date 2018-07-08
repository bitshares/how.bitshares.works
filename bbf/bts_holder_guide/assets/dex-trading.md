## Trading

This page will give a very quick introduction on how to interpret the terms used by the DEX and how trading pairs are presented.

#### Table of Contents:
- Pairs
- Market Overview
- Market
- Order Books
- Trading
- Order Matching

***

### Pairs

In BitShares, almost any asset can be traded with all other assets. Once we have picked two assets, we usually refer to a market pair. For instance, we can trade USD against EUR in the USD:EUR pair.

For sake of consistency, we will use the generalized terms base and quote such that pairs are represented as:

- quote : base

and for instance with base being USD and quote being EUR, denote the EUR:USD pair.

### Market Overview

The market overview that can be access via the explorer, shows a set of predefined default markets. Note that the list of default markets may vary depending on the wallet provider. Further markets can be added using the Find Markets tab. Adding a Star to your favorite markets will make it appear in your list of default markets.

		
<p align="center">
  <img src="/bbf/images/Holders/trade-market-overview.png" width="600" title="market overview">
</p>
				

### Market

When entering a market, you will presented with either the market depth
… or the price chart depending on your settings.
You can switch between your views by pressing the corresponding button as highlighted below.
		
<p align="center">
  <img src="/bbf/images/Holders/trade-market-overview2.png" width="650" title="market ">
</p>		

### Order Books

The order book consists of an ask and a bid side. Since trading pairs do not have a preferred orientation, and can be flipped, the following table shall give an overview of ask/bid and the corresponding buy/sell operations for each side:

|Side  | Sell  | Buy   |
|---|---|---|
| Ask  | quote | base  |
| Bid  | base  | quote |

Obviously, what is on the bid side of the USD:EUR pair will be on the ask side on the EUR:USD pair. Of course prices are internally represented as fractions, and thus results in both pairs being identical.

### Trading

To place a trading order, it is required to fill the form on either the ask or the bid side (respectively, buy or sell side). You will need to define a price and an amount to sell/buy. The cost for this order will be calculated automatically. Note that there will be an additional fee required to actually place the order.

Once the order is filled (i.e. someone sold/bought your offer), your account will be credited by the corresponding asset.

Unfilled orders can be canceled at any time.

### Order Matching

BitShares 2.0 matches orders on a first-come, first-serve basis and gives the buyer the best price possible up to the limit (also known as “walking the book”). Rather than charging unpredictable fees from market overlap (as has been in the previous network), the network charges a defined fee based upon the size of the order matched and the assets involved. Each asset issuer gets an opportunity to configure their fees.

***
