---
layout: post
category: story
title: tevador proposes 'radical idea for forward secrecy and instant wallet sync'
description: "tevador has proposed a 'radical idea for forward secrecy and instant wallet sync'."
tags: research
image: 
date: 2022-09-08 20:00
---

tevador[^1] has proposed[^2] a *radical idea for forward secrecy and instant wallet sync*:

> [..] the Diffie-Hellman key exchange will become the weakest point of Monero with respect to forward (or post-quantum) privacy. [..] we can use a 100x faster symmetric key derivation.

The idea is to get rid of the key exchange and that would imply a drastic protocol modification so that every user constructs their own outputs. 

### Advantages

- Smaller public addresses (just 1 pubkey instead of 2-3).
- Bypasses the 10 block lock time.[^3]
- No publicly observable Diffie-Hellman key exchange.[^4]

### Disadvantages

- The recipient learns the e-notes that are being spent.
- Each output needs a separate range proof, which is less efficient.
- The sender needs a private communication channel with the recipient to pass the partial transaction.


Consult MRL issue #106[^2] to learn more about the technical details of this proposal.

---

[^1]: https://github.com/tevador
[^2]: [https://github.com/monero-project/research-lab/issues/106](https://github.com/monero-project/research-lab/issues/106){:target="_blank"}{:rel="nofollow"}
[^3]: https://github.com/monero-project/research-lab/issues/95
[^4]: https://wikiless.org/wiki/Diffie%E2%80%93Hellman_key_exchange
