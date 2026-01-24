### Threat–Mitigation Mapping (Applied Analysis)

As part of this unit, I mapped identified threats to appropriate modelling techniques and mitigations to demonstrate applied understanding of threat modelling outputs.

| Identified Threat | Modelling Technique Used | Proposed Mitigation |
|------------------|-------------------------|-------------------|
| Spoofing of user identity | STRIDE | Strong authentication mechanisms and multi-factor authentication |
| Data tampering | Attack Tree | Input validation, integrity checks, and access controls |
| Privilege escalation | MITRE ATT&CK | Least-privilege access and role-based access control |
| Denial of service | STRIDE | Rate limiting and redundancy planning |
| Insider misuse | Hybrid approach | Logging, monitoring, and separation of duties |

This mapping demonstrates how threat modelling outputs can be translated into actionable security controls rather than remaining theoretical.

---

### Tool Selection and Justification

For this exercise, I selected STRIDE as the primary threat modelling framework because it provides a systematic method for identifying threats across confidentiality, integrity, and availability. STRIDE was complemented with references to the MITRE ATT&CK framework to contextualise identified threats against real-world attacker behaviours and techniques. This combined approach enabled broader threat coverage while maintaining a structured and repeatable analysis process.

---

### Critical Evaluation of Alternative Approaches

While attack trees provide deeper attacker-centric analysis and are effective for modelling complex attack paths, they were not applied in full detail for this exercise due to scope and time constraints. However, this unit highlighted that hybrid approaches combining STRIDE, attack trees, and ATT&CK can be particularly effective for complex systems and would be appropriate for larger-scale assessments.
