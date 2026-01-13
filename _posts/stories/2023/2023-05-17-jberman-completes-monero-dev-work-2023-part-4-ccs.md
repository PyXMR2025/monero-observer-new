---
layout: post
category: story
title: "Justin Berman completes Monero dev work CCS proposal"
description: "Justin Berman has published a third (and final) progress report for his full-time 2022-2023 (part 4) Monero dev work CCS proposal."
tags: [CCS, dev]
date: 2023-05-17 20:00
---

Justin Berman[^1] has published a third (and final) progress report[^2] for his full-time 2022-2023 (*part 4*) Monero dev work CCS proposal[^3]:

> Total hours worked: way over 480 (I stopped keeping track at 480).

### Work overview

- completed a mock implementation of an optimized wallet scanner that points to a live daemon [..] observed a speedup of ~35-45% (remote daemon) & a speedup of ~5-10% (local daemon)
- wrote a utility program called monero-blockchain-scanner[^4] that anyone can use to benchmark this scanner and compare it to wallet2

Justin is planning to open a new CCS proposal *soon* to get the scanner *production ready* and also continue with Seraphis wallet work.

The full dev update is available on Github in *!359*[^2].

---

[^1]: https://github.com/j-berman
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/359#note_21276](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/359#note_21276){:target="_blank"}
[^3]: [/j-berman-monero-development-3-months-ccs-proposal-part-4/](/j-berman-monero-development-3-months-ccs-proposal-part-4/)
[^4]: https://github.com/j-berman/monero/commit/c41f9a98a3eb4fb637c6bf677d2b296976dfe5d3
