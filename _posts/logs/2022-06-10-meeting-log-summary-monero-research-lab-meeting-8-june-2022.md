---
layout: post
category: story
title: "Meeting summary: Monero Research Lab, 8 June 2022"
description: "This is a comprehensive summary, with added reference links, of the Monero Research Lab meeting from June 8th, 2022, 1700 UTC."
tags: [logs]
image: 
meeting_name: "Monero Research Lab"
meeting_report: /monero-research-lab-meeting-8-june-2022
meeting_date: "2022-06-08"
meeting_logs: /assets/logs/220608-mrl.log
---

This is a comprehensive summary, with added reference links, of the MRL meeting[^0] from June 8th 2022, 1700 UTC.

### Logs

The raw, unedited, full log file for this meeting: 

[220608-mrl.log](/assets/logs/220608-mrl.log) (65 lines)

### Summary

*Note: it is possible that some relevant information may be missing from this summary; read the full log file for the complete, unedited discussion.*

- **Participants**: 8 (*UkoeHB[^1], rbrunner[^2], jberman[^3], Rucknium[^4], xmr-ack[^5], ooo123ooo1234567[^6], ArticMine[^7], cryptogrampy[^8]*)

- **(1) Updates**
	
	- (1.1) **on Monero fixes**:
	
	- jberman has been working on PR 7760[^9] exclusively (WIP branch[^10])
	
	- (1.2) **on statistical analysis and the decoy selection algorithm**:
	
	- Rucknium did some BCH-related work which can be re-purposed to improve https://monero.com/charts/shielded, was working alongside mj to *re-implement the C++ decoy selection algorithm in Python*[^11] and expects to have a formal specification for the DSA *soon*
  
  - (1.3) **on Seraphis[^12]**:
  
  - UkoeHB was working on the enote scanning workflow for seraphis
  
- **(2) Open discussions**  
  
  - (2.1) **on producing deanonymized dataset of stagenet Monero transactions[^13]**:
  
  - xmr-ack reported fixing a memory leak in their script which processes the collected dataset, added some multiprocessing in places to speed up the undersampling process and expects to have the new version of the preliminary dataset soon, on which to start retraining models on
  
  - (2.2) **on decoy selection improvements**:
  
  - Rucknium noted that Monero's weighting of the decoy selection by number of txs in each block would in fact **not** mitigate the issue with a spike in speculative activity shifting the real spend distribution, contrary to what he previously thought; UkoeHB agreed
  
  - (2.3) **on the MRL meeting agenda**:
  
  - UkoeHB proposed removing agenda items 6 (*Examine sample size and random seed matters in Monero's unit tests*[^14]'[^15]) and 7 (*Multisig Drijvers attack mitigation*[^16]'[^17]); Rucknium agreed
  
  - (2.4) **on Seraphis concerns**:
  
  - Rucknium mentioned Monero community vaguely defined concerns[^18] about additional view key options with Seraphis; UkoeHB agreed that there is *no ideal solution* and that it is important to discuss the pros and cons that go into design decisions, hoping that his recent comment[^19] helped clear up any confusion
  
  - rbrunner and Rucknium agreed that the topic itself is *controversial* and *tricky*
  
  - ArticMine chimed in to state that he prefers *the Jamtis[^20] approach than relying on heuristics*, as the heuristics approach would favor blockchain surveillance companies
  
  - cryptogrampy proposed discussing the concept of *subscription services / user accounts*, but wasn't yet ready to explain to UkoeHB specifically how such a workflow would look like
  
  - Rucknium provided some examples[^21]'[^22]'[^23]'[^24] to cryptogrampy, for inspiration
  
  - (2.5) **on MRL visibility and the MAGIC Monero Fund**:
  
  - Rucknium suggested that it would be nice to somehow get more visibility for MRL on the IACR jobs board[^25]; UkoeHB suggested setting *a large bounty for it*
  
  - Rucknium didn't feel like the MAGIC Monero Fund[^26] had *enough funds to be looking for lots of grant applications*
  
  - xmr-ack proposed funding *a prize for a Kaggle competition which would attract high quality datascience talent from all over to look into Monero*, once their current MAGIC grant[^27] is finished; Rucknium agreed that Kaggle is a good idea
  
---

Let me know if you find this kind of report helpful.

Feedback, edits always welcome @[/about](/about#signature).

**-3RA**

---

[^0]: https://github.com/monero-project/meta/issues/712
[^1]: https://github.com/UkoeHB
[^2]: https://github.com/rbrunner7/
[^3]: https://github.com/j-berman
[^4]: https://github.com/Rucknium
[^5]: https://github.com/ACK-J/
[^6]: @ooo123ooo1234567:matrix.org
[^7]: https://libredd.it/user/ArticMine
[^8]: https://github.com/CryptoGrampy
[^9]: https://github.com/monero-project/monero/pull/7760
[^10]: https://github.com/j-berman/monero/commits/7760-streamlined-logic
[^11]: https://github.com/Rucknium/monero-mrl-mj/tree/master/decoy
[^12]: https://github.com/UkoeHB/Seraphis
[^13]: [/ack-j-may-2022-magic-grants-research-report/](/ack-j-may-2022-magic-grants-research-report/)
[^14]: https://libera.monerologs.net/monero-dev/20211018#c39593
[^15]: https://libera.monerologs.net/monero-research-lab/20211018
[^16]: https://github.com/UkoeHB/drijvers-multisig-tech-note
[^17]: https://github.com/haveno-dex/haveno/issues/103
[^18]: https://libredd.it/v4wq1g/
[^19]: https://github.com/monero-project/research-lab/issues/92#issuecomment-1146810255
[^20]: https://gist.github.com/tevador/50160d160d24cfc6c52ae02eb3d17024
[^21]: https://read.cash
[^22]: https://noise.cash
[^23]: https://memo.cash
[^24]: https://member.cash
[^25]: https://www.iacr.org/jobs/
[^26]: https://magicgrants.org/Monero-Fund/
[^27]: [/magic-monero-fund-committee-funds-first-research-proposal/](/magic-monero-fund-committee-funds-first-research-proposal/)
