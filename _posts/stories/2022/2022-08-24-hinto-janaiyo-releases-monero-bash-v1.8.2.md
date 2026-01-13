---
layout: post
category: story
title: hinto-janaiyo releases monero-bash v1.8.2
description: "hinto-janaiyo has released v1.8.2 of Monero Bash wrapper for Linux, 'monero-bash'."
tags: mining
date: 2022-08-24 21:00
---

hinto-janaiyo[^1] has released v1.8.2[^2] of Monero Bash wrapper for Linux, *monero-bash*[^3].

## Updates and fixes

- Watch: More efficient, runs smoother on slower computers
- systemd: Services are now hardened & sandboxed [..][^4]
- Process: Fixed `monero-bash stop <process>` sometimes not detecting systemd process
- Process: `kill` command deprecated, `stop` will reliably auto-kill after 35-seconds
- [..]

The sources, SHA256SUM and .asc files can be found on Github[^2]. Always verify before using.

To learn more and support the project, consult hinto-janaiyo's new CCS proposal[^5] to finish developing monero-bash v2.

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.8.2](https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.8.2){:target="_blank"}{:rel="nofollow"}
[^3]: https://github.com/hinto-janaiyo/monero-bash
[^4]: https://github.com/hinto-janaiyo/monero-bash#Security
[^5]: [/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/](/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/)
