---
layout: post
category: story
title: "Rucknium's analysis exposes negative effects of ~43K 'Mordinals' on privacy of Monero users"
description: "Rucknium has posted his analysis of the empirical privacy impact of Mordinals (Monero 'NFTs'), revealing the extent to which Monero user privacy can be reduced 'when their transaction outputs are included in normal transaction ring signatures as decoys'."
image: average-effective-ring-size-monero-tx.png
tags: research
date: 2023-04-13 21:00
---

Rucknium[^1] has posted his analysis[^2] of the empirical privacy impact of Mordinals (Monero *NFTs*)[^3], revealing the extent to which Monero user privacy can be reduced *when their transaction outputs are included in normal transaction ring signatures as decoys*:

> **Average effective ring size fell to 12.5 at its lowest point. Nominal ring size is 16.** [..] **the "unluckiest" 5% of rings had an effective ring size of 9 or lower for two days in late March.** [..] 43,083 Mordinals were minted between March 10 and April 11, 2023, according to my count. The sum of fees paid by these Mordinal minting transactions was 7.47 XMR. These transactions placed 370 megabytes of data onto the Monero blockchain. 

Rucknium noted that without a hard fork or the cooperation of *the overwhelming majority of network nodes and mining pools*, the recently introduced patch[^4] (Monero 0.18.2.2[^5]) limiting the maximum size of *tx_extra* will not prevent *Mordinals with low-resolution images that fit in the 1060 byte limit* being *relayed and confirmed as normal*.

The researcher also published a relevant preliminary data report on *the share of outputs on Monero's blockchain that are Mordinals or coinbase outputs*[^6] that was updated last week.

The code to reproduce Rucknium's analysis is available on Github[^7]. 

Read the full post[^2] and consult previous Monero Observer reports to learn more about potential mitigations, arbitrary data and Mordinals[^8]'[^9]'[^10].

*This is an ongoing story and the report will be updated when new information is available.*

---

[^1]: https://github.com/Rucknium/
[^2]: [https://r.nf/12kv5m0/](https://r.nf/r/Monero/comments/12kv5m0/empirical_privacy_impact_of_mordinals_monero_nfts/){:target="_blank"}{:rel="nofollow"}
[^3]: https://mordinals.org/
[^4]: https://github.com/monero-project/monero/pull/8733
[^5]: [/monero-v0.18.2.2-fluorine-fermi-released/](/monero-v0.18.2.2-fluorine-fermi-released/)
[^6]: [https://gist.github.com/Rucknium/67cc9efdf7e43a40c52417611b322d43](https://gist.github.com/Rucknium/67cc9efdf7e43a40c52417611b322d43){:target="_blank"}{:rel="nofollow"}
[^7]: [https://github.com/Rucknium/misc-research/tree/main/Monero-Effective-Ring-Size](https://github.com/Rucknium/misc-research/tree/main/Monero-Effective-Ring-Size){:target="_blank"}{:rel="nofollow"}
[^8]: [/monero-punks-inscribes-first-nft-collection-monero/](/monero-punks-inscribes-first-nft-collection-monero/)
[^9]: [/monero-to-block-nfts-upcoming-release/](/monero-to-block-nfts-upcoming-release/)
[^10]: [/meeting-log-summary-monero-research-lab-meeting-1-march-2023/](/meeting-log-summary-monero-research-lab-meeting-1-march-2023/)
