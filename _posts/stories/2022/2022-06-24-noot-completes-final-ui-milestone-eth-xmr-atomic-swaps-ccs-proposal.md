---
layout: post
category: story
title: "Elizabeth completes final milestone for ETH-XMR atomic swaps CCS proposal"
description: "noot has completed the final milestone (#7: User Interface) for her ETH-XMR atomic swaps CCS proposal, which also includes the Metamask integration task."
tags: CCS
image: noot-xmr-eth-metamask-ui.png
date: 2022-06-24 21:00
last_modified_at: 2022-07-18
---

Elizabeth (noot[^1]) has completed[^2] the final milestone (#7: User Interface) for her ETH-XMR atomic swaps[^3] CCS proposal[^4], which also includes the Metamask[^5] integration task:

> Hey, milestone 7 (UI) has been completed! The UI has integration with Metamask so users can sign and submit transactions entirely in their browser and the swap daemon doesn't require access to an ETH private key. [..]

### Relevant PRs

- Some UI to get started #87[^6]
- Swaping modal #91[^7]
- Devnet setup script and showing errors in the UI #99[^8]
- ui: display multiple peers #110[^9]
- ui: metamask integration, swapd: implement external sender for front-end integration #126[^10]
- allow for multiple ongoing swaps #128[^11]
- Metamask store cleanup and bring back success message #129[^12]
- fixes for stagenet swap and UI #137[^13]  

Note that the UI can only be run locally at this stage:

> [..] hosting it on a website requires quite significant changes to the daemon, and would work much nicer packaged as a GUI.

Read the full dev report[^2] and consult *stagenet.md*[^14] to learn how you can join the network and try out the swap as a XMR-taker or XMR-maker.

### What's next 

We can expect an *audit-ready pre-production release* of the ETH-XMR atomic swap software next, before the mainnet launch.

A follow-up CCS proposal that could add protocol improvements such as an auxiliary Node.js client library wrapper, tor and ERC-20 token support is likely to be proposed soon by noot.

Consult the initial Monero Observer report[^15] to learn more about the project.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update: alpha release[^16] available; new CCS proposal submitted[^17].**

---

[^1]: https://github.com/noot
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/277#note_16905](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/277#note_16905){:target="_blank"}
[^3]: https://github.com/noot/atomic-swap/
[^4]: https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/277
[^5]: https://metamask.io/
[^6]: https://github.com/noot/atomic-swap/pull/87
[^7]: https://github.com/noot/atomic-swap/pull/91
[^8]: https://github.com/noot/atomic-swap/pull/99
[^9]: https://github.com/noot/atomic-swap/pull/110
[^10]: https://github.com/noot/atomic-swap/pull/126
[^11]: https://github.com/noot/atomic-swap/pull/128
[^12]: https://github.com/noot/atomic-swap/pull/129
[^13]: https://github.com/noot/atomic-swap/pull/137
[^14]: [https://github.com/noot/atomic-swap/blob/master/docs/stagenet.md](https://github.com/noot/atomic-swap/blob/master/docs/stagenet.md){:target="_blank"}{:rel="nofollow"}
[^15]: [/noot-xmr-eth-atomic-swaps-ccs-proposal/](/noot-xmr-eth-atomic-swaps-ccs-proposal/)
[^16]: https://github.com/noot/atomic-swap/releases/tag/v0.1.0
[^17]: [/noot-second-eth-xmr-atomic-swap-css-proposal](/noot-second-eth-xmr-atomic-swap-css-proposal)
