---
layout: post
category: story
title: "SyntheticBird45 starts work on 'Cuprate', an experimental Monero node written in Rust"
description: "SyntheticBird45 has started working on 'Cuprate', an 'upcoming experimental, modern & secure' Monero node written in Rust."
tags: dev
date: 2023-02-08 21:00
last_modified_at: 2023-04-18
---

SyntheticBird45[^1] has started working on *Cuprate*[^2], an *upcoming experimental, modern & secure* Monero node written in Rust:

> Releasing an alternative node will reinforce the Monero Network if a security vulnerability is discovered in the current node maintained by the monero-core team. [..] **I encourage anyone to review the work being done, discuss about it or propose agressive optimizations** [..]

### Features overview

- Traffic Obfuscation: Different protocol to bypass DPI will be available
- Blockchain Storage: LMDB replaced by RocksDB
- Sandboxing & System: maintained SELinux/Apparmor policy
- RPC: ZeroMQ & gRPC will be available to communicate with the node
- Terminal Interface: TUI library
- Tor connections: arti_client library will be embedded

The developer decided to abandon their recent CCS proposal[^3] and focus on coding instead[^4].

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 23/3/30: project looking for volunteers to help do benchmarks[^5].**

**Update 23/4/18: Boog90[^6] joins the project according to progress report[^7].**

---

[^1]: https://github.com/SyntheticBird45/
[^2]: [https://github.com/SyntheticBird45/cuprate/](https://github.com/SyntheticBird45/cuprate/){:target="_blank"}{:rel="nofollow"}
[^3]: [/uzern4m-ccs-proposal-rust-monero-node-preliminary-research-report/](/uzern4m-ccs-proposal-rust-monero-node-preliminary-research-report/)
[^4]: [https://r.nf/10wwb9c/](https://r.nf/10wwb9c/){:target="_blank"}{:rel="nofollow"}
[^5]: [https://r.nf/126s52k/](https://r.nf/r/Monero/comments/126s52k/comment/jeai6gh/){:target="_blank"}{:rel="nofollow"}
[^6]: https://github.com/boog900/
[^7]: [https://r.nf/12q2ooo/](https://r.nf/r/Monero/comments/12q2ooo/cuprate_2_months_later_and_the_quest_for/){:target="_blank"}{:rel="nofollow"}
