# RI-INTEROP-ELYDORA-001

**Status:** Completed bounded interoperability test  
**Test class:** External-system representability and receiver independence  
**Canonical web record:** https://responsibilityinfrastructure.com/interop#ri-interop-elydora-001

## Result

| Dimension | Result |
|---|---|
| Representability | PASS |
| Responsibility Completeness | PARTIAL |
| Receiver Independence | PASS |
| Overall | PARTIAL |
| RI Conformance | NOT ESTABLISHED |

## Tested source boundary

The test used a frozen public Elydora source state at commit:

`060a072f1fc42aff36c0e453d7549f66a66df731`

The bounded test asked whether source-supported facts could be represented in a Responsibility Infrastructure record and consumed by a generic RI receiver without Elydora-specific logic or invention of missing responsibility facts.

Under the tested conditions, source-supported facts were representable and a generic RI receiver consumed the RI record using RI fields only. Responsibility facts not established by the source material remained explicit gaps. A server round-trip was not established within this test boundary.

## Claims boundary

This result is deliberately narrow. It does **not** establish:

- Elydora adoption of Responsibility Infrastructure;
- endorsement, partnership or participation;
- certification or regulatory approval;
- full Responsibility Infrastructure conformance;
- Recognition or Registry standing;
- production interoperability beyond the tested source boundary;
- the truth of facts that were not present in the tested source material.

The result describes only the bounded test and frozen source state identified above. It is not a general assessment of Elydora, its security, quality, legality, fitness for purpose or commercial suitability.

## Research context

This test forms part of the empirical research programme associated with:

**AI Governance Is Not Enough to Prove Responsibility: A Conceptual and Testable Architecture for Demonstrable Responsibility in AI Systems.** Canonical public research edition, version 1.0 (2026), Responsibility Infrastructure Publications. DOI: https://doi.org/10.5281/zenodo.21848724

The paper provides the research hypothesis and terminology. The result above stands on the evidence of this bounded test; the paper itself is not evidence that the tested system conforms.

## Attribution, copyright and third-party rights

Elydora is named solely to identify the third-party source system used in the test. All Elydora names, marks, source code and documentation remain the property of their respective owners and remain subject to their applicable licences. The upstream source in this repository is distributed under its existing Apache License 2.0; this report does not alter or relicense that source.

This report does not imply affiliation, endorsement, sponsorship, certification or permission by the third-party project.

**Report copyright:** © 2026 LA TOUCHE HOLDINGS LTD. All rights reserved. Short quotations for research, review and citation are permitted with attribution and a link to the canonical record. No broader licence to modify, republish or redistribute this report is granted unless expressly stated in writing.

**Trade mark notice:** Responsibility Infrastructure® is a registered trade mark of LA TOUCHE HOLDINGS LTD in the United Kingdom. Third-party trade marks remain the property of their respective owners.
