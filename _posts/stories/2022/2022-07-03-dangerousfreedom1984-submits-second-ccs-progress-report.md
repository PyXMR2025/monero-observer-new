---
layout: post
category: story
title: "DangerousFreedom1984 submits second CCS progress report"
description: "DangerousFreedom1984 has submitted the second progress report for their CCS proposal to build Python tools that check for inflation in Monero."
tags: CCS
date: 2022-07-03 20:00
---

DangerousFreedom1984[^1] has submitted the second progress report[^2] for their CCS[^3] proposal to build Python tools that check for inflation in Monero:

> I would like to provide my second report regarding this CCS. [..] I HAVE NOT FOUND ANY BUG THAT COULD LEAD TO INFLATION.

### Progress overview

- Created functions to check and generate CLSAG signatures in Python.
- Created functions to check and generate the Monero style Bulletproofs in Python.
- Created some educational material to explain these concepts.
- Scanned the blockchain for transactions type 1 and type 2 (up to blockheight 1686275). 
- Improved a bit the website www.moneroinflation.com. [..]

### Planned work (July)

- Continue scanning the blockchain for all Bulletproofs txs as this is really a time taking operation.
- Improve the website. 
- Improve the performance, comments and writing of the Python codes. [..]

The full progress report is available on Gitlab[^2].

To learn more about DangerousFreedom1984's project, visit the *moneroinflation.com*[^4] website and consult the previous Monero Observer report[^5].

---

[^1]: https://github.com/DangerousFreedom1984
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/298#note_17010](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/298#note_17010){:target="_blank"}
[^3]: https://ccs.getmonero.org/proposals/monero-inflation-checker.html
[^4]: [https://www.moneroinflation.com/](https://www.moneroinflation.com/){:target="_blank"}
[^5]: [/dangerousfreedom1984-submits-ccs-proposal-python-inflation-tools/](/dangerousfreedom1984-submits-ccs-proposal-python-inflation-tools/)
