## User Issued Assets (UIAs)

Freely traded tokens created by individuals used for a variety of use-cases, such as stock, miles, event tickets or reputation points.

#### Table of Contents:
- Create Asset Feature
- View existing Asset

***

BitShares allows individuals and companies to create and issue their own tokens for anything they can imagine. The potential use cases for so called user-issued assets (UIA) are innumerable. On the one hand, UIAs can be used as simple event tickets deposited on the customers mobile phone to pass the entrance of a concert. On the other hand, they can be used for crowd funding, ownership tracking or even to sell equity of a company in form of stock.

All you need to do is click in order to create a new UIA is a few mouse clicks, define your preferred parameters for your coin, such as supply, precision, symbol, description and see your coin’s birth after only a few seconds. From that point on, you can issue some of your coins to whomever you want, sell them and see them instantly **traded against any other existing coin** on BitShares.

Unless you want some restriction. As the issuer, you have certain privileges over your coin, for instance, you can allow trading only in certain market pairs and define who actually is allowed to hold your coin by using white- and blacklists. Of course, an issuer can opt-out of his privileges indefinitely for the sake of trust and reputation.

As the owner of that coin, you don’t need to take care of all the technical details of blockchain technology, such as distributed consensus algorithms, blockchain development or integration. You don’t even need to run any mining equipment or servers, at all.

So what’s the drawback?

There is a drawback in this scenario, namely, a centralized issuance of new tokens. To some extend, this could be managed by a hierarchical multi-signature issuer account that prevents any single entity from issuing new coins but instead requires a consensus among an arbitrary set of people to agree on any changes to the coin.

Obviously, the regulations that apply to each kind of token vary widely and are often different in every jurisdiction. Hence, BitShares comes with tools that allow issuers to remain compliant with all applicable regulations when issuing assets assuming regulators allow such assets in the first place.


**Use Cases**

- Reward Points
- Fan Credits
- Flight Miles
- Event Tickets
- Digital Property
- Crowd-Funding
- Company Shares

***

### Create Asset Feature 

Go to **[Settings]** - **[Create Asset]**

1. Click [CREATE ASSET]

<p align="center">
  <img src="/bbf/images/uia-ui-1.png" width="150" title="Create Asset">
</p>
			
<p align="center">
  <img src="/bbf/images/uia-ui-2.png" width="600" title="Create Asset">
</p>
		
	
**Primary Settings**
<p align="center">
  <img src="/bbf/images/uia-ui-3-primary.png" width="600" title="Create Asset">
</p>

		
To allow transaction fees to be paid in the native asset, a core exchange rate is required at which a customer can implicitly trade the UIA into BTS from the asset’s *fee pool*. 

This also requires that the fee pool is funded (e.g. by the issuer). Since all prices in BitShares are internally represented as *fractions* (i.e. a/b), we need to define a ratio between quote (the UIA) and base (BTS), i.e. the numerator and denominator for price = a/b
	

| tab                      |                                                                               |
|--------------------------|-------------------------------------------------------------------------------|
| Symbol                   | will be reserved in the system for your assets. One the asset   <br/>  Note: Symbols with less than 5 characters are very expensive.                 |
| Maximum Supply          | Please consult the Networks fees in the explorer!   <br/> This is also a permanent setting and denotes the maximum amount of   <br/> shares that can ever exist at the same time.                                  |
| Number of Decimal Points | This is used to denoted the number of decimal places. A 0 will result in an asset <br/> that cannot be separated below integer amounts (e.g. 1, 2, ..)                |
| SmartCoin                |                                                                               |
| Quote Asset Amount       | Core exchange rate                                                            |
| Base Asset Amount        | Core exchange rate                                                            |
		

**Description**
		
<p align="center">
  <img src="/bbf/images/uia-ui-4-description.png" width="600" title="Create Asset">
</p>
		
|                          |                                                                               |
|---|---|
| Description              | can be used to let everyone know the purpose of the asset,                    | 
| Short Name               | is also a permanent setting and denotes the maximum amount                    |
| Preferred Market Pairing |                                                                               |  
| Asset Name               |                                                                               |

	
**Permissions (Optional)**

<p align="center">
  <img src="/bbf/images/uia-ui-5-permissions.png" width="600" title="Create Asset">
</p>	
		
Even though the default settings should be fine for most UIAs, we have the option to opt-out of some available features. (By default, or permissions are enabled).
	
**Note:** Once a permission has been set to false, the permission cannot be reactivated!

We have the options to opt-out of:

- Enabling Market Fees
- Requiring holders to be white-listed
- Issuer may transfer asset back to himself
- Issuer must approve all transactions
- Disable confidential transactions

**Note:** that setting these permissions does not imply that the features is enabled. To do so, we would also require to enable the corresponding flag(s). (See below)

	
**Flags (Optional)**

The flags are used to actually enable a particular features, such as market fees or confidential transfers.
	
If we have set the permission to have a market fee, we can enable the market fees here and set a percentage and max. fee.

We here also can enable the requirements for users to be white-listed, enable confidential transfers and give the issuer the power to withdraw its asset from customer accounts.
	
<p align="center">
  <img src="/bbf/images/uia-ui-6-flag.png" width="600" title="Create Asset">
</p>	

**The asset creation fee**

The asset creation fee depends on the length of your symbol. 3 Character Symbols are the shortest and are rather expensive while symbols with 5 or more characters are significantly cheaper.

50% of the asset creation fee are used to pre-fill the assets fee pool. From the other 50%, 20% go to the network and 80% go to the referral program. This means, that if you are a life-time member, you get back 40% of the asset creation fee after the vesting period (currently 90 days).

***
	
### View existing Asset 
	
		
Go to **[Explore]** - **[Asset]** - **[User Issues Assets]**

<p align="center">
  <img src="/bbf/images/uia-ui-7.png" width="600" title="Create Asset">
</p>	
	
		
		
		
		
		
		
		
		
		
		
