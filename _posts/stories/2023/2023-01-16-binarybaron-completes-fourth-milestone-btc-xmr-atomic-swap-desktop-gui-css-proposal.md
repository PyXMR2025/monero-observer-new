---
layout: post
category: story
title: "binarybaron completes fourth milestone for XMR-BTC atomic swap desktop GUI CCS proposal"
description: "binarybaron has completed the fourth milestone for their XMR-BTC atomic swap desktop GUI prototype CCS proposal."
tags: CCS
date: 2023-01-16 20:00
---

binarybaron[^1] has completed[^2] the fourth milestone for their XMR-BTC atomic swap desktop GUI prototype CCS proposal[^3]:

> This month we have finally released the GUI on Mainnet for the public to use! The release went smooth for the most part.

### Work overview

- GUI: Switched to Mainnet[^4]
- GUI: Added Auto Updater
- GUI: Fixed issue where starting tor on Linux would fail because of the read-only AppImage filesystem[^5]
- xmr-btc-swap: Reviewed and merged PR to allow config overrides using environment variables[^6]
- xmr-btc-swap: Submitted and merged PR to allow asb to set an external bitcoin redeem address to redeem the Bitcoin to once the swap is completed [^7]
- API, Rendezvous Point, front end: 100% uptime[^8]
- [..] 

Read the full update[^2] on Github.

Consult the previous Monero Observer report[^9] to learn more about the project.

---

[^1]: https://github.com/binarybaron
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/321#note_20357](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/321#note_20357){:target="_blank"}
[^3]: [https://ccs.getmonero.org/proposals/unstoppableswap-gui-2.html](https://ccs.getmonero.org/proposals/unstoppableswap-gui-2.html){:target="_blank"}{:rel="nofollow"}
[^4]: https://github.com/UnstoppableSwap/unstoppableswap-gui/pull/128
[^5]: https://github.com/UnstoppableSwap/unstoppableswap-gui/commit/5a40f8d8c88c8d7de5637b5ba93138cfcd9c0f91
[^6]: https://github.com/comit-network/xmr-btc-swap/commit/98296d8fa65393665651b2a535185a442b752d70
[^7]: https://github.com/comit-network/xmr-btc-swap/commit/b6201192c2adeac87c21c95a7e3ab4e4ddb31f3a
[^8]: https://stats.uptimerobot.com/XXoO7SnvzV/789405091
[^9]: [/binarybaron-second-btc-xmr-atomic-swap-desktop-gui-css-proposal/](/binarybaron-second-btc-xmr-atomic-swap-desktop-gui-css-proposal/)
