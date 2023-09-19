---
title: "StreamBed: capacity planning for stream processing"
collection: publications
permalink: /publication/2023-08-01-streambed
excerpt: 'StreamBed is a capacity planning system for stream processing. It predicts, ahead of any production deployment, the resources that a query will require to process an incoming data rate sustainably, and the appropriate configuration of these resources. StreamBed builds a capacity planning model by piloting a series of runs of the target query in a small-scale, controlled testbed. We implement StreamBed for the popular Flink DSP engine. Our evaluation with large-scale queries of the Nexmark benchmark demonstrates that StreamBed can effectively and accurately predict capacity requirements for jobs spanning more than 1,000 cores using a testbed of only 48 cores.'
date: 2023-08-01
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2309.03377'
citation: 'Rosinosky, G., Schmitz, D., & Rivière, E. (2023, September). StreamBed: capacity planning for stream processing. arXiv preprint arXiv:2309.03377'
---
[Online repository](https://github.com/CloudLargeScale-UCLouvain/StreamBed)