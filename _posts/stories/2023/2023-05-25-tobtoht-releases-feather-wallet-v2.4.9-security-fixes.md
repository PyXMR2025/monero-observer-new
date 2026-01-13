---
layout: post
category: story
title: "tobtoht releases Feather Wallet v2.4.9 with security fixes"
description: "tobtoht has released Feather Wallet version 2.4.9 with important security fixes and updates."
tags: wallets
date: 2023-05-25 21:00
---

tobtoht[^1] has released Feather Wallet[^2] version 2.4.9[^3]'[^4] with important security fixes and updates.

### Changes overview

```
Updated Monero to v0.18.2.2
Updated expat to 2.5.0
Patched Qt for CVE-2023-{32573,32762,32763}
Patched OpenSSL for CVE-2023-{0464,0465,0466,1255}
wizard: preserve words when switching to a different seed type
wizard: macos: fixed inverted buttons on the seed warning dialog
```

The complete list of changes can be found on the Changelog[^5] page and on Github[^6].

Feather Wallet's release process[^7] was updated to *always rebase on top of the latest Monero version* after the misunderstanding about the impact of the recently disclosed decoy selection vulnerability[^8] that was present in the Monero codebase until v0.18.2.2.

A GPG-signed list of the hashes[^9] is available on the official website and the release signing key can be downloaded from multiple locations[^10].

Feather is 100% community-sponsored and you can support development efforts by transferring any XMR amount to the project’s donation address[^11] or by accessing *Help → Donate to Feather* in the wallet.

---

[^1]: https://github.com/tobtoht
[^2]: https://featherwallet.org/
[^3]: [https://featherwallet.org/download/](https://featherwallet.org/download/){:target="_blank"}
[^4]: https://github.com/feather-wallet/feather/releases/tag/2.4.9
[^5]: https://featherwallet.org/changelog/
[^6]: [https://github.com/feather-wallet/feather/compare/2.4.5...2.4.9](https://github.com/feather-wallet/feather/compare/2.4.5...2.4.9){:target="_blank"}{:rel="nofollow"}
[^7]: [https://github.com/feather-wallet/feather/blob/master/RELEASE.md](https://github.com/feather-wallet/feather/blob/master/RELEASE.md){:target="_blank"}{:rel="nofollow"}
[^8]: [/jeffro256-vulnerability-disclosure-highlights-high-severity-bug-patched-monero-v0.18.2.2/](/jeffro256-vulnerability-disclosure-highlights-high-severity-bug-patched-monero-v0.18.2.2/)
[^9]: https://featherwallet.org/files/releases/hashes-2.4.9.txt
[^10]: https://docs.featherwallet.org/guides/release-signing-key
[^11]: [https://docs.featherwallet.org/guides/donate](https://docs.featherwallet.org/guides/donate){:target="_blank"}
