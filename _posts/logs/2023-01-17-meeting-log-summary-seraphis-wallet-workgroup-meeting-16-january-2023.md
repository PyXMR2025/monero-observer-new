---
layout: post
category: story
title: "Meeting summary: Seraphis Wallet Workgroup, 16 January 2023"
description: "This is a comprehensive summary, with added reference links, of the Seraphis Wallet Workgroup meeting from January 16th, 2023, 1800 UTC."
tags: [logs]
image: 
meeting_name: "Seraphis Wallet Workgroup"
meeting_report: /seraphis-wallet-workgroup-meeting-16-january-2023/
meeting_date: "2023-01-16"
meeting_logs: /assets/logs/230116-seraphis.log
date: 2023-01-17 21:00
---

This is a comprehensive summary, with added reference links, of the *Seraphis Wallet Workgroup* meeting[^0] from January 16th 2023, 1800 UTC.

### Logs

The raw, unedited, full log file for this meeting: 

[230116-seraphis.log](/assets/logs/230116-seraphis.log) (113 lines)

### Summary

*Note: it is possible that some relevant information may be missing from this summary; read the full log file for the complete, unedited discussion.*

- **Participants**: 10 (*one-horse-wagon[^1], ghostway[^2], rbrunner7[^3], dangerousfreedom[^4], gingeropolous[^5], jberman[^6], ofrnxmr[^7], Rucknium[^8], JoshBabb[^9], UkoeHB[^10]*)

- **(1) On Seraphis[^11] progress reports:**
	
- dangerousfreedom reported that he is *still working on the knowledge proofs* and expects to present *a first complete draft* *by next week*

- jberman successfully used UkoeHB's Seraphis library to *scan a legacy testnet chain from scratch and recover a wallet's balance*[^12]

- **(2) On using a formalized formatting system for comments (Doxygen)[^13]:**
	
- ghostway thought that *Doxygen with clang format* would be *okay*; dangerousfreedom agreed

- rbrunner7 shared an example of what comments in 'Doxygen style' look like in the existing Monero codebase[^14] and noted that the system is *quite big* and it *looks a bit like overkill*; ghostway pointed out that *using just a subset is still ok*

- JoshBabb noted that although *doxygen-generated comments aren't terribly useful*, one can *appreciate them alongside code styles and linting* as a reminder to comment by *providing a designated and pre-styled place for them*

- rbrunner7 acknowledged that the recommendation was *to more or less follow koe's style as visible in the header files of the Seraphis library*
	
- **(3) On the ambiguity of the term 'account' (vs 'wallet')[^15]:**

- rbrunner7 was wondering if the use of the term 'account' as a synonym for 'wallet' is widespread and proposed the workgroup *finds a way to circumvent* the *clash* of using the term 'account' for 2 different things

- UkoeHB shared his point of view: *a wallet is a stateful thing, while an account is more abstract* and noted that *calling the base keys your wallet creates ambiguity*

- rbrunner7 linked to the Moneropedia 'Account' entry[^16], for reference

- one-horse-wagon suggested *getting rid of the term account and sticking with wallets*, since *there is very little difference between the two terms*

- dangerousfreedom liked the *straight hierarchy* of *wallet->account->addresses* 
	
- jberman thought that *it makes more sense* to change the *CryptoNote class 'account'* and keep the term 'account' as used to *describe the feature to divide wallets by accounts*, in an effort to *avoid confusing users*

---

Let me know if you find this kind of report helpful.

Feedback, edits always welcome @[/about](/about#signature).

**-3RA**

---

[^0]: [/seraphis-wallet-workgroup-meeting-16-january-2023/](/seraphis-wallet-workgroup-meeting-16-january-2023/)
[^1]: (Matrix) @one-horse-wagon:matrix.org
[^2]: (Matrix) @ghostway:matrix.org
[^3]: https://github.com/rbrunner7/
[^4]: https://github.com/DangerousFreedom1984/
[^5]: https://github.com/Gingeropolous/
[^6]: https://github.com/j-berman/ 
[^7]: (Matrix) @ofrnxmr:matrix.org
[^8]: https://github.com/Rucknium/
[^9]: (Matrix) @JoshBabb:matrix.org 
[^10]: https://github.com/UkoeHB/
[^11]: https://github.com/UkoeHB/Seraphis/
[^12]: https://github.com/j-berman/monero-cpp/commit/bb270104b83c4d660cecfe5122fcd0f98a6f01bd
[^13]: https://github.com/seraphis-migration/wallet3/issues/26
[^14]: https://github.com/monero-project/monero/blob/master/src/cryptonote_core/blockchain.h
[^15]: https://github.com/seraphis-migration/wallet3/issues/44
[^16]: https://www.getmonero.org/resources/moneropedia/account.html
