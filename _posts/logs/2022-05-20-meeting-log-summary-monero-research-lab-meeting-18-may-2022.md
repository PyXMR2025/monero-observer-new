---
layout: post
category: story
title: "Meeting summary: Monero Research Lab, 18 May 2022"
description: "This is a comprehensive summary, with added reference links, of the Monero Research Lab meeting from May 18th, 2022, 1700 UTC."
tags: [logs]
image: 
meeting_name: "Monero Research Lab"
meeting_report: /monero-research-lab-meeting-18-may-2022
meeting_date: "2022-05-18"
meeting_logs: /assets/logs/220518-mrl.log
---

This is a comprehensive summary, with added reference links, of the MRL meeting[^0] from May 18th 2022, 1700 UTC.

### Logs

The raw, unedited, full log file for this meeting: 

[220518-mrl.log](/assets/logs/220518-mrl.log) (121 lines)

### Summary

*Note: it is possible that some relevant information may be missing from this summary; read the full log file for the complete, unedited discussion.*

- **Participants**: 10 (*UkoeHB[^1], jberman[^2], mj-xmr[^3], Rucknium[^4], kayabaNerve[^5], merope[^6], hyc[^7], dangerousfreedom[^8], moneromooo[^9], jeffro256[^10]*)

- **(1) Updates**

	- (1.1) **on the decoy algorithm:**
	
	- mj-xmr has delivered the first working Python implementation of the Gamma Picker algo[^11] and plans on forwarding the finalized work to Rucknium by Sunday
	
	- (1.2) **on Seraphis and Jamtis**:
	
	- UkoeHB has implemented a robust input selection solver for Seraphis, pushed multisig PRs forward a bit, updated Jamtis to support self-spends better (e.g. churn) and plans to finally implement the full enote scanning workflow
	
	- (1.3) **on statistical analysis (re: Minexmr fee increase[^12])**:
	
	- Rucknium decided to *go with Vector Autoregression*, essentially treating the fee increase as an *exogenous shock* and fiat/XMR exchange rate and hashing difficulty as endogenous
  
  - (1.4) **on ring signatures**:
  
  - dangerousfreedom has been learning about and implemented (in Python) Bulletproofs and CLSAG as it is in the C++ code; they are also continuing to scan the blockchain with the LibSodium library
  
  - (1.5) **on optimizations and fixes**:
  
  - jberman has finished up patching relatively trivial tor/i2p daemon connectivity bugs, reviewed/provided guide to rbrunner on completing 8076[^13], and is moving back over to reviewing 7760[^14]
  
  - rbrunner announced that they will start to work on 8076 shortly
  
- **(2) Reducing the 10 block lock discussion[^15]**  
  
  - UkoeHB and moneromooo agreed that *it will be difficult to evaluate whether changing the block limit is a good idea*
  
  - Rucknium mentioned the active attacker scenario in UkoeHB's MRL issue #95, triggering a discussion about different potential attack vectors
  
  - moneromooo mentioned Townforge[^16] and how players can *freely move money between output based and balance based* and there is no lock period for balance based transactions
  
  - no clear consensus was reached regarding this proposal, due to complexity of the issue and the timing of such a change in the context of the current pool situation 
  
---

Let me know if you find this kind of report helpful.

Feedback, edits always welcome @[/about](/about#signature).

**-3RA**

---

[^0]: https://github.com/monero-project/meta/issues/706
[^1]: https://github.com/UkoeHB
[^2]: https://github.com/j-berman
[^3]: https://github.com/mj-xmr
[^4]: https://github.com/Rucknium
[^5]: https://github.com/kayabaNerve
[^6]: @merope:matrix.org
[^7]: https://github.com/hyc
[^8]: https://github.com/DangerousFreedom1984
[^9]: https://github.com/moneromooo-monero
[^10]: https://github.com/jeffro256
[^11]: https://github.com/mj-xmr/monero-mrl-mj/blob/decoy/decoy/README.md#results
[^12]: [/minexmr-top-monero-pool-hashrate-drops-from-50-to-38-percent/](/minexmr-top-monero-pool-hashrate-drops-from-50-to-38-percent/)
[^13]: https://github.com/monero-project/monero/pull/8076 
[^14]: https://github.com/monero-project/monero/pull/7760
[^15]: https://github.com/monero-project/research-lab/issues/95
[^16]: https://www.townforge.net/




