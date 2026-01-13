---
layout: post
category: story
title: SChernykh releases P2Pool v3.3
description: "SChernykh has released P2Pool version 3.3 with several bug fixes and improvements."
tags: mining
image: 
date: 2023-04-30 20:00
---

SChernykh[^1] has released *P2Pool*[^2] version 3.3[^3] with several bug fixes and improvements.

### Changes overview

```
Fixed a rare sync bug (a new peer couldn't sync sometimes and needed a restart)
Improved stability (fixed a data race bug introduced in v3.2)
Stratum API: added block reward share percent
Refactored code to reduce compiled binary size
Improved internal memory allocation for TCP connections
Added --version command line parameter
TCPServer: use /64 prefix to ban IPv6 peers
Console can now read commands via localhost TCP [..]
```

The full list of changes is available on Github[^3].

Before using the software, you should verify the SHA256 sums with SChernykh's GPG key[^4].

The README[^5] has valuable information about features, defaults, how pool shares work, build instructions and a short mining guide.

If you need assistance, you can read the FAQ[^6] and join the project's IRC channels[^7].

*Note that all wallet addresses are public on P2Pool and only primary wallet addresses are supported (no subaddresses or integrated addresses).*

---

[^1]: https://github.com/SChernykh
[^2]: [https://p2pool.io/](https://p2pool.io/){:target="_blank"}
[^3]: [https://github.com/SChernykh/p2pool/releases/tag/v3.3](https://github.com/SChernykh/p2pool/releases/tag/v3.3){:target="_blank"}{:rel="nofollow"}
[^4]: https://p2pool.io/SChernykh.asc, https://github.com/monero-project/gitian.sigs/blob/master/gitian-pubkeys/SChernykh.asc
[^5]: https://github.com/SChernykh/p2pool/blob/master/README.md
[^6]: https://p2pool.io/#faq
[^7]: #monero-pools (irc), #p2pool-log (irc/libera)
