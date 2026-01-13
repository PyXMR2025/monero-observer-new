---
layout: post
category: story
title: "BTCPay Server 1.6.1 release fixes critical altcoins integration issue also affecting XMR merchants" 
description: "The new BTCPay Server v1.6.1 release fixes a critical bug which affects altcoins integration, including XMR-accepting merchants."
tags: merchants
image: 
date: 2022-07-11 21:00
---

The new BTCPay Server[^1] v1.6.1[^2] release fixes a critical bug which affects altcoins integration, including XMR-accepting merchants:

> This fix a critical issue introduced by 1.6.0. If you are using altcoins integration, you need to update urgently as some change rate may be inverted for some pairs.

### Bug fixes

```
- Fix stack overflow if ripio rate provider is unavailable @NicolasDorier
- Fix: For some asset pair the kraken rate was inverted (#3957) @NicolasDorier
```

The bug was initially reported[^3] by Sethforprivacy[^4] and the patched version was released by NicolasDorier[^5].

Users that are currently still on v1.6.0 and use altcoins should update as soon as possible to avoid customers paying with the wrong exchange rate. 

---

[^1]: https://btcpayserver.org/
[^2]: [https://github.com/btcpayserver/btcpayserver/releases/tag/v1.6.1](https://github.com/btcpayserver/btcpayserver/releases/tag/v1.6.1){:target="_blank"}{:rel="nofollow"}
[^3]: https://github.com/btcpayserver/btcpayserver/pull/3957
[^4]: https://github.com/sethforprivacy
[^5]: https://github.com/NicolasDorier
