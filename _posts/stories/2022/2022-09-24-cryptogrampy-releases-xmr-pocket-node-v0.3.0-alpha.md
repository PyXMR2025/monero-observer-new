---
layout: post
category: story
title: CryptoGrampy releases PocketNode v0.3.0-alpha
description: "CryptoGrampy has released version 0.3.0-alpha of 'xmr-pocket-node', a simple full/pruned Monero GUI node for Android."
tags: mining
image: 
date: 2022-09-24 20:00
last_modified_at: 2023-03-17
---

CryptoGrampy[^1] has released version 0.3.0-alpha[^2] of *xmr-pocket-node*[^3], a simple full/pruned Monero GUI node for Android:

> Xmr PocketNode for Android (one-tap #Monero GUI node) has now been updated to v18 [..] Happy to merge any PR's[^4]

### Changes

- Monerod32 and 64 bit ARM binaries updated to latest v18 (Should make PocketNode usable now)
- Switched from safe:sync to fast:async to speed up PocketNode sync time. If this causes LMDB corruption on your devices, please create issue tickets.

The .APK file can be downloaded from Github[^2].

To support CryptoGrampy's work, you can donate XMR to the address listed at the bottom of the  *README.me*[^5] file.

To learn more about the project, consult the previous Monero Observer report[^6].

*Note that this project is still a WiP. Use at your own risk.*

---

**Update: v0.4.0 released[^7]; fixed some links.**

---

[^1]: https://github.com/CryptoGrampy
[^2]: [https://github.com/CryptoGrampy/xmr-pocket-node/releases/tag/v0.3.0-alpha](https://github.com/CryptoGrampy/xmr-pocket-node/releases/tag/v0.3.0-alpha){:target="_blank"}
[^3]: https://github.com/CryptoGrampy/xmr-pocket-node/
[^4]: https://nitter.net/CryptoGrampy/status/1573763064360587266#m
[^5]: https://github.com/CryptoGrampy/xmr-pocket-node#donate
[^6]: [/cryptogrampy-looking-contributors-pocketnode-project/](/cryptogrampy-looking-contributors-pocketnode-project/)
[^7]: [/cryptogrampy-releases-xmr-pocket-node-v0.4.0-alpha/](/cryptogrampy-releases-xmr-pocket-node-v0.4.0-alpha/)
