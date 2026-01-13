---
layout: post
category: story
title: "binarybaron completes third milestone for XMR-BTC atomic swap desktop GUI CCS proposal"
description: "binarybaron has completed the third milestone for their XMR-BTC atomic swap desktop GUI prototype CCS proposal."
tags: CCS
date: 2022-12-09 20:00
---

binarybaron[^1] has completed[^2] the third milestone for their XMR-BTC atomic swap desktop GUI prototype CCS proposal[^3]:

> While working on the GUI, I've discovered a few things that are making developing tools on top of the xmr-btc-swap project much harder that it needs to be. [..] I decided to spent the majority of my time this month on implementing the JSON-RPC API for the CLI and migrating the GUI to use this API.

### Work overview

- GUI: Started to migrate the `GUI` to use the new WIP `RPC API`[^4]
- GUI: Some small style changes[^5]
- GUI: Started investigating an issue where the electrum server to be used is not selected in an efficent manner
- GUI: Started working on a questionaire that'll be presented to new users on startup [..]
- xmr-btc-swap: Reviewed and merged PR to allow ASB config to be configured using environment variables[^6]
- xmr-btc-swap: Fixed compilation issue on M1, M2 Mac[^7]
- xmr-btc-swap: I provided feedback and guidance on developing the RPC API for the CLI, and worked on the issue myself.
- API, Rendezvous Point, front end: 100% uptime[^8]
- [..] 

Read the full update[^2] on Github for more details.

Consult the previous Monero Observer report[^9] to learn more about the project.

---

[^1]: https://github.com/binarybaron
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/321#note_19896](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/321#note_19896){:target="_blank"}
[^3]: [https://ccs.getmonero.org/proposals/unstoppableswap-gui-2.html](https://ccs.getmonero.org/proposals/unstoppableswap-gui-2.html){:target="_blank"}{:rel="nofollow"}
[^4]: https://github.com/UnstoppableSwap/unstoppableswap-gui/tree/cli-to-rpc
[^5]: https://github.com/UnstoppableSwap/unstoppableswap-gui/commit/24f9219864fe60144a0f32374312ad8ba2c9ba6c
[^6]: https://github.com/comit-network/xmr-btc-swap/pull/1231
[^7]: https://github.com/comit-network/xmr-btc-swap/pull/1207
[^8]: https://stats.uptimerobot.com/XXoO7SnvzV/789405091
[^9]: [/binarybaron-second-btc-xmr-atomic-swap-desktop-gui-css-proposal/](/binarybaron-second-btc-xmr-atomic-swap-desktop-gui-css-proposal/)
