---
layout: post
category: story
title: "Monero community decides to temporarily remove MyMonero and Edge lightweight wallets from Getmonero.org"
description: "The Monero community has decided to temporarily remove (PR #2030) the 'MyMonero' and 'Edge' lightweight XMR wallets from the official Getmonero.org website, until they are 'confirmed to be working with the hard fork'."
tags: wallets
image: 
date: 2022-08-25 20:00
last_modified_at: 2022-08-30
---

The Monero community has decided to temporarily remove (PR #2030[^1]) the *MyMonero*[^2] and *Edge*[^3] lightweight XMR wallets from the official Getmonero.org website, until they are *confirmed to be working with the hard fork*:

> [..] GetMonero.org should not point users to another wallet that is also currently not working. Once MyMonero is confirmed to be working with the hard fork, it can be added to Downloads again. (issue #2029[^4])

MyMonero reacted by releasing version 1.3.2 for their web[^5], mobile[^6] and desktop (Linux/Mac)[^7] wallets:

> Our web wallet, as well as our Mac and Linux apps have now been patched. Our engineers are still busy working on our mobile apps and Windows systems. We will provide further updates once these are all up and running.[^8]

Edge has restored the ability to *detect received Monero transactions and render Monero balances*[^9], but XMR transfers are currently not possible, as the wallet is using MyMonero's SDK.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 22/8/29: MyMonero is now *fully operational* on all platforms[^10].**

**Update 22/8/30: MyMonero and Edge were readded to the getmonero.org website[^11].**

---

[^1]: [https://github.com/monero-project/monero-site/pull/2030](https://github.com/monero-project/monero-site/pull/2030){:target="_blank"}{:rel="nofollow"}
[^2]: https://mymonero.com/
[^3]: https://edge.app/
[^4]: [https://github.com/monero-project/monero-site/issues/2029](https://github.com/monero-project/monero-site/issues/2029){:target="_blank"}{:rel="nofollow"}
[^5]: https://github.com/mymonero/mymonero-web-js/pull/64
[^6]: https://github.com/mymonero/mymonero-mobile/releases/tag/v1.3.2
[^7]: https://github.com/mymonero/mymonero-app-js/releases/tag/v1.3.2
[^8]: https://github.com/mymonero/mymonero-app-js/issues/513#issuecomment-1227235460
[^9]: https://nitter.net/EdgeWallet/status/1562861513861320704#m
[^10]: https://github.com/monero-project/monero-site/pull/2035#issuecomment-1230483247
[^11]: [/mymonero-edge-wallets-readded-getmonero-website/](/mymonero-edge-wallets-readded-getmonero-website/)
