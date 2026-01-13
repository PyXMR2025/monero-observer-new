---
layout: post
category: story
title: P2Pool to hardfork on March 18th at 21:00 UTC
description: "sech1 has announced that P2Pool (both main and mini) will hardfork to new consensus rules on March 18th at 21:00 UTC."
tags: mining
image: 
date: 2023-01-11 20:00
last_modified_at: 2023-03-18
---

sech1[^1] has announced[^2] that P2Pool[^3] (both main and mini) will hardfork to new consensus rules on March 18th at 21:00 UTC:

> The hardfork is necessary to improve P2Pool scalability and reduce the impact on Monero blockchain. You'll need to update to P2Pool v3.0 or newer version before this time.

### Schedule

```
January (2nd half) - Testnet
January 31 - P2Pool v3.0 binaries
February (TBD) - Monero GUI v0.18.2.0 and Gupax with P2Pool v3.0
March 18 - P2Pool HF
```

### Changes overview

- Dynamic PPLNS window (from fixed 2160 blocks (~6 hours) to a dynamic cap)[^4]
- Duplicate share IDs fix[^5]
- New transaction generation algorithm[^6]'[^7]

The network upgrade should address the issue with P2Pool spamming too many outputs to the blockchain, which currently reduces effective ring size for everyone using Monero, *down to 12-13 decoys instead of 16*.

To better understand the issue, consult the relevant MRL discussions on Github[^8]'[^9] and run Rucknium's P2Pool coinbase outputs analysis R script file[^10].

The updated codebase can be inspected in the P2Pool *hardfork*[^11] branch.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 23/1/31: P2Pool v3.0 is out[^12]; make sure to update before March 18th.**

**Update 23/3/18: sech1 reported HF was successful[^13].**

---

[^1]: https://r.nf/user/sech1
[^2]: [https://r.nf/1095730/](https://r.nf/1095730/){:target="_blank"}{:rel="nofollow"}
[^3]: [https://p2pool.io/](https://p2pool.io/){:target="_blank"}
[^4]: https://github.com/SChernykh/p2pool/issues/221
[^5]: https://github.com/SChernykh/p2pool/issues/222
[^6]: https://github.com/SChernykh/p2pool/issues/223
[^7]: https://github.com/SChernykh/p2pool/issues/225
[^8]: https://github.com/monero-project/research-lab/issues/108
[^9]: https://github.com/monero-project/research-lab/issues/109
[^10]: https://github.com/Rucknium/misc-research/tree/main/Monero-p2pool-Output-Stats
[^11]: [https://github.com/SChernykh/p2pool/tree/hardfork](https://github.com/SChernykh/p2pool/tree/hardfork){:target="_blank"}{:rel="nofollow"}
[^12]: [/schernykh-releases-p2pool-v3.0/](/schernykh-releases-p2pool-v3.0/)
[^13]: [/p2pool-hard-fork-successful/](/p2pool-hard-fork-successful/)
