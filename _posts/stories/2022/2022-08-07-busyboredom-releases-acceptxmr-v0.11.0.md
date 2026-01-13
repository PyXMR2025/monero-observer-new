---
layout: post
category: story
title: busyboredom releases AcceptXMR v0.11.0
description: "busyboredom has released v0.11.0 of the Monero payment gateway library, 'AcceptXMR'."
tags: services
image: 
date: 2022-08-07 22:00
---

busyboredom[^1] has released v0.11.0[^2] of the Monero payment gateway library, *AcceptXMR*[^3]:

> New AcceptXMR version is out with lots of little quality-of-life improvements and features (including daemon login support)[^4]

## Changelog overview

- Add a `status()` method to `PaymentGateway` for determining whether the `PaymentGateway` is already running.
- Add TLS support.
- Add daemon login support.
- Replace Reqwest with Hyper to improve compile time.
- Use primary address instead of public spend key when creating `PaymentGateways`.
- Fix a bug where a change in the order of transactions in the txpool would cause all relevant invoices to update, even though no new relevant transactions had been added.
- [..]

To learn more about the project, consult the code repository README.md[^5] file and the updated demo[^6] on busyboredom's website.

Note that the library is *young and unproven*, use it at your own risk.

---

[^1]: https://github.com/busyboredom
[^2]: [https://github.com/busyboredom/acceptxmr/releases/tag/v0.11.0](https://github.com/busyboredom/acceptxmr/releases/tag/v0.11.0){:target="_blank"}
[^3]: https://github.com/busyboredom/acceptxmr
[^4]: https://matrix.to/#/!ZdVDBBouJUyQVsewKn:monero.social/$ls78IT6y-11NY5NYu7I9PqzIQkgsI01aan88yfMHESI?via=monero.social
[^5]: https://github.com/busyboredom/acceptxmr#readme
[^6]: https://busyboredom.com/projects/acceptxmr 
