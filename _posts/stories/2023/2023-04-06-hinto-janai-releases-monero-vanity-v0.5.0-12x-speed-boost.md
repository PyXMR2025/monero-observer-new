---
layout: post
category: story
title: hinto-janai's monero-vanity gets ~12x speed boost with v0.5.0 release
description: "hinto-janai has released 'monero-vanity' version 0.5.0 with an improved key generation speed of 72 million keys/second that allows the CPU-only tool to find custom (vanity) XMR addresses ~12x faster."
tags: services
image: 
date: 2023-04-06 21:00
---

hinto-janai[^1] has released *monero-vanity*[^2] version 0.5.0[^3] with an improved key generation speed of 72 million keys/second that allows the CPU-only tool to find custom (vanity) XMR addresses ~12x faster:

```
12x speed increase (5.8 mil/sec -> 72 mil/sec)
```

The software is now faster than both vanity-monero[^4] (400k/sec) and vanity-xmr-cuda[^5] (8.1 million/sec).

Consult the README.md[^6] file in the project's code repository for speed estimates, CLI/GUI usage and build instructions.

The sources, binaries, SHA256SUM and .asc files can be found on the Github release page[^3]. Always verify before using.

*Note that monero-vanity is still a work in progress and the code was not audited. Use with substantial amounts of money at your own risk.*

---

[^1]: https://github.com/hinto-janai
[^2]: https://github.com/hinto-janai/monero-vanity/
[^3]: [https://github.com/hinto-janai/monero-vanity/releases/tag/v0.5.0](https://github.com/hinto-janai/monero-vanity/releases/tag/v0.5.0){:target="_blank"}{:rel="nofollow"}
[^4]: https://github.com/monero-ecosystem/vanity-monero
[^5]: https://github.com/SChernykh/vanity_xmr_cuda
[^6]: [https://github.com/hinto-janai/monero-vanity#readme](https://github.com/hinto-janai/monero-vanity#readme){:target="_blank"}{:rel="nofollow"}
