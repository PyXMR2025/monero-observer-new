---
layout: post
category: story
title: "Meeting summary: Seraphis Wallet Workgroup, 14 November 2022"
description: "This is a comprehensive summary, with added reference links, of the Seraphis Wallet Workgroup meeting from November 14th, 2022, 1800 UTC."
tags: [logs]
image: 
meeting_name: "Seraphis Wallet Workgroup"
meeting_report: /seraphis-wallet-workgroup-meeting-14-november-2022/
meeting_date: "2022-11-14"
meeting_logs: /assets/logs/221114-seraphis.log
date: 2022-11-17 21:00
---

This is a comprehensive summary, with added reference links, of the *Seraphis Wallet Workgroup* meeting[^0] from November 14th 2022, 1800 UTC.

### Logs

The raw, unedited, full log file for this meeting: 

[221114-seraphis.log](/assets/logs/221114-seraphis.log) (130 lines)

### Summary

*Note: it is possible that some relevant information may be missing from this summary; read the full log file for the complete, unedited discussion.*

- **Participants**: 10 (*rbrunner7[^1], one-horse-wagon[^2], jberman[^3], JoshBabb[^4], UkoeHB[^5], Rucknium[^6], moneromoooo[^7], interloper[^8], BusyBoredom[^9], spacekitty420[^10]*)

- **(1) On the Seraphis HF ETA**
	
- rbrunner7 was wondering when the hardfork to Seraphis might take place; one-horse-wagon suggested *3 years if all goes well*; UkoeHB and jberman agreed on a more *optimistic* 2 years estimate

- **(2) On choosing a project name[^11]**

- rbrunner7 shared some options: *Seraphis wallet* and *wallet3*

- jberman voted for *wallet3*, arguing that calling it *Seraphis wallet* would limit it to Seraphis and could potentially cause confusion *if there is some significant upgrade in the future*

- UkoeHB voted against *wallet3*, as that would imply *another monolith*, and suggested *xmr wallet suite* (wallet_suite) instead

- one-horse-wagon suggested *The Seraphis Project*, as that could help with advertising/funding: *we need a name that sells out there*; UkoeHB didn't particularly care about the *marketing aesthetic*

- rbrunner7 voted for *Seraphis wallet*, discarding *wallet3* as *non-descript* and *a bit boring* 

- JoshBabb voted for *wallet3*, as that is related to wallet2 and to Monero by context: *Seraphis doesn't relate to Monero to me yet*; rbrunner7 noted that wallet2 is *insider-knowledge*

- Rucknium suggested the group should also consider *threats of users being scammed*

- rbrunner7 acknowledged the lack of consensus and closed the subject: *maybe the people over in #monero-community can duke it out*

- **(3) On nesting Seraphis folders in the Monero core repo[^12]**

- UkoeHB commented that they plan to, *later this week*, do a commit to reorganize things accordingly

- rbrunner7 offered to *help set up a repository* and *guide UkoeHB when he reorganizes his library*

- rbrunner7 shared the main proposed approaches: *1) Add a number of Seraphis-related "top level" folders, i.e. in `/src`.*, and *2) Add something like 2 such top-level folders, and then go one level deeper within those.*

- UkoeHB thought that it doesn't make sense to have subfolders: *Multisig utilities depend on seraphis crypto and seraphis mulitisig depends on the multisig utilities, and multisig utils are in the main `src/`*

- rbrunner7 wondered if anyone would object to adding 10 more folders to the existing 30 folders in *`/src`*[^13], considering that *people attach to such folders and folder names*
	
- UkoeHB commented that although rearranging files and folders is *a bit tedious*, it is *not a big deal*	
	
- jberman didn't have anything to object, but noted that he would prefer to *avoid a ton of new top-level folders*
	
- BusyBoredom noted that he would expect to see, from the perspective of a new Monero developer, *a `wallet/` folder inside `src/` with contents broken out further bellow that*, as opposed to *things relating to wallet internals inside `src/`*
	
- rbrunner7 remarked that it is *a bit early to decide something* and *some experimentation is probably in order* before changing topics

- **(4) Seraphis terminology**

	- (4.1) **on term to use for 'output' (enotes)[^14]**:

	- rbrunner7 asked if everyone is in agreement to replace the term *output* with the new *enote* term coined by UkoeHB

	- one-horse-wagon, interloper, rbrunner7, spacekitty420 and jberman agreed 

	- JoshBabb wondered if the existence of the 'enotes' cryptocurrency project[^15] and a *registered trademark for two different applications* could be a deal breaker; rbrunner7 didn't see any problem with that
	
	- rbrunner7 noted that everyone present is in agreement and unless there are any objections post-meeting, *enote* will replace *output*
	
	- (4.2) **on naming unique transaction identifiers (transaction id/transaction hash)[^16]**:

	- rbrunner7, spacekitty420 and UkoeHB voted for using 'transaction id' instead of 'transaction hash'
	
	- (4.3) **on avoiding the term 'transfer'[^17]**:
	
	- rbrunner7 voted to avoid using the *potentially misleading* term for the Seraphis wallet, noting that *transfer* is currently being used in *various ways* in *wallet2*, in CLI wallet commands, and RPC server commands 
	
	- one-horse-wagon agreed with rbrunner7 and noted that the term is a *catchall for everything* and it can be *easily misunderstood*
	
	- UkoeHB didn't think that *it makes sense to fully ban* the term: *in our world a transaction is a thing and transfer funds is what it does*
	
---

Let me know if you find this kind of report helpful.

Feedback, edits always welcome @[/about](/about#signature).

**-3RA**

---

[^0]: [/seraphis-wallet-workgroup-meeting-14-november-2022/](/seraphis-wallet-workgroup-meeting-14-november-2022/)
[^1]: https://github.com/rbrunner7/
[^2]: (Matrix) @one-horse-wagon:matrix.org
[^3]: https://github.com/j-berman/ 
[^4]: (Matrix) @JoshBabb:matrix.org
[^5]: https://github.com/UkoeHB/
[^6]: https://github.com/Rucknium/
[^7]: https://github.com/moneromooo-monero/
[^8]: (IRC/Libera) interloper
[^9]: https://github.com/busyboredom/
[^10]: (Matrix) @spacekitty420:matrix.org 
[^11]: https://github.com/seraphis-migration/wallet3/issues/15/
[^12]: https://github.com/seraphis-migration/wallet3/issues/29/
[^13]: https://github.com/monero-project/monero/tree/master/src/
[^14]: https://github.com/seraphis-migration/wallet3/issues/1/
[^15]: https://www.enotes.online/
[^16]: https://github.com/seraphis-migration/wallet3/issues/14/
[^17]: https://github.com/seraphis-migration/wallet3/issues/18/
