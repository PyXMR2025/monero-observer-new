---
layout: post
category: story
title: "Monero Dev Activity Report - Week 8 2023: 16 PRs, 5 Issues"
description: "This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions."
tags: dev
image: 
date: 2023-02-26 20:00
---

This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions.

## 1 - PRs (16, 10:2:4)

Opened (10)

`monero-project/monero`: 

- **#8745[^1]** workflows: update dependencies to fix warnings (selsta)
- **#8746[^2]** workflows: update dependencies to fix warnings [release-v0.18] (selsta)
- **#8747[^3]** wallet: remove CLI code for non default ring sizes (jeffro256)
- **#8748[^4]** simplewallet: print fully qualified filename for new wallets (moneromooo-monero)
- **#8750[^5]** build: fix BUILD_DEBUG_UTILITIES (jeffro256)

`monero-project/monero-gui`: 

- **#4123[^6]** workflows: update dependencies to fix warnings (selsta)
- **#4125[^7]** README: fix debian repo (selsta)

`monero-project/monero-site`: 

- **#2130[^8]** add information about sites' I2P support (HardenedSteel)
- **#2131[^9]** add self-hosted wallet generator (erciccione)
- **#2133[^10]** blog: add v0.18.2.0 release notes (selsta)

Closed (2)

`monero-project/monero`: 

- **#8734[^11]** wallet: move connection control into NodeRPCProxy (jeffro256)

`monero-project/monero-gui`: none

`monero-project/monero-site`: 

- **#2019[^12]** downloads: mark wallets that could leak data (erciccione)

Merged (4)

`monero-project/monero`: none

`monero-project/monero-gui`: 

- **#4121[^13]** cmake: fix windows deploy (selsta)
- **#4124[^14]** DaemonManager: remove systemd check (plowsof)
- **#4120[^15]** build: prepare v0.18.2.0 (selsta)
- **#4109[^16]** docker: update hidapi to 0.13.1 on linux (selsta)

`monero-project/monero-site`: none

## 2 - ISSUES (5, 3:2)

Opened (3)

`monero-project/monero`: 

- **#8749[^17]** Why is there no serializable_unordered_map template function for serialization (EWIT521)

`monero-project/monero-gui`: 

- **#4122[^18]** monerod runs as dbus.service (plowsof)

`monero-project/monero-site`: 

- **#2132[^19]** devguides: daemon rpc get_transactions outputs description (plowsof)

Closed (2)

`monero-project/monero`: none

`monero-project/monero-gui`: 

- **#2043[^20]** [UX] Move seed into a separate screen of the onboarding flow (GBKS)
- **#4117[^21]** No longer able to build for macOS (Ventura 13.2) (rfpm)

`monero-project/monero-site`: none

That's it for this week's dev activity report. I will try and publish one every Sunday. Let me know if I missed anything or if you want to see any other statistics/repos included in future reports. Feedback/edits: @ [/about](/about).

Previous reports are listed in the [[dev]](/tag/dev) section. 

**-3RA**

---

[^1]: [https://github.com/monero-project/monero/pull/8745](https://github.com/monero-project/monero/pull/8745){:target="_blank"}{:rel="nofollow"}
[^2]: [https://github.com/monero-project/monero/pull/8746](https://github.com/monero-project/monero/pull/8746){:target="_blank"}{:rel="nofollow"}
[^3]: [https://github.com/monero-project/monero/pull/8747](https://github.com/monero-project/monero/pull/8747){:target="_blank"}{:rel="nofollow"}
[^4]: [https://github.com/monero-project/monero/pull/8748](https://github.com/monero-project/monero/pull/8748){:target="_blank"}{:rel="nofollow"}
[^5]: [https://github.com/monero-project/monero/pull/8750](https://github.com/monero-project/monero/pull/8750){:target="_blank"}{:rel="nofollow"}
[^6]: [https://github.com/monero-project/monero-gui/pull/4123](https://github.com/monero-project/monero-gui/pull/4123){:target="_blank"}{:rel="nofollow"}
[^7]: [https://github.com/monero-project/monero-gui/pull/4125](https://github.com/monero-project/monero-gui/pull/4125){:target="_blank"}{:rel="nofollow"}
[^8]: [https://github.com/monero-project/monero-site/pull/2130](https://github.com/monero-project/monero-site/pull/2130){:target="_blank"}{:rel="nofollow"}
[^9]: [https://github.com/monero-project/monero-site/pull/2131](https://github.com/monero-project/monero-site/pull/2131){:target="_blank"}{:rel="nofollow"}
[^10]: [https://github.com/monero-project/monero-site/pull/2133](https://github.com/monero-project/monero-site/pull/2133){:target="_blank"}{:rel="nofollow"}

[^11]: [https://github.com/monero-project/monero/pull/8734](https://github.com/monero-project/monero/pull/8734){:target="_blank"}{:rel="nofollow"}
[^12]: [https://github.com/monero-project/monero-site/pull/2019](https://github.com/monero-project/monero-site/pull/2019){:target="_blank"}{:rel="nofollow"}

[^13]: [https://github.com/monero-project/monero-gui/pull/4121](https://github.com/monero-project/monero-gui/pull/4121){:target="_blank"}{:rel="nofollow"}
[^14]: [https://github.com/monero-project/monero-gui/pull/4124](https://github.com/monero-project/monero-gui/pull/4124){:target="_blank"}{:rel="nofollow"}
[^15]: [https://github.com/monero-project/monero-gui/pull/4120](https://github.com/monero-project/monero-gui/pull/4120){:target="_blank"}{:rel="nofollow"}
[^16]: [https://github.com/monero-project/monero-gui/pull/4109](https://github.com/monero-project/monero-gui/pull/4109){:target="_blank"}{:rel="nofollow"}

[^17]: [https://github.com/monero-project/monero/issues/8749](https://github.com/monero-project/monero/issues/8749){:target="_blank"}{:rel="nofollow"}
[^18]: [https://github.com/monero-project/monero-gui/issues/4122](https://github.com/monero-project/monero-gui/issues/4122){:target="_blank"}{:rel="nofollow"}
[^19]: [https://github.com/monero-project/monero-site/issues/2132](https://github.com/monero-project/monero-site/issues/2132){:target="_blank"}{:rel="nofollow"}

[^20]: [https://github.com/monero-project/monero-gui/issues/2043](https://github.com/monero-project/monero-gui/issues/2043){:target="_blank"}{:rel="nofollow"}
[^21]: [https://github.com/monero-project/monero-gui/issues/4117](https://github.com/monero-project/monero-gui/issues/4117){:target="_blank"}{:rel="nofollow"}
