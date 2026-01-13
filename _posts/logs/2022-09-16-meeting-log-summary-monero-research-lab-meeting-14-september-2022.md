---
layout: post
category: story
title: "Meeting summary: Monero Research Lab, 14 September 2022"
description: "This is a comprehensive summary, with added reference links, of the Monero Research Lab meeting from September 14th, 2022, 1700 UTC."
tags: [logs]
image: 
meeting_name: "Monero Research Lab"
meeting_report: /monero-research-lab-meeting-14-september-2022/
meeting_date: "2022-09-14"
meeting_logs: /assets/logs/220914-mrl.log
date: 2022-09-16 21:00
---

This is a comprehensive summary, with added reference links, of the MRL meeting[^0] from September 14th 2022, 1700 UTC.

### Logs

The raw, unedited, full log file for this meeting: 

[220914-mrl.log](/assets/logs/220914-mrl.log) (54 lines)

### Summary

*Note: it is possible that some relevant information may be missing from this summary; read the full log file for the complete, unedited discussion.*

- **Participants**: 9 (*dangerousfreedom[^1], one-horse-wagon[^2], jberman[^3], rbrunner[^4], Rucknium[^5], ajs_[^6], UkoeHB[^7], xmrack[^8], chch3003[^9]*)

- **(1) Updates**
	
	- (1.1) **on Monero inflation tools[^10] and Seraphis[^11]**:
	
	- dangerousfreedom finished scanning the blockchain: *bp and clsag era*, using his own Rust tools, and is planning to create *auditability proofs to seraphis* and help develop a *minimum useful seraphis wallet*[^12]
	
	- dangerousfreedom confirmed that no new anomalies turned up while scanning, thanks to Bulletproofs
	
	- (1.2) **on statistical analysis / OSPEAD[^13]**:
	
	- Rucknium included the statement: "*I consider exploration of ring classification to be out of scope of this OSPEAD CSS.*" into a newly added section on classification of rings by Decoy Selection Algorithm. 
	
	- Rucknium announced that *the disclosable part of OSPEAD fully specified plan* will be released as soon as the MAGIC Monero Fund campaign[^14] to raise funds for mj-xmr's C++ work for OSPEAD begins, probably *next week*
		
	- (1.3) **on Monero dev work, Seraphis and Jamtis**:
	
	- jberman was mostly doing dev work for the past week, fixing various bugs[^15], and is planning to complete *background sync mode* next and then prepare to *dive* into Seraphis/Jamtis[^16] along with rbrunner and dangerousfreedom 
	
	- rbrunner invited contributors to join the *#no-wallet-left-behind:haveno.network*[^17] Seraphis/Jamtis project[^18] Matrix room
	
	- UkoeHB continued their work on the Seraphis library[^19] *legacy integration* and a *non-multisig* working demo could be ready *by next week*
  	
	- (1.4) **on Monero's deterministic build process[^20]**:
	
	- one-horse-wagon was *intently looking* for ways to *increase the number of deterministic builders before a code version is released*, but concluded that *the process cannot be made any more easier*

	- (1.5) **on Monero Konferenco 2023[^21] and MRL recruitment**:

  - ajs_ and a few others *started making plans for MoneroKon 2023* and would like to seek *technical co-sponsorship with IEEE Computer Society*[^22] in an effort to attract more researchers to the conference and help with *MRL recruitment efforts*[^23]
 
  - (1.6) **on Monero research papers**:
  
  - Rucknium mentioned that xmrack's *Lord of the Rings: An Empirical Analysis of Monero's Ring Signature Resilience to Artifically Intelligent Attacks* (PDF[^24], report[^25]) MAGIC-funded research paper *is making the rounds*.

- **(2) Open discussions**  
  
  - (2.1) **on Monero funding systems**:
  
  - Rucknium explained the need for both the CCS[^26] and MAGIC Grant's Monero Fund[^27] to chch3003
  
  - (2.2) **on quantum resistance**:
  
  - one-horse-wagon expressed concerns about the coming era of quantum computers: *Big corporations and governments will have them. The MRL will not at least initally.*
  
  - dangerousfreedom thought that *quantum computers are so far from being a threat* and proposed exploring the *algorithms that are in the final phase of NIST*; tevador linked to their *Zero-cost post-quantum mitigations for Seraphis*[^28] draft
  
---

Let me know if you find this kind of report helpful.

Feedback, edits always welcome @[/about](/about#signature).

**-3RA**

---

[^0]: [/monero-research-lab-meeting-14-september-2022/](/monero-research-lab-meeting-14-september-2022/)
[^1]: https://github.com/DangerousFreedom1984/
[^2]: @one-horse-wagon:matrix.org
[^3]: https://github.com/j-berman/ 
[^4]: https://github.com/rbrunner7/
[^5]: https://github.com/Rucknium/
[^6]: https://repo.getmonero.org/ajs
[^7]: https://github.com/UkoeHB/
[^8]: https://github.com/ACK-J/
[^9]: @chch3003:matrix.org 
[^10]: https://github.com/DangerousFreedom1984/monero_inflation_checker
[^11]: https://github.com/UkoeHB/Seraphis
[^12]: [/dangerousfreedom1984-ccs-proposal-moneroinflation-seraphis-jamtis/](/dangerousfreedom1984-ccs-proposal-moneroinflation-seraphis-jamtis/)
[^13]: [/rucknium-ospead-ccs-proposal/](/rucknium-ospead-ccs-proposal/)
[^14]: https://github.com/MAGICGrants/Monero-Fund/issues/21
[^15]: https://github.com/monero-project/monero/commits?author=j-berman&since=2022-09-01&until=2022-09-14
[^16]: https://gist.github.com/tevador/50160d160d24cfc6c52ae02eb3d17024
[^17]: https://matrix.to/#/#no-wallet-left-behind:haveno.network
[^18]: [/rbrunner7-calls-dedicated-effort-establish-migration-path-monero-seraphis-jamtis-hf/](/rbrunner7-calls-dedicated-effort-establish-migration-path-monero-seraphis-jamtis-hf/)
[^19]: https://github.com/seraphis-migration/wallet3/issues/8
[^20]: https://github.com/monero-project/monero/blob/master/contrib/gitian/README.md
[^21]: https://monerokon.com/
[^22]: https://www.computer.org/
[^23]: https://leddit.xyz/pkg3d6/
[^24]: https://github.com/ACK-J/Monero-Dataset-Pipeline/blob/main/Lord_of_the_Rings__An_Empirical_Analysis_of_Monero_s_Ring_Signature_Resilience_to_Artificially_Intelligent_Attacks.pdf
[^25]: [/ack-j-completes-magic-funded-research-proposal/](/ack-j-completes-magic-funded-research-proposal/)
[^26]: https://ccs.getmonero.org/
[^27]: https://magicgrants.org/funds/monero
[^28]: https://gist.github.com/tevador/23a84444df2419dd658cba804bf57f1a

