
**********************************
Fund (Send) & Transactions
**********************************

.. contents:: Table of Contents

-----

|

Fund your Account
===================

Two Options to Fund your Account
-----------------------------------
 
- **Send (Transfer)**: This is for between BitShares account holders to send funds. On the BitShares Blockchain , people never need to deal with *addresses* or *public keys*. BitShares account holders can use their *account names* for communication. 
- **Deposits**: BitShares account holders can use one of our partners to move over existing funds into your BitShares account.


Send (Transfer)
========================

Currently, there are two forms to send funds. One is **Send** on the top menu. Another one is **Send (legacy)** on the side menu. Both work the same. 

First, we want to list what information on the Send form. Next, you can check each item in the Send form images.

Send Forms items and descriptions
-----------------------------------

+---+----------------------------------+--------------------------------------------------------------------------------------+
|   |    Item                          |       Description                                                                    |
+===+==================================+======================================================================================+
| 1 | Sender's BitShares Account name  | This would be your BitShares Account Name (e.g. *bitshares-users*)                   |
+---+----------------------------------+--------------------------------------------------------------------------------------+
| 2 | TO                               | Another BitShares Account name whom you want to send funds                           |
+---+----------------------------------+--------------------------------------------------------------------------------------+
| 3 | QUANTITY                         | - This is a dropdown list and will show all assets you have in the wallet account.   |
+   +                                  +--------------------------------------------------------------------------------------+
|   |                                  | - Type in a sending amount   - AVAILABLE: a selected asset available total amounts   |
+---+----------------------------------+--------------------------------------------------------------------------------------+
| 4 | MEMO/MESSAGE                     | (option)                                                                             |
+---+----------------------------------+--------------------------------------------------------------------------------------+
| 5 | FEE                              | Transaction fee you pay                                                              |
+---+----------------------------------+--------------------------------------------------------------------------------------+
| 6 | SEND                             | (button)                                                                             |
+---+----------------------------------+--------------------------------------------------------------------------------------+
| 7 | PASSWORD                         | If you have not logged in to the wallet, you will be asked to login                  |
+---+----------------------------------+--------------------------------------------------------------------------------------+
| 8 | LOGIN                            | (button)                                                                             |
+---+----------------------------------+--------------------------------------------------------------------------------------+
| 9 | CONFIRM                          | (button) last check before you send founds                                           |
+---+----------------------------------+--------------------------------------------------------------------------------------+

Form: Send
--------------

A send (transfer) operation moves funds from user ``A`` to user ``B``.
In contrast to most other blockchain-based financial networks, we do **not** use *addresses* or *public keys* for transfers.

Instead, all that is needed for transfers is:

* source account name: From
* destination account name: To
* funds (amount and asset): Quantity 
* asset/token type
* memo (optional)

A transfer may contain a memo with arbitrary text.

.. note:: The ``memo`` is **encrypted** by default can only be decrypted by the participants of the transfer! The transfer fee depends on the length of the memo!
   
.. image:: ../images/Send-1.png
        :alt: bitshares 
        :width: 650px
        :align: center	

> After click [SEND], you need to login (if it's not yet) and [CONFIRM] the Transaction.

**Form: Send - Transfer details (legacy form)**

.. image:: ../images/send-transfer2.png
        :alt: bitshares 
        :width: 650px
        :align: center	
		

|

Deposit
============

Currently, there are two forms to deposit funds. One is **Deposit** and another one is **Deposit (Beta)**. Both locate on the side menu. 
 
BitShares has partners to provide Transfer (i.g. Gateway/Bridge) services which you can choose from. Each Transfer service has own instruction and available coins to handle. When you select a Transfer Service, please follow the instruction. In the next section, we will show you several examples and patterns to compare the deposit forms.

.. note:: On the BitShares blockchain, people never need to deal with *addresses* or *public keys* but can instead use account names. Your account name becomes the *email address* for your funds.


Deposit Forms Items and Descriptions
--------------------------------------

+---+-------------------------+--------------------------------------------------------------------------------------+
|   |    Item                 |       Description                                                                    |
+===+=========================+======================================================================================+
| 1 | Transfer Service        | A dropdown list - Select a transfer service                                          |
+---+-------------------------+--------------------------------------------------------------------------------------+
| 2 | Service Type            | A service you use                                                                    |
+---+-------------------------+--------------------------------------------------------------------------------------+
| 3 | Coin Name               | A dropdown list - Select the coin name you want to deposit                           |
+---+-------------------------+--------------------------------------------------------------------------------------+
| 4 | Deposit / Withdraw tabs | Select *Deposit* tab                                                                 |
+---+-------------------------+--------------------------------------------------------------------------------------+
| 5 | Address                 | Your deposit address to transfer funds.                                              |
+---+-------------------------+--------------------------------------------------------------------------------------+
| 6 | Memo                    | Your Memo information to transfer funds. (*Not all coins' transfers use `Memo`*)     |
+---+-------------------------+--------------------------------------------------------------------------------------+
| 7 | BitShares Account Name  | This would be your BitShares Account name                                            |
+---+-------------------------+--------------------------------------------------------------------------------------+

  If you cannot select an Asset on the Deposit(Beta) form, try to login to your wallet first. 

Examples
^^^^^^^^^
  
**(Example 1) Deposit STEEM by using a Gateway service**

You use `ADDRESS` and `MEMO` to deposit funds. The below images show a Deposit and a Deposit(Beta) forms.

.. image:: ../images/deposit-steem-legacy.png
        :alt: bitshares 
        :width: 650px
        :align: center	
		
.. image:: ../images/deposit-steem-2.png
        :alt: bitshares 
        :width: 350px
        :align: center	
		
		
**(Example 2) Deposit EOS by using a Gateway service**

You use `ADDRESS` to deposit funds. The below images show a Deposit and a Deposit(Beta) forms.

.. image:: ../images/deposit-eos-legacy.png
        :alt: bitshares 
        :width: 650px
        :align: center	
		
.. image:: ../images/deposit-eos-2.png
        :alt: bitshares 
        :width: 300px
        :align: center	
		
**(Example 3) Deposit BTS**

You use BitShares Account Name as `ADDRESS` to deposit funds. The below image shows a Deposit(Beta) form.

.. image:: ../images/deposit-bts.png
        :alt: bitshares 
        :width: 300px
        :align: center
		
---------------

.. _transactions:


Transactions
========================
   
.. _proposed-transactions:

Proposed Transactions
-------------------------

The Graphene technology allows users to *propose* a transaction on the blockchain which requires approval of multiple accounts in order to execute.

At any time, a proposal can be approved in a single transaction if sufficient signatures are available (see ``proposal_update_operation`` as constructed by the ``approve_proposal`` call), as long as the authority tree to approve the proposal does not exceed the maximum recursion depth. In practice, however, it
is easier to use proposals to acquire all approvals, as this leverages on-chain notification of all relevant parties that their approval is required. Off-chain multi-signature approval requires some off-chain mechanism for acquiring several signatures on a single transaction.  This off-chain synchronization can be avoided using proposals.

The user proposes a transaction, then signatory accounts use add or remove their approvals from this operation. When a sufficient number of approvals have been granted, the operations in the proposal are evaluated. Even if the transaction fails, the proposal will be kept until the expiration time, at which point, if sufficient approval is granted, the transaction will be evaluated a final time.
This allows transactions which will not execute successfully until a given time to still be executed through the proposal mechanism. The first time the proposed transaction succeeds, the proposal will be regarded as resolved, and all future updates will be invalid.

The proposal system allows for arbitrarily complex or recursively nested authorities. If a recursive authority (i.e. an authority which requires approval of 'nested' authorities on other accounts) is required for a proposal, then a second proposal can be used to grant the nested authority's approval. That is, a second proposal can be created which, when sufficiently approved, adds the approval of a nested authority to the first proposal. This multiple-proposal scheme can be used to acquire approval for an arbitrarily deep authority tree.


.. image:: proposed-transactions.png
        :alt: Proposed Transactions
        :width: 890px
        :align: center

|



Note that each account in the figure can carry a **different weight**. An example
of how to setup your permissions accordingly is given in
:ref:`account-permissions`.



Confidential Transactions
--------------------------

A confidential transfer is one that hides the amount being sent. Confidential
transfers are also referred to as blinded transfers. It makes use of Oleg
Andreev's `blind signatures`_.

When privacy is important no account is ever used twice and it is impossible for
any third party to identify how money is moving through blockchain analysis
alone.


.. _blind signatures: http://blog.oleganza.com/post/77474860538/blind-signatures

  
|

|
