---
layout: post
category: story
title: "MMGen Wallet implements Monero 'offline transaction autosigning'"
description: "MMGen Wallet, the command-line online/offline multi-crypto wallet, has implemented Monero 'offline transaction autosigning'."
tags: wallets
date: 2023-04-24 21:00
---

MMGen Wallet[^1], the command-line online/offline multi-crypto wallet, has implemented Monero *offline transaction autosigning*[^2]:

> Cold signing of Monero transactions with maximum convenience. [..] A unique security feature is that signing wallets are created afresh in volatile memory for each transacting session and thus disappear when the signing machine is powered down.

Run `mmgen-xmrwallet --help` for documentation about offline autosigning in MMGen. For general information about Monero offline signing, visit monerodocs.org[^3].

To support the project, transfer some XMR to the donation address listed at the bottom of the *README.md*[^4] file on Github.

Consult the previous Monero Observer report[^5] to learn more about MMGen.

*Note: inspect the code before using, if you can read Python.*

---

[^1]: [https://mmgen-wallet.cc/](https://mmgen-wallet.cc/){:target="_blank"}{:rel="nofollow"}
[^2]: [https://github.com/mmgen/mmgen/commit/de77f9c27d5413ec79480dedc490fbd2835ce389](https://github.com/mmgen/mmgen/commit/de77f9c27d5413ec79480dedc490fbd2835ce389){:target="_blank"}{:rel="nofollow"}
[^3]: https://monerodocs.org/cold-storage/offline-transaction-signing/
[^4]: https://github.com/mmgen/mmgen#readme
[^5]: [/mmgen-cli-crypto-wallet-v13.2.0-released/](/mmgen-cli-crypto-wallet-v13.2.0-released/)

