---
layout: post
category: story
title: "Monero Dev Activity Report - Week 24 2022: 8 PRs, 5 Issues"
description: "This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions."
tags: dev
image: 
date: 2022-06-19 21:00
---

This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions.

## 1 - PRs (8, 7:1:0)

Opened (7)

`monero-project/monero`:

- **#8384[^1]** Revert "Make RPC server functions that read db thread safe" (j-berman)
- **#8385[^2]** rpc: --rpc-ssl-persistent CLI option (jeffro256)
- **#8387[^3]** Label multisig as unsafe, not experimental, as #8149 isn't merged (kayabaNerve)
- **#8388[^4]** Chunk /gettransactions to avoid hitting restricted RPC limit (tobtoht)
- **#8390[^5]** Add fish shell completions for monerod and monero-wallet-gui (LeoNero)
- **#8391[^6]** simplewallet: print usage when given no args (hinto-janaiyo)
- **#8392[^7]** cryptonote_basic: do not print name of a possibly invalid type (moneromooo-monero)

`monero-project/monero-gui`: none

Closed (1)

`monero-project/monero`: 

- **#8383[^8]** Move DB lock guard to later stage (SChernykh)

`monero-project/monero-gui`: none

Merged (0)

`monero-project/monero`: none

`monero-project/monero-gui`: none

## 2 - ISSUES (5, 1:4)

Opened (1)

`monero-project/monero`: none

`monero-project/monero-gui`: 

- **#3948[^9]** Monero GUI forgets some of its configuration (usernamesaredumb2)

Closed (4)

`monero-project/monero`: 

- **#8386[^10]** Many core_tests not currently passing (paulshapiro)
- **#8389[^11]** Memory leak in monerod v0.17.3.2-release (daemonserj)
- **#8393[^12]** Cmake cannot find Boost on Fedora when building a static-release (larteyoh)

`monero-project/monero-gui`: 

- **#3941[^13]** Cannot change blockchain location (CountCypher)

That's it for this week's dev activity report. I will try and publish one every Sunday. Let me know if I missed anything or if you want to see any other statistics/repos included in future reports. Feedback/edits: @ [/about](/about).

Previous reports are listed in the [[dev]](/tag/dev) section. 

**-3RA**

---

[^1]: https://github.com/monero-project/monero/pull/8384
[^2]: https://github.com/monero-project/monero/pull/8385
[^3]: https://github.com/monero-project/monero/pull/8387
[^4]: https://github.com/monero-project/monero/pull/8388
[^5]: https://github.com/monero-project/monero/pull/8390
[^6]: https://github.com/monero-project/monero/pull/8391
[^7]: https://github.com/monero-project/monero/pull/8392

[^8]: https://github.com/monero-project/monero/pull/8383

[^9]: https://github.com/monero-project/monero-gui/issues/3948

[^10]: https://github.com/monero-project/monero/issues/8386
[^11]: https://github.com/monero-project/monero/issues/8389
[^12]: https://github.com/monero-project/monero/issues/8393

[^13]: https://github.com/monero-project/monero-gui/issues/3941

