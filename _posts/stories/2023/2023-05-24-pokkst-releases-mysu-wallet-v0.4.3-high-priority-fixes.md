---
layout: post
category: story
title: "pokkst releases Mysu Wallet v0.4.3 with 'high priority' fixes"
description: "pokkst has released version 0.4.3 of MyNero Wallet with two 'high priority' bug fixes."
tags: wallets
date: 2023-05-24 20:00
last_modified_at: 2023-05-25
---

pokkst[^1] has released version 0.4.3[^2] of Mysu Wallet[^3] with two *high priority* bug fixes:

> This update has a few app-specific bug fixes, mainly UI stuff, but also has two bug fixes for the Monero codebase, one for the recent decoy selection vulnerability disclosed earlier today, and one for a DNS leak that still has an open pull request[^4]

### Changes overview

```
* Fixes for UI when creating multi-output transactions
* Onboarding flow UI changes
* Changed the button to send transactions in send flow to a slider
* HIGH PRIORITY: Implements DNS leak fix [..]
* HIGH PRIORITY: Updates Monero code to 0.18.2.2 [..]
```

The complete changelog is available on the website[^5].

To support the project you can donate XMR to the address listed on the website[^3].

*Note that Mysu is still in early development. The project's Github repository[^6] is no longer maintained[^7], as pokkst decided to move the source code to I2P[^8].*

---

**Update: versions 0.4.3.1 and 0.4.3.2 were released with a few minor bug fixes.**

---

[^1]: (XMPP w/OMEMO) pokkst at xmpp dot is
[^2]: [https://mysu.dev/download/](https://mynero.net/download/){:target="_blank"}
[^3]: [https://mysu.dev/](https://mysu.dev/){:target="_blank"}
[^4]: [https://r.nf/13q2mui/](https://r.nf/r/Monero/comments/13q2mui/mysu_wallet_043_is_now_available_this_contains/){:target="_blank"}{:rel="nofollow"}
[^5]: https://mynero.net/changelog.txt
[^6]: https://github.com/pokkst/monero-wallet/
[^7]: https://github.com/pokkst/monero-wallet/commit/eb070811c9c5ac93d6040758a465cc7037fb117e/
[^8]: (I2P) http://4hsesnr6mjb4qrflgf5gezjaszzoqnnisin7ywzbsv6pgcxysiaq.b32.i2p/pokkst/mynero

