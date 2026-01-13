---
layout: post
category: story
title: hinto-janaiyo releases Gupax v1.1.2
description: "hinto-janaiyo has released version 1.1.2 of the cross-platform GUI for mining Monero on P2Pool using XMRig, 'Gupax'."
tags: mining
date: 2023-02-07 20:00
---

hinto-janaiyo[^1] has released version 1.1.2[^2] of the cross-platform GUI for mining Monero on P2Pool using XMRig, *Gupax*[^3].

### Changes overview

- Windows: Fixed Gupax crashing on certain CPU-based graphics (integrated + basic drivers)
- Windows: Fixed P2Pool Advanced command inputs being ignored
- P2Pool/XMRig: Fixed parsing of localhost into 127.0.0.1
- P2Pool/XMRig: Current (non-saved) text-box values are now used instead of "old" selected values for custom nodes/pools
- Log: Only Gupax console logs will be printed (libraries filtered out)

The full changelog, sources, SHA256SUM and .asc files can be found on Github[^2] and on the new *gupax.io* website[^4].

Consult hinto-janaiyo's CCS proposal[^5] to learn more about the project.

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/gupax/releases/tag/v1.1.2](https://github.com/hinto-janaiyo/gupax/releases/tag/v1.1.2){:target="_blank"}{:rel="nofollow"}
[^3]: https://github.com/hinto-janaiyo/gupax/
[^4]: [https://gupax.io/](https://gupax.io/){:target="_blank"}
[^5]: [/hinto-janaiyo-submits-ccs-proposal-gupax/](/hinto-janaiyo-submits-ccs-proposal-gupax/)
