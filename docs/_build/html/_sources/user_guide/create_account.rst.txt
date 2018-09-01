
*************************
Create a BitShares Wallet
*************************


.. contents:: Table of Contents

-----------

|

Terminology
========================

In this section, we want to describe Terminologies  and guide you to create and register your BitShares Account. 


**Wallet**

Wallets interacts with the blockchain to process accounts and funds functionalities. Users register to create a single wallet. The single wallet can carry many accounts. Users who have a lifetime membership (LTM) can register multiple accounts in parallel; all of them are stored in a single wallet. Also, users can create multiple wallets to organize their accounts properly.

**Accounts**

In BitShares, you can create own **unique account name**, so, you can remember easily. And you will use the account name to communicate (e.g. Send fund) with other BitShares account users (BTS Holders) like an email address. The advantage of using account name is that people can identify you by using a readable and memorable word instead of cryptographic addresses.

Each user has at least one account that can be used to interact with the blockchain. The account can be seen as a single banking account with an individual balance, transaction history, etc. Since these accounts are registered on the blockchain and are open to the public, we recommend to pick a pseudonym to achieve some privacy. 

**Keys**

Keys refer to the cryptography used to secure access to your account and funds. It is of importance to prevent others from gaining access to these keys.  

BitShares has *owner, active and memo keys*. And each key has *public key and private key*. It's important to know that Owner permission has administrative powers over the whole account. Active Permission is considered as an “online” permission that allows to access funds and some account settings. 

-------------

|


Light wallet or Web wallet?
==============================

Before we create a wallet, let's check what type of wallet you can have as your BitShares wallet. Quick check the below chart. 
		
.. image:: ../images/BitShares-wallet-flow.png
        :alt: wallet 
        :width: 550px
        :align: center	
		

Did you find out which type of wallet you want to have? 

- If you want to install **Light Wallet (BitShares UI)**, download `BitShares UI Releases <https://github.com/bitshares/bitshares-ui/releases>`_ file and install it to your machine. 
   - *This does not mean you will have a Local wallet.*
- If you want to use **Web Wallet**, go to this link (https://wallet.bitshares.org).

-----

|

Create an Account
===================
In this section, you will create a **Cloud wallet**. 

We use the term Cloud Wallet, but technically nothing is stored in the cloud. We call the Cloud Wallet because **you can use your credentials (username and password) from any web browser** at any time to gain access to your account. 

**Welcome BitShares - Create Account & Login form**

.. image:: ../images/welcome-bitshares1.png
        :alt: bitshares 
        :width: 300px
        :align: center	
		

Steps
------

* 1.Click [**CREATE ACCOUNT**]
* 2.Type in [**ACCOUNT NAME**]. You can create your unique BitShares account name.
* 3.Set a password. Copy and use a **GENERATED PASSWORD**
* 4.Type or paste your password to confirm.
* 5.Check the check boxes. **Make sure you read before you check!**
* 6.Click [**CREATE ACCOUNT**]

.. image:: ../images/create-account1.png
        :alt: bitshares 
        :width: 350px
        :align: center	
		
Before you submit, check your password one more time if you saved the correct one.

**ONLY you can open your wallet again. No one can help.** Do not lose it!

 
- 7.Click **[SHOW ME MY PASSWORD**] and double check if you have a correct password.
- 8.Click [**OK,TAKE ME TO THE DASHBOARD**]

.. image:: ../images/create-account4.png
        :alt: bitshares 
        :width: 350px
        :align: center	

- Click the top menu [**Dashbord**] if it did not open. 

.. image:: ../images/dashboard.png
        :alt: bitshares 
        :width: 600px
        :align: center	
	

Now, you have a BitShares **Cloud Wallet**. Before you fund to your account, let's login to make sure if you have a correct password. 		

-------------
	
|

Login
==========

Click a **Locked Key** icon in the top right corner to open a login form.

.. image:: ../images/topmenu-lock.png
        :alt: bitshares 
        :width: 550px
        :align: center	
	

Cloud Wallet Login form
---------------------------

If you followed the above steps to create a BitShares account, you have a Cloud Wallet as a default wallet. 

On the Login form, you can see which wallet Login form for. (i.e., Login with: Account name (cloud wallet))

.. image:: ../images/login-cloud-wallet.png
        :alt: bitshares 
        :width: 400px
        :align: center	
	
If you logged in successfully, you would find a **Unlocked Key**.

.. image:: ../images/topmenu-unlock2.png
        :alt: bitshares 
        :width: 600px
        :align: center	
		
-------------

|
	
Advanced: Create an Account
=============================

In this section, you will create a **Local Wallet**. 

If you have a Cloud Wallet, you can access your wallet from any browsers. However, the Local Wallet, you can only access your funds from **the same computer and web browser** that you have used to register and create your account.

The Local wallet requires you to create **a backup file** to manage your account and funds. The backup file can be used to move 

.. image:: ../images/local-login1.png
        :alt: bitshares 
        :width: 300px
        :align: center	

Steps
----------

- 1.Click [**advanced form**]
- 2.Type in [**ACCOUNT NAME**]. You can create your unique BitShares account name.
- 3.Set a password. Create own strong password.
- 4.Type or paste your password to confirm.
- 5.Click [**CREATE ACCOUNT**]

> **If this is yore first account, a faucet will pay the registration fee for you!** 

.. image:: ../images/local-login2a.png
        :alt: bitshares 
        :width: 300px
        :align: center	

> **Your Web Browser is your Wallet:**  Please read the information below.

.. image:: ../images/local-login2b.png
        :alt: bitshares 
        :width: 300px
        :align: center	

- Click [**CREATE BACKUP NOW**] 

.. image:: ../images/local-login3.png
        :alt: bitshares 
        :width: 300px
        :align: center	


**It's extremely important you to create a backup of your account and keep a safe place**. 

- Click [**DOWNLOAD**] to save a backup (.bin) file. 

.. image:: ../images/local-login4.png
        :alt: bitshares 
        :width: 300px
        :align: center	


**Congratulation, you're ready!**


.. image:: ../images/local-login5.png
        :alt: bitshares 
        :width: 300px
        :align: center	


-----------


BitShares Wallet Features
================================

Quick Review Wallet Options
-------------------------------

.. image:: ../images/functions1.png
        :alt: wallet 
        :width: 650px
        :align: center	


+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
|    | Item name                |  note                                                                                                         |
+====+==========================+===============================================================================================================+		
| 1  | Dashboard                | The Wallet Portfolio, Open Orders, Margin Positions, and Activity information                                 |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 2  | Exchange                 | BitShares Exchange, Trading information                                                                       |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+ 
| 3  | Explore                  | BitShares Live Blockchain, Assets, Accounts, Witnesses members, Committee members, Markets, and Fee Schedule  |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 4  | Send                     | Opens a Send form. You can send funds to other BitShares Account Holders                                      |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 5  | A BitShares account name | A account name that the data shows on a Dashboard page                                                        |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 6  | Key icon                 | By click, opens a login form. Locked/Unlocked Key icon shows if you've logged in the account currently        |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 7  | Side Menu icon           | Side Menu icon opens the wallet other menus in a dropdown list                                                |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 8  | Asset Total              | Currently showing in a Dashboard Total Assets                                                                 |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 9  | BitShares Wallet Version | The Release Version of BitShares UI Wallet                                                                    |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 10 | Latency                  | The delay of Network connection                                                                               |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+
| 11 | Server Node name         | A server node name that you are connecting                                                                    |
+----+--------------------------+---------------------------------------------------------------------------------------------------------------+

|

Dashboard
^^^^^^^^^^^^^^^

.. image:: ../images/dashboard3.png
        :alt: Dashboard 
        :width: 650px
        :align: center	
		
		
**Dashboard Tabs**

+------------------+-------------------------------------------------------------------------------------------------+
|   Tab name       |  note                                                                                           |
+==================+=================================================================================================+
| Portfolio        | Your Assets list. You can filter the assets and hide some assets if you don't need to watch.    |
+------------------+-------------------------------------------------------------------------------------------------+
| Open Orders      |                                                                                                 |
+------------------+-------------------------------------------------------------------------------------------------+
| Margin Positions |                                                                                                 |
+------------------+-------------------------------------------------------------------------------------------------+
| Activity         | Show your all transactions. (i.e., The below shows a type of transactions to choose from.)      |
+------------------+-------------------------------------------------------------------------------------------------+

**Activity - Filters**

.. image:: ../images/dashboard-activity2.png
        :alt: Dashboard 
        :width: 450px
        :align: center	
		
|

Side Menus - Dropdown items
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


+------------------+-------------------------------------------------------------------------------------------------+
|   option         |                                                                                                 |
+==================+=================================================================================================+
| login            | By click, opens a login form.                                                                   |
+------------------+-------------------------------------------------------------------------------------------------+
| Create Account   | Users who have a lifetime membership (LTM) can register multiple accounts in parallel;          |
+                  +-------------------------------------------------------------------------------------------------+
|                  | all of them are stored in a single wallet                                                       |
+------------------+-------------------------------------------------------------------------------------------------+
| Send(legacy)     | Transfer details (Original page). **Send** on the top menu is new form.                         |
+------------------+-------------------------------------------------------------------------------------------------+
| Deposit          | Deposit funds from other parties (Original Deposit page)                                        |
+------------------+-------------------------------------------------------------------------------------------------+
| Deposit(beta)    | Select an asset you want to deposit and provide you a sending address, Gateway,                 |
|                  | identicon, and notes.                                                                           |
+------------------+-------------------------------------------------------------------------------------------------+
| Withdraw         |  (Original Withdraw page)                                                                       |
+------------------+-------------------------------------------------------------------------------------------------+
| Withdraw(beta)   | Search an asset to withdraw                                                                     |
+------------------+-------------------------------------------------------------------------------------------------+
| Settings         | You can manage your wallet appearance  and other settings.                                      |
+                  +-------------------------------------------------------------------------------------------------+
+                  + Settings - CLOUD Wallet Login Mode:                                                             +
+                  +-------------------------------------------------------------------------------------------------+
|                  | - General                                                                                       |
|                  | - Accounts                                                                                      |
|                  | - Restore/Import                                                                                |
|                  | - Nodes                                                                                         |
|                  | - Faucet                                                                                        |
|                  | - Reset settings                                                                                |
+                  +-------------------------------------------------------------------------------------------------+
|                  | Settings - LOCAL Wallet Login Mode:                                                             |
+                  +-------------------------------------------------------------------------------------------------+
|                  | - General                                                                                       |
|                  | - Local Wallet                                                                                  |
|                  | - Accounts                                                                                      |
|                  | - Password                                                                                      |
|                  | - Backup                                                                                        |
|                  | - Restore/Import                                                                                |
|                  | - Access                                                                                        |
|                  | - Faucet                                                                                        |
+------------------+-------------------------------------------------------------------------------------------------+
| News             | BitShares Blockchain Foundation and other News                                                  |
+------------------+-------------------------------------------------------------------------------------------------+
| Help             | Open a Help page                                                                                |
+------------------+-------------------------------------------------------------------------------------------------+
| Voting           | You can vote for Witnesses, Committee or Workers. Or you can set a Proxy to case a vote.        |
+                  +-------------------------------------------------------------------------------------------------+
|                  | Voting is important: in Bitshares in the same way it is important to the community              |
|                  | in which you live. The weight of your vote is directly correlated to the number of BTS you own. |
+                  +-------------------------------------------------------------------------------------------------+
|                  | If you aren't heavily involved in the community, you are encouraged to choose a proxy who       |
|                  | represents your interests.                                                                      |
+------------------+-------------------------------------------------------------------------------------------------+
| Asset            |  Issued Assets                                                                                  |
+------------------+-------------------------------------------------------------------------------------------------+
| Signed Message   |                                                                                                 |
+------------------+-------------------------------------------------------------------------------------------------+
| Membership stats | Basic Member is a default membership. You can upgrade to Lifetime Membership here.              |
+------------------+-------------------------------------------------------------------------------------------------+
| Vesting balances | Vesting balances contain any fees earned through the referral program or from worker pay,       |
+                  +-------------------------------------------------------------------------------------------------+
|                  | For example. They have a tain vesting period and are continually unlocked during                |
|                  | that vesting period until all of the balances are available                                     |
+------------------+-------------------------------------------------------------------------------------------------+
| Whitelist        | You can set Whitelist and/or Blicklist. Also, you can view 'Whitelisted by' and                 |
|                  | 'Blacklisted by'.                                                                               |
+------------------+-------------------------------------------------------------------------------------------------+
| Permissions      | You can review/renew each account’s (Active, Owner, and Memo) Public keys                       |  
|                  | and Private keys information.                                                                   |
+                  +-------------------------------------------------------------------------------------------------+
|                  | Active Permission: It’s consider to be the “online” permission. control accessing funds         |
|                  | and some account settings.                                                                      |
+                  +-------------------------------------------------------------------------------------------------+
|                  | Owner Permission: This permission has administrative power over the account                     |
|                  | Also, if you want to change your Cloud Wallet password, use the “Cloud Wallet” tab page.        |
+------------------+-------------------------------------------------------------------------------------------------+
| (Accounts)       |                                                                                                 |
+------------------+-------------------------------------------------------------------------------------------------+


		
|

|








