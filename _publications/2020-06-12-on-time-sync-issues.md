---
title: "On Time Synchronization Issues in Time-Sensitive Networks with Regulators and Nonideal Clocks"
collection: publications
permalink: /publication/2020-06-12-on-time-sync-issues
excerpt: 'In this paper, we model for the first time the effect of non-ideal clocks and of time synchronization within the Network Calculus framework. We also also prove that using a TSN ATS in a network with non-ideal (even synchronized) clocks can yield unbounded latencies.' 
date: 2022-06-12
venue: 'Proceedings of the ACM on Measurement and Analysis of Computing Systems'
doi: 'https://doi.org/10.1145/3392145'
---
Flow reshaping is used in time-sensitive networks (as in the context of IEEE TSN and IETF Detnet) in order to reduce burstiness inside the network and to support the computation of guaranteed latency bounds. This is performed using per-flow regulators (such as the Token Bucket Filter) or interleaved regulators (as with IEEE TSN Asynchronous Traffic Shaping, ATS). The former use one FIFO queue per flow, whereas the latter use one FIFO queue per input port. Both types of regulators are beneficial as they cancel the increase of burstiness due to multiplexing inside the network. It was demonstrated, by using network calculus, that they do not increase the worst-case latency. However, the properties of regulators were established assuming that time is perfect in all network nodes. In reality, nodes use local, imperfect clocks. Time-sensitive networks exist in two flavours: (1) in non-synchronized networks, local clocks run independently at every node and their deviations are not controlled and (2) in synchronized networks, the deviations of local clocks are kept within very small bounds using for example a synchronization protocol (such as PTP) or a satellite based geo-positioning system (such as GPS). We revisit the properties of regulators in both cases. In non-synchronized networks, we show that ignoring the timing inaccuracies can lead to network instability due to unbounded delay in per-flow or interleaved regulators. We propose and analyze two methods (rate and burst cascade, and asynchronous dual arrival-curve method) for avoiding this problem. In synchronized networks, we show that there is no instability with per-flow regulators but, surprisingly, interleaved regulators can lead to instability. To establish these results, we develop a new framework that captures industrial requirements on clocks in both non-synchronized and synchronized networks, and we develop a toolbox that extends network calculus to account for clock imperfections.

[Accepted Version](http://ludoinspace.github.io/files/2020-06-12-on-time-sync-issues.pdf)

Recommended citation: Ludovic Thomas and Jean-Yves Le Boudec. 2020. On Time Synchronization Issues in Time-Sensitive Networks with Regulators and Nonideal Clocks. *Proc. ACM Meas. Anal. Comput. Syst.* 4, 2, Article 27 (June 2020), 41 pages. https://doi.org/10.1145/3392145

[BibTeX](http://ludoinspace.github.io/files/2020-12-01-quic-opportunities-threats-satcom-bib.bib)
