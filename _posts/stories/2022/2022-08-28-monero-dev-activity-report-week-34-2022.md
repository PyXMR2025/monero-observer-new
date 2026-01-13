---
layout: post
category: story
title: "Monero Dev Activity Report - Week 34 2022: 33 PRs, 12 Issues"
description: "This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions."
tags: dev
image: 
date: 2022-08-28 18:00
---

This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions.

## 1 - PRs (33, 7:3:23)

Opened (7)

`monero-project/monero`:

- **#8527[^1]** daemon: remove redundant check (serhack)
- **#8528[^2]** serialization: forbid reading 0 varints from empty data (moneromooo-monero)
- **#8529[^3]** rpc: remove overwriting value (serhack)
- **#8534[^4]** build: prepare v0.18.1.1 (selsta)
- **#8535[^5]** rpc: avoid superfluous buffer copy (jeffro256)
- **#8538[^6]** Fix shared_ptr cycle in test_epee_connection.test_lifetime (vtnerd)

`monero-project/monero-gui`: 

- **#4013[^7]** cmake: update libicu dll version (selsta)

Closed (3)

`monero-project/monero`: 

- **#8530[^8]** Release v0.18 (WooKeyWallet)
- **#4139[^9]** [Do Not Merge] Adding "light wallet server" that is mymonero compatible (vtnerd)
- **#7649[^10]** Cleanup TCP shutdown sequence in epee server (vtnerd)

`monero-project/monero-gui`: none

Merged (23)

`monero-project/monero`: 

- **#8299[^11]** feat(trezor): add HF15 support, BP+ (ph4r05)
- **#8323[^12]** DOCS: Rework Portable storage format example (jeffro256)
- **#8333[^13]** Focus Doxygen documentation (jeffro256)
- **#8352[^14]** epee: more dead code (jeffro256)
- **#8359[^15]** GCC: unused warnings (jeffro256)
- **#8379[^16]** Fix use of rtxn without a mdb_txn_safe wrapper (hyc)
- **#8381[^17]** Fixed get_block_template_backlog performance (SChernykh)
- **#8415[^18]** txpool: continue pool pruning even if a tx can't be found (j-berman)
- **#8419[^19]** Fix some paths for toolchain / build (hyc)
- **#8427[^20]** zmq: publish submitted txs via zmq (j-berman)
- **#8428[^21]** keccak: error out if passed mdlen 100 (moneromooo-monero)
- **#8442[^22]** Bump Gitian build instructions to v0.18.1.0 (sethforprivacy)
- **#8444[^23]** gpg_keys: add jeffro256 key (jeffro256)
- **#8450[^24]** Fix occasional mining test failure (moneromooo-monero)
- **#8465[^25]** ledger support for hf 15 (BP+, view tags) [master] (j-berman)
- **#8491[^26]** Bump Gitian build instructions to v0.18.1.0 [Release Branch] (sethforprivacy)
- **#8460[^27]** randomx: update submodule (selsta)
- **#8462[^28]** device: set ledger min app version (selsta)
- **#8486[^29]** dns_util: remove outdated DNSSEC DS trust anchor (selsta)
- **#8490[^30]** version: bump master version number (selsta)
- **#8495[^31]** repo: remove ldns leftovers (selsta)
- **#8496[^32]** README: unbound is not vendored anymore (selsta)
- **#8497[^33]** depends: remove unused packages (selsta)

`monero-project/monero-gui`: none

## 2 - ISSUES (12, 5:7)

Opened (5)

`monero-project/monero`: 

- **#8531[^34]** scan_tx causes extra transfers with fee=0 (woodser)
- **#8532[^35]** Wallet transactions disappear after first confirmation when wallet rpc started with offline daemon (woodser)
- **#8537[^36]** Restoring multisig wallet fails (tmoravec)

`monero-project/monero-gui`: 

- **#4015[^37]** Pruned Node Language and Bootstrap Mode (PicoDeNero)
- **#4017[^38]** Recommendation for monero-gui-wallet-guide.pdf (or gui tool for ip binding in Monero wallet) (Poecilia)

Closed (7)

`monero-project/monero`: 

- **#8474[^39]** DNSSEC DS record out of date in dns_utils.cpp (OrvilleRed)
- **#8473[^40]** RockPro64 sync struggles (dawiepoolman)
- **#8536[^41]** Wallet cli does not connect to daemon, although curl works (aghamir)
- **#8453[^42]** monero-wallet-cli - Crash on macOS(Arm or x64) (realityworks)
- **#8533[^43]** Could blockchain sync use more than 2 cores? (stefan-reich)

`monero-project/monero-gui`: 

- **#4014[^44]** Wayland support (Froggy232)
- **#4016[^45]** I used the monero gui, my balance is not displayed and my transaction history is missing. (web26082022)

That's it for this week's dev activity report. I will try and publish one every Sunday. Let me know if I missed anything or if you want to see any other statistics/repos included in future reports. Feedback/edits: @ [/about](/about).

Previous reports are listed in the [[dev]](/tag/dev) section. 

**-3RA**

---

[^1]: https://github.com/monero-project/monero/pull/8527
[^2]: https://github.com/monero-project/monero/pull/8528
[^3]: https://github.com/monero-project/monero/pull/8529
[^4]: https://github.com/monero-project/monero/pull/8534
[^5]: https://github.com/monero-project/monero/pull/8535
[^6]: https://github.com/monero-project/monero/pull/8538

[^7]: https://github.com/monero-project/monero-gui/pull/4013

[^8]: https://github.com/monero-project/monero/pull/8530
[^9]: https://github.com/monero-project/monero/pull/4139
[^10]: https://github.com/monero-project/monero/pull/7649

[^11]: https://github.com/monero-project/monero/pull/8299
[^12]: https://github.com/monero-project/monero/pull/8323
[^13]: https://github.com/monero-project/monero/pull/8333
[^14]: https://github.com/monero-project/monero/pull/8352
[^15]: https://github.com/monero-project/monero/pull/8359
[^16]: https://github.com/monero-project/monero/pull/8379
[^17]: https://github.com/monero-project/monero/pull/8381
[^18]: https://github.com/monero-project/monero/pull/8415
[^19]: https://github.com/monero-project/monero/pull/8419
[^20]: https://github.com/monero-project/monero/pull/8427
[^21]: https://github.com/monero-project/monero/pull/8428
[^22]: https://github.com/monero-project/monero/pull/8442
[^23]: https://github.com/monero-project/monero/pull/8444
[^24]: https://github.com/monero-project/monero/pull/8450
[^25]: https://github.com/monero-project/monero/pull/8465
[^26]: https://github.com/monero-project/monero/pull/8491
[^27]: https://github.com/monero-project/monero/pull/8462
[^28]: https://github.com/monero-project/monero/pull/8462
[^29]: https://github.com/monero-project/monero/pull/8486
[^30]: https://github.com/monero-project/monero/pull/8490
[^31]: https://github.com/monero-project/monero/pull/8495
[^32]: https://github.com/monero-project/monero/pull/8496
[^33]: https://github.com/monero-project/monero/pull/8497

[^34]: https://github.com/monero-project/monero/issues/8531
[^35]: https://github.com/monero-project/monero/issues/8532
[^36]: https://github.com/monero-project/monero/issues/8537

[^37]: https://github.com/monero-project/monero-gui/issues/4015
[^38]: https://github.com/monero-project/monero-gui/issues/4017

[^39]: https://github.com/monero-project/monero/issues/8474
[^40]: https://github.com/monero-project/monero/issues/8473
[^41]: https://github.com/monero-project/monero/issues/8536
[^42]: https://github.com/monero-project/monero/issues/8453
[^43]: https://github.com/monero-project/monero/issues/8533

[^44]: https://github.com/monero-project/monero-gui/issues/4014
[^45]: https://github.com/monero-project/monero-gui/issues/4016

