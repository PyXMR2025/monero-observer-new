---
layout: post
category: story
title: "Justin Berman posts CCS progress report after ~200 hours of dev work"
description: "Justin Berman has published the first progress report for his full-time 2022-2023 'part 4' Monero dev work CCS proposal."
tags: dev
image: 
date: 2023-01-01 19:00
---

Justin Berman[^1] has published the first progress report[^2] for his full-time 2022-2023 (*part 4*) Monero dev work CCS proposal[^3]:

> **Update 1: ~200 hours**

### CCS work overview

- Completed my investigation stress testing the daemon RPC server when the pool has lots of txs in it
- Implemented a basic "block scanner" using @koe's Seraphis library [..]

Justin plans to continue working on *Seraphis balance recovery* instead of the *Seraphis input selection* as I initially mentioned in the proposal:

> My immediate goal is: **Use the Seraphis lib to implement a legacy full wallet scanner that makes network requests for chain data to the daemon.**

Read the full update on Github in *!359*[^2].

---

[^1]: https://github.com/j-berman
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/359#note_20257](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/359#note_20257){:target="_blank"}
[^3]: [/j-berman-monero-development-3-months-ccs-proposal-part-4/](/j-berman-monero-development-3-months-ccs-proposal-part-4/)
