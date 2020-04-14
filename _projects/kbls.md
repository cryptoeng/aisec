---
title: "KBLS"
author: franziskus
---

[KBLS](https://www.forschung-it-sicherheit-kommunikationssysteme.de/projekte/kbls) is a project funded by the BMBF as part of the [post-quantum crypto initiative](https://www.forschung-it-sicherheit-kommunikationssysteme.de/foerderung/bekanntmachungen/pqk).

Data is currently encrypted with schemes that can't be broken by todays computers in reasonable time. In future however quantum computers will be able to do so. This creates a big security risk for currently used communication systems. It is therefore necessary to make sure that cryptographic algorithms that are resistant to attacks by quantum computers are available and usable.

### Goals and Approach

The [Botan crypto library](https://botan.randombit.net/) supports a large number of cryptographic algorithms already and is recommended by the [BSI](https://www.bsi.bund.de/EN/TheBSI/thebsi_node.html). The goal of this project is to extend Botan with algorithms that are considered resistant to attacks by quantum computers to ensure that users can achieve long-term security in their applications. All algorithms should offer usable APIs that minimise the possibility of misusing them. Usability of the implemented changes are evaluated by engineers to identify possible issues. The implementation should further be efficient such that it is possible to run it on resource constraint devices. Another focus of the implementation is crypto-agility, i.e. the used cryptographic algorithms can be easily replaced by other algorithms.

All implementation results are proposed for integration into upstream Botan. Other results are published at academic conferences and proposed for integration into international standards.

### Coordinator
Fraunhofer AISEC, Garching bei München 

### Partners
* Technische Universität Berlin
* neXenio GmbH, Berlin
* Rohde & Schwarz Cybersecurity GmbH, München


