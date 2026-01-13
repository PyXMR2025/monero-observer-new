---
layout: post
category: story
title: "Monero Dev Activity Report - Week 37 2022: 22 PRs, 7 Issues"
description: "This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions."
tags: dev
image: 
date: 2022-09-18 21:00
---

This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions.

## 1 - PRs (22, 9:2:11)

Opened (9)

`monero-project/monero`:

- **#8564[^1]** Fix static builds for Ubuntu 22.04 (LocalMonero)
- **#8565[^2]** wallet: avoid extra copy when importing to view only wallet (jeffro256)
- **#8566[^3]** wallet2: fix rescanning tx via scan_tx [release] (j-berman)
- **#8568[^4]** wallet2: fix rescanning tx via scan_tx [master] (j-berman)
- **#8569[^5]** levin_abstract_invoke: remove dead code (jeffro256)
- **#8570[^6]** fix build in netbsd (mmyjona)
- **#8571[^7]** Keys: Update for expired 'rbrunner7' key, valid 2 years (rbrunner7)
- **#8572[^8]** unit_tests: suppress memwipe uninit warnings (jeffro256xxx)

`monero-project/monero-gui`: 

- **#4030[^9]** build: prepare v0.18.1.1 (selsta)

Closed (2)

`monero-project/monero`: 

- **#8563[^10]** Update CMakeLists.txt to fix Ubuntu 22.04 static builds (requires building libzmq3 from source (LocalMonero)
- **#8025[^11]** unit tests: Harden flaky decoy output selection tests (j-berman)

`monero-project/monero-gui`: none

Merged (11)

`monero-project/monero`: 

- **#8551[^12]** multisig: fix seed restore (suggestions by @UkoeHB) [master] (j-berman)
- **#8556[^13]** wallet2: check wallet compatibility with daemon's hard fork version [master] (j-berman)
- **#8544[^14]** wallet2: check wallet compatibility with daemon's hard fork version [release] (j-berman)
- **#8545[^15]** multisig: fix seed restore (suggestions by @UkoeHB) [release] (j-berman)

`monero-project/monero-gui`: 

- **#4000[^16]** repo: remove ldns leftovers (selsta)
- **#4003[^17]** docker: update linux dependencies (selsta)
- **#4011[^18]** main: add --no-igd to simple mode flags (selsta)
- **#4013[^19]** cmake: update libicu dll version (selsta)
- **#4025[^20]** docker: update qt to 5.15.6 (tobtoht)
- **#4026[^21]** installer: allow to install on arm64 (selsta)
- **#4031[^22]** Update translations from webalte (Monero-Weblate)

## 2 - ISSUES (7, 4:3)

Opened (4)

`monero-project/monero`: 

- **#8562[^23]** SOCKS5 not supported (vdo)
- **#8567[^24]** Address doesn't belong to the wallet while I created the address with wallet RPC "create_address" (devilrayzl)
- **#8573[^25]** When syncing blockchain "Error in handle_invoke_map: std::bad_alloc" (gst2233)

`monero-project/monero-gui`: 

- **#4028[^26]** monero wallet v18 unusable in xwindows (oppianmatt)

Closed (3)

`monero-project/monero`: 

- **#8561[^27]** monero-wallet-rpc freezes during getting height and synchronization (gst2233)
- **#8537[^28]** Restoring multisig wallet fails (tmoravec)

`monero-project/monero-gui`: 

- **#4029[^29]** Sent XMR to GUI WALLET, balance shows 0 (gregus79)

That's it for this week's dev activity report. I will try and publish one every Sunday. Let me know if I missed anything or if you want to see any other statistics/repos included in future reports. Feedback/edits: @ [/about](/about).

Previous reports are listed in the [[dev]](/tag/dev) section. 

**-3RA**

---

[^1]: https://github.com/monero-project/monero/pull/8564
[^2]: https://github.com/monero-project/monero/pull/8565
[^3]: https://github.com/monero-project/monero/pull/8566
[^4]: https://github.com/monero-project/monero/pull/8568
[^5]: https://github.com/monero-project/monero/pull/8569
[^6]: https://github.com/monero-project/monero/pull/8570
[^7]: https://github.com/monero-project/monero/pull/8571
[^8]: https://github.com/monero-project/monero/pull/8572

[^9]: https://github.com/monero-project/monero-gui/pull/4030

[^10]: https://github.com/monero-project/monero/pull/8563
[^11]: https://github.com/monero-project/monero/pull/8025

[^12]: https://github.com/monero-project/monero/pull/8551
[^13]: https://github.com/monero-project/monero/pull/8556
[^14]: https://github.com/monero-project/monero/pull/8544
[^15]: https://github.com/monero-project/monero/pull/8545

[^16]: https://github.com/monero-project/monero-gui/pull/4000
[^17]: https://github.com/monero-project/monero-gui/pull/4003
[^18]: https://github.com/monero-project/monero-gui/pull/4011
[^19]: https://github.com/monero-project/monero-gui/pull/4013
[^20]: https://github.com/monero-project/monero-gui/pull/4025
[^21]: https://github.com/monero-project/monero-gui/pull/4026
[^22]: https://github.com/monero-project/monero-gui/pull/4031

[^23]: https://github.com/monero-project/monero/issues/8562
[^24]: https://github.com/monero-project/monero/issues/8567
[^25]: https://github.com/monero-project/monero/issues/8573

[^26]: https://github.com/monero-project/monero-gui/issues/4028

[^27]: https://github.com/monero-project/monero/issues/8561
[^28]: https://github.com/monero-project/monero/issues/8537

[^29]: https://github.com/monero-project/monero-gui/issues/4029

