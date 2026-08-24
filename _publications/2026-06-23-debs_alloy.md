---
title: "Alloy: Transparent Proxy-Based Coupling Between Stream Processing and Storage"
collection: publications
permalink: /publication/2026-06-23-debs_alloy
excerpt: 'Stream storage and processing workflows support a wide range of applications, from enterprise data lakes to IoT analytics. Streams are ingested and stored in broker clusters, e.g., using Apache Kafka, while processing engines like Apache Flink execute queries. In such a setup, however, streams are read, sent, and (de)serialized in full between storage and processing, even when only a subset is relevant, leading to inefficiencies in networking and computation.
We present Alloy, a novel approach for reducing the cost of coupling stream storage and processing. Alloy filters data on storage nodes and sends only what is useful for a specific query to the processing cluster. A distinctive feature of Alloy is its transparency: the data plane uses WebAssembly plugins deployed atop the Envoy proxy, interposing between Apache Flink and Apache Kafka to perform selection and projection without modifying either system. The Alloy control plane analyzes queries as part of the regular Flink submission and configures proxies accordingly. Evaluation using microbenchmarks and Nexmark shows that Alloy drastically reduces network usage while maintaining or reducing CPU utilization, with minimal latency impact.'
date: 2026-06-23
venue: 'DEBS ''26: Proceedings of the 19th ACM International Conference on Distributed and Event-based Systems'
paperurl: 'https://dl.acm.org/doi/10.1145/3809481.3812609'
citation: 'Rosinosky, G., Schmitz, D., & Riviere, E. (2026, June). Alloy: Transparent Proxy-Based Coupling Between Stream Processing and Storage. In Proceedings of the 20th ACM International Conference on Distributed and Event-based Systems (pp. 23-36).'
---
[Online repository](https://github.com/CloudLargeScale-UCLouvain/alloy)