---
layout: post
category: story
title: "Monero CLI v0.18.2.1 'Fluorine Fermi' tagged"
description: "The official Monero CLI v0.18.2.1 'Fluorine Fermi' has been tagged and the release binaries should be out soon. The GUI version will shortly be tagged as well."
tags: [dev, wallets]
date: 2023-03-27 21:00
last_modified_at: 2023-04-04
---

The official Monero CLI v0.18.2.1 *Fluorine Fermi*[^1] has been tagged and the release binaries should be out soon. The GUI[^2] version will be tagged shortly.

### Release overview

```
15 commits
30 files changed
7 contributors
```

Note that this point release is a direct response to Monero ordinals. It includes tevador's patch that limits the size of `tx_extra` to ~1KB, as previously reported[^3].

The full list of changes for this point release is available on Github[^4].

Contributors are encouraged to share the results of their deterministic build processes[^5] by making a pull request to the *monero-project/gitian.sigs*[^6] repository.

*This is an ongoing story and the report will be updated when new information is available.*

---

**Update 23/3/29: release delayed (PRs: #8811, #8813)[^7]'[^8].**

**Update 23/4/4: Monero CLI/GUI v0.18.2.2 tagged[^9]'[^10].**

---

[^1]: [https://github.com/monero-project/monero/releases/tag/v0.18.2.1](https://github.com/monero-project/monero/releases/tag/v0.18.2.1){:target="_blank"}{:rel="nofollow"}
[^2]: https://github.com/monero-project/monero-gui/tags
[^3]: [/monero-to-block-nfts-upcoming-release/](/monero-to-block-nfts-upcoming-release/)
[^4]: [https://github.com/monero-project/monero/compare/v0.18.2.0...v0.18.2.1](https://github.com/monero-project/monero/compare/v0.18.2.0...v0.18.2.1){:target="_blank"}{:rel="nofollow"}
[^5]: [https://github.com/monero-project/monero/tree/master/contrib/gitian#gitian-building](https://github.com/monero-project/monero/tree/master/contrib/gitian#gitian-building){:target="_blank"}{:rel="nofollow"}
[^6]: https://github.com/monero-project/gitian.sigs/
[^7]: https://github.com/monero-project/monero/pull/8811
[^8]: https://github.com/monero-project/monero/pull/8813
[^9]: [https://github.com/monero-project/monero/releases/tag/v0.18.2.2](https://github.com/monero-project/monero/releases/tag/v0.18.2.2){:target="_blank"}{:rel="nofollow"}
[^10]: [https://github.com/monero-project/monero-gui/releases/tag/v0.18.2.2](https://github.com/monero-project/monero-gui/releases/tag/v0.18.2.2){:target="_blank"}{:rel="nofollow"}
