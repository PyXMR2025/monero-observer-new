---
layout: post
category: story
title: "hinto-janaiyo submits CCS proposal to finish developing	monero-bash v2.0.0"
description: "hinto-janaiyo has submitted a new CCS proposal to finish developing v2.0.0 of the 'monero-bash' Linux CLI wrapper/manager for Monero, P2Pool and XMRig."
tags: CCS
date: 2022-07-21 22:00
last_modified_at: 2022-11-06
---

hinto-janaiyo[^1] has submitted a new CCS proposal[^2] to finish developing version 2.0.0[^3] of the *monero-bash*[^4] Linux CLI wrapper/manager for Monero, P2Pool[^5] and XMRig[^6]:

> [..] I've been continuing to maintain monero-bash, adding updates and fixing bugs [..] [Proposal] Work for 3 months to finish monero-bash v2.0.0 at 10XMR per month, regardless of fiat pricing, for a total of 30XMR.

```
Total funding: 38 XMR (only upon full completion).

ETA (hours): 3 months (243 hours @ ~20 Hrs/week).
```

### Proposed milestones

- Add multi-threading to downloads/verification
- Fix Fedora Linux issues (systemd, SELinux)
- Support all P2Pool options
- Support more monerod/monero-wallet-cli options
- Create & manage a seperate user for processes
- Keep wallet passwords/seeds encrypted in memory (prevents coredump leak)
- Improved documentation
- Improved status information
- Improved debug logging
- Cleaner UI

To learn more about the script, its folder structure and configuration, consult the monero-bash guide[^7].

hinto-janaiyo has recently started contributing[^8] to the core Monero codebase and is also maintaining XMRig-Auto-Build[^9] and monero-toolchain[^10].

To read the full proposal, share your feedback, ask questions and support this CCS, consult !333[^2].

---

**Update 22/7/30: added time estimations and work hour details[^11].** 

**Update 22/9/27: updated proposal, changed the payout scheme[^12].**

**Update 22/11/6: proposal closed[^13].**

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/333](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/333){:target="_blank"}
[^3]: https://github.com/hinto-janaiyo/monero-bash/tree/v2
[^4]: https://github.com/hinto-janaiyo/monero-bash
[^5]: https://p2pool.io
[^6]: https://xmrig.com
[^7]: https://github.com/hinto-janaiyo/monero-bash/blob/main/docs/help.md
[^8]: https://github.com/monero-project/monero/pulls?q=is%3Apr+author%3Ahinto-janaiyo
[^9]: [/hinto-janaiyo-releases-xmrig-auto-build-v1.2/](/hinto-janaiyo-releases-xmrig-auto-build-v1.2/)
[^10]: [/hinto-janaiyo-releases-monero-toolchain-v2.0.0/](/hinto-janaiyo-releases-monero-toolchain-v2.0.0/)
[^11]: https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/333/diffs?commit_id=22e023e7cce64da09370f98d8b9e5d757b0cac3f
[^12]: https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/333#note_18794
[^13]: [/the-monero-moon-monero-bash-ccs-proposals-closed/](/the-monero-moon-monero-bash-ccs-proposals-closed/)
