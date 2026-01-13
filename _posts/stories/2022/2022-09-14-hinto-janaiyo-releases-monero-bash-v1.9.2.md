---
layout: post
category: story
title: hinto-janaiyo releases monero-bash v1.9.2
description: "hinto-janaiyo has released version 1.9.2 of the Monero Bash wrapper for Linux, 'monero-bash'."
tags: mining
image: 
date: 2022-09-14 20:00
---

hinto-janaiyo[^1] has released version 1.9.2[^2] of the Monero Bash wrapper for Linux, *monero-bash*[^3].

## Updates and fixes

- Status: Fixed P2Pool stat errors on empty API file
- Safety: Added debug screen on fatal errors (dangerous file operation, config error, etc)
- systemd: Wait `60` seconds instead of `35` before sending `SIGKILL` to processes
- systemd: Default signal for stopping processes is now softer `SIGINT` instead of `SIGTERM`

The sources, SHA256SUM and .asc files can be found on Github[^2]. Always verify before using.

To learn more and support the project, consult hinto-janaiyo's new CCS proposal[^4] to finish developing monero-bash v2.

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.9.2](https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.9.2){:target="_blank"}
[^3]: https://github.com/hinto-janaiyo/monero-bash
[^4]: [/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/](/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/)
