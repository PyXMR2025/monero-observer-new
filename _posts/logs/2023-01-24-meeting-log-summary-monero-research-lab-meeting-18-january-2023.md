---
layout: post
category: story
title: "Meeting summary: Monero Research Lab, 18 January 2023"
description: "This is a comprehensive summary, with added reference links, of the Monero Research Lab meeting from January 18th, 2023, 1700 UTC."
tags: [logs]
image: 
meeting_name: "Monero Research Lab"
meeting_report: /monero-research-lab-meeting-18-january-2023/
meeting_date: "2023-01-24"
meeting_logs: /assets/logs/230118-mrl.log
date: 2023-01-24 21:00
---

This is a comprehensive summary, with added reference links, of the MRL meeting[^0] from January 18th 2023, 1700 UTC.

### Logs

The raw, unedited, full log file for this meeting: 

[230118-mrl.log](/assets/logs/230118-mrl.log) (83 lines)

### Summary

*Note: it is possible that some relevant information may be missing from this summary; read the full log file for the complete, unedited discussion.*

- **Participants**: 7 (*UkoeHB[^1], Rucknium[^2], rbrunner[^3], vtnerd[^4], one-horse-wagon[^5], dangerousfreedom[^6], isthmus[^7]*)

- **(1) Updates**
	
  - (1.1) **on Seraphis[^8]**:
	
	- UkoeHB *continued cleanup of the seraphis library*[^9] (ie. *updated the legacy balance recovery stuff to support non-default hw devices*)
	
	- dangerousfreedom was still working on the *knowledge proofs*
	
  - (1.2) **on Monero Light Wallet Server[^10]**:
	
	- vtnerd added admin-rest-api functions to monero-lws[^11] and was looking forward to working on Bulletproofs++[^12]
	
  - (1.3) **on statistical analysis, privacy, fungibility, P2Pool research[^13]**:
	
	- Rucknium did *some historical analysis of the P2Pool outputs issue*[^14] and how that affects the privacy of non-mining users
	
	- ishtmus has been *doing housekeeping* on *the fungibility defect labeling framework* and other drafts
	
- **(2) Open discussions**  
  
  - (2.1) **on Seraphis[^8]**:
  
	- UkoeHB attempted to initiate a discussion about the tradeoff/issue of having *seraphis tx implementations in separate structures* versus the alternative of making *every tx component a variant*
  
  - (2.2) **on OSPEAD[^15] and MAGIC Monero Fund[^16]**:			
	
	- Rucknium was still *waiting for ArticMine's feedback* on his draft: *it's been 4 months so at some point I will just have to implement the plan in the document hyc and isthmus gave a green light to the general plan*[^17]
	
	- Rucknium also noted that *OSPEAD will have some blind spots due to lack of C++ support* after *other members of the MAGIC Monero Committee* voted to close mj's fundraiser[^18] due to a *lack of funds raised after two months*
	
	- UkoeHB was wondering *how much code is needed to get OSPEAD in shape*; Rucknium shared a *very rough guess*: *the total number of C++ lines that would need to be written for tasks 1 - 3 there is...maybe 2k*
	
	- isthmus was curious if *the analysis code* could be written in something other than C++; Rucknium thought that *a fast language* like C, Rust, and *even Fortran* would be *nice* and revealed that he is planning to write it in R; hyc noted that Fortran *might actually be most appropriate for the job* 
	
	- rbrunner suggested a *somewhat pragmatic first attempt* to get *'something' better than now out of the door*; Rucknium agreed and underlined that *not having fast code doesn't stop the project*: *It creates some blind spots. I will make it work with the resources that we have.*
	
---

Let me know if you find this kind of report helpful.

Feedback, edits always welcome @[/about](/about#signature).

**-3RA**

---

[^0]: [/monero-research-lab-meeting-18-january-2023/](/monero-research-lab-meeting-18-january-2023/)
[^1]: https://github.com/UkoeHB/
[^2]: https://github.com/Rucknium/
[^3]: https://github.com/rbrunner7/
[^4]: https://github.com/vtnerd/
[^5]: https://github.com/One-horse-wagon/
[^6]: https://github.com/DangerousFreedom1984/
[^7]: https://github.com/mitchellpkt/
[^8]: https://github.com/UkoeHB/Seraphis/
[^9]: [/ukoehb-submits-long-term-seraphis-library-ccs-proposal/](/ukoehb-submits-long-term-seraphis-library-ccs-proposal/)
[^10]: https://github.com/vtnerd/monero-lws/
[^11]: https://github.com/vtnerd/monero-lws/pull/62/
[^12]: https://github.com/Liam-Eagen/BulletproofsPP/
[^13]: https://github.com/Rucknium/misc-research/tree/main/Monero-p2pool-Output-Stats/
[^14]: https://github.com/monero-project/research-lab/issues/109/
[^15]: [/rucknium-ospead-ccs-proposal/](/rucknium-ospead-ccs-proposal/)
[^16]: https://monerofund.org/
[^17]: [/rucknium-publishes-ospead-fully-specified-estimation-plan/](/rucknium-publishes-ospead-fully-specified-estimation-plan/)
[^18]: https://monerofund.org/projects/statistical_attack_reduction/

