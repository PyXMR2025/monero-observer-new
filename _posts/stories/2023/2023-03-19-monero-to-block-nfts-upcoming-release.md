---
layout: post
category: story
title: "Monero to block NFTs in upcoming release"
description: "In response to the new 'Monero Ordinals Project', Monero devs decided to promptly merge tevador's proposed patch (PR #8733) which limits the maximum size of 'tx_extra that's allowed in the transaction pool' to ~1 KB (1060 bytes)."
tags: [culture, dev]
date: 2023-03-19 23:00
last_modified_at: 2023-04-04
---

In response to the new *Monero Ordinals Project*[^1], Monero devs decided[^2] to promptly merge tevador's proposed patch (PR #8733[^3]) which limits the maximum size of *tx_extra that's allowed in the transaction pool* to ~1 KB (1060 bytes):

> This patch is really needed now that someone has released something to (ab)use the unconstrained size of the field. (jtgrassie)[^4]

This move should mitigate most of the *damage* done by nonfungible tokens in their current form, but since it's a non-consensus change (no HF), mining pools must agree to use the upcoming v0.18.2.1[^5] point release for it to be efficient.

The total number of NFTs minted on Monero has increased from 100 to ~1K[^6] in less than 5 days.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 23/3/27: v0.18.2.1 release was tagged[^7]; 'The Mordinal share of outputs on chain has been about 24% for the last 72 hours', according to Rucknium[^8].**

**Update 23/4/4: Monero CLI/GUI v0.18.2.2 tagged[^9]'[^10]; Rucknium posted updated data on Mordinal transaction volume[^11].**

---

[^1]: [/monero-punks-inscribes-first-nft-collection-monero/](/monero-punks-inscribes-first-nft-collection-monero/)
[^2]: https://libera.monerologs.net/monero-dev/20230318#c221339
[^3]: [https://github.com/monero-project/monero/pull/8733](https://github.com/monero-project/monero/pull/8733){:target="_blank"}{:rel="nofollow"}
[^4]: https://github.com/monero-project/monero/pull/8733#issuecomment-1472706918
[^5]: https://github.com/monero-project/monero/pull/8785
[^6]: https://mordinals.org/
[^7]: [/monero-cli-v0.18.2.1-fluorine-fermi-tagged/](/monero-cli-v0.18.2.1-fluorine-fermi-tagged/)
[^8]: https://gist.github.com/Rucknium/67cc9efdf7e43a40c52417611b322d43, https://libera.monerologs.net/monero-research-lab/20230327#c227144
[^9]: [https://github.com/monero-project/monero/releases/tag/v0.18.2.2](https://github.com/monero-project/monero/releases/tag/v0.18.2.2){:target="_blank"}{:rel="nofollow"}
[^10]: [https://github.com/monero-project/monero-gui/releases/tag/v0.18.2.2](https://github.com/monero-project/monero-gui/releases/tag/v0.18.2.2){:target="_blank"}{:rel="nofollow"}
[^11]: [https://gist.github.com/Rucknium/67cc9efdf7e43a40c52417611b322d43](https://gist.github.com/Rucknium/67cc9efdf7e43a40c52417611b322d43){:target="_blank"}{:rel="nofollow"}
