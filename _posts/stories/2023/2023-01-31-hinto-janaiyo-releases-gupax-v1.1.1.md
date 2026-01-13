---
layout: post
category: story
title: Gupax v1.1.1 released
description: "hinto-janaiyo has released version 1.1.1 of the cross-platform GUI for mining Monero on P2Pool using XMRig, 'Gupax'."
tags: mining
date: 2023-01-31 19:00
---

hinto-janaiyo[^1] has released version 1.1.1[^2] of the cross-platform GUI for mining Monero on P2Pool using XMRig, *Gupax*[^3].

### Changes overview

- [Update] Remote Nodes: Replaced [Community Monero Nodes] with known ZMQ-enabled Remote Nodes
- [Update] P2Pool: Added warning in [P2Pool Simple] tab about privacy/practical downsides when using remote nodes
- [Fix] Ping: Fixed ping end lag; Remote node pings are as fast as the slowest ping instead of always taking 10 seconds flat
- [Fix] UI: Top/Bottom bars are smaller, fixes some UI overflowing or being cramped
 [..]

The full changelog, sources, SHA256SUM and .asc files can be found on Github[^2] and on the new *gupax.io* website[^4].

Consult hinto-janaiyo's CCS proposal[^5] to learn more about the project.

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/gupax/releases/tag/v1.1.1](https://github.com/hinto-janaiyo/gupax/releases/tag/v1.1.1){:target="_blank"}{:rel="nofollow"}
[^3]: https://github.com/hinto-janaiyo/gupax/
[^4]: [https://gupax.io/](https://gupax.io/){:target="_blank"}
[^5]: [/hinto-janaiyo-submits-ccs-proposal-gupax/](/hinto-janaiyo-submits-ccs-proposal-gupax/)
