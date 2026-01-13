---
layout: post
category: story
title: SChernykh releases P2Pool v3.2 with support for UPnP port forwarding
description: "SChernykh has released P2Pool version 3.2 with with support for UPnP port forwarding and several fixes and improvements"
tags: mining
image: 
date: 2023-03-31 19:00
---

SChernykh[^1] has released *P2Pool*[^2] version 3.2[^3] with support for UPnP port forwarding and several fixes and improvements.

### Changes overview

```
Added UPnP port forwarding support
StratumServer: show a warning for invalid shares
Fixed stdin redirection for console command input: #238, thanks twlee79
Startup check: don't let user connect to a node without ZMQ
Disabled "127.0.0.1 banned" log spam that could happen sometimes [..]
```

The full list of changes is available on Github[^3].

Before using the software, you should verify the SHA256 sums with SChernykh's GPG key[^4].

The README[^5] has valuable information about features, defaults, how pool shares work, build instructions and a short mining guide.

If you need assistance, you can read the FAQ[^6] and join the project's IRC channels[^7].

*Note that all wallet addresses are public on P2Pool and only primary wallet addresses are supported (no subaddresses or integrated addresses).*

---

[^1]: https://github.com/SChernykh
[^2]: https://github.com/SChernykh/p2pool/
[^3]: [https://github.com/SChernykh/p2pool/releases/tag/v3.2](https://github.com/SChernykh/p2pool/releases/tag/v3.2){:target="_blank"}{:rel="nofollow"}
[^4]: https://p2pool.io/SChernykh.asc, https://github.com/monero-project/gitian.sigs/blob/master/gitian-pubkeys/SChernykh.asc
[^5]: https://github.com/SChernykh/p2pool/blob/master/README.md
[^6]: https://p2pool.io/#faq
[^7]: #monero-pools (irc), #p2pool-log (irc/libera)
