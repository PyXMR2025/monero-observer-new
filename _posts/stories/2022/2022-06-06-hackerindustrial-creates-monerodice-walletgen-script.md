---
layout: post
category: story
title: "HackerIndustrial creates 'MoneroDice-WalletGen' script that generates offline XMR wallet seeds by rolling dice"
description: "HackerIndustrial has created 'MoneroDice-WalletGen', a Python script that can generate offline Monero wallet seeds by rolling dice."
tags: wallets
image: monerodice-walletgen.png
date: 2022-06-06 19:00
---

HackerIndustrial[^1] has created *MoneroDice-WalletGen*[^2], a Python script that can generate offline Monero wallet seeds by rolling dice:

> To use the script you will need one 6-sided dice. The dice is used as a form of entropy for the random hex that the seed is generated from.

The resulting seed can be used with the official Monero GUI & CLI wallets[^3].

HackerIndustrial has also recently submitted a CCS proposal to build *MoneroSigner*[^4], a fork of *Seedsigner*[^5] that supports Monero.

---

[^1]: https://repo.getmonero.org/HackerIndustrial
[^2]: [https://github.com/Monero-HackerIndustrial/MoneroDice-WalletGen](https://github.com/Monero-HackerIndustrial/MoneroDice-WalletGen){:target="_blank"}
[^3]: https://www.getmonero.org/downloads/
[^4]: [/hackerindustrial-submits-monerosigner-ccs-proposal](/hackerindustrial-submits-monerosigner-ccs-proposal)
[^5]: https://seedsigner.com/
