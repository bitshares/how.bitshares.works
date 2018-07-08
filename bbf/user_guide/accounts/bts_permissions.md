## Permissions

In BitShares, each account has defferent type of permissions. Both are implemented using [Elliptic Curve Cryptography](https://en.wikipedia.org/wiki/Elliptic_curve_cryptography) (ECC) with public and private keys.

|   permission type       |  note            |
| ------------------- |---------- |
| Owner Permission    | This permission has administrative powers over the whole account and should be considered for ‘backup’ strategies. |                           
| Active Permission | Allows to access funds and some account settings, but cannot change the owner permission and is thus considered the “online” permissions.|                            

> Note: You can find the keys for your permissions in your BitShsares UI wallet Settings.

## Authorities 

In BitShares an **authority** consists of one or many entities that authorize an action, such as transfers or trades.

An authority consists of one or several pairs of an account name with a **weight**.

In order to obtain a valid transaction, the sum of the weights from signing the parties has to exceed the threshold as defined in the permissions.

## Hierarchical Corporate Accounts

BitShares designs permissions around people, rather than around cryptography, making it easy to use. Every account can be controlled by any weighted combination of other accounts and private keys. This creates a hierarchical structure that reflects how permissions are organized in real life, and makes multi-user control over funds easier than ever. Multi-user control is the single biggest contributor to security, and, when used properly, it can virtually eliminate the risk of theft due to hacking.

Read more about [Multi-Signature](/core/knowledge_base/multi-signature.md#multi-signature)


***
