---
layout: post
category: story
title: "hinto-janaiyo releases 'monero-gpg' script"
description: "hinto-janaiyo has released the first version of 'monero-gpg', a Bash script that GPG-signs a message or a file and includes the current Monero block stats at the bottom."
tags: services
image: 
date: 2022-05-25 21:00
---

hinto-janaiyo[^1] has released the first version (v1[^2]) of *monero-gpg*[^3], a Bash script that GPG-signs a message or a file and includes the current Monero block stats at the bottom:

> A cool by-product of Proof of Work is that you can use block hashes as a sort of time-minimum. If you include a block's hash in a message, that message at the bare minimum was created when that block was first relayed to the network. 

## Usage

`./monero-gpg <your_file> [monero-rpc ip]`

## Monero block info attached

```
=== monero info ===
[ height ] <height>   # height of most recent block
[  time  ] <time>     # timestamp of block (always UTC)
[  hash  ] <hash>     # overall hash of block (not PoW hash)
```

## Example

```
-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

eec687333fa31cbf116ad4f9eeeec0364dd90ce5dcc1376bea59277e6086a92b  monero-gpg

=== monero info ===
[ height ] 2631227
[  time  ] Wed May 25 01:52:39 PM UTC 2022
[  hash  ] dd9957a60db2f740b63299b66a30a5556a86793ec0222272c279866d471b6661
-----BEGIN PGP SIGNATURE-----

iQIzBAEBCAAdFiEEIZWO6UWYAoL8uEnI10g/bKJ9Gx0FAmKOOC0ACgkQ10g/bKJ9
Gx11ExAAmdSm8WyPGBrR3HeFhlQAwAVEA+ve0wWWStzLEMSawa9kjG/G6etUCKjU
I/KFy6kxxYlKhgFH8onduIhmA1ENvBqCQhXbgEt1v2TW/ipSVmBX5dP0UEZ8YJVM
6agtSXUe5bSqSaxGdDLyFIrgNCPB63v8Bg0lSHAN6D276022ZIFy2feCx56cbuzw
RBGxSfISvDT83+D92ceKqiIba8sxGuh5zoVyOjD84L7dsar0AKbeVvamvhYXDgM2
3/O7Q0lrGeaO2lAlHiYpoEKrzDKioaBXmnlOSh8rI6VTAvfZ7duHuTOaDBaMIyHJ
eTzERkJwv3xC2gzm+Rk+9fibJRY+8ozkzIO7zwH7OArhaSfcEyL2NVdK5Mu9QsaT
sGOVb83nH4BBkWFUOZTTHaav6WVHy9Let6lERecrj6ebGtxLUTVOTRXA8+UdQf7q
lzLWHaDA+HASYnnaLsEGfudMgvUlfCwtyn7LA9HesOYrbDWK5Lk2wPHbS/13ZGPA
l31htWOq0xDNDg9oomQOICCPUxUSpS+36qfm9Db+xsiiP7yCsHlZYNf7okP3vUb6
lW0e118X9hS+8qKlvcHN94RTPG7A+zRQDZF4nkneZQB1V2b2uiw/C3HFB5OuHrrz
ecfWA05uD69Zo1+1ZwFCpj+PNG0NvtgJ2chM+fz4MPJOLMlC+Co=
=oKG/
-----END PGP SIGNATURE-----
```

Consult the Github repository *README.md*[^4] for more examples. 

Inspect the source code[^5] and verify the signature of *monero-gpg* before using the script. 

---

[^1]: https://github.com/hinto-janaiyo
[^2]: [https://github.com/hinto-janaiyo/monero-gpg/releases/tag/v1](https://github.com/hinto-janaiyo/monero-gpg/releases/tag/v1){:target="_blank"}{:rel="nofollow"}
[^3]: https://github.com/hinto-janaiyo/monero-gpg
[^4]: https://github.com/hinto-janaiyo/monero-gpg#readme
[^5]: https://github.com/hinto-janaiyo/monero-gpg/blob/main/monero-gpg
