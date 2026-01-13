---
layout: post
category: story
title: "pokkst creates 'Monero Decoy Scanner' Python script"
description: "pokkst has created 'Monero Decoy Scanner', a Python script that listens to the chain for transactions that use certain outputs as decoy ring members."
tags: services
date: 2022-06-27 20:00
---

pokkst[^1] has created *Monero Decoy Scanner*[^2], a Python script that listens to the chain for transactions that use certain outputs as decoy ring members:

> hopefully others find this useful for tracking when outputs are used as decoy ring members in real-time[^3]

The script requires Python 3 and a `monerod`[^4] instance.

To learn how to configure the script, consult pokkst's *monero-decoy-scanner* repository README file[^5].

---

[^1]: https://github.com/pokkst/
[^2]: [https://github.com/pokkst/monero-decoy-scanner](https://github.com/pokkst/monero-decoy-scanner){:target="_blank"}{:rel="nofollow"}
[^3]: https://nitter.net/pokkst/status/1541196530794774529
[^4]: https://monerodocs.org/interacting/monerod-reference/
[^5]: https://github.com/pokkst/monero-decoy-scanner#readme
