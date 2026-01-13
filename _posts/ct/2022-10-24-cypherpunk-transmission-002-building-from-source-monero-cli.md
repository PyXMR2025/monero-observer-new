---
layout: post
category: story
title: "CT-002: Building from source - Monero CLI"
description: "CT-002: Building from source usually involves a series of steps, such as compiling, linking, running automated tests and packaging. It can sound like a nightmare for new users, but it certainly is not."
tags: [CT, guides]
image: ct-002-build-source-monero-cli.png
date: 2022-10-24 18:00
---

*This is the second report in the new Cypherpunk Transmission series.*

## Motivation

Anyone can download, run and install binaries that were built by someone else. Relatively few users ever build their own programs, despite the advantages:

- security (no need to trust potentially compromised binaries, rely on source code integrity)
- control (build for any distro, hardware, add/remove options)
- knowledge (become a contributor to FLOSS)

Building from source usually involves a series of steps, such as compiling, linking, running automated tests and packaging. It can sound nightmarish for new users, but it certainly is not.

By getting familiar with the process, you will also be able to start contributing to your favorite open source projects, like Monero.

## Assumptions

* you have (sudo) access to a GNU/Linux machine (Debian/-based)
* 1GB+ free disk space && ~1 hour free time
* you are not scared of *dragons*

## Compiling Monero
 
Let's practice by compiling the official Monero CLI Wallet from source.

### 1. Install dependencies

Paste this long command in a terminal to upgrade packages, install git, and all dependencies:

`sudo apt update && sudo apt upgrade -y && sudo apt install build-essential cmake pkg-config libssl-dev libzmq3-dev libunbound-dev libsodium-dev libunwind8-dev liblzma-dev libreadline6-dev libexpat1-dev libpgm-dev qttools5-dev-tools libhidapi-dev libusb-1.0-0-dev libprotobuf-dev protobuf-compiler libudev-dev libboost-chrono-dev libboost-date-time-dev libboost-filesystem-dev libboost-locale-dev libboost-program-options-dev libboost-regex-dev libboost-serialization-dev libboost-system-dev libboost-thread-dev python3 ccache doxygen graphviz git`

### 2. Get source code

Recursively clone the repository and change directory to source code root:

`git clone --recursive https://github.com/monero-project/monero && cd monero`

### 3. Build

Compile the most stable Monero release:

`git checkout release-v0.18 && make` 

Done! The executable files (including `monerod`, `monero-wallet-cli`) can be found in `build/Linux/release-v0.18/release/bin`. 

*Note that the process might take a while to complete.*

## Observations

- to compile and test the most recent (unstable) software, use `git checkout master && make`
- to enable parallel build, use `make -j<number of threads>` instead of `make` (minimum 1 core, 2GB/thread)
- to build and run optional tests to verify binaries, run `make release-test` (may take hours to complete)
- to build for other distros/hardware and learn more about different build options, consult the official docs
- you can also experiment by building related software from source (ie. Monero GUI, XMRig, P2Pool)
	
Reach out to other Monero contributors if you get any errors or if you discover anything interesting during your journey. 

---

## Feedback

Let me know if you find this helpful and, depending on interest, I will do my best to post a new [Cypherpunk Transmission](/tag/CT/) report every (other?) Monday.

Questions, edits and suggestions are always appreciated @ [/about/](/about/).

**-3RA**

*Credit goes to gnuteardrops from [monero.graphics](https://monero.graphics/){:target="_blank"} for the amazing xkcd graphic. Work and xkcd Script font licensed under [CC BY-NC 3.0](https://github.com/ipython/xkcd-font/blob/master/LICENSE){:target="_blank"}{:rel="nofollow"}.* 

