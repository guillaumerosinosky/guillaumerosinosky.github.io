---
title: "Charon: Fine-Grain Resource Allocation and Optimized Task Placement for Multi-Query Distributed Stream Processing"
collection: publications
permalink: /publication/2026-06-22-sac_charon
excerpt: 'Distributed Stream Processing (DSP) enables the analysis of large volumes of continuous data. A DSP engine generally executes multiple queries on a shared cluster. However, state-of-the-art DSP engines such as Apache Flink provision resources to queries in isolation and as one-size-fits-all units of CPU and memory, despite the variety of their requirements.
We propose Charon, a novel approach that dynamically assigns resources to processing elements at fine-grained levels and considers the complete set of colocated queries in its placement strategies, thereby improving consolidation and resource efficiency. Charon uses optimized placement strategies based on a bin-packing optimization algorithm, while respecting the throughput requirements of each query. We implement Charon in Flink and the Flink Kubernetes Operator. We evaluate our approach using queries from the Nexmark multi-query benchmark and demonstrate its effectiveness in improving resource utilization compared to Flink.'
date: 2026-06-22
venue: 'SAC ''26: Proceedings of the 41st ACM/SIGAPP Symposium on Applied Computing'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3748522.3779716'
citation: 'Schmitz, D., Rosinosky, G., & Rivière, E. (2026, March). Charon: Fine-Grain Resource Allocation and Optimized Task Placement for Multi-Query Distributed Stream Processing. In Proceedings of the 41st ACM/SIGAPP Symposium on Applied Computing (pp. 265-273).'
---