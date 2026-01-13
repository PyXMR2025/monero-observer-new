---
layout: post
category: story
title: "Boog90 submits CCS proposal to build alternative Monero node in Rust"
description: "Boog90 has submitted a CCS proposal looking to build an alternative Monero node in Rust."
tags: CCS
date: 2022-12-30 22:00
last_modified_at: 2023-04-18
---

Boog90[^1] has submitted a CCS proposal[^2] looking to build an alternative Monero node in Rust:

> Currently there is only one Monero node (monerod) and it's built in C/C++. [..] Having just one implementation of monerod leaves the network vulnerable to attacks that target just one implementation, having multiple separate implementations would make the network more resilient to these attacks.

```
Total funding: 423 XMR ($45/h @ 35 h/wk).

ETA: ~39 weeks.
```

### Milestones overview

- M1: Verification functions and random-x crate (110 XMR)
- M2: Database and network code to sync and store blockchain (110 XMR)
- M3: Final features (RPC, anonymity net support, pruning, Dandelion++) (203 XMR)

Boog90 helped update the Rust Monero Library[^3] for the recent hardfork and fixed multiple *consensus issues*. Relevant pull requests are available in the *monero-rs*[^4] repository. 

To read the full proposal, share your feedback, ask questions and support this CCS, consult !370[^2].

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 22/12/31: proposal closed[^5] by Boog90 without comment, after community criticism; announcement thread and Reddit username were deleted[^6].**

**Update: 23/4/18: Boog90 joins Cuprate project[^7].**

---

[^1]: https://github.com/boog900/
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/370](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/370){:target="_blank"}
[^3]: https://crates.io/crates/monero/
[^4]: https://github.com/monero-rs/monero-rs/pulls?q=is%3Apr+author%3ABoog900/
[^5]: https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/370#note_abc0c3d10c476a5ee960cb1630e6b6850a3f7e4c
[^6]: https://libreddit.de/r/Monero/comments/zzd19g/ccs_proposal_rust_monero_node/
[^7]: https://r.nf/r/Monero/comments/12q2ooo/cuprate_2_months_later_and_the_quest_for/
