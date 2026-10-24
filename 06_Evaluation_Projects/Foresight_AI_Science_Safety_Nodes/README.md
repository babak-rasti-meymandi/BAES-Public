# Evaluating Human Authorization and Semantic Deviation in AI-Assisted Engineering

**Project record:** Foresight Institute — AI for Science & Safety Nodes  
**Focus area:** II. Coordination and Accountability — Human Empowerment  
**Applicant:** Babak Rasti M.  
**Project:** BAES — Babak AI Engineering Standard  
**Status:** Proposal drafted; project preparation in progress  
**Proposed duration:** 12 weeks after commencement and funding  
**Proposed request:** USD 30,000

## Purpose

This project proposes a bounded, evidence-based evaluation of whether explicit distinctions among human intent, delegated authority, execution behavior, and subsequent approval help identify unauthorized changes and unresolved authorization questions in AI-assisted engineering.

The initial test case is a software migration in which a human explicitly instructs an AI system to preserve existing behavior. The AI changes an edge case while attempting to correct a defect, the tests pass, and a human approves the pull request. The evaluation asks what the available evidence establishes about the deviation and whether the approval demonstrates informed authorization.

The project will evaluate BAES rather than presume it is effective. Negative findings, ambiguity, false positives, missed deviations, and limitations are in scope.

## Research questions

1. **Deviation detection:** Can a defined protocol distinguish execution consistent with explicit human intent from execution that changes specified behavior?
2. **Authorization evidence:** Can the evidence distinguish explicit acceptance of a disclosed deviation from approval where understanding or authorization is not established?
3. **Evidence sufficiency:** What evidence is needed to connect human intent, delegated authority, execution, and subsequent decisions?
4. **Practical value:** Does a BAES-based evaluation improve results over a predefined baseline that does not explicitly represent these distinctions?

## Planned method

1. Define the protocol, baseline, criteria, and evidence requirements before the main evaluation.
2. Build reproducible scenario variants, including unauthorized deviation, explicit disclosure and acceptance, and approval without sufficient evidence of informed authorization.
3. Run controlled AI-assisted evaluations and preserve relevant prompts, model/version details, inputs, criteria, and outputs where feasible.
4. Compare both approaches on the same cases; report detected and missed deviations, false positives, unresolved authorization questions, and limitations.
5. Publish the agreed research outputs for independent inspection and reproduction.

AI-generated assessments will not be treated as independent ground truth. Human review will be used to examine the protocol and ambiguous or inconsistent results.

## Planned deliverables

- Public evaluation protocol and criteria.
- Reproducible scenario/test suite.
- Limited working demonstration of the evaluation process.
- Comparative results, including negative findings and failure cases.
- Final report with limitations and reproducibility instructions.

## Relationship to BAES and intellectual-property boundary

BAES is a pre-existing, independently developed standard. This project is intended to be a separable evaluation work package, not a proposal to create BAES from scratch.

The proposed public outputs are the project-specific evaluation methods and criteria, test cases, reproducibility materials, applicable evaluation code, results, and final report. The complete pre-existing BAES corpus is not proposed as a funded deliverable.

Before accepting funding, the boundary between pre-existing materials and newly funded work, applicable licenses, and any rights required by the funder must be made explicit and agreed. Project outputs will not be excluded from required open release merely because they relate to BAES; any exclusions must be identified and comply with the funder's terms.

## Proposed work plan

| Period | Work |
|---|---|
| Weeks 1–2 | Protocol, baseline, evidence criteria |
| Weeks 3–5 | Scenario construction and reproducibility setup |
| Weeks 6–9 | Controlled evaluation and comparison |
| Weeks 10–11 | Independent review of protocol and selected findings, if feasible |
| Week 12 | Analysis and public release |

This is a proposed schedule beginning after funding and necessary arrangements are in place, not a claim that work has already commenced under a grant.

## Proposed budget

| Item | Amount (USD) |
|---|---:|
| Applicant research, engineering, and execution | $18,000 |
| Compute and research infrastructure | $1,500 |
| Conditional travel, visa-related costs, and accommodation | $5,000 |
| Independent review | $2,000 |
| Public release and reproducibility preparation | $1,000 |
| Directly related overhead | $2,500 |
| **Total** | **$30,000** |

The budget is provisional and subject to the funder's cost rules and agreement on the work plan. The applicant cannot personally pre-finance the evaluation. Travel is conditional on funding, visa eligibility, and feasible arrangements; if in-person participation is not possible, any budget or participation change must be agreed with the funder.

## In-person participation

The applicant is willing to travel to a Foresight Node in San Francisco or Berlin if a visa is granted and the project covers necessary travel and accommodation. Visa issuance and self-funded international travel are not guaranteed.

## Scope and limitations

The pilot investigates one bounded mechanism by which delegated AI execution can diverge from human intent. A software migration scenario alone cannot establish a reduction in existential AI risk or general effectiveness across all engineering settings. Any broader claims would require further evaluation.

## Project navigation

- [To-do list and project status](ToDo-List.md)
- [BAES public repository](https://github.com/babak-rasti-meymandi/BAES-Public)
- [BAES introduction](../../01_BAES_Introduction.md)

## Source of truth

Use [ToDo-List.md](ToDo-List.md) to track status, decisions, open questions, and next actions. Mark work complete only when the corresponding artifact or evidence exists. Keep private BAES development records and confidential strategy out of this public project folder.
