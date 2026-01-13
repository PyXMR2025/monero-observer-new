---
layout: post
category: story
title: SChernykh releases P2Pool v3.1
description: "SChernykh has released P2Pool version 3.1 with several updates and fixes."
tags: mining
image: 
date: 2023-02-28 21:00
---

SChernykh[^1] has released *P2Pool*[^2] version 3.1[^3] with several updates and fixes.

### Changes overview

```
Updated --no-autodiff description in help prompt
Updated curl to 7.88.1
Updated libzmq to the latest master branch
Fixed a few data races and other small bugs
Fix: Stratum status could show invalid hashrate and/or effort % [..]
```

The full list of changes is available on Github[^3].

Before using the software, you should verify the SHA256 sums with SChernykh's GPG key[^4].

The README[^5] has valuable information about features, defaults, how pool shares work, build instructions and a short mining guide.

If you need assistance, you can read the FAQ[^6] and join the project's IRC channels[^7].

It is important to mention that P2Pool will hardfork[^8] to new consensus rules on March 18th at 21:00 UTC and users must update to version 3.0 or newer before this date.

*Note that all wallet addresses are public on P2Pool and only primary wallet addresses are supported (no subaddresses or integrated addresses).*

---

[^1]: https://github.com/SChernykh
[^2]: https://github.com/SChernykh/p2pool/
[^3]: [https://github.com/SChernykh/p2pool/releases/tag/v3.1](https://github.com/SChernykh/p2pool/releases/tag/v3.1){:target="_blank"}{:rel="nofollow"}
[^4]: https://p2pool.io/SChernykh.asc, https://github.com/monero-project/gitian.sigs/blob/master/gitian-pubkeys/SChernykh.asc
[^5]: https://github.com/SChernykh/p2pool/blob/master/README.md
[^6]: https://p2pool.io/#faq
[^7]: #monero-pools (irc), #p2pool-log (irc/libera)
[^8]: [/p2pool-hardfork-18-march-2023/](/p2pool-hardfork-18-march-2023/)
