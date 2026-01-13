---
layout: post
category: story
title: hinto-janaiyo releases monero-bash v1.8.3
description: "hinto-janaiyo has released v1.8.3 of Monero Bash wrapper for Linux, 'monero-bash'."
tags: mining
image: 
date: 2022-08-31 19:00
---

hinto-janaiyo[^1] has released v1.8.3[^2] of Monero Bash wrapper for Linux, *monero-bash*[^3].

## Updates and fixes

- Edit/Reset: New option to specifically edit/reset either `[config]` or `[systemd]`
- Help: Color-coded help screen: `monero-bash help`
- RPC: Fixed trailing error text
- Config: Values are handled more strictly/safely
- systemd: Warning will be printed if an old service file is detected

The sources, SHA256SUM and .asc files can be found on Github[^2]. Always verify before using.

To learn more and support the project, consult hinto-janaiyo's new CCS proposal[^4] to finish developing monero-bash v2.

*Reminder: v2.0.0 is in progress and v1.x.x versions will not be compatible.*

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.8.3](https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.8.3){:target="_blank"}
[^3]: https://github.com/hinto-janaiyo/monero-bash
[^4]: [/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/](/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/)
