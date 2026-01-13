---
layout: post
category: story
title: SChernykh releases P2Pool v2.5
description: "SChernykh has released P2Pool version 2.5."
tags: mining
image: 
date: 2022-10-31 18:00
---

SChernykh[^1] has released *P2Pool*[^2] version 2.5[^3] with the following improvements and bug fixes:

- Significantly reduced memory usage [..]
- Added `--p2p-external-port` command line parameter
- Fix: api didn't always save total hashes
- Fix: data race during shutdown
- [..]

The full list of changes is available on Github[^3].

Before using the software, you should verify the SHA256 sums with SChernykh's GPG key[^4].

The README[^5] has valuable information about features, defaults, how pool shares work, build instructions and a short mining guide.

If you need assistance, you can read the FAQ[^6] and join the project's IRC channels[^7].

*Note that all wallet addresses are public on P2Pool and only primary wallet addresses are supported (no subaddresses or integrated addresses).*

---

[^1]: https://github.com/SChernykh
[^2]: https://github.com/SChernykh/p2pool/
[^3]: [https://github.com/SChernykh/p2pool/releases/tag/v2.5](https://github.com/SChernykh/p2pool/releases/tag/v2.5){:target="_blank"}{:rel="nofollow"}
[^4]: https://p2pool.io/SChernykh.asc, https://github.com/monero-project/gitian.sigs/blob/master/gitian-pubkeys/SChernykh.asc
[^5]: https://github.com/SChernykh/p2pool/blob/master/README.md
[^6]: https://p2pool.io/#faq
[^7]: #monero-pools (irc), #p2pool-log (irc/libera)
