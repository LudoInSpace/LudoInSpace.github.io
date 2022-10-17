---
title: "PhD Defense"
collection: talks
type: "Defense"
excerpt: "I defended my PhD on September 12th, 2022 at ISAE-SUPAERO, Toulouse, France"
permalink: /talk/2022-09-12-phd-defense
date: 2022-09-12
location: "ISAE-SUPAERO, Toulouse, France"
---

***Analysis of the side-effects on latency bounds of combinations of scheduling, redundancy and synchronization mechanisms in time-sensitive networks.***

[Final version of my manuscript](/files/2022-10-phd-dissertation.pdf)

Jury
----

Rapporteurs:

- Mr. Ye-Qiong SONG, Professor at University of Lorraine
- Mr. Jens B. SCHMITT, Professor at University of Kaiserslautern

Examiners:

- Mrs. Claire PAGETTI, Research Engineer at ONERA Toulouse
- Mrs. Liliana CUCU-GROSJEAN, Research Director at INRIA Paris

Supervisors:

- Mrs. Ahlem MIFDAOUI, Professor at ISAE-SUPAERO, Toulouse
- Mr. Jean-Yves LE BOUDEC, Professor at EPFL, Lausanne

Date and Place
--------------

September 12th, 2022 at 1:30pm at ISAE-SUPAERO, Toulouse, France

Video of the Presentation
-------------------------

[Video of the Presentation](https://youtu.be/ij6ow5XTr4Q)

Slides
------

[Animated](https://ludoinspace.github.io/files/2022-09-ludovic-thomas-defense-slides-animated.pdf) / [Handout*](https://ludoinspace.github.io/files/2022-09-ludovic-thomas-defense-slides-handout.pdf)

*Some pages of the handout version might have an incorrect rendering, please refer to the animated version in case of a doubt.

Abstract
--------

Time-sensitive networks, as in the context of IEEE Time-Sensitive Networking (TSN) and IETF Deterministic Networking (DetNet), support safety-critical applications by providing deterministic services with guaranteed latency bounds.
Several mechanisms, such as schedulers and traffic regulators (TSN ATS, asynchronous traffic shaping), were developed, and their effects on worst-case latency bounds have been widely studied in the literature by using the network-calculus framework.
Time-sensitive networks are also required, however, to offer an easy reconfiguration with alternative paths, a high level of reliability and sometimes a time-synchronization service.
To meet these needs, multi-path topologies were developed to enable the reconfiguration, and a set of redundancy and synchronization mechanisms were developed to provide high reliability and time synchronization.
Although the mechanisms can rely on their own theory to validate their adequacy
to their respective objective, their side effects on the latency bounds and their interactions with the schedulers and traffic regulators have hardly been analyzed in the literature.
In this thesis, we use the network-calculus framework to analyze the combinations of mechanisms and their effects on latency bounds in time-sensitive networks with multi-path topologies.

Our main contributions at the theoretical level are as follows:
1/ We develop an algorithm (FP-TFA) for computing latency bounds in networks with multi-path topologies that lead to cyclic dependencies.
We propose and analyze the partial-deployment approach of traffic regulators (either per-flow or TSN ATS) and another algorithm (LCAN) for breaking all cyclic dependencies at minimal cost.
2/ We analyze the effect of redundancy mechanisms on latency bounds by capturing their behavior with the network-calculus framework. 
We analyze their interactions with traffic regulators. 
We find that TSN ATS can yield unbounded latencies when used with redundancy mechanisms.
3/ We provide a time model that captures the clock non-idealities of synchronized and non-synchronized networks within the network-calculus framework.
We show that traffic regulators with non-ideal clocks can lead to latency penalties; with TSN ATS this penalty is unbounded even in tightly synchronized networks. 
We propose two methods (rate-and-burst cascade and ADAM) for adapting the parameters of the traffic regulators and for addressing the above issue.

We also provide contributions of practical interest:
a) the xTFA modular tool that computes latency bounds by using the results of the thesis,
b) a module for simulating the effects of local clocks in the discrete-event simulator ns-3, and
c) an application of our results to an industrial use-case.
