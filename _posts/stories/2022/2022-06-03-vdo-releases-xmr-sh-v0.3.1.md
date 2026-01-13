---
layout: post
category: story
title: "vdo releases 'xmr.sh' v0.3.1"
description: "vdo has released v0.3.1 of 'xmr.sh', a Docker-based single command Monero node bootstrapper script."
tags: mining
image: xmr-sh.png
date: 2022-06-03 18:00
---

vdo[^1] has released v0.3.1[^2] of *xmr.sh*[^3], a Docker-based single command Monero node bootstrapper script:

> xmr.sh script wizard sets up a new server running a monero node daemon with Docker compose, with your choice of SSL certificates for your domain, network selection, a Tor hidden service, Grafana dashboard and more.

### Changes

- Grafana dashboard
- Local volumes
- Uninstall script

The script makes it easy for anyone to run a Monero node on any server running Debian 11, Ubuntu Focal or Fedora 36, with a single command:

```
sudo bash -c "$(curl  -sLSf https://get.xmr.sh)"
```

Note that for a more secure production deployment, it is recommended to clone the source code and proceed manually.

To learn more about the project, consult the project's code repository[^4] and FAQ[^5] section.

---

[^1]: https://github.com/vdo
[^2]: [https://github.com/vdo/xmr.sh/releases/tag/v0.3.1](https://github.com/vdo/xmr.sh/releases/tag/v0.3.1){:target="_blank"}{:rel="nofollow"}
[^3]: [https://xmr.sh/](https://xmr.sh/){:target="_blank"}
[^4]: https://github.com/vdo/xmr.sh
[^5]: https://github.com/vdo/xmr.sh/wiki/FAQ
