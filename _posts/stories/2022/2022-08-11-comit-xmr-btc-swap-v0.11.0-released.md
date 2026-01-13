---
layout: post
category: story
title: "COMIT 'xmr-btc-swap' v0.11.0 released"
description: "The new 0.11.0 version of COMIT's XMR-BTC atomic swap implementation 'xmr-btc-swap' was released and it updates to Monero v0.18.0.0."
tags: services
image: 
date: 2022-08-11 20:00
---

Version 0.11.0[^1] of COMIT[^2]'s XMR-BTC atomic swap implementation (*xmr-btc-swap*[^3]) was released, and it updates to Monero v0.18.0.0[^4]:

> I'm happy to report that we've been busy upgrading the tool in prep for the hard fork, with a bunch of improvements in general, and are releasing version 0.11 today![^5]

## Changes overview

- Update from Monero v0.17.2.0 to Monero v0.18.0.0
- Change Monero nodes to Rino tool nodes
- Always write logs as JSON to files
- Reduce Monero locking transaction fee amount from 0.000030 to 0.000016 XMR [..]
- Reduce required confirmations for Bitcoin transactions from 2 to 1 [..]
- Both the ASB and CLI now support the Identify protocol. [..]
- [..]

Downloads, hashes, and the complete list of changes are available on the release page[^1].

Visit Github[^3] to learn more about the *Bitcoin-Monero Cross-chain Atomic Swap* and join COMIT's Matrix channel[^6] if you need help.

Read the *Safety*[^7] section of the README.md file before using this tool.

*Note that COMIT is no longer maintaing the project[^8]. binarybaron, lescuer97 and delta1 are the current maintainers of xmr-btc-swap.*

---

[^1]: [https://github.com/comit-network/xmr-btc-swap/releases/tag/0.11.0](https://github.com/comit-network/xmr-btc-swap/releases/tag/0.11.0){:target="_blank"}{:rel="nofollow"}
[^2]: https://comit.network
[^3]: https://github.com/comit-network/xmr-btc-swap
[^4]: [/monero-v0.18.0.0-fluorine-fermi-released/](/monero-v0.18.0.0-fluorine-fermi-released/)
[^5]: https://libredd.it/wly8of
[^6]: https://matrix.to/#/#comit-monero:matrix.org
[^7]: https://github.com/comit-network/xmr-btc-swap#safety
[^8]: [/comit-btc-xmr-atomic-swap-project-looking-maintainers/](/comit-btc-xmr-atomic-swap-project-looking-maintainers/)
