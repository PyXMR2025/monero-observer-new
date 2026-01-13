---
layout: post
category: story
title: "Monero Dev Activity Report - Week 25 2022: 8 PRs, 11 Issues"
description: "This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions."
tags: dev
image: 
date: 2022-06-26 21:00
---

This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions.

## 1 - PRs (8, 7:1:0)

Opened (7)

`monero-project/monero`:

- **#8394[^1]** cryptonote_basic: catch crypto api errors (moneromooo-monero)
- **#8395[^2]** wallet2: fix invalid memory access importing invalid outputs (moneromooo-monero)
- **#8396[^3]** Valgrind fixes for unit tests (moneromooo-monero)
- **#8400[^4]** Depends: Unbound disable getentropy()/reallocarray() (glibc < 2.26) (TheCharlatan)
- **#8404[^5]** wallet2: remove obsolete rpc version check (tobtoht)

`monero-project/monero-gui`: 

- **#3949[^6]** docker: update Qt to 5.15.5 (selsta)
- **#3954[^7]** Transfer: don't create offline tx before wallet is synced (selsta)

Closed (1)

`monero-project/monero`: 

- **#8392[^8]** cryptonote_basic: do not print name of a possibly invalid type (moneromooo-monero)

`monero-project/monero-gui`: none

Merged (0)

`monero-project/monero`: none

`monero-project/monero-gui`: none

## 2 - ISSUES (11, 6:5)

Opened (6)

`monero-project/monero`: 

- **#8397[^9]** Add generate_blocks addr numblocks [starting_nonce] command to monerod when in regtest mode (LeoNero)
- **#8398[^10]** get_tx_key should support raw_monero_tx blob as input (SamsungGalaxyPlayer)
- **#8402[^11]** Monerod shuts down at random times (ksdhans)
- **#8403[^12]** error creating wallet via RPC (saravananp-001)
- **#8405[^13]** Unspendable dust outputs (> 0.00000582 XMR~) (hinto-janaiyo)

`monero-project/monero-gui`: 

- **#3953[^14]** XMR was lost after trying to send to another wallet (xmr2206)

Closed (5)

`monero-project/monero`: 

- **#8399[^15]** Monero transferred funds haven't arrived (davidbroomhead)
- **#8401[^16]** When will the new version be released (v0.18) (EWIT521)

`monero-project/monero-gui`: 

- **#3950[^17]** Monero transferred funds haven't arrived (davidbroomhead)
- **#3951[^18]** Payment proof issue (rikanox)
- **#3952[^19]** Daemon stuck at block height 2651490 (C0smicfrog)

That's it for this week's dev activity report. I will try and publish one every Sunday. Let me know if I missed anything or if you want to see any other statistics/repos included in future reports. Feedback/edits: @ [/about](/about).

Previous reports are listed in the [[dev]](/tag/dev) section. 

**-3RA**

---

[^1]: https://github.com/monero-project/monero/pull/8394
[^2]: https://github.com/monero-project/monero/pull/8395
[^3]: https://github.com/monero-project/monero/pull/8396
[^4]: https://github.com/monero-project/monero/pull/8400
[^5]: https://github.com/monero-project/monero/pull/8404

[^6]: https://github.com/monero-project/monero-gui/pull/3949
[^7]: https://github.com/monero-project/monero-gui/pull/3954

[^8]: https://github.com/monero-project/monero/pull/8392

[^9]: https://github.com/monero-project/monero/issues/8397
[^10]: https://github.com/monero-project/monero/issues/8398
[^11]: https://github.com/monero-project/monero/issues/8402
[^12]: https://github.com/monero-project/monero/issues/8403
[^13]: https://github.com/monero-project/monero/issues/8405

[^14]: https://github.com/monero-project/monero-gui/issues/3953

[^15]: https://github.com/monero-project/monero/issues/8399
[^16]: https://github.com/monero-project/monero/issues/8401

[^17]: https://github.com/monero-project/monero-gui/issues/3950
[^18]: https://github.com/monero-project/monero-gui/issues/3951
[^19]: https://github.com/monero-project/monero-gui/issues/3952

