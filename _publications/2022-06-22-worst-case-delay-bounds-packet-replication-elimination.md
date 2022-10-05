---
title: "Worst-Case Delay Bounds in Time-Sensitive Networks With Packet Replication and Elimination"
collection: publications
permalink: /publication/2022-06-22-worst-case-delay-bounds-packet-replication-elimination
excerpt: 'Packet replication and elimination functions are used by time-sensitive networks (as in the context of IEEE TSN and IETF DetNet) to increase the reliability of the network. Packets are replicated onto redundant paths by a replication function. Later the paths merge again and an elimination function removes the duplicates. This redundancy scheme has an effect on the timing behavior of time-sensitive networks and many challenges arise from conducting timing analyses. The replication can induce a burstiness increase along the paths of replicates, as well as packet mis-ordering that could increase the delays in the crossed bridges or routers. The induced packet mis-ordering could also negatively affect the interactions between the redundancy and scheduling mechanisms such as traffic regulators (as with per-flow regulator and interleaved regulator, implemented by TSN asynchronous traffic shaping). Using the network calculus framework, we provide a method of worst-case timing analysis for time-sensitive networks that implement redundancy mechanisms in the general use case, i.e., at end-devices and/or intermediate nodes. We first provide a network calculus toolbox for bounding the burstiness increase and the amount of reordering caused by the elimination function of duplicate packets. We then analyze the interactions with traffic regulators and show that their shaping-for-free property does not hold when placed after a packet elimination function. We provide a bound for the delay penalty when using per-flow regulators and prove that the penalty is not bounded with interleaved regulators. Finally, we use an industrial use-case to show the applicability and the benefits of our findings.'
date: 2022-06-20
venue: 'IEEE/ACM Transactions on Networking'
paperurl: 'https://doi.org/10.1109/TNET.2022.3180763'
citation: 'L. Thomas, A. Mifdaoui and J. -Y. L. Boudec, "Worst-Case Delay Bounds in Time-Sensitive Networks With Packet Replication and Elimination," in <i>IEEE/ACM Transactions on Networking</i>, 2022, doi: 10.1109/TNET.2022.3180763.'
---
This paper is about the number 1. The number 2 is left for future work.

[Author's Version](http://ludoinspace.github.io/files/2022-06-20-packet-replication-author-version.pdf)

[Supplementary Material](https://doi.org/10.1109/TNET.2022.3180763/mm1)

Recommended citation: L. Thomas, A. Mifdaoui and J. -Y. L. Boudec, "Worst-Case Delay Bounds in Time-Sensitive Networks With Packet Replication and Elimination," in <i>IEEE/ACM Transactions on Networking</i>, 2022, doi: 10.1109/TNET.2022.3180763.

[BibTeX](http://ludoinspace.github.io/files/2022-06-20-packet-replication-citation.bib)