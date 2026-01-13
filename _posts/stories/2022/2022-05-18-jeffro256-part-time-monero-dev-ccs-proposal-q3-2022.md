---
layout: post
category: story
title: jeffro256 submits CCS proposal for 3 months of part-time Monero dev work
description: jeffro256 has submitted their first CCS proposal to work part-time on Monero development for 3 months.
tags: CCS
date: 2022-05-18 20:00
last_modified_at: 2023-04-04
---

jeffro256[^1] has submitted their first CCS proposal[^2] to work part-time on Monero development for 3 months:

> I propose to spend 30 hours a week for 3 months working on Monero Core and the Monero GUI. 

```
Total funding proposed: 70 XMR (USD 30/hr * 30 hrs/week * 12 weeks).

ETA: ~3 months.
```

## Tasks overview

- Work with @selsta to protect GUI users in 'simple mode' by implementing a trusted community node system
- Create a RPC SSL connection integrity indicator for the CLI and GUI wallets
- Allow GUI users more fine-grained control of their SSL connections
- Create a more thorough UI for warning users of GUI mode of high fees
- Draft a formal Levin/Cryptonote protocol specification
- Revamp Doxygen documentation
- Do other general documentation of the codebase
- Transition legacy OpenSSL code to comply with OpenSSL 3.0 (already started)
- Explore using faster & smaller EC OpenSSL certificates in place of traditional RSA certificates
- Continue to remove dead code, and simplify codebase, especially the (epee module)
- Misc developing / reviews

jeffro256's first PR was merged on March 18th. The complete list of merged pull requests is available on Github[^3].

To read, share your feedback, ask questions and support this proposal, consult !319[^2].

---

**Update 22/7/22: ready for funding[^4].**

**Update 22/7/24: fully funded.**

**Update 22/9/24: first dev update posted, M1 completed[^5].**

**Update 22/11/19: October dev update posted, M2 completed[^6].**

**Update 23/4/4: final dev update posted, M3 completed[^7].**

---

[^1]: https://github.com/jeffro256
[^2]: [https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/319](https://repo.getmonero.org/monero-project/ccs-proposals/-/merge_requests/319){:target="_blank"} 
[^3]: https://github.com/monero-project/monero/pulls?q=is%3Apr+is%3Amerged+author%3Ajeffro256
[^4]: [/jberman-jeffro256-ccs-proposals-ready-funding](/jberman-jeffro256-ccs-proposals-ready-funding)
[^5]: [/jeffro256-posts-september-2022-dev-update/](/jeffro256-posts-september-2022-dev-update/)
[^6]: [/jeffro256-posts-october-2022-dev-update/](/jeffro256-posts-october-2022-dev-update/)
[^7]: [/jeffro256-posts-final-ccs-milestone-update/](/jeffro256-posts-final-ccs-milestone-update/)
