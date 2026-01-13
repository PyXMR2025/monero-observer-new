---
layout: post
category: story
title: "Monero Dev Activity Report - Week 7 2023: 16 PRs, 7 Issues"
description: "This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions."
tags: dev
image: 
date: 2023-02-19 22:00
---

This weekly report aims to provide a big picture view of Monero development activity, increase community support for existing devs and, hopefully, encourage new contributions.

## 1 - PRs (16, 4:0:12)

Opened (4)

`monero-project/monero`: 

- **#8743[^1]** depends: remove unused packages (tobtoht)

`monero-project/monero-gui`: 

- **#4120[^2]** build: prepare v0.18.2.0 (selsta)
- **#4121[^3]** cmake: fix windows deploy (selsta)

`monero-project/monero-site`: 

- **#2129[^4]** maintenance of merchants.yml (HardenedSteel)

Closed (0)

`monero-project/monero`: none

`monero-project/monero-gui`: none

`monero-project/monero-site`: none

Merged (12)

`monero-project/monero`: 

- **#8736[^5]** Revert "epee: when loading a JSON RPC payload, ensure params is an ob… (moneromooo-monero)
- **#8737[^6]** depends: bump openssl to 1.1.1t (tobtoht)
- **#8738[^7]** depends: bump openssl to 1.1.1t [release-v0.18] (tobtoht)
- **#8720[^8]** p2p: update seed nodes (selsta)
- **#8721[^9]** p2p: update seed nodes [release-v0.18] (selsta)
- **#8739[^10]** build: prepare v0.18.2.0 (selsta)

`monero-project/monero-gui`: 

- **#3878[^11]** wizard: redesign seed page (selsta)
- **#3936[^12]** p2pool: Restart monerod only when needed and with proper args (devhyper)
- **#4092[^13]** p2pool: Stop p2pool mining on node switch (devhyper)
- **#4103[^14]** docker: update Windows and Linux Qt to 5.15.8 (selsta)
- **#4112[^15]** p2pool: update to v3.0 (SChernykh)
- **#4113[^16]** Utils: simplify ago func (ufUNnxagpM)

`monero-project/monero-site`: none

## 2 - ISSUES (7, 3:4)

Opened (3)

`monero-project/monero`: 

- **#8741[^17]** wallet RPC method generate_from_keys with bad address (dimalinux)
- **#8742[^18]** monerod: [windows] Mysterious "disk leak," while Monero daemon is running (opportunistic)

`monero-project/monero-gui`: 

- **#4119[^19]** SELinux 'has detected a problem' on RHEL 9.1 / Rocky / AlmaLinux (David-Else)

`monero-project/monero-site`: none

Closed (4)

`monero-project/monero`: 

- **#8744[^20]** Wallet RPC get_balance returns an incorrect unlocked_balance value intermittently. (suggalla)

`monero-project/monero-gui`: 

- **#3911[^21]** monerod second instance started by GUI (MainTsk)
- **#3935[^22]** p2pool mining excessive ram usage never reclaims reboots required (tehoblivious)
- **#4118[^23]** trouble building on ArchLinux (dbear496)

`monero-project/monero-site`: none

That's it for this week's dev activity report. I will try and publish one every Sunday. Let me know if I missed anything or if you want to see any other statistics/repos included in future reports. Feedback/edits: @ [/about](/about).

Previous reports are listed in the [[dev]](/tag/dev) section. 

**-3RA**

---

[^1]: [https://github.com/monero-project/monero/pull/8743](https://github.com/monero-project/monero/pull/8743){:target="_blank"}{:rel="nofollow"}
[^2]: [https://github.com/monero-project/monero-gui/pull/4120](https://github.com/monero-project/monero-gui/pull/4120){:target="_blank"}{:rel="nofollow"}
[^3]: [https://github.com/monero-project/monero-gui/pull/4121](https://github.com/monero-project/monero-gui/pull/4121){:target="_blank"}{:rel="nofollow"}
[^4]: [https://github.com/monero-project/monero-site/pull/2129](https://github.com/monero-project/monero-site/pull/2129){:target="_blank"}{:rel="nofollow"}

[^5]: [https://github.com/monero-project/monero/pull/8736](https://github.com/monero-project/monero/pull/8736){:target="_blank"}{:rel="nofollow"}
[^6]: [https://github.com/monero-project/monero/pull/8737](https://github.com/monero-project/monero/pull/8737){:target="_blank"}{:rel="nofollow"}
[^7]: [https://github.com/monero-project/monero/pull/8738](https://github.com/monero-project/monero/pull/8738){:target="_blank"}{:rel="nofollow"}
[^8]: [https://github.com/monero-project/monero/pull/8720](https://github.com/monero-project/monero/pull/8720){:target="_blank"}{:rel="nofollow"}
[^9]: [https://github.com/monero-project/monero/pull/8721](https://github.com/monero-project/monero/pull/8721){:target="_blank"}{:rel="nofollow"}
[^10]: [https://github.com/monero-project/monero/pull/8739](https://github.com/monero-project/monero/pull/8739){:target="_blank"}{:rel="nofollow"}

[^11]: [https://github.com/monero-project/monero-gui/pull/3878](https://github.com/monero-project/monero-gui/pull/3878){:target="_blank"}{:rel="nofollow"}
[^12]: [https://github.com/monero-project/monero-gui/pull/3936](https://github.com/monero-project/monero-gui/pull/3936){:target="_blank"}{:rel="nofollow"}
[^13]: [https://github.com/monero-project/monero-gui/pull/4092](https://github.com/monero-project/monero-gui/pull/4092){:target="_blank"}{:rel="nofollow"}
[^14]: [https://github.com/monero-project/monero-gui/pull/4103](https://github.com/monero-project/monero-gui/pull/4103){:target="_blank"}{:rel="nofollow"}
[^15]: [https://github.com/monero-project/monero-gui/pull/4112](https://github.com/monero-project/monero-gui/pull/4112){:target="_blank"}{:rel="nofollow"}
[^16]: [https://github.com/monero-project/monero-gui/pull/4113](https://github.com/monero-project/monero-gui/pull/4113){:target="_blank"}{:rel="nofollow"}

[^17]: [https://github.com/monero-project/monero/issues/8741](https://github.com/monero-project/monero/issues/8741){:target="_blank"}{:rel="nofollow"}
[^18]: [https://github.com/monero-project/monero/issues/8742](https://github.com/monero-project/monero/issues/8742){:target="_blank"}{:rel="nofollow"}
[^19]: [https://github.com/monero-project/monero-gui/issues/4119](https://github.com/monero-project/monero-gui/issues/4119){:target="_blank"}{:rel="nofollow"}

[^20]: [https://github.com/monero-project/monero/issues/8744](https://github.com/monero-project/monero/issues/8744){:target="_blank"}{:rel="nofollow"}
[^21]: [https://github.com/monero-project/monero-gui/issues/3911](https://github.com/monero-project/monero-gui/issues/3911){:target="_blank"}{:rel="nofollow"}
[^22]: [https://github.com/monero-project/monero-gui/issues/3935](https://github.com/monero-project/monero-gui/issues/3935){:target="_blank"}{:rel="nofollow"}
[^23]: [https://github.com/monero-project/monero-gui/issues/4118](https://github.com/monero-project/monero-gui/issues/4118){:target="_blank"}{:rel="nofollow"}
