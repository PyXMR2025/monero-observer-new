---
layout: post
category: story
title: "Getmonero.org temporarily down for maintenance"
description: "Getmonero.org is temporarily down for maintenance as the Monero Core team works on fixing a 'borked' system caused by an 'OS upgrade' that was apparently required by a Jekyll update."
tags: services
date: 2023-01-31 22:00
last_modified_at: 2023-02-02
---

Getmonero.org[^1] is temporarily down for maintenance as the Monero Core team works on fixing a *borked* system caused by an *OS upgrade* that was apparently required by a Jekyll update[^2]:

> it was an OS upgrade that seems to have borked something [..] we're just upgrading the server and we were struggling with the IPMI being unresponsive; the CDN is still up, and we'll have it fixed in the next 12 hours (fluffypony)[^3]

> We're generally aware of the up&down of the various getmonero websites, since they are directly related to our ongoing progress of the server. (binaryFate)[^4]

To download Monero software during the downtime, users can opt to use selsta's mirror[^5]'[^6]. Make sure to verify[^7] the signature and check the hashes before installation.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update: issue was resolved, everything is back up[^8].**

---

[^1]: https://getmonero.org/
[^2]: https://libera.monerologs.net/monero-site/20230131#c198174
[^3]: https://libera.monerologs.net/monero/20230131#c198124
[^4]: [https://libera.monerologs.net/monero-site/20230131#c198407](https://libera.monerologs.net/monero-site/20230131#c198407){:target="_blank"}
[^5]: [https://gui.xmr.pm/v0.18.1.2.html](https://gui.xmr.pm/v0.18.1.2.html){:target="_blank"}
[^6]: https://github.com/monero-project/meta/issues/789#issuecomment-1410210834
[^7]: [/verify-install-update-monero-cli-wallet-linux-guide/](/verify-install-update-monero-cli-wallet-linux-guide/)
[^8]: https://nitter.pussthecat.org/binaryFate/status/1621005744052264960#m
