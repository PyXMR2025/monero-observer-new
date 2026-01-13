---
layout: post
category: story
title: busyboredom releases AcceptXMR v0.12.0
description: "busyboredom has released v0.12.0 of the Monero payment gateway library, 'AcceptXMR'."
tags: services
image: 
date: 2023-03-19 20:00
---

busyboredom[^1] has released v0.12.0[^2] of the Monero payment gateway library, *AcceptXMR*[^3]:

> This marks the last of the "prerequisites" to beginning the "Standalone AcceptXMR" CCS work (BusyBoredom[^4])

### Changes overview

```
* Added:
- Sqlite store as a reliable alternative to Sled.
- Implement Ord and PartialOrd for InvoiceId.
- InvoiceStorage trait [..]
* Changed:
- Increase MSRV to 1.65.
- Make PaymentGateway generic over InvoiceStore.
- Add additional store argument to PaymentGateway::builder [..]
* Removed:
- Iterator implementation on Subscriber.
- db_path() method of PaymentGateway [..]
```

To learn more about the project, consult the README[^5] file, test the updated demo[^6], and read the associated CCS proposal[^7] that is currently looking for funding[^8].

*Note that the library is 'young and unproven', use it at your own risk.*

---

[^1]: https://github.com/busyboredom
[^2]: [https://github.com/busyboredom/acceptxmr/releases/tag/v0.12.0](https://github.com/busyboredom/acceptxmr/releases/tag/v0.12.0){:target="_blank"}{:rel="nofollow"}
[^3]: https://github.com/busyboredom/acceptxmr
[^4]: https://libera.monerologs.net/monero-community/20230319#c221802
[^5]: https://github.com/busyboredom/acceptxmr#readme
[^6]: [https://busyboredom.com/projects/acceptxmr](https://busyboredom.com/projects/acceptxmr){:target="_blank"}
[^7]: [/busyboredom-ccs-proposal-standalone-acceptxmr-wordpress-support/](/busyboredom-ccs-proposal-standalone-acceptxmr-wordpress-support/)
[^8]: [https://ccs.getmonero.org/proposals/busyboredom-standalone-acceptxmr.html](https://ccs.getmonero.org/proposals/busyboredom-standalone-acceptxmr.html){:target="_blank"}
