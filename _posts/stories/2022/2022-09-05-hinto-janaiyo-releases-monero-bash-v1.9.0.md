---
layout: post
category: story
title: hinto-janaiyo releases monero-bash v1.9.0 with Tor support
description: "hinto-janaiyo has released version 1.9.0 of the Monero Bash wrapper for Linux, 'monero-bash', which adds Tor support."
tags: mining
image: 
date: 2022-09-05 19:00
---

hinto-janaiyo[^1] has released version 1.9.0[^2] of the Monero Bash wrapper for Linux, *monero-bash*[^3], which adds Tor support.

## Updates and fixes

- Tor Integration: All monero-bash connections can now be routed through Tor
- HTTP Spoofing: Fake HTTP headers can now be set to blend in with browsers
- Config: monero-bash.conf/p2pool.conf are now automatically upgraded (merged with old config)
- Watch: A new screen buffer is used, exiting will now return to your original terminal instead of clearing
- Tor: New command to test Tor connection: monero-bash tor
- Watch: Fixed date spacing

The sources, SHA256SUM and .asc files can be found on Github[^2]. Always verify before using.

To learn more and support the project, consult hinto-janaiyo's new CCS proposal[^4] to finish developing monero-bash v2.

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.9.0](https://github.com/hinto-janaiyo/monero-bash/releases/tag/v1.9.0){:target="_blank"}
[^3]: https://github.com/hinto-janaiyo/monero-bash
[^4]: [/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/](/hinto-janaiyo-submits-ccs-proposal-monero-bash-v2/)
