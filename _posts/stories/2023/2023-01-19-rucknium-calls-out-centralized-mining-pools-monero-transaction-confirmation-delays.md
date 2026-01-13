---
layout: post
category: story
title: "Rucknium calls out centralized mining pools for unnecessarily delaying XMR transaction confirmations by 60 seconds"
description: "Rucknium has published a new article in which he calls out centralized mining pools for unnecessarily delaying XMR transaction confirmations by 60 seconds."
image: coin-comparison-tx-eligibility-barchart.png
tags: [mining, research]
date: 2023-01-19 21:00
last_modified_at: 2023-03-10
---

Rucknium[^1] has published a new article[^2]'[^3] in which he calls out centralized mining pools for unnecessarily delaying XMR transaction confirmations by 60 seconds:

> This makes Monero confirmations slower than Litecoin even though Litecoin’s average block time is 2.5 minutes, compared to Monero’s 2 minutes flat. Mining pool operators could solve this issue by adding new transactions to their block templates more frequently, like P2Pool already does.

The researcher recommends mining pools update their block templates at least *every 30 seconds*, preferably *every 10 seconds*, *if the database operations are not expensive*.

Read Rucknium's complete analysis on his website[^2] and share your thoughts on Reddit[^4]. 

The R scripts that can be used to reproduce the analysis are available in the *Monero-TX-Confirm-Delay*[^5] Github repository. Find the data files on *rucknium.me/data*[^6].

To support Rucknium's ongoing research work, you can donate[^7] XMR, WOW, BCH, or BTC.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 23/1/20: apparently hashvault.pro is now updating their block templates every 20 seconds (down from ~2 minutes)[^8]; moneroocean.stream also updates faster (30 seconds)[^9]'[^10].**

**Update 23/3/10: Rucknium confirms XMR transactions now '60 seconds faster'[^11].**

---

[^1]: https://github.com/Rucknium/
[^2]: [https://rucknium.me/posts/monero-pool-transaction-delay/](https://rucknium.me/posts/monero-pool-transaction-delay/){:target="_blank"}
[^3]: (onion) http://d6ac5qatnyodxisdehb3i4m7edfvtukxzhhtyadbgaxghcxee2xadpid.onion/posts/monero-pool-transaction-delay/
[^4]: [https://r.nf/10gapp9/](https://r.nf/r/Monero/comments/10gapp9/centralized_mining_pools_are_delaying_monero/){:target="_blank"}{:rel="nofollow"}
[^5]: https://github.com/Rucknium/misc-research/tree/main/Monero-TX-Confirm-Delay/
[^6]: https://rucknium.me/data/
[^7]: [https://rucknium.me/donate/](https://rucknium.me/donate/){:target="_blank"}
[^8]: https://r.nf/r/Monero/comments/10gapp9/centralized_mining_pools_are_delaying_monero/j52n5uc/?context=3
[^9]: https://r.nf/r/MoneroMining/comments/10gb98a/comment/j524qqf/
[^10]: https://r.nf/r/Monero/comments/10gapp9/centralized_mining_pools_are_delaying_monero/j53p2v4/
[^11]: [/rucknium-monero-transaction-confirmations-now-60-seconds-faster/](/rucknium-monero-transaction-confirmations-now-60-seconds-faster/)
