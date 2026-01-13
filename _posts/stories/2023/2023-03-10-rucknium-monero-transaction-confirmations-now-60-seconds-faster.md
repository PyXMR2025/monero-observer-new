---
layout: post
category: story
title: "Rucknium: 'Monero transaction confirmations are now 60 seconds faster'"
description: "Rucknium has confirmed that most centralized mining pool operators responded positively to his January 19th research and XMR transaction confirmations are now '60 seconds faster'."
image: xmr-tx-delay-all.png
tags: [mining, research, pinned]
date: 2023-03-10 22:00
---

Rucknium[^1] has confirmed[^2] that most centralized mining pool operators responded positively to his January 19th research[^3] and XMR transaction confirmations are now *60 seconds faster*:

> The average time that a Monero transaction has to wait for its first confirmation has fallen **from 3.5 minutes to 2.5 minutes**. That's a full minute improvement in less than two months!

### Pool updates

```
* Config changed:
- HashVault & MoneroOcean: January 20 (~24 hours)
- SupportXMR: January 24th (5 days)
- Nanopool: February 1st (13 days)
* Unknown:
- xmrpool.eu
* Config NOT changed:
- c3pool & 2miners
```

ofrnxmr[^4] and ACK-J[^5] also took part in this joint effort by helping contact pools and asking them to change their default configurations.

DataHoarder[^6] contributed code to gather *mined block data* from centralized mining pools, while plowsof[^7] and the MRL's research computing server[^8] contributed computing resources for *mempool data gathering*.

To learn more about this story, read the previous Monero Observer report[^9], and join the discussion thread[^10].

*This is an ongoing story and the report will be updated when new information is available.*

---

[^1]: https://github.com/Rucknium/
[^2]: [https://rucknium.me/posts/monero-transactions-60-seconds-faster/](https://rucknium.me/posts/monero-transactions-60-seconds-faster/){:target="_blank"}
[^3]: https://rucknium.me/posts/monero-pool-transaction-delay/
[^4]: https://nitter.net/nahuhhXMR/
[^5]: https://github.com/ACK-J/
[^6]: https://git.gammaspectra.live/WeebDataHoarder/monero-blocks
[^7]: https://github.com/plowsof/
[^8]: https://ccs.getmonero.org/proposals/gingeropolous_zenith_storage.html
[^9]: [/rucknium-calls-out-centralized-mining-pools-monero-transaction-confirmation-delays/](/rucknium-calls-out-centralized-mining-pools-monero-transaction-confirmation-delays/)
[^10]: [https://r.nf/11nu4aj/](https://r.nf/r/Monero/comments/11nu4aj/monero_transaction_confirmations_are_now_60/){:target="_blank"}{:rel="nofollow"}
