# UNIT 7 – An Introduction to the Concepts of Quantitative Risk Modelling

## Unit Overview
This unit introduced the principles of Quantitative Risk Modelling (QRM) and examined probabilistic and decision-based approaches for analysing risk. The focus was on understanding when quantitative methods are appropriate, how they differ from qualitative approaches, and the limitations and assumptions inherent in each technique. Key methods explored included Monte Carlo simulation, Bayesian inference, and Multi-Criteria Decision-Making (MCDM) techniques such as AHP and ANP.

---

## Quantitative Risk Modelling Concepts
Quantitative Risk Modelling seeks to represent uncertainty numerically using probabilities, distributions, and statistical reasoning. Unlike qualitative approaches, QRM enables numerical comparison of risks and supports data-driven decision-making. However, QRM is highly dependent on the quality of input data and underlying assumptions.

---

## Monte Carlo Simulation
Monte Carlo simulation uses repeated random sampling to model uncertainty and variability within a system. It is particularly useful when outcomes depend on multiple uncertain variables. Strengths of the approach include its ability to model complex systems and produce probability distributions rather than single-point estimates. However, the technique requires reliable input data and well-defined assumptions, as poorly constructed models may create a false sense of accuracy.

---

## Bayesian Risk Modelling
Bayesian risk modelling applies Bayes’ Theorem to update probabilities as new evidence becomes available. This approach is particularly effective in cybersecurity and operational risk contexts where threat likelihoods evolve over time. While Bayesian methods support continuous learning, they rely on prior probability estimates, which may introduce subjectivity if not carefully justified.

---

## Multi-Criteria Decision-Making (MCDM)
MCDM techniques such as Analytic Hierarchy Process (AHP) and Analytic Network Process (ANP) support structured decision-making where multiple, often conflicting, criteria must be considered. These approaches enhance transparency but are sensitive to expert judgement and weighting inconsistencies.

---

## Collaborative Discussion Contribution – CVSS and Quantitative Alternatives
As part of this unit, I contributed to the collaborative discussion examining limitations of the Common Vulnerability Scoring System (CVSS), drawing on Wunder et al. (2024). I argued that CVSS often produces inconsistent and context-insensitive scores due to reliance on static metrics and subjective interpretation. I supported this critique by linking CVSS limitations to Bayesian risk modelling concepts, noting that probabilistic approaches allow risk likelihoods to be updated as new threat intelligence emerges.

I further argued that FAIR-based quantitative risk assessment models provide a more effective alternative for organisational decision-making by expressing cyber risk in financial terms and separating loss frequency from loss magnitude. Through peer engagement, I reflected on the value of hybrid approaches that combine CVSS for technical vulnerability triage with quantitative risk models for strategic prioritisation.

---

## Critical Evaluation
Quantitative risk models offer valuable numerical insight but can create a false sense of precision if uncertainties and assumptions are not communicated clearly. Hybrid approaches combining quantitative and qualitative methods often provide more realistic and actionable representations of risk.

---

## Personal Contribution and Reflection
I engaged with quantitative modelling exercises and collaborative discussions to critically evaluate the suitability of different risk modelling techniques. This unit reshaped my understanding of risk by highlighting the importance of context, transparency, and appropriate method selection in quantitative analysis. The learning gained directly informed my approach to later assessments involving probabilistic risk estimation and executive-level decision support.

---

## Learning Application

Unit 7 introduced the foundational concepts of **quantitative risk modelling**, including the use of structured numerical approaches such as probability distributions, event trees, and basic statistical analysis to represent uncertainty in risk outcomes. This unit emphasised that quantitative techniques can offer richer insight into risk likelihood and impact when sufficient data or reasonable assumptions are available, and that these models can support more informed decision-making than qualitative assessments alone.

The learning from Unit 7 directly influenced my approach to the **individual project**, where quantitative risk modelling techniques were applied to assess supply chain and operational risks. Specifically, concepts such as probability distributions and quantitative interpretation of risk outcomes helped frame the selection of Fault Tree Analysis (FTA) and guided assumptions used in Monte Carlo simulation during the risk evaluation process. These methods added depth to the individual assessment by allowing estimation of risk variability and projected impacts under uncertainty.

---

## References
Asadabadi, M., Chang, E. and Saberi, M. (2019) Are MCDM methods useful? Cogent Engineering, 6(1).  
https://doi.org/10.1080/23311916.2019.162315  

Metropolis, N. (1987) The Beginning of the Monte Carlo Method. Los Alamos Science.  
https://www.osti.gov/servlets/purl/6236021  

Wunder, J., Kurtz, A., Eichenmüller, C., Gassmann, F. and Benenson, Z. (2024) Shedding Light on CVSS Scoring Inconsistencies.  
https://doi.org/10.1145/  

Downey, A. (2022) Think Bayes 2.  
https://allendowney.github.io/ThinkBayes2/  

Aven, T. and Thekdi, S. (2025) Risk Science. Routledge.
