## What’s different in BitShares

### Authorities

BitShares employs a first of its kind hierarchical private key system to facilitate regular keys and backup keys. **Regular (active) keys** are for day-to-day usage, while a separate backup **(owner) key** can be used to recover access to an account in case of loss of the regular keys.

Ideally the owner key is meant to be stored offline, and only used when the account’s keys need to be changed or to recover a lost key. BitShares also facilitates the use of a Master Password that encrypts all keys.

### Encrypted Memos

An account on the BitShares Blockchain has a so called **memo public key** associated with it that allows for initiating encrypted communications by means of a shared secreted obtain via the Elliptic-curve Diffie-Hellman Algorithm. This allows to attach encrypted messages to transfers that only sender and receiver can decrypt.

### Fees

Similar to most other Blockchains, interacting with the BitShares Blockchains comes with a fee for using its features (i.e. operations). Each operation comes with its own fee that can potentially be paid in any other token that is registered on the BitShares Blockchain next to the core native BTS token, if the governor of the other token chooses to support that.

### Identiry

BitShares makes use of human-readable account names that have to be registered together with public-keys in the blockchain prior to its usage.

Thus, the blockchain acts as a name-to-public-key resolver similar to the traditional domain name service (DNS). These named accounts enable users to easily remember and communicate their account information instead of using error-prone addresses.

### Permissions

The BitShares Blockchain designs permissions around accounts, rather than around cryptography, making it easier to use. Every account can be controlled by weighted combination of other accounts and/or keys. This creates a hierarchical structure that reflects how permissions are organized in real life, and makes multi-user control over funds easier for users.

Hence, BitShares does technically not have multi-signature accounts, but has multi-account permissions. That said, each public/private key pair is assigned a weight, and a threshold is defined for the authority. In order for a transaction to be valid, enough entities must sign so that the sum of their weights meets or exceeds the threshold.

***
