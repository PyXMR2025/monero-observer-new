---
layout: post
category: story
title: "CT-001: Threat modeling demystified"
description: "CT-001: Threat modeling demystified. Everything is a trade-off, tools and techniques are ephemeral, and that's why threat modeling is key. A list of the most probable threats to your security and privacy endeavors shouldn't be too hard to create."
tags: [CT, guides]
image: ct-001-complexity-is-great.png
date: 2022-10-17 21:00
---

*This is the first report in the new Cypherpunk Transmission series.*

## Motivation

There is no such thing as *full* privacy and security. It's impossible to protect all your assets from everyone all the time. 

Everything is a trade-off, tools and techniques are ephemeral, and that's why threat modeling is key. 

A list of the most probable threats to your security and privacy endeavors shouldn't be too hard to create.

## Assumptions

* you care *enough* about privacy and security

## Threat modeling A-T-F-R-M
 
```
(A)ssets - (T)hreats - (F)ails - (R)isks - (M)itigations
```

Let's take a closer look at each step:

#### (A) Assets

What assets do you want to protect? Identify assets worth protecting.

#### (T) Threats

Who do you want to protect the assets from? Which *adversaries* might be interested in those assets? Speculate.

#### (F) Fails

How bad are the consequences if you fail to protect the assets from those threats? What capabilities does your adversary have?

#### (R) Risks

What is the probability that any of those *fail scenarios* might happen?

#### (M) Mitigations

How much convenience are you willing to sacrifice in order to prevent the fail scenarios? What are you technical and financial constraints?

## Example scenario

*Jane (34, married with kids, works at small company)*

> Jane thinks she might have a rare illness and doesn't want her family, friends and co-workers to find out about it at this point.

(A)

- **medical search queries**

(T)
 
- **interested**: family, friends, co-workers
- **indirectly interested**: big tech/search engines
- not really interested: ISP, OS, hackers

(F) 

- family has access to Jane's devices (laptop, phone)
- friends and co-workers can see her public social media stuff
- search engines can see the queries and her IP address
- the company might be able to get a hold of her search queries via a third party
- ISP/OS has the capability to inspect/capture/profile her traffic
- someone might be able to place a keylogger on her machine
- **fail**: people might change their behavior towards Jane 
- **fail**: she might lose her job
- **fail**: blackmail is a possibility

(R) 

- **very high probability**: friends see her social media posts related to the medical searches
- **very high probability**: family member accidentally finds browser with search query open
- **high probability**: family member sees targeted (medical) ads on her social media
- **high probability**: suspicious husband looks at the browser history
- **high probability**: the search engine shares her data with third parties
- very low probability: the ISP or OS shares traffic with her company (no real incentive)
- very low probability: a hacker could log her keystrokes and blackmail her (poor risk-reward)

(M) 

- no-go: installing the tor browser/using a Tails usb might be a red flag; family could ask unnecessary questions
- no-go: locking (password) phone/laptop could also raise suspicions
- no-go: having a separate sim card dedicated to this (with no history/contacts) is risky and might become a burden 
- **plan**: avoid posting anything related to (A) on social media
- **plan**: use a SearX/SearXNG search instance; always remember to close browser and clear history
- **plan**: use a separate (dedicated) browser in incognito mode on a home machine; do not use it for any other stuff (this should mitigate most probable scenarios)

## Observations

Although imperfect, the random example above should provide a big picture view of the threat modeling process and hopefully help you get started.

Here are a few notes to keep in mind:

- review your security plan periodically and revise it accordingly
- do not share your own specific threat model scenario with anyone
- use pen and paper and protect/destroy the actual list after you're done
- more complex != more secure; keep it simple

---

## Feedback

Let me know if you find this helpful and, depending on interest, I will do my best to post a new [Cypherpunk Transmission](/tag/CT/) report every (other?) Monday.

Questions, edits and suggestions are always appreciated @ [/about/](/about/).

**-3RA**

*Credit goes to gnuteardrops from [monero.graphics](https://monero.graphics/){:target="_blank"} for the amazing xkcd graphic. Work and xkcd Script font licensed under [CC BY-NC 3.0](https://github.com/ipython/xkcd-font/blob/master/LICENSE){:target="_blank"}{:rel="nofollow"}.* 

