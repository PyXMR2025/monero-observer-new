---
layout: post
category: story
title: "UkoeHB submits new CCS proposal to build core Seraphis library"
description: "UkoeHB has submitted a new CCS proposal to build the 'core Seraphis library'."
tags: CCS
date: 2022-08-19 20:00
last_modified_at: 2022-12-26
---

UkoeHB[^1] has submitted a new CCS proposal[^2] to build the *core Seraphis library*[^3]:

> In the last CCS period I decided that an actual wallet proof-of-concept is too ambitious. My more modest/realistic goal is to complete the Seraphis library so wallets can be (relatively) easily built.

```
Total funding: 122 XMR (50 USD + 0.2 XMR Rate).

ETA: 12 weeks (20hr/wk, 240hrs total).
```

### Tasks overview

- Legacy/Seraphis integration so old cryptonote-style enotes can be spent in Seraphis transactions.
- Seraphis-style coinbase transaction type.
- Test out tevador's x25519 library for enote ECDH instead of ed25519 [..]
- Miscellaneous code cleanup
- Update the Seraphis draft, which I have not touched for 6 months.

To learn more about UkoeHB's work, consult the most recent dev update[^4] and the previous Monero Observer report[^5].

To share your feedback, ask questions and support this proposal, consult !338[^2].

---

**Update 22/8/24: ready for funding[^6].**

**Update 22/8/31: fully funded[^7].**

**Update 22/12/26: dev update posted[^8], new CCS submitted[^9].**

---

[^1]: https://github.com/UkoeHB
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/338](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/338){:target="_blank"}
[^3]: https://github.com/UkoeHB/Seraphis, https://github.com/UkoeHB/monero/tree/seraphis_lib
[^4]: https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/314#note_18262
[^5]: [/ukoehb-submits-second-seraphis-wallet-poc-ccs-proposal/](/ukoehb-submits-second-seraphis-wallet-poc-ccs-proposal/)
[^6]: [/ukoehb-seraphis-library-ccs-proposal-ready-funding/](/ukoehb-seraphis-library-ccs-proposal-ready-funding/)
[^7]: [/ukoehb-seraphis-library-ccs-proposal-fully-funded/](/ukoehb-seraphis-library-ccs-proposal-fully-funded/)
[^8]: https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/338#note_20190
[^9]: [/ukoehb-submits-long-term-seraphis-library-ccs-proposal/](/ukoehb-submits-long-term-seraphis-library-ccs-proposal/)
