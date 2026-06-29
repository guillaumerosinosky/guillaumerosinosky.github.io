---
title: "A Tale of Many Streams: Characterizing a Hybrid Batch-Stream Production Workload in Digazu, a Data Lake supported by Apache Kafka and Flink"
collection: publications
permalink: /publication/2025-06-09-tale_stream
excerpt: 'Many industries rely on analyzing large volumes of combined historical and live data. A data lake facilitates these operations by supporting an integrated data ingestion, storage, replay, and analysis workflow.
A modern data lake is distributed and combines a processing engine, able to seamlessly process large volumes of existing data as well as continuous flows of new data, such as Apache Flink, with a storage infrastructure able to ingest and replay this data, such as Apache Kafka.
This use of Flink in this setting departs from the commonly agreed model of stream processing queries operating over windows of events, maintaining a bounded and relatively small state per operator. Instead, hybrid batch-stream queries typically process an existing data set in its entirety before updating results with incoming stream data, leading to a large accumulated state. Given the industry’s importance of such usages, understanding their characteristics and how they differ from common assumptions in designing and evaluating stream processing systems is of utmost importance.
We present in this paper the analysis of a large-scale hybrid batch-stream workload collected from a production deployment of Digazu, a modern data lake building upon Kafka and Flink. We characterize 142 different sources of data and 129 hybrid batch-stream queries. Our analysis offers valuable insights into the nature of data and queries in typical data lake deployment, which will assist designers of such systems and associated benchmarks.'
date: 2025-06-09
venue: 'DEBS ''25: Proceedings of the 19th ACM International Conference on Distributed and Event-based Systems'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3629104.3666034'
citation: 'Rosinosky, G., Schmitz, D., & Rivière, E. (2024, June). StreamBed: capacity planning for stream processing. In Proceedings of the 18th ACM International Conference on Distributed and Event-based Systems (pp. 90-102).'
---
[Online repository](https://github.com/CloudLargeScale-UCLouvain/StreamBed)