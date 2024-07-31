---
title: "Extracting Threat Intelligence From Cheat Binaries For Anti-Cheating"
collection: publications
permalink: /publication/RAID'23
excerpt: 'Rampant cheating in games drives developers to seek solutions, leading to the creation of CheatFighter, an automated system that extracts intelligence from cheat binaries to randomize data, effectively countering 80 out of 86 real-world cheats in under a minute for Android and Windows games.'
date: 2023-10-16
venue: 'Proceedings of the 26th International Symposium on Research in Attacks, Intrusions and Defenses'
slidesurl: 'http://mdsakibanwar.github.io/files/Cheatfighter_Presentation.pdf'
paperurl: 'http://mdsakibanwar.github.io/files/cheatfighter.pdf'
citation: 'Md Sakib Anwar, Chaoshun Zuo, Carter Yagemann, and Zhiqiang Lin. 2023. Extracting Threat Intelligence From Cheat Binaries For Anti-Cheating. In Proceedings of the 26th International Symposium on Research in Attacks, Intrusions and Defenses (RAID '23). Association for Computing Machinery, New York, NY, USA, 17–31. https://doi.org/10.1145/3607199.3607211'
---

Rampant cheating remains a serious concern for game developers who fear losing loyal customers and revenue. While numerous anti-cheating techniques have been proposed, cheating persists in a vibrant (and profitable) illicit market. Inspired by novel insights into the economics behind cheat development and recent techniques for defending against advanced persistent threats (APTs), we propose a fully automated methodology for extracting “cheat intelligence” from widely distributed cheat binaries to produce a “memory access graph” that guides selective data randomization to yield immune game clients. We have implemented a prototype system for Android and Windows games, CheatFighter, and evaluated it on 86 cheats collected from a variety of real-world sources, including Telegram channels and online forums. CheatFighter successfully counteracts 80 of the real-world cheats in under a minute, demonstrating practical end-to-end protection against widespread cheating.