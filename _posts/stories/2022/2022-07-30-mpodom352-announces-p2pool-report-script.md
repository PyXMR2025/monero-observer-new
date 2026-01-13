---
layout: post
category: story
title: "MPodom352 announces 'p2pool-report' Python script which generates P2Pool mining revenue reports"
description: "MPodom352 has announced the release of 'p2pool-report', an open source Python script which generates P2Pool mining revenue reports (.odt/.pdf/.png)."
tags: [mining, services]
image: p2pool-report.png
date: 2022-07-30 18:00
---

MPodom352[^1] has announced[^2] the release of *p2pool-report*[^3], an open source Python script which generates P2Pool[^4] mining revenue reports (.odt/.pdf/.png):

> I recently made a script which generates a .pdf report of your p2pool mining revenue. [..] It's currently on Github, licensed under GPLv3+/CC-BY-SA 4.0 for the template. (.odt/.pdf)

### Functionality

```
Import data from p2pool.observer's api and p2pool.log.
Automatically fill in blanks and generate a .pdf report.
```

The script is currently lacking some features like uncle block stats, HR estimation, XMR to USD revenue conversion and others.

Consult the project's README[^5] file for more information.

If you are familiar with Python, inspect the source code[^6] before using the script.

---

[^1]: https://libredd.it/user/MPodom352
[^2]: [https://libredd.it/wbz7a0](https://libredd.it/wbz7a0){:target="_blank"}{:rel="nofollow"}
[^3]: [https://github.com/AsBenDoge/p2pool-report](https://github.com/AsBenDoge/p2pool-report){:target="_blank"}{:rel="nofollow"}
[^4]: https://p2pool.io
[^5]: https://github.com/AsBenDoge/p2pool-report#readme
[^6]: https://github.com/AsBenDoge/p2pool-report/blob/main/report.py
