---
layout: post
category: story
title: SChernykh releases P2Pool v2.7
description: "SChernykh has released P2Pool version 2.7."
tags: mining
image: 
date: 2023-01-03 21:00
---

SChernykh[^1] has released *P2Pool*[^2] version 2.7[^3] with the following improvements and fixes:

- High fee transactions are now added to the block template immediately to improve the average reward for mined blocks
- Fixed share counter not resetting to 0 sometimes when the initial sync is finished
- Stricter P2P protocol checks to detect misbehaving peers
- [..]

The full list of changes is available on Github[^3].

Before using the software, you should verify the SHA256 sums with SChernykh's GPG key[^4].

The README[^5] has valuable information about features, defaults, how pool shares work, build instructions and a short mining guide.

If you need assistance, you can read the FAQ[^6] and join the project's IRC channels[^7].

*Note that all wallet addresses are public on P2Pool and only primary wallet addresses are supported (no subaddresses or integrated addresses).*

---

[^1]: https://github.com/SChernykh
[^2]: https://github.com/SChernykh/p2pool/
[^3]: [https://github.com/SChernykh/p2pool/releases/tag/v2.7](https://github.com/SChernykh/p2pool/releases/tag/v2.7){:target="_blank"}{:rel="nofollow"}
[^4]: https://p2pool.io/SChernykh.asc, https://github.com/monero-project/gitian.sigs/blob/master/gitian-pubkeys/SChernykh.asc
[^5]: https://github.com/SChernykh/p2pool/blob/master/README.md
[^6]: https://p2pool.io/#faq
[^7]: #monero-pools (irc), #p2pool-log (irc/libera)
