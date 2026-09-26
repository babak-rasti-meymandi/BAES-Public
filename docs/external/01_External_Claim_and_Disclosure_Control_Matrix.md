# BAES — External Claim & Disclosure Control Matrix

**Document Status:** Public Engineering Record  
**Version:** v0.1  
**Purpose:** Define a lightweight control for preparing external-facing BAES material without overstating claims or disclosing restricted development material.

---

## 1. Purpose and Scope

BAES external material is intended to provide a clear evaluation surface for researchers, engineers, organizations, and other technically qualified reviewers.

This document establishes two complementary disciplines:

1. **Claim discipline** — distinguish established statements from hypotheses, limitations, and non-claims.
2. **Disclosure discipline** — distinguish material suitable for public/external release from material that requires review or must remain restricted.

This document does **not** define BAES itself and does not authorize changes to the BAES architecture.

---

## 2. Claim Classes

| Class | Meaning | External treatment |
|---|---|---|
| C1 — Established | Directly established within the current BAES record | May be stated directly, subject to scope |
| C2 — Supported | Supported by documented analysis or development evidence, but not independently validated | State with appropriate qualification |
| C3 — Hypothesis | Proposed interpretation, research question, or proposition | Label explicitly as a hypothesis or question |
| C4 — Not Established | The available record does not establish the claim | Do not present as fact |
| C5 — Not Claimed | BAES explicitly makes no such claim | State as a boundary/non-claim when relevant |

### External wording rule

A stronger claim must never be inferred from a weaker claim.

In particular:

- Internal development evidence is not equivalent to independent external validation.
- A conceptual distinction is not automatically a demonstrated practical benefit.
- A proposed applicability is not evidence of universal applicability.
- Absence of an identified contradiction is not proof of completeness.

---

## 3. Disclosure Classes

| Class | Meaning | Default treatment |
|---|---|---|
| D0 — Public Safe | Suitable for unrestricted public release | May be published |
| D1 — Public Safe with Qualification | Suitable for public release only with explicit scope/qualification | Publish only with approved wording |
| D2 — Review Required | Potentially releasable but requires deliberate review before external use | Do not publish automatically |
| D3 — Restricted / Excluded | Internal, confidential, strategic, or otherwise unsuitable for public release | Exclude from public material |

### Default rule

When disclosure status is uncertain, treat the material as **D2** until reviewed.

---

## 4. Claim–Disclosure Mapping

Every substantive external claim should be traceable through the following chain:

**Claim ID → Claim Text → Claim Class → Evidence Source → Evidence Location → Disclosure Class → Approved External Wording**

This mapping is an editorial/release-control mechanism. It is not a new BAES layer, model, phase, or normative requirement.

---

## 5. Public-Safe Content Categories

The following categories are generally appropriate for external introduction, subject to ordinary review:

- BAES purpose and high-level positioning
- Problem space addressed by BAES
- What BAES is
- What BAES is not
- High-level conceptual architecture
- High-level Human–AI interaction distinctions
- Publicly stated principles
- Synthetic or non-confidential worked examples
- Current development status
- Explicit limitations and non-claims
- Questions for external technical or academic review
- Public references and the Public Engineering Record

---

## 6. Content Requiring Review or Exclusion

The following should not be copied into public material merely because it exists in the internal development record:

- Internal research chronology
- Rejected candidate concepts and exploratory branches
- Private research notes
- Internal gate mechanics unless intentionally released
- Confidential correspondence
- Organization-specific engagement strategy
- Funding, employment, residence, or negotiation strategy
- Private target assessments
- Sensitive unpublished technical details
- Material from restricted repositories
- Any content whose disclosure classification has not been established

These categories are governed by the release decision, not by assumptions about what an external reader might already know.

---

## 7. External Organization Neutrality

Core BAES public documents should remain organization-neutral.

Specific universities, companies, institutes, laboratories, or other recipients belong in target-specific engagement records and correspondence, not in the normative/public BAES core.

This preserves a single BAES public record while allowing different external audiences to receive different contextual introductions.

---

## 8. External Evidence Boundary

BAES may describe its internal development and validation activities accurately, but external material should distinguish:

- **Development evidence** — evidence generated during BAES development.
- **External review** — criticism, validation, or analysis supplied by independent parties.
- **Independent validation** — evidence produced through an appropriately independent evaluation.

The existence of the first does not imply the existence of the latter two.

---

## 9. External Review Questions

External material may explicitly invite reviewers to challenge:

1. Whether the stated problem is meaningful and sufficiently distinct.
2. Whether the conceptual boundaries are correctly drawn.
3. Whether existing frameworks or engineering practices already address the same need.
4. Whether the distinctions are useful in practical AI systems.
5. Whether the model remains useful for agentic or increasingly autonomous systems.
6. Whether the proposed boundaries create unnecessary engineering overhead.
7. Where BAES may be unnecessary.
8. What evidence would contradict or materially weaken the current claims.

---

## 10. Release Gate

Before external publication or targeted distribution, verify:

- [ ] The document contains no restricted material.
- [ ] Every substantive claim has an appropriate claim class.
- [ ] Claims do not exceed the evidence supporting them.
- [ ] Hypotheses are identified as hypotheses.
- [ ] Non-claims and limitations are preserved where relevant.
- [ ] No organization-specific strategy has entered the BAES Core.
- [ ] No confidential correspondence or private material is included.
- [ ] Development evidence is not described as independent validation.
- [ ] The intended audience and purpose are clear.
- [ ] The final version has been deliberately approved for release.

---

## 11. Relationship to BAES

This document is an **external-material preparation and release-control record**.

It does not:

- modify the Frozen Foundation;
- create a new Foundation concept;
- create a new Foundation Model;
- create a new Engineering Model;
- create a new architectural layer;
- create a new BAES phase;
- reopen previously closed research.

Its purpose is solely to maintain accuracy, scope discipline, and disclosure discipline while presenting BAES externally.

---

## 12. Current Status

**Status:** Active external-publication control document  
**Version:** v0.1

The document may evolve as the public record and external-review process mature, without changing the underlying BAES architecture.
