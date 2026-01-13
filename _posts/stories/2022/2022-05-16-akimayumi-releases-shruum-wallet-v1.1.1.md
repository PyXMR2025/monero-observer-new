---
layout: post
category: story
title: "akimayumi releases Shruum Wallet v1.1.1"
description: "akimayumi has released Shruum Wallet v1.1.1."
tags: wallets
image: 
last_modified_at: 2022-05-19
---

akimayumi[^1] has released Shruum Wallet[^2] v1.1.1:

> Shruum has been updated to v1.1.1.[..] There is now a Telegram group chat as well due to popular demand.[^3]

### Changelog

```
- Updates the monero library to 0.17.3.2
- Fixes issue where wallet would perform the auto timeout check while syncing blocks (like restoring a wallet)
- Adds an option for disabling RPC connectivity check when clicking on a wallet [..]
- Fixes some more connectivity issues [..]
- The Tor icon in the top right on the home screen now changes color based on node connectivity
```

Full changelog, .APK downloads and usage instructions can be found in the release announcement[^3] and on the mayumi.one website[^4].

To learn more about the Monerujo fork, consult my previous report[^5].

---

**Update: version 1.1.6 available[^6], adds a fix for the required "http://" prefix when adding a node, and some UI modifications[^7].**

---

[^1]: https://git.mayumi.one/mayumi
[^2]: [https://git.mayumi.one/mayumi/shruum](https://git.mayumi.one/mayumi/shruum){:target="_blank"}
[^3]: [https://libredd.it/uqzbx3/](https://libredd.it/uqzbx3/){:target="_blank"}{:rel="nofollow"}
[^4]: [https://mayumi.one/](https://mayumi.one/){:target="_blank"} (clearnet), http://muxillqtju4w44zb5creqezvmuw7qcar4zlseeyhuci4rfaoenh4auad.onion/ (onion)
[^5]: [/akimayumi-forks-monerujo-shruum-wallet/](/akimayumi-forks-monerujo-shruum-wallet/)
[^6]: https://mayumi.one/fdroid/repo/
[^7]: https://nitter.net/_akimayumi/status/1527111812088532994#m
