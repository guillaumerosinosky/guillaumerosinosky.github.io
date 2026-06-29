---
title: "A Tale of Many Streams: Characterizing a Hybrid Batch-Stream Production Workload in Digazu, a Data Lake supported by Apache Kafka and Flink"
collection: publications
permalink: /publication/2023-08-01-tale_stream
excerpt: 'StreamBed is a capacity planning system for stream processing. It predicts, ahead of any production deployment, the resources that a query will require to process an incoming data rate sustainably, and the appropriate configuration of these resources. StreamBed builds a capacity planning model by piloting a series of runs of the target query in a small-scale, controlled testbed. We implement StreamBed for the popular Flink DSP engine. Our evaluation with large-scale queries of the Nexmark benchmark demonstrates that StreamBed can effectively and accurately predict capacity requirements for jobs spanning more than 1,000 cores using a testbed of only 48 cores.'
date: 2025-06-09
venue: 'DEBS '25: Proceedings of the 19th ACM International Conference on Distributed and Event-based Systems'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3629104.3666034'
citation: 'Rosinosky, G., Schmitz, D., & Rivière, E. (2024, June). StreamBed: capacity planning for stream processing. In Proceedings of the 18th ACM International Conference on Distributed and Event-based Systems (pp. 90-102).
---
[Online repository](https://github.com/CloudLargeScale-UCLouvain/StreamBed)