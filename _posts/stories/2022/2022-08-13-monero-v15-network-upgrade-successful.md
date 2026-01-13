---
layout: post
category: story
title: "Monero v15 network upgrade successful"
description: "Block 2688888 was mined and it looks like Monero's v15 network upgrade was successful."
tags: [dev, pinned]
image: monero-v15.png
date: 2022-08-13 22:00
---

Block 2688888[^1] was mined and it looks like Monero's v15 network upgrade was successful:

> Block hash (height): 6bd4550a97aaba2eeab7be8cd70041ba0651e1a25300a4b963c83eb764a7149c (2688888)

The network did encounter a *one-time* minor issue which led to the *loss* of ~50 transactions at fork height:

> [..] at the fork height old txs got dropped from pools because they didn't have the minimum fee. (jberman)[^2]

> [..] we lost about 50tx on fork (selsta)[^3]

v14 transactions should still be permitted for a short period, according to MRL's *Rucknium*[^4]:

> v14 txs will be valid for another 24 hours I believe. This is the so-called "double fork" that minimizes user-level disruptions

*-TrustyDwarf-*[^5] shared the output of the `hard_fork_info` *monerod*[^6] command, which shows that more than 35% of nodes (~3.6K/10K) have already updated their Monero daemon to the required version (v16):

> hard_fork_info version 16 not enabled, 3618/10080 votes, threshold 0 current version 15, voting for version 16 

**Make sure to upgrade your nodes and wallets to continue using Monero.**

Read the Getmonero.org blog post[^7] for more information about the v15 hard fork.

*Thanks to gnuteardrops from monero.graphics for the Monero v15 poster[^8].*

*This is an ongoing story and the report will be updated when new information is available.*

---

[^1]: [https://xmrchain.net/search?value=2688888](https://xmrchain.net/search?value=2688888){:target="_blank"}
[^2]: https://libera.monerologs.net/monero-dev/20220813#c134478
[^3]: https://libera.monerologs.net/monero-dev/20220813#c134484
[^4]: https://libera.monerologs.net/monero-community/20220813#c134306
[^5]: https://libredd.it/r/Monero/comments/wnlpnx/it_happened/ik656c7/?context=3
[^6]: https://monerodocs.org/interacting/monerod-reference/
[^7]: [https://www.getmonero.org/2022/04/20/network-upgrade-july-2022.html](https://www.getmonero.org/2022/04/20/network-upgrade-july-2022.html){:target="_blank"}
[^8]: https://monero.graphics/all/monero-v15/
