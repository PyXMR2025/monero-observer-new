---
layout: post
category: story
title: "LocalMonero discovers malicious browser extension targeting XMR users"
description: "LocalMonero has discovered a malicious browser extension disguised as 'Google Sheets 2.1' that was targeting XMR users on their platform."
tags: security
image: localmonero-trade-malware-demo.png
date: 2022-10-20 21:00
---

LocalMonero[^1] has discovered[^2] a malicious browser extension disguised as *Google Sheets 2.1* that was targeting XMR users on their platform:

> [..] a user reported to us that the address that they specified when opening a trade wasn't actually the address to which the coins were sent to. [..] this doesn't work like the clipboard-replacing malware we've all heard about. Instead, **this malware actually waits until you hit the submit button before replacing the address in a way that's hidden from you unless it errors out.**

The affected user was using the Chrome browser on a Windows machine that was infected with malware (*Trojan.BitCoinMiner*) undetected by a Windows Defender scan, but reported by *MalwareBytes*.

According to the LocalMonero team, *a malicious Windows system task that was designed to run that [vbscript] file* was trying to install the browser extensions on any Chromium-based browsers.

### Not affected

- Firefox-based browsers (including Tor Browser)
- browser launched in private/incognito mode with all extensions disabled
- website accessed in *NoJS* mode (even on a compromised browser)

### Security tips

- never open unknown links and never trust unknown files
- use Whonix/Tails/Qubes/Linux instead of Windows
- LocalMonero recommends using the *Ungoogled Chromium* browser

Read the full post[^2] and watch the user's video recording[^3] to better understand how this type of malware operates.

*This is an ongoing story and the report will be updated when new information is available.*

---

[^1]: https://localmonero.co
[^2]: [https://libreddit.de/y8xmph](https://libreddit.de/y8xmph){:target="_blank"}{:rel="nofollow"}
[^3]: https://matrix.agoradesk.com/_matrix/media/r0/download/agoradesk.com/MBmDdubTdHUIZVDDjQfwoudW
