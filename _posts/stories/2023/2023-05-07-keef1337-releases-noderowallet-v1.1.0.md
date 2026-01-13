---
layout: post
category: story
title: "keef1337 releases noderowallet v1.1.0"
description: "keef1337 has released 'noderowallet' v1.1.0 with 'browser/bun compatibility, custom fetch support*' and several bug fixes."
tags: wallets
date: 2023-05-07 20:00
last_modified_at: 2023-05-07
---

keef1337[^1] has released *noderowallet* v1.1.0[^2]'[^3] with *browser/bun compatibility, custom fetch support* and several bug fixes:

> greetings! in this release, i removed all node.js modules and now noderowallet only relies on the fetch global, this means it should also work in the browser and other JS runtimes like bun.[^4]

Consult the git commits[^5] for the full list of changes. 

To learn more about the Node.js library, read the previous Monero Observer report[^6].

*Note: inspect the code before using and block the RPC port with a firewall when using monero-wallet-rpc without authentication to avoid loss of funds.*

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update: v1.1.1/1.1.2 were released with a few fixes[^7].**
 
---

[^1]: https://git.kyun.host/keef1337/
[^2]: [https://git.kyun.host/keef1337/noderowallet](https://git.kyun.host/keef1337/noderowallet){:target="_blank"}
[^3]: [https://www.npmjs.com/package/noderowallet/v/latest](https://www.npmjs.com/package/noderowallet/v/latest){:target="_blank"}{:rel="nofollow"}
[^4]: [https://r.nf/r/Monero/comments/139ywrk/noderowallet_110_released_browserbun/jj4ehz8/?context=3](https://r.nf/r/Monero/comments/139ywrk/noderowallet_110_released_browserbun/jj4ehz8/?context=3){:target="_blank"}{:rel="nofollow"}
[^5]: https://git.kyun.host/keef1337/noderowallet/commit/91090ae6de3888a07ae973eeb79200b151710232
[^6]: [/keef1337-releases-noderowallet-nodejs-library-interacting-monero-wallet-rpc/](/keef1337-releases-noderowallet-nodejs-library-interacting-monero-wallet-rpc/)
[^7]: https://git.kyun.host/keef1337/noderowallet/commit/7208cc3dd1146c8753af6ea75b0518025f1bb323, https://git.kyun.host/keef1337/noderowallet/commit/eb6039dad7e3fd276aba8445236773f568d7f915
