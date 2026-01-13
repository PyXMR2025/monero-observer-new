---
layout: post
category: story
title: SChernykh releases P2Pool v3.4
description: "SChernykh has released P2Pool version 3.4 with several bug fixes and improvements."
tags: mining
date: 2023-05-31 20:00
---

SChernykh[^1] has released *P2Pool*[^2] version 3.4[^3] with several bug fixes and improvements.

### Changes overview

```
Fixed a crash at startup (introduced in v3.3) when running as a service on some Linux systems
Added MacOS aarch64 build (Apple Silicon).
Prefer DNS TXT records to load the IP:port list of seed nodes.
Changed BLOCK_FOUND wording to make it clear who found the block
P2Pool now checks Monero node ping at startup and shows a warning if it's 100 ms or more
P2PServer: fixed use after free bug on shutdown[..]
```

The full list of changes is available on Github[^3].

Before using the software, you should verify the SHA256 sums with SChernykh's GPG key[^4].

The README[^5] has valuable information about features, defaults, how pool shares work, build instructions and a short mining guide.

If you need assistance, read the FAQ[^6] and join the project's IRC channels[^7].

*Note that all wallet addresses are public on P2Pool and only primary wallet addresses are supported (no subaddresses or integrated addresses).*

---

[^1]: https://github.com/SChernykh
[^2]: [https://p2pool.io/](https://p2pool.io/){:target="_blank"}
[^3]: [https://github.com/SChernykh/p2pool/releases/tag/v3.4](https://github.com/SChernykh/p2pool/releases/tag/v3.4){:target="_blank"}{:rel="nofollow"}
[^4]: https://p2pool.io/SChernykh.asc, https://github.com/monero-project/gitian.sigs/blob/master/gitian-pubkeys/SChernykh.asc
[^5]: https://github.com/SChernykh/p2pool/blob/master/README.md
[^6]: https://p2pool.io/#faq
[^7]: #monero-pools (irc), #p2pool-log (irc/libera)
