---
layout: post
category: story
title: "tobtoht releases Feather Wallet v2.1.0"
description: "tobtoht has released Feather Wallet version 2.1.0."
tags: wallets
date: 2022-08-12 18:00
---

tobtoht[^1] has released Feather Wallet[^2] version 2.1.0[^3]:

> Windows users that installed Feather using the installer should update manually. Download the 2.1.0 installer from featherwallet.org/download and follow the installation procedure like normal.[^4]

### Changes

```
- Updated Monero to v0.18.1.0
- Sweeping or sending all spendable balance to an integrated address should no longer throw an error
- Fixed an issue that could cause the built-in updater to fail to install Feather (Windows installer)
- Importing a transaction should no longer hang the UI
```

### Known issues

```
- macOS: the webcam QR scanner is not enabled for this release
```

The complete list of improvements and bug fixes can be found in the release announcement[^4].

A GPG-signed list of the hashes[^5] is available on the official website and the signing key[^6] can be downloaded from the Github repository.

*Note: All Feather versions 1.0.1 and lower will stop working after the August 13 hardfork. Make sure to update your wallet to 2.0.0 or later.*

---

[^1]: https://github.com/tobtoht
[^2]: https://featherwallet.org/
[^3]: [https://featherwallet.org/download/](https://featherwallet.org/download/){:target="_blank"}, [https://github.com/feather-wallet/feather/releases/tag/2.1.0](https://github.com/feather-wallet/feather/releases/tag/2.1.0){:target="_blank"}{:rel="nofollow"}
[^4]: https://libredd.it/wmly8h
[^5]: https://featherwallet.org/files/releases/hashes-2.1.0.txt
[^6]: https://raw.githubusercontent.com/feather-wallet/feather/master/utils/pubkeys/featherwallet.asc
