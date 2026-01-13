---
layout: post
category: story
title: "ETH-XMR atomic swaps initial mainnet release 'in the next month or two', according to noot"
description: "The initial mainnet release for noot's ETH-XMR atomic swaps project could be ready 'in the next month or two', according to her latest development update."
tags: dev
image: 
date: 2022-11-26 20:00
last_modified_at: 2023-05-05
---

The initial mainnet release for noot[^1]'s ETH-XMR atomic swaps[^2] project could be ready *in the next month or two*, according to her latest development update[^3]:

> We've been focusing on implementing the remaining features and refactors needed to productionize the code and make it more user-friendly. [..] I don't have an exact date yet, but I believe we're coming very close to the finish line for an initial mainnet release, ideally in the next month or two (if everything goes well!)

### Progress overview

- disk persistence has been implemented
- ERC20 support is fully completed with integration tests
- an Ethereum event watcher was implemented
- relayer support for ETH-takers has been implemented
- `swapd` now controls a monero-wallet-rpc instance directly [..]

To test the swap locally or on stagenet, follow the instructions on Github[^5]'[^6] and join the project's Matrix room[^4] for technical support and discussions.

Consult the previous Monero Observer report[^7]'[^8] to learn more about noot's work.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update: beta live on mainnet[^9].**

---

[^1]: https://github.com/noot/
[^2]: https://github.com/AthanorLabs/atomic-swap/
[^3]: [https://libreddit.de/z5c9k7/](https://libreddit.de/z5c9k7/){:target="_blank"}{:rel="nofollow"}
[^4]: https://matrix.to/#/#ethxmrswap:matrix.org
[^5]: https://github.com/AthanorLabs/atomic-swap/blob/master/docs/local.md
[^6]: https://github.com/AthanorLabs/atomic-swap/blob/master/docs/stagenet.md
[^7]: [/noot-eth-xmr-atomic-swap-gofundme-campaign-fully-funded/](/noot-eth-xmr-atomic-swap-gofundme-campaign-fully-funded/)
[^8]: [/noot-executes-first-ever-mainnet-xmr-eth-atomic-swap-arbitrum-wins-bounty/](/noot-executes-first-ever-mainnet-xmr-eth-atomic-swap-arbitrum-wins-bounty/)
[^9]: [/noot-eth-xmr-atomic-swap-beta-release-live-mainnet/](/noot-eth-xmr-atomic-swap-beta-release-live-mainnet/)
