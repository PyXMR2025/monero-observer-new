---
layout: post
category: story
title: LeoNero submits CCS proposal for 2 months of full-time Monero dev work
description: "LeoNero has submitted their first CCS proposal to work full-time on Monero development for the next 8 weeks."
tags: CCS
date: 2022-06-29 22:00
last_modified_at: 2022-07-05
---

LeoNero[^1] has submitted their first CCS proposal[^2] to work full-time on Monero development for the next 8 weeks:

> I propose to work for two months (July and August), 40h a week [..]

```
Funding: 118.26 XMR (USD 45/hr * 40 hrs/week * 8 weeks).

ETA: ~8 weeks.
```

## Tasks overview

- Implement `get_tx_key should support raw_monero_tx blob as input`[^3]
- Implement `Add generate_blocks addr numblocks [starting_nonce] command to monerod when in regtest mode`[^4]
- Update InProofV2 to V3[^5]
- Implement UnspentProof, as described in Zero To Monero[^6]
- [..]

The dev has already opened a few `monero`[^7] and `monero-site`[^8] pull requests.

To read, share your feedback, ask questions and support this proposal, consult !327[^2].

---

**Update 22/7/5: proposal closed/canceled by author (no reason specified)[^9].**

---

[^1]: https://github.com/LeoNero
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/327](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/327){:target="_blank"} 
[^3]: https://github.com/monero-project/monero/issues/8398
[^4]: https://github.com/monero-project/monero/issues/8397
[^5]: https://github.com/monero-project/monero/issues/7353
[^6]: https://github.com/monero-project/monero/issues/7353
[^7]: https://github.com/monero-project/monero/pulls/LeoNero
[^8]: https://github.com/monero-project/monero-site/pulls/LeoNero
[^9]: [/leonero-cancels-monero-dev-work-ccs-proposal](/leonero-cancels-monero-dev-work-ccs-proposal)
