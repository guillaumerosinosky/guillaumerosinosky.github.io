---
title: "Justin: Hybrid CPU/Memory Elastic Scaling for Distributed Stream Processing"
collection: publications
permalink: /publication/2025-06-15-dais_justin
excerpt: 'Distributed Stream Processing (DSP) engines analyze continuous data via queries expressed as a graph of operators. Auto-scalers adjust the number of parallel instances of these operators to support a target rate. Current auto-scalers couple CPU and memory scaling, allocating resources as one-size-fits-all packages. This contrasts with operators’ high diversity of requirements.
We present Justin, an auto-scaler that enables hybrid CPU and memory scaling of DSP operators. Justin monitors both CPU usage and the performance of operators’ storage operations. Its mechanisms enable fine-grain memory allocation for tasks upon a query reconfiguration. The Justin policy identifies individual operators’ memory pressure and decides between adjusting parallelism and/or memory assignment. We implement Justin in Apache Flink, extending the Flink Kubernetes Operator and the DS2 CPU-only auto-scaler. Using the Nexmark benchmark, our evaluation shows that Justin identifies suitable resource allocation in as many or fewer reconfiguration steps as DS2 and supports a target rate with significantly fewer CPU and memory resources.'
date: 2025-06-15
venue: 'IFIP International Conference on Distributed Applications and Interoperable Systems (DAIS) 2025'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-95728-4_6'
citation: 'Schmitz, D., Rosinosky, G., & Rivière, E. (2025, June). Justin: Hybrid CPU/Memory elastic scaling for distributed stream processing. In IFIP International Conference on Distributed Applications and Interoperable Systems (pp. 102-118). Cham: Springer Nature Switzerland.'
---
[Artifact](https://zenodo.org/records/15209785)

[Online repository](https://github.com/CloudLargeScale-UCLouvain/flink-justin)