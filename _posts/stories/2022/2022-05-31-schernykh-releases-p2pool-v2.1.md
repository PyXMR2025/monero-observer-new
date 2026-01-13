---
layout: post
category: story
title: SChernykh releases P2Pool v2.1
description: "SChernykh has released P2Pool version 2.1."
tags: mining
image: 
---

SChernykh[^1] has released *P2Pool*[^2] version 2.1[^3] with the following changes:

- Stratum server now uses automatic difficulty adjustment by default. [..]
- Added console command workers to show miners connected to the stratum server
- Made handling of internet outages more robust. [..]
- Stratum sever doesn't ban localhost anymore [..]
- Added "SYNCHRONIZED" log message when the initial sync completes
- Fixed executable stack in Linux binary
- Added block reward share percent to miner api
- Various other small bug fixes and stability improvements

## Wallets with P2Pool support

  * Official Monero CLI and GUI v0.17.2.3 and newer
  * Monerujo v2.1.0 "Vertant" and newer
  * Cake Wallet v4.2.7 and newer
  * Monero.com by Cake Wallet
  * Feather Wallet v1.0.0 and newer
  * MyMonero

Before using the software, you should verify the SHA256 sums with SChernykh[^1]'s GPG key[^4].

The README[^5] has valuable information about features, defaults, how pool shares work, build instructions and a short mining guide.

If you need assistance, you can read the FAQ[^6] and reach out to other P2Pool miners on irc[^7].

---

[^1]: https://github.com/SChernykh
[^2]: https://github.com/SChernykh/p2pool/
[^3]: [https://github.com/SChernykh/p2pool/releases/tag/v2.1](https://github.com/SChernykh/p2pool/releases/tag/v2.1){:target="_blank"}{:rel="nofollow"}
[^4]: https://p2pool.io/SChernykh.asc, https://github.com/monero-project/gitian.sigs/blob/master/gitian-pubkeys/SChernykh.asc
[^5]: https://github.com/SChernykh/p2pool/blob/master/README.md
[^6]: https://p2pool.io/#faq
[^7]: #monero-pools (irc), #p2pool-log (irc/libera)
