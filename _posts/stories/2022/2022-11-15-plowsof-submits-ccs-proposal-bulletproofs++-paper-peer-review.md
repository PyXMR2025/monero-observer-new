---
layout: post
category: story
title: "plowsof submits CCS proposal to get Bulletproofs++ paper peer-reviewed"
description: "plowsof has submitted a CCS proposal looking to get the ePrint version of the Bulletproofs++ paper 'peer-reviewed'."
tags: CCS
date: 2022-11-15 21:00
last_modified_at: 2023-03-31
---

plowsof[^1] has submitted a CCS proposal[^2] looking to get the ePrint version[^3] of the Bulletproofs++[^4] paper[^5] *peer-reviewed*:

> This CCS will provide funding for the first step towards Bulletproofs++ implementation in Monero. [..] The deliverable is a write-up which will include recommendations, notes, weaknesses, and issues (if any) of the BP++ paper.

```
Total funding: 155 XMR.

ETA: EOY.
```

### Milestones

- M1: Bp++ eprint paper audit (155 XMR)

### Proposed events timeline (not part of this CCS)

- Q4 2022: C++ PoC for comparing performance between Bp+ and Bp++ (by CypherStack[^6])
- Q1 2023: PoC implementation for Monero (by UkoeHB[^7])
- Q2-Q4 2023: Paper review and implementation audit (by Quarkslab[^8])
- TBD: one or two more implementation audits (possibly by CypherStack[^5])

Bulletproofs++, if implemented in Monero, could further reduce typical transaction size and significantly improve verification performance[^9].

To read the full proposal, share your feedback, ask questions and support this CCS, consult !358[^2].

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 22/11/16: proposal edited after today's MRL meeting[^10]: timeline removed; title changed from *audit* to *peer review* to *reduce confusion*; Cypherstack will start the audit *early December*; a separate CCS proposal will be submitted for the PoC code audit.**

**Update 23/3/23: moved to funding stage[^11].**

**Update 23/3/31: fully funded[^12]; review is on hold (author is planning to release a new version of the paper on April 19th)[^13].**

---

[^1]: https://github.com/plowsof/
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/358](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/358){:target="_blank"}
[^3]: https://eprint.iacr.org/2022/510/
[^4]: https://github.com/Liam-Eagen/BulletproofsPP/
[^5]: [https://moneroresearch.info/index.php?action=resource_RESOURCEVIEW_CORE&id=83/](https://moneroresearch.info/index.php?action=resource_RESOURCEVIEW_CORE&id=83/){:target="_blank"}
[^6]: https://cypherstack.com/
[^7]: https://github.com/UkoeHB/
[^8]: https://www.quarkslab.com/
[^9]: https://github.com/monero-project/research-lab/issues/101/
[^10]: [221116-mrl.log](/assets/logs/221116-mrl.log)
[^11]: [/plowsof-ccs-proposal-bulletproofs++-peer-review-ready-funding/](/plowsof-ccs-proposal-bulletproofs++-peer-review-ready-funding/)
[^12]: [/plowsof-ccs-proposal-bulletproofs++-peer-review-fully-funded/](/plowsof-ccs-proposal-bulletproofs++-peer-review-fully-funded/)
[^13]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/358#note_21015](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/358#note_21015){:target="_blank"}
