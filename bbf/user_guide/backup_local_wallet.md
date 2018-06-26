## Backups and Restore your Wallet

#### Table of Contents:
- [Create Local Wallet Backup](/bbf/user_guide/backup_local_wallet.md#create-local-wallet-backup)
   - [Backup Types](/bbf/user_guide/backup_local_wallet.md#backup-types)
   - [How to Create a backup (.bin) file](/bbf/user_guide/backup_local_wallet.md#how-to-create-a-backup-bin-file)
   - [How to Create a Brainkey backup (Advanced User Only)](/bbf/user_guide/backup_local_wallet.md#how-to-create-a-brainkey-backup-advanced-user-only)
- [Restore / Import](/bbf/user_guide/backup_local_wallet.md#restore--import)
   - [Restore / Import Options](/bbf/user_guide/backup_local_wallet.md#restore--import-options)
   - [How to Restore from a backup (.bin) file](/bbf/user_guide/backup_local_wallet.md#how-to-restore-from-a-backup-bin-file)
   - [How to Check *Active Local Wallet* name](/bbf/user_guide/backup_local_wallet.md#how-to-check-active-local-wallet-backup-file-name)
   - [How to Recover Account with Brain key](/bbf/user_guide/backup_local_wallet.md#how-to-recover-account-with-brain-key)
   
   
***

> If you use a Cloud Wallet, you do not need to create a backup. **You do not have the option also.**

## Create Local Wallet Backup
It is recommended to make regular backups of your Local wallet. Please note that in order to recover from a backup you will also need to provide the passphrase (password) because backups are encrypted. If you lose your wallet backup file or your passphrase, you will not be able to access any of your funds again.

You are the only individual that has access to your account and funds, it is your responsibility to make a secure backup of your registered Local wallet account.

### Backup Types
There are three types of backups.

| type |    |
|-------|--------------|
| Create local wallet backup | create a Binary File (.bin)  |
| Create brainkey backup | give you long random phrases. You need to write down.  |
| Create favorites backup |  |

***

### How to Create a backup (.bin) file

1. Open a Side menu and select [**Settings**]
1. In [**Settings**], select [**Backup**]. 
1. Make sure the backup type is *Create local wallet backup*
1. Click [**CREATE BACKUP NOW**]
1. Check your backup file name (e.g. bts_somrthing_20180420.bin)
1. Click [**DOWNLOAD**]

#### Store this backup in at least two secure locations only accessible by you

<p align="center">
  <img src="/bbf/images/backup-1.png" width="550" title="Backup">
</p>

<p align="center">
  <img src="/bbf/images/backup-2.png" width="550" title="Backup">
</p>

***

#### About the Brain Key

The brain key is used as source for all cryptographic keys generated in the wallet. If you have it secured, you will be able to regain access to your accounts and funds (unless the access keys have been changed)

### How to Create a Brainkey backup (Advanced User Only)

1. Open a Side menu and select [**Settings**]
1. In [**Settings**], select [**Backup**]. 
1. (#1) Make sure the backup type is *Create brainkey backup*
1. (#2) Type in a password
1. (#3) Click [**SHOW BRAINKEY**]
1. (#4) Write down *Brainkey* (i.g. very random long phrases)
1. (#5) Click [**I'VE WRITTEN IT DOWN**] 

#### Write it down!! Anyone with access to your recovery key will have access to funds with in the local wallet.

<p align="center">
  <img src="/bbf/images/backup-brainkey.png" width="670" title="Backup">
</p>

<p align="center">
  <img src="/bbf/images/backup-brainkey2.png" width="670" title="Backup">
</p>

***


## Restore / Import

> We assume you have created a backup file (.bin) and use a Local wallet.

### Restore / Import Options

| option |    |
|-------|--------------|
| Restore from a backup file (.bin) | restore from a backup file and a password  |
| Import a private key | import Private keys to a Local wallet. The imported keys will be saved in the bin file. If this happens, you cannot rely on the brainkey for backup after that. |
| Import a BTS 0.9.3c key export file (.json) |  |
| Restore using a local wallet brainkey | use a password and a Brain key |
| Restore favorites using a json file |  |


### How to Restore from a backup (.bin) file

1. Open a Side menu and select [**Settings**]
2. In [**Settings**], select [**Restore/Import**]. 
3. (#1) Make sure you selected *Restore from a backup file (.bin)*
4. (#2) Click [**Browse...**] to find a backup file. 


<p align="center">
  <img src="/bbf/images/restore1.png" width="670" title="Backup">
</p>

<p align="center">
  <img src="/bbf/images/restore3.png" width="670" title="Restore">
</p>

5. (#3) Type in a password
6. (#4) Click [**SUBMIT**]

<p align="center">
  <img src="/bbf/images/restore4.png" width="670" title="Restore">
</p>

7. (#5) Type in *New Local Wallet Name* if you want to change the backup file name.
8. (#6) Click [**ACCEPT**]
9. (#7) **Ready to Restore** - below "RESTORE(..... WALLET)" is a button. Click it. 
10. You will find "Successfully  restored (....)wallet.  Done!!
11. (#8) Click [**DASHBOARD**]

<p align="center">
  <img src="/bbf/images/restore5.png" width="670" title="Restore">
</p>
<p align="center">
  <img src="/bbf/images/restore6.png" width="670" title="Restore">
</p>

### How to Check Active Local Wallet backup file name

- [**Settings**] - [**Local Wallet**] - Active Local Wallet

<p align="center">
  <img src="/bbf/images/restore7.png" width="670" title="Restore">
</p>

***

### How to Recover Account with Brain key

1. Open a Side menu and select [**Settings**]
2. In [**Settings**], select [**Restore/Import**]. 
3. (#1) Make sure you selected *Restore using a local wallet brainkey*
4. (#2) Type in a password
5. (#3) Type in a password (Confirm)


<p align="center">
  <img src="/bbf/images/brainkey1.png" width="670" title="Backup">
</p>

6. (#4) Type in new *Local Wallet Name* if needed. (e.g. "default-test-brainkey-restore")

<p align="center">
  <img src="/bbf/images/brainkey2.png" width="670" title="Restore">
</p>
<p align="center">
  <img src="/bbf/images/brainkey3.png" width="670" title="Restore">
</p>

7. (#5) Type in **BRAINKEY**
8. (#6) Click [CREATE NEW LOCAL WALLET]

<p align="center">
  <img src="/bbf/images/brainkey4.png" width="670" title="Restore">
</p>

9. (#7) Click [DONE]
10. (#8) Let's check *ACTIVE LOCAL WALLET* name (Go to [Settings] - [Local Wallet])

<p align="center">
  <img src="/bbf/images/brainkey5.png" width="670" title="Restore">
</p>


***
