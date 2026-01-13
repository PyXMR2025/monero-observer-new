---
layout: post
category: story
title: "Cheat Sheet: Monero CLI Wallet"
description: "Using the Monero CLI Wallet to create subaddresses, transfer funds, view transactions, connect to remote nodes, and other basic tasks is not complicated at all. Hopefully this cheat sheet can showcase that fact and encourage more users to use the CLI."
tags: [guides, pinned]
image: 
date: 2022-06-07 23:00
---

## Motivation

Using the Monero CLI Wallet to create subaddresses, transfer funds, view transactions, connect to remote nodes, and other basic tasks is not complicated at all. 

Hopefully this cheat sheet can showcase that fact and encourage more users to use the CLI.

## Assumptions

- the Monero CLI Wallet is already installed on your machine (if not, consult my previous [Linux install guide](/verify-install-update-monero-cli-wallet-linux-guide/))

## Cheat Sheet

*Note that this is a WiP.*

---

**Show all addresses**

*`address all`*

Example:

```
address all
```

That's it.

---

**Create a new subaddress**

*`address new [<label text with white spaces allowed>]`*

Examples:

```
address new
```

The command above creates a new XMR subaddress with no label.

```
address new gift
```

And this one creates a new XMR subaddress labeled *gift*.

---

**Display balance**

*`balance`*

Example:

```
balance
```

Done.

---

**Transfer funds**

*`transfer <address> <amount>`*

Example:

```
transfer 867TAc58FK2ScH6Kyz9VSJZYSKGbyGfRiJB7M7yV2qEdamdQsxJafEbXxp6QoAkVCjjarKTbsmsZuEm1XymGmSquRdZnN2C 0.035
```

This command transfers 0.035 XMR to Monero Observer's tips address.

---

**Show transactions**

*`show_transfers [in|out|pending|failed|pool]`*

Examples:

```
show_transfers
```

This command lists all transactions, regardless of their status.

```
show_transfers pending
```

This command lists all transfers that are currently pending.

---

**Connect to a remote node**

*`[torsocks] ./monero-wallet-cli --daemon-address <address>:<port>`*

Example:

```
./monero-wallet-cli --daemon-address http://p2pmd.xmrvsbeast.com:18081
```

This command starts the wallet and connects to xmrvsbeast's clearnet node.

Example:

```
torsocks ./monero-wallet-cli --daemon-address 6dsdenp6vjkvqzy4wzsnzn6wixkdzihx3khiumyzieauxuxslmcaeiad.onion:18081
```

And this one connects to boldsuck's remote .onion node. Note that tor/torsocks needs to be installed first.

---

**Setting: toggle password on incoming transfers**

`set ask-password [0|1]`

Example:

*`set ask-password 0`*

This command disables the setting and you will not be asked to enter the wallet password whenever you receive a transfer.

---

**Setting: toggle inactivity lock**

`set inactivity-lock-timeout [0|1]`

Example:

*`set inactivity-lock-timeout 0`*

This command disables the setting and the wallet will not automatically lock.

---

**Synchronize wallet**

`refresh`

Example:

*`refresh`*

That's all you need to do to refresh the wallet, if it is *[out of sync]* with the Monero network.

---

**Close wallet**

`exit`

Example:

*`exit`*

This command safely closes the wallet. It is not recommended to substitute that for *CTRL+C* / close terminal.

---


/END (WiP)

### Feedback

Let me know if you find this helpful and I will maintain and potentially create other cheat sheets in the future. 

Questions, edits and suggestions are always appreciated @ [/about](/about/#signature).

**-3RA**

