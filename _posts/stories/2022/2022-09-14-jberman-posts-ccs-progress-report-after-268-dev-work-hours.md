---
layout: post
category: story
title: "Justin Berman posts CCS progress report after ~268 hours of dev work"
description: "Justin Berman has published the first progress report for his full-time 2022 'part 3' Monero dev work CCS proposal."
tags: dev
image: 
---

Justin Berman[^1] has published the first progress report[^2] for his full-time 2022 (*part 3*) Monero dev work CCS proposal[^3]:

> **Hours worked: ~268**

### CCS work overview

- Wallets (CLI, GUI, and RPC tested) will check compatibility with the daemon's hard fork version when connecting and scanning[^4]
- Collaborated with @koe to fix multisig seed restore[^5]
- Reviewed the Ledger devs' final update to their Monero app for the hard fork[^6]
- Completed the Ledger integration for the hard fork in the Monero repo[^7]
- Made necessary hard fork changes to utility used by mining pools[^8]
[..]

To read the full report, consult the GH comment[^2].

---

[^1]: https://github.com/j-berman
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/330#note_18609](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/330#note_18609){:target="_blank"}
[^3]: [/jberman-monero-development-ccs-proposal-3-months/](/jberman-monero-development-ccs-proposal-3-months/)
[^4]: https://github.com/monero-project/monero/pull/8544
[^5]: https://github.com/monero-project/monero/pull/8545
[^6]: https://github.com/j-berman/app-monero/pull/1
[^7]: https://github.com/monero-project/monero/pull/8465
[^8]: https://github.com/Snipa22/node-cryptonote-util/pull/7
