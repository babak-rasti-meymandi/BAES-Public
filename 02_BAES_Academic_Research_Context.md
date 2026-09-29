# BAES — Academic & Research Context

**Audience:** Universities, research institutes, research groups, and engineering-science communities

## 1. The Research Problem

BAES examines an engineering problem arising from increasingly capable AI systems.

As AI systems move from information retrieval toward sustained investigation, reasoning, tool use, recommendation, delegation, and autonomous or semi-autonomous execution, several concepts may become tightly coupled within the same system:

* human intent;
* technical capability;
* delegated authority;
* AI reasoning;
* evidence;
* recommendation;
* human decision; and
* authorized execution.

These concepts are related, but they are not necessarily equivalent.

A central question for BAES is whether these distinctions can be represented explicitly enough within engineering systems to remain understandable, traceable, reviewable, and governable as AI capability increases.

BAES therefore proposes an engineering structure for examining these relationships.

The structure itself remains subject to examination, testing, criticism, comparison, and refinement.

## 2. Why This May Be Research-Worthy

The problem intersects several established research areas without being reducible to any one of them.

Relevant areas include:

* Human–AI Interaction;
* Human–Computer Interaction;
* AI and agentic systems;
* software and systems engineering;
* socio-technical systems;
* AI assurance and safety;
* authorization and delegation;
* provenance and traceability;
* distributed decision-making; and
* governance of technical systems.

BAES does not claim to replace these fields.

Instead, it proposes an engineering surface through which relationships between them can be described and examined explicitly.

## 3. Central Conceptual Relationship

The current BAES conceptual representation is:

**Human Intent → Delegation → AI Investigation / Reasoning → Evidence → Recommendation / Challenge → Human Decision → Authorized Execution → Result → Traceability**

This is a conceptual representation rather than a prescribed workflow.

It is intended to make distinctions visible that can otherwise become implicit within increasingly complex AI-enabled systems.

## 4. Research Questions

The current formulation of BAES opens questions such as:

### Conceptual Questions

* Are the proposed distinctions between intent, authority, reasoning, evidence, decision, and execution sufficiently precise?
* Which distinctions are fundamental and which are engineering representations?
* Are any important concepts missing?

### Engineering Questions

* Can the proposed distinctions be represented in practical AI-enabled systems?
* Can they remain meaningful across different system architectures?
* Can they support reviewable and traceable execution?
* Where do the proposed boundaries become difficult or impossible to maintain?

### Cross-Domain Questions

* Do the distinctions remain meaningful across software engineering, scientific research, medicine, law, archaeology, linguistics, and other domains?
* Which aspects are domain-independent?
* Which require domain-specific profiles or policies?

### Comparative Questions

* How does the proposed structure relate to existing approaches in Human–AI Interaction, agent systems, authorization, assurance, provenance, safety engineering, and governance?
* Does BAES provide useful distinctions that are absent, implicit, or differently represented in existing approaches?
* Where does BAES overlap with existing work, and where does it not?

### Empirical Questions

* Can the proposed structure be evaluated using realistic AI-enabled systems?
* Does explicit representation of authority, evidence, decisions, and execution improve traceability or reviewability?
* What failure modes appear when these distinctions are not explicit?

These questions are intentionally open. The public record does not assume their answers.

## 5. Proposed Evaluation Dimensions

For future examination of the public formulation, BAES proposes the following dimensions:

* **Conceptual clarity**
* **Boundary distinguishability**
* **Cross-domain stability**
* **Traceability**
* **Reviewability**
* **Implementability**
* **Failure/counterexample resistance**

**These are proposed evaluation dimensions, not validated results.**

This section identifies possible examination dimensions only; it does not report empirical validation or claim that BAES has already been demonstrated against them.

## 6. Research Character

BAES is deliberately technology-neutral and domain-independent.

This allows the proposed engineering structure to be examined across different AI architectures, implementations, organizational settings, and application domains.

Potential research methods include:

* conceptual analysis;
* formal or semi-formal modeling;
* engineering experiments;
* agent-system studies;
* traceability studies;
* comparative analysis with existing standards and frameworks;
* case studies; and
* empirical investigation of Human–AI interaction.

The appropriate method depends on the research question being investigated.

## 7. Relationship to Existing Research and Standards

BAES is presented within an existing body of research and engineering practice rather than as an isolated discipline.

Selected points of reference include:

* **Human–AI Interaction:** Amershi et al., *Guidelines for Human–AI Interaction*, CHI 2019. The work presents 18 design guidelines and reports multiple rounds of evaluation. citeturn1search3
* **AI assurance and risk:** NIST, *Artificial Intelligence Risk Management Framework (AI RMF 1.0)*, NIST AI 100-1 (2023). NIST describes it as a voluntary, use-case-agnostic framework for managing AI risks. citeturn1search6
* **Authorization:** NIST SP 800-162, *Guide to Attribute Based Access Control (ABAC) Definition and Considerations*. It provides a formalized treatment of authorization based on attributes, policies, rules, and relationships. citeturn2search0
* **Provenance:** W3C, *PROV Overview* and *PROV Model Primer*. PROV provides a model and related specifications for representing provenance information and the entities, activities, and agents involved in producing or influencing an object. citeturn1search0turn1search7
* **Ethical and socio-technical systems engineering:** IEEE 7000-2021, *IEEE Standard Model Process for Addressing Ethical Concerns during System Design*, provides a systems-engineering process for incorporating ethical values and traceability into system design. citeturn2search14
* **AI management and governance:** ISO/IEC 42001:2023 specifies requirements for establishing, implementing, maintaining, and continually improving an AI management system within an organization. citeturn2search12

These references are not presented as endorsements of BAES, nor as evidence that BAES is equivalent to any of them. They are points of comparison for future examination.

## 8. Example Research Environment

Consider an AI-assisted engineering system that investigates a production failure.

The system may:

1. receive a human-defined objective;
2. operate within delegated authority;
3. inspect authorized information;
4. develop hypotheses;
5. distinguish observations from assumptions;
6. collect and evaluate evidence;
7. produce recommendations;
8. receive a human decision;
9. execute an authorized action; and
10. record the resulting activity and outcome.

A research study can examine whether the resulting engineering record clearly distinguishes:

* the original human objective;
* delegated authority;
* information gathered by the AI;
* AI reasoning and hypotheses;
* evidence;
* recommendations;
* human decisions;
* authorization for execution;
* executed actions; and
* resulting traceability.

The example is intentionally simple. Its purpose is to provide a concrete environment in which the proposed distinctions can be examined.

It is not a claim that BAES is required for such systems.

## 9. Cross-Domain Research Example — Archaeological Research

Consider an archaeological and historical-linguistic research task involving Achaemenid Old Persian cuneiform.

A researcher may ask an AI system to investigate the meaning and historical relationships of terms such as **patikara-** and **pīruš**.

The documented Old Persian form **patikara-** is glossed as “representation, statue, picture” in an Old Persian–English glossary, and is attested in Achaemenid inscriptions. citeturn0search41turn0search2

The Old Persian form **pīruš** is attested in Darius I's Susa inscription DSf with the meaning “ivory”; Encyclopaedia Iranica relates Old Persian *pīru-* to the wider Near Eastern *pīru/pēru* word family associated with elephant/ivory terminology. citeturn0search1turn0search0

For BAES, the research point is not to pre-judge either etymological question. The AI could be delegated to:

1. locate inscriptional attestations and authoritative lexical sources;
2. compare forms, meanings, chronology, and proposed historical relationships;
3. distinguish documented evidence from hypotheses;
4. present competing interpretations and uncertainty;
5. recommend which claims require further human review; and
6. leave acceptance of an interpretation and any resulting research-record change to the authorized researcher.

The same BAES distinctions therefore become visible in a domain that is not software engineering: human research intent, delegated AI investigation, evidence, recommendation or challenge, human decision, authorized modification of a research record, and traceability.

The example is illustrative. It does not assert that a proposed relationship between *patikara-* and English *picture*, or between *pīruš* and later forms, is established merely because the forms can be compared.

## 10. Current Status

BAES is an independent engineering standard under development.

The current public record describes the present formulation and its development as a documented engineering effort.

BAES is not presented here as a formally recognized academic or external standard.

Its concepts, boundaries, models, and applicability remain open to external examination and research.

## 11. Potential Institutional Engagement

Academic institutions and research groups may find BAES relevant to:

* research collaboration;
* interdisciplinary research programs;
* Human–AI and agent-system research;
* software and systems engineering research;
* AI assurance and traceability studies;
* doctoral or postdoctoral research topics;
* experimental studies of agentic systems; and
* research connecting technical systems with organizational decision structures.

Possible engagement could include independent critique, comparative analysis, formalization, empirical evaluation, implementation experiments, or collaborative research.

The public record is intentionally concise. Detailed research planning should be developed within the context of a specific research question, research group, or institutional program.

---

**BAES — Babak AI Engineering Standard**
