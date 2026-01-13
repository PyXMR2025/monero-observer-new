---
layout: post
category: story
title: "xmrvsbeast proposes bounty for adding P2Pool mining feature to Monero GUI Wallet in Simple mode"
description: "xmrvsbeast has proposed a bounty for adding a Monero GUI Wallet feature that would allow users to mine on P2Pool in *Simple mode*, via remote nodes."
tags: bounties
image: 
date: 2022-06-08 19:00
---

xmrvsbeast[^1] has proposed a bounty[^2] for adding a Monero GUI Wallet[^3] feature that would allow users to mine on P2Pool[^4] in *Simple mode*[^5], via remote nodes:

> I really see it as a opportunity to onboard a broad base of users who may end up running their own node eventually when they get more serious about mining and Monero.[^6]

```
Total Bounty: 2 XMR (to date)
```

### Requirements

- Code is open-source
- Code is submitted to the Monero repo as a pull-request[^7]
- Pull request is accepted into Monero's code base after review
- Automatically populate the "start up flags" with the required options based on remote node in use by wallet: "--host moneronode.com --rpc-port 18089 --zmq-port 18083"
- Automatically check configured remote node for p2pool compatibility
- Notify user if node is not compatible and suggest to search internet for a node with a suggested search term example: "P2Pool compatible Monero remote nodes"

To start working on the project yourself, you should make your intentions public by posting a comment in the bounty's thread.

To increase the bounty you can contribute some XMR to the bounty address posted by the *Monero Bounties Bot*[^2].

Note that this proposal is somewhat controversial. Read the associated Reddit thread[^8] for more information.

*This is an ongoing story and the report will be updated if/when new information is available.*

---

[^1]: https://libredd.it/user/xmrvsbeast
[^2]: [https://bounties.monero.social/posts/67](https://bounties.monero.social/posts/67){:target="_blank"}
[^3]: https://www.getmonero.org/downloads/#gui
[^4]: https://p2pool.io/
[^5]: https://github.com/monero-ecosystem/monero-GUI-guide/blob/master/monero-GUI-guide.md#about-the-simplebootstrap-mode
[^6]: https://libredd.it/r/Monero/comments/v7jr96/bounty_p2pool_mining_in_monero_gui_wallet_in/ibld2ku/?context=3
[^7]: https://github.com/monero-project/monero-gui/pulls
[^8]: [https://libredd.it/v7jr96/](https://libredd.it/v7jr96/){:target="_blank"}{:rel="nofollow"}
