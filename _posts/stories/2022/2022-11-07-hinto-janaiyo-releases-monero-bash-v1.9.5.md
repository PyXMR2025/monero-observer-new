---
layout: post
category: story
title: hinto-janaiyo releases monero-bash v1.9.5
description: "hinto-janaiyo has released version 1.9.5 of the Monero Bash wrapper for Linux, 'monero-bash'."
tags: mining
image: 
date: 2022-11-07 19:00
---

hinto-janaiyo[^1] has released version 1.9.5[^2] of the Monero Bash wrapper for Linux, *monero-bash*[^3] with multiple updates and bugfixes:

- Status: Specific processes can now be specified: monero-bash status [monero / p2pool / xmrig]
- Wallet: All non-wallet files (files without matching .keys) will be ignored
- Watch: Fixed XMRig stats not being formatted correctly when switching back from other stats

The full changelog is available on Github[^4].

The sources, SHA256SUM and .asc files can be found on Github[^2]. Always verify before using.

hinto-janaiyo has recently decided to close the CCS proposal[^5] and finish developing monero-bash v2 on his *own time instead*[^6].

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.9.5](https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.9.5){:target="_blank"}
[^3]: https://github.com/hinto-janaiyo/monero-bash
[^4]: https://github.com/hinto-janaiyo/monero-bash/compare/v1.9.4...v1.9.5
[^5]: [/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/](/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/)
[^6]: https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/333#note_19345
