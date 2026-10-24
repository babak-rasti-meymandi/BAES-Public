# Project To-Do List

**Project:** Evaluating Human Authorization and Semantic Deviation in AI-Assisted Engineering  
**Funder opportunity:** Foresight Institute — AI for Science & Safety Nodes  
**Last updated:** 2026-10-24  
**Current status:** Proposal drafted; application requirements and project artifacts still need verification/completion.

This file is the working status record. Update it when an action is completed, and link the resulting artifact or evidence where possible. Do not mark an item complete based only on intention.

## Status legend

- [x] Completed or already established before this project folder was created.
- [ ] Not yet verified or not yet completed.
- [!] Decision, dependency, or risk requiring explicit resolution.

## 1. Work already done

- [x] BAES exists as a pre-existing, independently developed technology-neutral standard for Human–AI Engineering Interaction.
- [x] The core pilot problem is defined: an AI system changes existing behavior despite an explicit instruction to preserve it.
- [x] The important scenario distinctions are identified: unauthorized deviation, explicit disclosure and acceptance, and pull-request approval without sufficient evidence of informed authorization.
- [x] A draft grant proposal has been prepared with four research questions, a five-phase method, deliverables, a proposed 12-week schedule, a USD 30,000 budget, open-publication intent, and an intellectual-property boundary.
- [x] The applicant's travel position is defined: willing to attend a Foresight Node if a visa is granted and travel/accommodation are covered; no personal pre-financing of the evaluation.
- [x] This public project folder, its overview, and this task tracker have been created.

## 2. Immediate priorities — before submission

- [ ] **Verify the current call requirements.** Confirm eligibility for an independent applicant, the exact deadline and time zone, required application route/fields, funding range, Node attendance expectations, and any geographic or residency restrictions.
- [ ] **Map the proposal to the call.** Confirm that “II. Coordination and Accountability — Human Empowerment” is the correct current focus-area wording and that the project directly satisfies its criteria.
- [ ] **Prepare the application-ready version.** Adapt the proposal to the actual form or submission instructions; do not assume this narrative alone is a valid submission.
- [ ] **Check the scope and claims.** Keep claims bounded; do not imply that the pilot establishes broad AI safety impact or that BAES has already demonstrated effectiveness.
- [ ] **Confirm the budget against funder rules.** In particular, verify applicant compensation, overhead, compute, independent review, travel, visa, and accommodation eligibility. Do not assume the $2,500 overhead or $5,000 travel line will be accepted.
- [ ] **Resolve the open-source/IP boundary in writing.** Identify what is pre-existing BAES material versus new funded work, and verify what license and rights the funder requires for each funded output.
- [ ] **Make travel contingency explicit.** State that attendance depends on visa issuance and funded travel; ask how the travel allocation should be handled if attendance is impossible.
- [ ] **Assemble supporting links.** Check the public BAES repository, the relevant scenario or pilot material, and applicant profile for accuracy and accessibility.
- [ ] **Final consistency review.** Ensure the title, applicant identity, focus area, timeline, deliverables, budget total, and open-publication commitments agree across all materials.
- [ ] **Submit only after the actual application requirements are verified.** Record the submission date, confirmation, and any follow-up obligations here.

## 3. Research design — protocol and baseline

- [ ] Define the unit of analysis and what counts as a semantic/behavioral deviation.
- [ ] Specify how the original human instruction and its scope are represented as the reference.
- [ ] Define observable evidence for execution, disclosure, review, approval, and explicit acceptance.
- [ ] Define outcome categories before running the main evaluation: compliant execution, detected deviation, missed deviation, false positive, authorization established, authorization not established, and unresolved/insufficient evidence.
- [ ] Predefine scoring rules and adjudication procedure so that results are not retrofitted to favor BAES.
- [ ] Specify the baseline method precisely. It must be credible, reproducible, and evaluated on the same cases and evidence as the BAES-based method.
- [ ] Decide whether evaluators will be blinded to condition or method where feasible.
- [ ] Record limitations, confounders, and the small-pilot/generalization boundary.

## 4. Scenario suite and evidence

- [ ] Formalize the primary migration scenario: legacy deposit-interest module; instruction to preserve existing behavior; AI changes a rare compound-interest edge case; tests pass; human approves a pull request.
- [ ] Create a case where the deviation is unauthorized and evidence clearly establishes the original instruction.
- [ ] Create a case where the AI discloses the proposed deviation and the human explicitly accepts it through an identifiable authorization event.
- [ ] Create a case where the pull request is approved but the evidence does not establish that the deviation was understood or authorized.
- [ ] Define evidence artifacts for each case (for example: original instruction, relevant before/after behavior, diff, test results, disclosure, review record, and authorization record).
- [ ] Separate scenario facts from evaluator interpretations.
- [ ] Create expected classifications and a rationale for each test case before running the evaluation.
- [ ] Add further variants only where they distinguish competing explanations or test a stated research question.
- [ ] Remove confidential, personal, or otherwise restricted material from public test fixtures.

## 5. Evaluation implementation and execution

- [ ] Decide the minimum viable demonstration and avoid building a larger software product than the research requires.
- [ ] Record model/provider, model version, run date, prompts, inputs, settings, outputs, and failures where technically feasible.
- [ ] Establish repeat-run rules and how nondeterministic outputs will be handled.
- [ ] Run both BAES-based and baseline evaluations against identical scenario/evidence conditions.
- [ ] Preserve raw outputs separately from normalized labels and final analysis.
- [ ] Have a human review ambiguous classifications and disagreements; do not treat AI output as ground truth.
- [ ] Calculate and report counts/rates for detected deviations, missed deviations, false positives, and unresolved authorization questions, with denominators and case definitions.
- [ ] Document all protocol changes made after initial runs and distinguish exploratory results from confirmatory results.

## 6. Review, publication, and final reporting

- [ ] Identify a feasible independent reviewer and confirm availability, scope, compensation, and independence before budgeting them as committed.
- [ ] Prepare a reproducibility package with protocol, scenarios, evaluation instructions, relevant code, and data/output formats.
- [ ] Write the report with methods, baseline, results, failures, negative findings, limitations, and future work.
- [ ] Check that public artifacts do not accidentally disclose the complete pre-existing BAES corpus or other restricted materials.
- [ ] Apply the license and release conditions agreed with the funder.
- [ ] Publish the funded outputs and link them from this folder.
- [ ] Update the project overview and record the final grant/project status.

## 7. Proposed 12-week execution sequence

| Period | Planned work | Exit condition |
|---|---|---|
| Weeks 1–2 | Protocol, baseline, criteria, evidence definitions | Protocol and comparison baseline fixed before main evaluation |
| Weeks 3–5 | Scenario suite and reproducibility setup | Cases, evidence bundles, and expected classifications documented |
| Weeks 6–9 | Controlled runs and comparison | Evaluation outputs and failures recorded for both approaches |
| Weeks 10–11 | Independent review, if feasible | Review comments and dispositions recorded |
| Week 12 | Analysis and release | Final report and agreed public artifacts released |

The schedule begins only after funding and necessary arrangements. It is a proposal, not evidence that the grant has been awarded or that funded work has begun.

## 8. Decisions and risks log

- [!] **Grant status:** Draft proposal exists. Submission, award, and funding are not confirmed in this record.
- [!] **Call requirements:** Must be verified against the current official call before submission.
- [!] **Baseline:** Not yet specified in sufficient operational detail; this is a central research-design task.
- [!] **Measurement validity:** Classification criteria must be fixed before the main evaluation to reduce confirmation bias.
- [!] **Independent review:** Proposed but not yet arranged.
- [!] **IP and licensing:** Final boundary and required licenses must be agreed before accepting funds.
- [!] **Travel:** Depends on visa issuance and funded costs; no self-funded travel is assumed.
- [!] **Budget eligibility:** All categories remain provisional until checked against funder rules.

## 9. Change log

- **2026-10-24:** Created the public project folder, README, and initial task tracker from the current grant-proposal draft and established BAES/pilot context.
