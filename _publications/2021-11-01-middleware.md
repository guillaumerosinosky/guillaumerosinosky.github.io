---
title: "PProx: efficient privacy for recommendation-as-a-service"
collection: publications
permalink: /publication/2021-11-01-middleware
excerpt: '[Presentation video](https://www.youtube.com/watch?v=WTJfoH6jLd4) 

Multi-tenancy enables cost-effective SaaS through resource consolidation. Multiple customers, or tenants, are served by a single application instance, and isolation is enforced at the application level. Ser- vice load for different tenants can vary over time, requiring applications to scale in and out. A large class of SaaS providers operates legacy applications structured around a relational (SQL) database. These applications achieve tenant isolation through dedicated fields in their relational schema and are not designed to support scaling operations. We present a novel solution for scaling in or out such applications through the migration of a tenant’s data to new application and database instances. Our solution requires no change to the application and incurs no service downtime for non-migrated tenants. It leverages external tables and foreign data wrappers, as supported by major relational databases. We evaluate the approach using two multi-tenant applications: Iomad, an ex- tension of the Moodle Learning Management System, and Camunda, a business process management platform. Our results show the usability of the method, minimally impacting performance for other tenants during migration and leading to increased service capacity after migration.'
date: 2021-11-01
venue: 'Middleware'
paperurl: 'http://hdl.handle.net/2078.1/252558'
citation: 'Rosinosky, G., Da Silva, S., Ben Mokhtar, S., Négru, D., Réveillère, L., & Rivière, E. (2021, November). PProx: efficient privacy for recommendation-as-a-service. In Proceedings of the 22nd International Middleware Conference (pp. 14-26).'
---
[Online repository](https://github.com/CloudLargeScale-UCLouvain/PProx)