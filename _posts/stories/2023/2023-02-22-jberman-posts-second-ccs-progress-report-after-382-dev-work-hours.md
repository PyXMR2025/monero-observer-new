---
layout: post
category: story
title: "Justin Berman posts CCS progress report after ~382 hours of Monero dev work"
description: "Justin Berman has published a second progress report for his full-time 2022-2023 'part 4' Monero dev work CCS proposal."
tags: dev
date: 2023-02-22 20:00
---

Justin Berman[^1] has published a second progress report[^2] for his full-time 2022-2023 (*part 4*) Monero dev work CCS proposal[^3]:

> **Update 2: ~382 hours**

### Work overview

- Used the Seraphis lib to implement a multithreaded scanner that is clocking in ~5-10% faster than wallet2 [..][^4]
- Investigated an issue causing some self-compiled daemons to hog the CPU. (Proposed a patch that prevents this from occurring.)[^5]
- Continued discussion and ideation on the migration to update wallets [..][^6]

The full dev update is available on Github in *!359*[^2].

---

[^1]: https://github.com/j-berman
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/359#note_20759](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/359#note_20759){:target="_blank"}
[^3]: [/j-berman-monero-development-3-months-ccs-proposal-part-4/](/j-berman-monero-development-3-months-ccs-proposal-part-4/)
[^4]: https://github.com/j-berman/monero-cpp/blob/2648d5f501f739d295516298df72939bc778b7e7/src/utils/monero_utils.cpp#L1250-L1291
[^5]: https://github.com/monero-project/monero/issues/8685#issuecomment-1396659121
[^6]: https://github.com/seraphis-migration/strategy/issues/2#issuecomment-1435447881
