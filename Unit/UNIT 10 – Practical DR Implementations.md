# UNIT 10 – Practical Applications and Issues in Disaster Recovery Implementations

## Unit Overview
This unit examined the practical design and implementation of Disaster Recovery (DR) solutions, focusing on how Recovery Time Objectives (RTOs) and Recovery Point Objectives (RPOs) influence technical and architectural decisions. The unit also explored Disaster Recovery as a Service (DRaaS), vendor lock-in, cloud resilience, and security considerations in modern recovery environments.

---

## Impact of RTO and RPO on DR Design
RTO and RPO are key drivers in selecting appropriate disaster recovery solutions. Short RTOs require highly available systems with rapid failover, while strict RPOs necessitate near-real-time data replication. This unit demonstrated that aggressive recovery objectives significantly increase cost and complexity, making alignment with business priorities essential.

For example:
- **Low RTO / Low RPO:** Requires hot standby or active-active architectures.
- **Moderate RTO / RPO:** Can be met using warm standby and scheduled replication.
- **High RTO / RPO:** Often supported through cold standby and periodic backups.

---

## Disaster Recovery Solution Models
Several DR solution models were reviewed, including on-premise redundancy, cloud-based replication, and DRaaS offerings. DRaaS was identified as a scalable and cost-effective solution for organisations lacking in-house recovery infrastructure. However, reliance on third-party providers introduces dependencies that must be carefully managed.

---

## DRaaS Benefits and Limitations
DRaaS provides benefits such as rapid deployment, reduced capital expenditure, and simplified testing. However, limitations include reduced visibility into underlying infrastructure, reliance on provider availability, and potential challenges in meeting strict RTO/RPO requirements during widespread outages.

---

## Vendor Lock-In and Security Challenges
Vendor lock-in was identified as a significant risk in cloud-based DR solutions. Proprietary platforms and data formats can make migration costly and complex. To mitigate this risk, organisations should adopt portable architectures, use open standards, and maintain documented exit strategies.

Security concerns in modern DR environments include data confidentiality during replication, access control, and network segmentation. These risks can be mitigated through encryption, identity and access management, and regular security testing.

---

## Critical Evaluation
This unit highlighted that no single DR solution is universally optimal. Over-engineered solutions can waste resources, while under-engineered designs expose organisations to unacceptable risk. Effective DR design requires balancing resilience, cost, security, and vendor dependency, supported by continuous testing and review.

---

## Personal Contribution and Reflection
I contributed to discussions evaluating DR solution trade-offs and vendor lock-in risks. This unit strengthened my ability to design recovery strategies aligned with business requirements and critically assess cloud-based recovery services. The learning gained informed my approach to later assessments involving high-availability system design and continuity planning.

---

## Learning Application

Unit 10 focused on the **practical implementation of disaster recovery (DR) strategies**, including the real-world considerations of recovery mechanisms, failover procedures, continuity requirements, and testing plans. This unit emphasised how disaster recovery goes beyond planning to include steps such as backup validation, recovery rehearsals, tiered infrastructure design, and continuous improvement of DR processes.

The learning from Unit 10 directly influenced my **individual project**, particularly in designing the disaster recovery components of the business continuity strategy. Practical insights such as the need for periodic testing, automated failover mechanisms, geographically distributed infrastructure, and structured procedures for data restoration informed how I proposed recovery solutions that were both realistic and aligned with organisational resilience goals. This ensured that the disaster recovery measures were not just theoretical, but potentially implementable within the context of the identified risks and organisational capabilities.


---

## References
Alhazmi, O. and Malaiya, Y. (2013) Evaluating disaster recovery plans using the cloud. *Proceedings of the Annual Reliability and Maintainability Symposium*, pp. 1–6.  
https://ieeexplore.ieee.org/document/6482245  

Kumar, A. (2024) Cloud Vendor Lock-In: Identify, Strategies and Mitigate.  
https://www.cloudcomputing-news.net  

Corbari, G.I. et al. (2024) Mission Thread Analysis: Establishing a Common Framework. *The Cyber Defense Review*, 9(1), pp. 37–54.  

Sutton, D. (2021) *Information Risk Management*. BCS.
