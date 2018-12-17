
*************************************
BitShares Client and Login Mode
*************************************

.. contents:: Table of Contents

------------------

|

BitShares Client
========================
You have sole control of your accounts and funds and they are created on your computer (within the light-client or the browser web-client). 

- If you created a **Clout wallet**, you will be able to access to your wallet by using your credentials (username and password) from any browser or computers. You do not need to worry about a backup files. (*You do not have the functionality.*)  

- If you created a **Local wallet**, you will be able to access your account **only** on the computer that you have used to register and create your account. If you have created a backup file, you can import it and restore your wallet somewhere else.


Light Client
----------------
Download client files and install BitShares Wallet to your computer.

**> Note: This download does not mean that you will have a Local wallet.**

- `Download the Official Light Client <https://bitshares.org/download>`_
- `BitShares-UI – Latest Release <https://github.com/bitshares/bitshares-ui/releases>`_

**BitShares-UI**: 
This is a web application and runs in a browser. A connection is established to a trusted node in the network that serves as a gateway to the rest of the ecosystem.

Web Client
-------------

Access the network and open the wallet in the browsers via one of our partners.

- wallet.bitshares.org https://wallet.bitshares.org
- (more...)

------------

|

Login Forms
=============

Cloud Wallet Login
---------------------

The cloud wallet only allows for a single account to be accessed at a time. This wallet is generally the correct choice for a new user. 

**Login Form** 

You login with your account name and your password. The login form shows which type of wallet you login to. (i.e., Login with: **Account name (cloud wallet)**)


.. image:: ../images/login-cloud-wallet.png
        :alt: bitshares 
        :width: 400px
        :align: center	
		

Local Wallet Login
--------------------

A Big difference between a Cloud wallet and a Local wallet is the local wallet creates a database within your browser. This means that access to your funds is tied to the browser only. If you attempt to access your local wallet from any other computer, or any other browser, it will fail unless you actively import your backup file from the original browser backup file.

**Login Form** 

You select your Local wallet backup file name and type your password to login a Local wallet. The **Key file(.bin)** should be your wallet backup file name. The backup file contains all your keys information. 


.. image:: ../images/login-local2.png
        :alt: bitshares 
        :width: 400px
        :align: center	
		
-----

|
		
Summary 
=============

The difference between a Cloud wallet and a Local Wallet.

Cloud Wallet
----------------

- BitShare UI wallet will create a **Cloud wallet** as a default wallet. (i.e., [CREATE ACCOUNT])
- The Cloud wallet allows you to login from any web browser at any time to gain access to your account by using your credentials (username and password).
- The Cloud wallet only allows for a single account to be accessed at a time. 
- If you have a Cloud wallet, you don't need to worry about a backup. (*You don't have the functionality in the Cloud wallet*).
- **You can switch the INTERFACE by using the [Settings] - [General] - [Login Mode], however your account won't switch, only the *interface* switches.** 
- **Even you import Private keys (was in the Cloud wallet) to the Local wallet, you do not have a brain key to associate with the Private keys you imported. Therefor, a brainkey restore won't find those Private keys. (In this case, no meaning to do a brainkey backup and restore.)**
- **The Cloud wallet has no brainkey.** The password is basically the equivalent of the brainkey, but it's only used for that one account.
  
Local Wallet
---------------

- **If you know you want to have a Local wallet, use an [advanced form] link on the Welcome to BitShares form and create a backup file. This is the only way to create a Local wallet.** 
- The Local wallet creates a correct pair of keys (a brainkey and private keys) and save the information to your browser.
- The Local wallet creates a database with in your browser. This means that you can only access your funds from the same computer and web browser that you have used to register and create your account.  If you attempt to access your local wallet from any other computer, or any other browser, it will fail unless you actively import your backup file from the original browser backup file.
- You have to create a backup files to manage the Cloud wallet account. 
- The Cloud wallet has Backup options. Go to [Settings] - [Backup] to find. 
  - **Create local wallet backup** : create a Binary File (.bin) backup.
  - **Create brainkey backup** : give you long random phrases. You need to write down and keep it in a safe place.
- The backup files can be used to move your local wallet to different computers or different browsers. In order to restore your local wallet you will need the backup file and your password! Therefor, it’s extremely important you create a backup and keep a safe place.


Settings - LOGIN MODE
-----------------------

**Users often misunderstand about this feature.** 

This setting feature allows you to select the LOGIN MODE. You can just switch the *interface*. You are **not** switching your account from one to another. 

Go to [Settings] - [General] - **LOGIN MODE** to find the feature.

.. image:: ../images/login-mode-set.png
        :alt: bitshares 
        :width: 550px
        :align: center	

  By switching **the interface** from a **Cloud Wallet Mode** to a **Local Wallet Mode**, you can;

  - restore an old Local wallet backup file or 
  - create a new account.

> **This feature only switch the *interface*! Not your account self.**

-----

|


Frequently asked Questions
===============================

- **Can I switch (by changing the Wallet Mode or importing private keys) my Cloud wallet to a Local wallet?**

  - No. Your account won't switch, only the *interface* switches. 
  
- **I have a Cloud wallet. Can I have a Local wallet?** 

  - Yes. But you will have to create new account for the Local wallet. 
  
- **How can I move my funds from a Cloud wallet to a Local wallet?**

  - We mentioned before. You have to create new account for the Local wallet. You can create the Local wallet by using an [**advanced form**] link on Welcome to BitShares form. After you created new Local wallet, send your funds from your old account (Cloud wallet) to new account (Local wallet). And create a backup!!
  
- **I have a Cloud wallet. Do I have to save my private keys information somewhere?**

  - Not necessary. Because the Could wallet always do it for extra security. Also lets you login without exposing your owner key, you can login using only the active key.
  
- **Can I change a Cloud wallet password?** 

  - Yes. 
  
  - Go to `How to change a password if using a Cloud Wallet <https://github.com/bitshares/bitshares-ui/wiki/Cloud-Wallet-Login-and-changing-password>`_ : from BitShares UI wiki
  
- **Can I change a Local wallet password?** 

  - Yes.
  
  - Go to [**Settings**] - [**Password**] - Change your password. Use this page
  . 
- **There is [Create Account] in a Side navigation menu. Can I create and add new account in the same wallet I logged in?**

  - Yes. However, the account you logged in must have a LifeTime Membership (LTM) stats.

|


