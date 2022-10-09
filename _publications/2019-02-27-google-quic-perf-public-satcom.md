---
title: "Google QUIC performance over a public SATCOM access"
collection: publications
permalink: /publication/2019-02-27-google-quic-perf-public-satcom
excerpt: 'In this paper, we report the first evaluations of QUIC using a real public SATCOM access. We find that the page load time with QUIC can be twice as long as with TCP.' 
date: 2019-02-27
venue: 'International journal of satellite communications and networking'
doi: '10.1002/sat.1301'
---
Google Quick UDP Internet Connections (QUIC) accounts for almost 10 % of the Internet traffic, and the protocol is not standardized at the Internet Engineering Task Force (IETF) yet. We distinguish Google QUIC (GQUIC) and IETF QUIC (IQUIC) since there may be differences between the two. Both Google and IETF versions run over UDP and cannot be split the way satellite systems usually do with TCP connections. The need for adapting any-QUIC parameters needs to be evaluated. Since GQUIC is available, we analyze its behavior over a satellite communication system. In our evaluations, GQUIC quick connection establishment does not compensate an inappropriate congestion control. The resulting page downloading time doubles when using GQUIC as opposed to the performance with optimized split TCP connections. This paper concludes that specific tuning are required when any-QUIC runs over a high bandwidth delay product (BDP) network.

[Published Version](https://doi.org/10.1002/sat.1301)

Recommended citation: Ludovic Thomas, Emmanuel Dubois, Nicolas Kuhn and Emmanuel Lochin. Google QUIC performance over a public SATCOM access. Int J Satell Commun Network. 2019; 37: 601– 611. https://doi.org/10.1002/sat.1301 

[BibTeX](http://ludoinspace.github.io/files/2019-02-27-google-quic-perf-public-satcom-bib.bib)