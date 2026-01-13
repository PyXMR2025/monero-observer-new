---
layout: post
category: story
title: SChernykh releases P2Pool v2.2.1
description: "SChernykh has released P2Pool version 2.2.1."
tags: mining
image: 
date: 2022-07-08 18:00
---

SChernykh[^1] has released *P2Pool*[^2] version 2.2.1[^3] with the following bug fixes:

- Fixed 100% CPU load on one core after running for a while
- Fixed autodiff gave very low-difficulty job
- Fixed p2pool hangs if monerod is not running
- Fixed Enable console commands processing only when console is available
- Fixed various crashes during P2Pool shutdown

Important to note is that this version is **required** for the coming Monero v15[^4] network upgrade and older p2pool releases will be incompatible after that.

Before using the software, you should verify the SHA256 sums with SChernykh[^1]'s GPG key[^5].

The README[^6] has valuable information about features, defaults, how pool shares work, build instructions and a short mining guide.

If you need assistance, you can read the FAQ[^7] and reach out to other P2Pool miners on irc[^8].

---

[^1]: https://github.com/SChernykh
[^2]: https://github.com/SChernykh/p2pool/
[^3]: [https://github.com/SChernykh/p2pool/releases/tag/v2.2.1](https://github.com/SChernykh/p2pool/releases/tag/v2.2.1){:target="_blank"}{:rel="nofollow"}
[^4]: [/monero-hard-fork-rescheduled-13-august-2022/](/monero-hard-fork-rescheduled-13-august-2022/)
[^5]: https://p2pool.io/SChernykh.asc, https://github.com/monero-project/gitian.sigs/blob/master/gitian-pubkeys/SChernykh.asc
[^6]: https://github.com/SChernykh/p2pool/blob/master/README.md
[^7]: https://p2pool.io/#faq
[^8]: #monero-pools (irc), #p2pool-log (irc/libera)
