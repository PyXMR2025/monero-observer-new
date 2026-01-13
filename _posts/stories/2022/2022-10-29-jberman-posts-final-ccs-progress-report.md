---
layout: post
category: story
title: "Justin Berman posts final CCS progress report"
description: "Justin Berman has published the final progress report for his full-time 2022 'part 3' Monero dev work CCS proposal."
tags: dev
image: 
date: 2022-10-29 18:00
---

Justin Berman[^1] has published the final progress report[^2] for his full-time 2022 (*part 3*) Monero dev work CCS proposal[^3]:

> **Hours worked: ~532**

### CCS work overview

- Submitted PR's for the background sync feature in the GUI, CLI, and RPC wallets [..][^4]'[^5]
- Re-wrote my fix to rescan a tx via the scan transaction feature to patch a wider set of issues.[^6]'[^7]
- Patched a bug in my wallet version compatibility code [..][^8]'[^9]
- Submitted a patch for a couple bugs preventing users from being able convert an existing full wallet into a watch-only wallet in the GUI.[^10]
- Started setting up a stress test framework to gauge how PR 8076 [..] perform under heavy load.[^11]

To read the full report, consult the GH comment[^2].

---

[^1]: https://github.com/j-berman
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/330#note_19233](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/330#note_19233){:target="_blank"}
[^3]: [/jberman-monero-development-ccs-proposal-3-months/](/jberman-monero-development-ccs-proposal-3-months/)
[^4]: https://github.com/monero-project/monero/pull/8619
[^5]: https://github.com/monero-project/monero-gui/pull/4050
[^6]: https://github.com/monero-project/monero/pull/8566
[^7]: https://github.com/monero-project/monero-gui/pull/4051
[^8]: https://github.com/monero-project/monero/pull/8585
[^9]: https://github.com/monero-project/monero-gui/pull/4036
[^10]: https://github.com/monero-project/monero/pull/8616
[^11]: https://github.com/monero-project/monero/pull/8076
