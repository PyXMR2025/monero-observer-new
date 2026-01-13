---
layout: post
category: story
title: "Monero Dev Activity Report - Week 31 2022: 8 PRs, 12 Issues"
description: "This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions."
tags: dev
image: 
date: 2022-08-07 21:00
---

This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions.

## 1 - PRs (8, 5:3:0)

Opened (5)

`monero-project/monero`:

- **#8483[^1]** feat(trezor): add HF15 support, BP+, release-v0.18 (ph4r05)
- **#8486[^2]** dns_util: remove outdated DNSSEC DS trust anchor (selsta)

`monero-project/monero-gui`: 

- **#3993[^3]** fix and update copyright notice (coquizen)
- **#3994[^4]** libwalletqt: refresh once on wallet opening (selsta)
- **#3995[^5]** main: only check mining status when using local node (selsta)

Closed (3)

`monero-project/monero`: 

- **#8479[^6]** GUI: multisig api support (reemuru)
- **#8482[^7]** wallet2, RPC: Optimize RPC calls for periodic refresh from 3 down to 1 (erciccione)

`monero-project/monero-gui`: 

- **#3990[^8]** [WIP] M/N Multisig Support (reemuru)

Merged (0)

`monero-project/monero`: none

`monero-project/monero-gui`: none

## 2 - ISSUES (12, 5:7)

Opened (5)

`monero-project/monero`: 

- **#8476[^9]** Offline sign transactions requires "Try using export_outputs all" periodically. (nape-max)
- **#8478[^10]** failed to get output distribution (bogdangainusa)
- **#8480[^11]** sweep_* command: Please add an "error" when args (index and address) are incorrectly placed (afungible)
- **#8484[^12]** Segfault and corrupt wallet files caused by exporting and importing outputs with monero-wallet-rpc (woodser)

`monero-project/monero-gui`: 

- **#3996[^13]** VERY WEIRD interface at computer wake up (lpoirothattermann)

Closed (7)

`monero-project/monero`: 

- **#8477[^14]** monero-wallet-rpc fails to connect to daemon: (sne4ker)
- **#8481[^15]** Monero 18.0.0 vs. Ledger Nano X (fabiobfava)
- **#8485[^16]** Unknown command 'mining_status' (vincent7128)
- **#8487[^17]** monerod crashes after failing to store HTTP SSL cert/key for RPC server (bloatmode)

`monero-project/monero-gui`: 

- **#3989[^18]** v18 syncing issues linux (fugbixer)
- **#3991[^19]** Monero gui v 0.18.0.0 not working with latest Ledger app. GUI states update to at least 1.6.x when app is at 1.7.8 (jtmoderate876)
- **#3992[^20]** 0.18 Monero GUI not working with ledger S (FelixMuellCode)

That's it for this week's dev activity report. I will try and publish one every Sunday. Let me know if I missed anything or if you want to see any other statistics/repos included in future reports. Feedback/edits: @ [/about](/about).

Previous reports are listed in the [[dev]](/tag/dev) section. 

**-3RA**

---

[^1]: https://github.com/monero-project/monero/pull/8483
[^2]: https://github.com/monero-project/monero/pull/8486

[^3]: https://github.com/monero-project/monero-gui/pull/3993
[^4]: https://github.com/monero-project/monero-gui/pull/3994
[^5]: https://github.com/monero-project/monero-gui/pull/3995

[^6]: https://github.com/monero-project/monero/pull/8479
[^7]: https://github.com/monero-project/monero/pull/8482

[^8]: https://github.com/monero-project/monero-gui/pull/3990

[^9]: https://github.com/monero-project/monero/issues/8476
[^10]: https://github.com/monero-project/monero/issues/8478
[^11]: https://github.com/monero-project/monero/issues/8480
[^12]: https://github.com/monero-project/monero/issues/8484

[^13]: https://github.com/monero-project/monero-gui/issues/3996

[^14]: https://github.com/monero-project/monero/issues/8477
[^15]: https://github.com/monero-project/monero/issues/8481
[^16]: https://github.com/monero-project/monero/issues/8485
[^17]: https://github.com/monero-project/monero/issues/8487

[^18]: https://github.com/monero-project/monero-gui/issues/3989
[^19]: https://github.com/monero-project/monero-gui/issues/3991
[^20]: https://github.com/monero-project/monero-gui/issues/3992

