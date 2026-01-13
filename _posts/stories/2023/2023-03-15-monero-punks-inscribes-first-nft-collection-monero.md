---
layout: post
category: story
title: "'Monero Punks' inscribes first-ever NFT collection on Monero"
description: "'Monero Punks' has inscribed the first-ever 100 NFTs on Monero, thanks to the new 'Monero Ordinals Project'."
tags: culture
image: mordinals.png
date: 2023-03-15 22:00
last_modified_at: 2023-04-04
---

*Monero Punks*[^1] has inscribed the first-ever 100 NFTs[^2] on Monero, thanks to the new *Monero Ordinals Project*[^3]:

> First 100 Monero Punks were inscribed with inscriptions 2-102. Thanks a lot for the help of amazing @m0rdinals team![^4]

Technical details and instructions on how to mint and control inscriptions are available on Github/Gitbook[^5]'[^6]:

> An "ordinal" is considered to be the output of a transaction (the 0th output) that contains special data (tx_extra_ordinal_register in the extra field) [..] Implementing ordinals in Monero seemed like an interesting and challenging idea to us.

From a cultural point of view, it is hard to see how NFTs could ever find *success* on Monero, considering the community's divergent fundamental values.

However, the timing of this project is rather curious, as it seems to coincide with the resurface of the *tx_extra*[^7] debate in recent MRL meetings[^8]. It will be interesting to see if this story has any impact on future discussions.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 23/3/16: Monero community reacted promptly to the story, with lots of calls to remove[^9] ordinals on Monero / *tx_extra*, while others tried making the case for keeping the feature[^10].**

**Update 23/3/17: (extra information) Monero Ordinals Project uses Monero's 'tx_extra' field[^7] in transactions created with its own modified fork of the Monero CLI wallet to mint ordinals on top of the Monero blockchain.**

**Update 23/3/19: PR to limit size of 'tx_extra' was merged in effort to block NFTs[^11].**

**Update 23/3/25: Monero Ordinals Project responded to community efforts to restrict *mordinals* (NFTs)[^12].**

**Update 23/4/4: m0rdinals devs introduced the ability to transfer mordinals and a new software patch addressing low quality images: *aggressive price scaling algorithm for image storing, based on Monero's priority coefficient*[^13]; apparently the mordinals.org viewer app is currently only displaying mordinals submitted with a high enough fee.**

---

[^1]: https://moneropunks.com/
[^2]: [https://mordinals.org/](https://mordinals.org/){:target="_blank"}{:rel="nofollow"}
[^3]: [https://github.com/mooonero/mordinals/](https://github.com/mooonero/mordinals/){:target="_blank"}{:rel="nofollow"}
[^4]: [https://nitter.net/MoneroPunks/status/1635384299905253377/](https://nitter.net/MoneroPunks/status/1635384299905253377/){:target="_blank"}{:rel="nofollow"}
[^5]: https://github.com/mooonero/mordinals#technical-details
[^6]: https://mordinals.gitbook.io/handbook/
[^7]: [https://github.com/monero-project/monero/issues/6668/](https://github.com/monero-project/monero/issues/6668/){:target="_blank"}{:rel="nofollow"}
[^8]: [/meeting-log-summary-monero-research-lab-meeting-1-march-2023/](/meeting-log-summary-monero-research-lab-meeting-1-march-2023/), [/assets/logs/230222-mrl.log](/assets/logs/230222-mrl.log), [https://libera.monerologs.net/monero-research-lab/20230315](https://libera.monerologs.net/monero-research-lab/20230315){:target="_blank"}
[^9]: https://nitter.net/xmrpriest/status/1636393536923787265, https://libera.monerologs.net/monero/20230316#c218695, https://nitter.net/MoneroPunks/status/1636483268206895104, https://mordinals.org/item/101
[^10]: https://nitter.net/BawdyAnarchist_/status/1636409412461150208
[^11]: [/monero-to-block-nfts-upcoming-release/](/monero-to-block-nfts-upcoming-release/)
[^12]: [https://nitter.net/m0rdinals/status/1639220588828057601](https://nitter.net/m0rdinals/status/1639220588828057601){:target="_blank"}{:rel="nofollow"}
[^13]: https://nitter.net/m0rdinals/status/1642448369284182017
