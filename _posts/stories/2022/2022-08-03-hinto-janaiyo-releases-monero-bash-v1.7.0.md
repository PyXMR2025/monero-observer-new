---
layout: post
category: story
title: hinto-janaiyo releases monero-bash v1.7.0
description: "hinto-janaiyo has released v1.7.0 of Monero Bash wrapper for Linux, 'monero-bash'."
tags: mining
image: 
date: 2022-08-03 20:00
last_modified_at: 2002-08-04
---

hinto-janaiyo[^1] has released v1.7.0[^2] of Monero Bash wrapper for Linux, *monero-bash*[^3].

## Updates and fixes

- P2Pool: Default log level 2 -> 1
- Update: UI more clearly indicates if up-to-date or not
- Update: Exits 0 on new packages, 1 on up-to-date
- Upgrade: Exits 0 on success, 1 on failure
- Version: Exits 0 on up-to-date, 1 on old packages
- Misc: General UI changes
- `status`: Fixed always exiting 1
- `monero-bash seed`: Fixed, but still experimental
- Safety: Using a non-GNU/Linux OS or a Bash version less than v5 will error & exit

The sources, SHA256SUM and .asc files can be found on Github[^2]. Always verify before using.

To learn more and support the project, consult hinto-janaiyo's new CCS proposal[^4] to finish developing monero-bash v2.

*Reminder: v2.0.0 is in progress and v1.x.x versions will not be compatible.*

---

**Update 22/08/04: new package manager prototype available[^5].**

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.7.0](https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.7.0){:target="_blank"}
[^3]: https://github.com/hinto-janaiyo/monero-bash
[^4]: [/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/](/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/)
[^5]: https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/333#note_18105
