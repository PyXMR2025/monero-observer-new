---
layout: post
category: story
title: "binarybaron completes first milestone for XMR-BTC atomic swap desktop GUI CCS proposal"
description: "binarybaron has completed the first milestone for their XMR-BTC atomic swap desktop GUI prototype CCS proposal."
tags: CCS
date: 2022-08-10 21:00
---

binarybaron[^1] has completed[^2] the first milestone for their XMR-BTC atomic swap desktop GUI prototype CCS proposal[^3]:

> Despite the "July" label of the first milestone, it was to be paid after one month after the proposal was fully funded. Responding to comments on the initial proposal and submitting the proposal took a little longer than expected.

### Work overview

- users are now able to attempt a manual cancel and refund within the GUI if the swap is not automatically refunded by `swap-cli`
- efforts to make the cancellation and refund mechanism more stable was started with issue 683[^4] in the `xmr-btc-swap` repository
- the official API[^5], Rendezvous Point[^6] and front end[^7], all had 100% uptime last month
- frontend development work to turn the unstoppableswap.net website from a dynamic interface to a download page for the desktop GUI was started[^8]'[^9] [..]

Read the full update[^2] on Github for more details.

Consult the previous Monero Observer report[^10] to learn more about the project.

---

[^1]: https://github.com/binarybaron
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/321#note_18171](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/321#note_18171){:target="_blank"}
[^3]: https://ccs.getmonero.org/proposals/unstoppableswap-gui-2.html
[^4]: https://github.com/comit-network/xmr-btc-swap/issues/683
[^5]: https://stats.uptimerobot.com/XXoO7SnvzV/789405091
[^6]: https://stats.uptimerobot.com/XXoO7SnvzV/790024720
[^7]: https://stats.uptimerobot.com/XXoO7SnvzV/788668322
[^8]: https://github.com/UnstoppableSwap/unstoppableswap-site/tree/download-button
[^9]: https://deploy-preview-1--unstoppableswap-site.netlify.app/
[^10]: [/binarybaron-second-btc-xmr-atomic-swap-desktop-gui-css-proposal/](/binarybaron-second-btc-xmr-atomic-swap-desktop-gui-css-proposal/)
