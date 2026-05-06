# AI Vendor Evaluation Scoring Model

**Author:** Dev Kewalramani  
**Version:** 1.0

---

## Overview

Use this scoring model to evaluate AI platform vendors for enterprise deployment. Complete one scorecard per vendor. Compare composite scores to inform selection decisions.

All governance requirements (Section 1) must be met before capability evaluation proceeds. Vendors who fail governance requirements are eliminated regardless of capability score.

---

## Section 1: Governance Requirements (Pass/Fail)

All items must be confirmed before proceeding to scored evaluation.

| Requirement | Confirmed | Notes |
|---|---|---|
| Data not used for vendor model training without consent | ☐ | |
| SOC 2 Type II certified | ☐ | |
| GDPR/CCPA compliance mechanisms available | ☐ | |
| Data residency options meet requirements | ☐ | |
| Audit log available and retained per policy | ☐ | |
| Incident response SLA defined | ☐ | |

**Governance Result:** ☐ Pass — proceed to scored evaluation  ☐ Fail — vendor eliminated

---

## Section 2: Capability Assessment (30% of composite score)

Score each item 1-5. Weight-average to produce dimension score.

| Capability Dimension | Weight | Score (1-5) | Weighted Score |
|---|---|---|---|
| Performance on primary use case tasks | 40% | | |
| Performance on secondary use case tasks | 25% | | |
| Output consistency and reliability | 20% | | |
| Latency at production volume | 15% | | |
| **Capability Dimension Score** | | | |

**Evidence:** Describe task evaluation methodology and results.

---

## Section 3: Total Cost of Ownership (25% of composite score)

| TCO Component | Year 1 Estimate | Year 2 Estimate | Year 3 Estimate |
|---|---|---|---|
| API / licensing costs | | | |
| Integration development | | | |
| Infrastructure and tooling | | | |
| Training and change management | | | |
| Ongoing management | | | |
| **Total TCO** | | | |

**3-Year TCO Score (1-5):** _____  
Scoring guide: 5 = lowest TCO among evaluated vendors, 1 = highest TCO

---

## Section 4: Integration and Operability (15% of composite score)

| Integration Dimension | Weight | Score (1-5) | Weighted Score |
|---|---|---|---|
| API quality and documentation | 35% | | |
| SDK availability for required languages | 25% | | |
| Enterprise system compatibility | 25% | | |
| Monitoring and observability tooling | 15% | | |
| **Integration Dimension Score** | | | |

---

## Section 5: Vendor Stability and Support (10% of composite score)

| Stability Dimension | Weight | Score (1-5) | Weighted Score |
|---|---|---|---|
| Financial health and runway | 30% | | |
| Roadmap credibility and alignment | 30% | | |
| Enterprise support SLA quality | 25% | | |
| Reference customer quality | 15% | | |
| **Stability Dimension Score** | | | |

---

## Composite Score Calculation

| Dimension | Weight | Dimension Score | Weighted Score |
|---|---|---|---|
| Capability | 30% | | |
| Total Cost of Ownership | 25% | | |
| Governance and Compliance | 20% | Pass/Fail | N/A if Pass |
| Integration and Operability | 15% | | |
| Vendor Stability and Support | 10% | | |
| **Composite Score** | 100% | | |

---

## Selection Recommendation

**Vendor Name:**  
**Composite Score:**  
**Governance Result:**  
**Recommendation:** ☐ Select ☐ Conditional Select ☐ Do Not Select  

**Rationale:**

**Conditions (if conditional):**

**Evaluator:** _________________ **Date:** _______  
**Reviewer:** _________________ **Date:** _______
