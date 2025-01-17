# LawEnforcementResources

Resources provided by the community that can serve to be useful for Law Enforcement worldwide

## Free Training

* [NW3C - Online Training](https://www.nw3c.org/online-training) - Free online training provided by NW3C. Great for padding the CV with training! US LE only. Outside US LE may have to contact NW3C to ask for access, but I can't promise LE outside of the USA can access the training. 
* [Texas A&M TEEX - Cybersecurity](https://teex.org/program/cybersecurity/) - Any class with the FEMA logo (A) is free! Stock up on the certificates of completion!

## Ransomware Decryption Resources

* [NO MORE RANSOM](https://www.nomoreransom.org/en/index.html) - Ransomware decryption tools/platform.

## Malware Analysis
* [Any.run](https://app.any.run/) - Interactive Online Malware Analysis Sandbox - ANY.RUN
* [VirusTotal](https://www.virustotal.com/) - Analyze suspicious files and URLs to detect types of malware, automatically share them with the security community.
* [Hybrid Analysis](https://www.hybrid-analysis.com/) - Free Automated Malware Analysis Service - powered by Falcon Sandbox.
* [Cuckoo Sandbox](https://cuckoo.cert.ee/) - Cuckoo Sandbox.

### Phishing
* [PhishTank](http://phishtank.org/) - PhishTank is a collaborative clearing house for data and information about phishing on the Internet.

## Mobile Investigations

### Pin Code and Pattern Lock Resources

* [All Possible Pattern Locks](https://github.com/ByteRockstar1996/All-Possible-Pattern-Locks) - text files containing all possible pin combinations to 9 chars.
* [Predictability of Android Lock Patterns](https://arstechnica.com/information-technology/2015/08/new-data-uncovers-the-surprising-predictability-of-android-lock-patterns/) - Ars Technica artile about Android lock patterns.
* [10 Most Common Pattern Locks](https://www.youtube.com/watch?v=zD4ge-HPIGQ) - YouTube video about common lock patterns.
* [Common lock Patterns Cheat Sheet](https://github.com/Digital-Forensics-Discord-Server/LawEnforcementResources/raw/main/CommonLockPatterns.jpg) - from Pinterest/sanketmisal
* [Android Pattern Lock](https://github.com/delight-im/AndroidPatternLock) - GitHub repo with pattern text files.

## IP Resolution Services

* [MaxMind](https://www.maxmind.com/en/home) - useful for resolving IPs. MaxMind is known for offering better geolocation than most other similar services. 

## MLA Resources

* [UNODC SHERLOC](https://sherloc.unodc.org/cld/en/st/home.html) - Legislation, CNA list and treaties.


## End-to-end encrypted messengers
| Name | URL | iOS | Android | Windows | Mac | Linux | Web |
|--|--|--|--|--|--|--|--|
| BRIAR | https://briarproject.org/ | ✕ | ✓ | ✕ | ✕ | ✕ | ✕ |
| Element | https://element.io/ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Jitsi | https://meet.jit.si/ | ✓ | ✓ | ✕ | ✕ |  ✕ | ✓ |
| Line | https://line.me/en/ | ✓ | ✓ | ✕ | ✕ |  ✕ | ✕ |
| Session | https://getsession.org/ | ✓ | ✓ | ✓ | ✓ | ✓ | ✕ |
| Signal | https://www.signal.org/ | ✓ | ✓ | ✓ | ✓ | ✓ | ✕ |
| Silence | https://silence.im/ | ✕ | ✓ | ✕ | ✕ | ✕ | ✕ |
| Telegram | https://telegram.org/ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Threema | https://threema.ch/en/ | ✓ | ✓ | ✕ | ✕ | ✕ | ✓ |
| Tox | https://tox.chat/ | ✕ | ✓ | ✓ | ✓ | ✓ | ✕ |
| Viber | https://www.viber.com/ | ✓ | ✓ | ✓ | ✓ | ✓ | ✕ |
| WhatsApp | https://www.whatsapp.com/ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Wickr Me | https://wickr.com/ | ✓ | ✓ | ✓ | ✓ | ✓ | ✕ |
| Wire | https://wire.com/en/ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |

## Self Contained and Darknet Resources

* [TOR](https://www.torproject.org/) - The Onion Router. 
  * **```.onion```**
* [I2P](https://geti2p.net/en/) - The Invisible Internet Project. 
  * **```.i2p``` ```.b32.i2p```**
* [Lokinet](https://lokinet.org/) - Anonymous Internet Access.
  * **```.loki```**
* [ZeroNet](https://zeronet.io/) - Decentralized websites using Bitcoin cryptography and the BitTorrent network.
  * **```.bit``` ```https://zeronet.link/xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx```**
* [Retroshare](https://retroshare.cc/) - Retroshare establish encrypted connections between you and your friends to create a network of computers, and provides various distributed services on top of it: forums, channels, chat, mail...
* [OpenBazaar](https://openbazaar.org/) - A FREE ONLINE MARKETPLACE. NO PLATFORM FEES. NO RESTRICTIONS. EARN CRYPTOCURRENCY.
* [Freenet](https://freenetproject.org/) - Freenet is a peer-to-peer platform for censorship-resistant communication and publishing.
* [Tails](https://tails.boum.org/) - is a portable operating system that protects against surveillance and censorship. 
* [Whonix](https://www.whonix.org/) - Software That Can Anonymize Everything You Do Online.

## Regular Expressions
* Tor hidden services (V2 & V3) 
  * **```[a-z2-7]{16}.onion|[a-z2-7]{56}.onion```**
* I2P hidden service (b32)
  * **```([a-zA-Z0-9]{52}.b32.i2p)```**
* I2P hidden service (.i2p)
  * **```([a-zA-Z0-9]+\.i2p(?<!b32\.i2p))```** 

### Cryptocurrency Regular Expressions
* Bitcoin address (SegWit & Legacy)  (BTC)
  *  **```([13]{1}[a-km-zA-HJ-NP-Z1-9]{26,33}|bc1[a-z0-9]{39,59})```**
* Litecoin address (LTC)
  * **```[LM3][a-km-zA-HJ-NP-Z1-9]{26,33}```**
* Ethereum & Ethereum Classic address (ETH & ETC)
  * **```0x[a-fA-F0-9]{40}```**
* Ripple address (XRP)
  * **```[0-9a-zA-Z]{24,34}```**
* Dogecoin address (DOGE)
  * **```D{1}[5-9A-HJ-NP-U]{1}[1-9A-HJ-NP-Za-km-z]{32}```**
* Monero address (XMR)
  * **```[48][0-9AB][1-9A-HJ-NP-Za-km-z]{93}```**
* Dash address (DASH)
  * **```X[1-9A-HJ-NP-Za-km-z]{33}```**

### Cryptocurrency Address Examples
**The addresses generated below are completely random and are in no way affilated with this repository, do not send money to the addresses listed below!!!**

* Bitcoin (Legacy)
  * **```1F1tAaz5x1HUXrCNLbtMDqcw6o5GNn4xqX```**
* Bitcoin (SegWit)
  * **```bc1qj89046x7zv6pm4n00qgqp505nvljnfp6xfznyw```**
* Litecoin (Legacy)
  * **```LVtdzELRdQDTa35y1bQPKTSvL3TEv1y5Ut```** 
* Ethereum & Ethereum Classic
  * **```0xF25228015a2be633a6a60e9cB4643813DAf28AA0```**
* Ripple
  * **```rJiZJRSiseTcKWepsAC6ed6EDbgu2ohPov```**
* Monero
  * **```49fpXfThF8bZwuLADG1WZ57vM8oNEuQGaHyBEomSXaaAZhCQqX6j4E9QNz6cqniBrian3zZhu7UpkD85MbrsrjvwMTxqnqe```**
* DogeCoin
  * **```DJJ2gcQ6WP59Z7mRuGKaW6sbMpcBvGqfoE```**
* Dash
  * **```XcsNx9hSEqDzFZrBrVViiZ8GhYgndBVyEY```** 

# Contributing to This Project

New to GitHub? No problem! Fork this repo by clicking on the `Fork` button on the top right of this page. 

![image](https://user-images.githubusercontent.com/36825567/131013036-a7874694-3256-4e0e-87e8-13dc1d402b31.png)

After that, you'll be working off of your Fork of this repository, which is effectively a snapshop in time. 

![image](https://user-images.githubusercontent.com/36825567/131013270-7c991c8d-d1b9-4f84-8c3d-9ef20a8d86e4.png)

As time goes on, this repository will evolve and your Fork will be left behind if you don't keep it updated. Be sure to Fetch Upstream prior contributing more so you have the most up to date copy of the repository before you starting adding to it!

![GitHubFetchandMergeandContributeExample](https://user-images.githubusercontent.com/36825567/131013496-8b547597-8e97-443e-88bb-ce75501f07c9.gif)

Above is an example of Fetch Upstream combined with doing a Pull Request, which is what you should do when you have something new to the repo you'd like to add to the main repo.

New to Markdown? No problem! Use [StackEdit](https://stackedit.io/app#) to write in Markdown with live preview. Additionally, GitHub has a useful guide for Markdown syntax [here](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). 
