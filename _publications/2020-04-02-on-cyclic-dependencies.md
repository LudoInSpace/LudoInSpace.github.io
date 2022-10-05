---
title: "On Cyclic Dependencies and Regulators in Time-Sensitive Networks"
collection: publications
permalink: /publication/2020-04-02-on-cyclic-dependencies
excerpt: 'In this paper, we investigate the effect of cyclic dependencies on latency bounds in time-sensitive networks.' 
date: 2020-04-02
venue: 'Proceedings of 2019 IEEE the Real-Time Systems Symposium (RTSS)'
doi: '10.1109/RTSS46320.2019.00035'
---
For time-sensitive networks, as in the context of IEEE TSN and IETF Detnet, cyclic dependencies are associated with certain fundamental properties such as improving availability and decreasing reconfiguration effort. Nevertheless, the existence of cyclic dependencies can cause very large latency bounds or even global instability, thus making the proof of the timing predictability of such networks a much more challenging issue. Cyclic dependencies can be removed by reshaping flows inside the network, by means of regulators. We consider FIFO-per-class networks with two types of regulators: perflow regulators and interleaved regulators (the latter reshape entire flow aggregates). Such regulators come with a hardware cost that is less for an interleaved regulator than for a perflow regulator; both can affect the latency bounds in different ways. We analyze the benefits of both types of regulators in partial and full deployments in terms of latency. First, we propose Low-Cost Acyclic Network (LCAN), a new algorithm for finding the optimum number of regulators for breaking all cyclic dependencies. Then, we provide another algorithm, Fixed- Point Total Flow Analysis (FP-TFA), for computing end-to-end delay bounds for general topologies, i.e., with and without cyclic dependencies. An extensive analysis of these proposed algorithms was conducted on generic grid topologies. For these test networks, we find that FP-TFA computes small latency bounds; but, at a medium to high utilization, the benefit of regulators becomes apparent. At high utilization or for high line transmission-rates, a small number of per-flow regulators has an effect on the latency bound larger than a small number of interleaved regulators. Moreover, interleaved regulators need to be placed everywhere in the network to provide noticeable improvements. We validate the applicability of our approaches on a realistic industrial time-sensitive network.

[Accepted Version](http://ludoinspace.github.io/files/2020-04-02-on-cyclic-dependencies.pdf)

Recommended citation: Ludovic Thomas, Jean-Yves Le Boudec and Ahlem Mifdaoui, "On Cyclic Dependencies and Regulators in Time-Sensitive Networks," 2019 IEEE Real-Time Systems Symposium (RTSS), 2019, pp. 299-311, doi: 10.1109/RTSS46320.2019.00035.

[BibTeX](http://ludoinspace.github.io/files/2020-04-02-on-cyclic-dependencies-bib.bib)
