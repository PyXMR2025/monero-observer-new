---
layout: post
category: story
title: "keef1337 releases 'noderowallet' Node.js library for interacting with monero-wallet-rpc"
description: "keef1337 has announced the release of 'noderowallet*', a zero-dependency Node.js library for interacting with the Monero Wallet RPC."
tags: wallets
date: 2023-04-30 20:00
---

keef1337[^1] has announced[^2] the release of *noderowallet*[^3]'[^4], a zero-dependency Node.js library for interacting with the Monero Wallet RPC[^5]:

> [..] written in TypeScript, documented with JSDoc, with BigInt support. [..] you can do pretty much anything related to monero with this library

noderowallet is apparently being used by VPS provider *kyun.host*[^6] to process XMR payments.

Consult the Git repository[^3] for usage instructions. 

*Note: inspect the code before using and block the RPC port with a firewall when using monero-wallet-rpc without authentication to avoid loss of funds.*

*This is an ongoing story and the report will be updated when new information is available.*

---

[^1]: https://git.kyun.host/keef1337/
[^2]: [https://r.nf/1339q7y/](https://r.nf/r/Monero/comments/1339q7y/noderowallet_a_nodejs_library_for_interacting/){:target="_blank"}{:rel="nofollow"}
[^3]: [https://git.kyun.host/keef1337/noderowallet](https://git.kyun.host/keef1337/noderowallet){:target="_blank"}
[^4]: [https://www.npmjs.com/package/noderowallet](https://www.npmjs.com/package/noderowallet){:target="_blank"}{:rel="nofollow"}
[^5]: https://www.getmonero.org/resources/developer-guides/wallet-rpc.html
[^6]: [https://kyun.host/](https://kyun.host/){:target="_blank"}
[^7]: https://kyun.host/services
