---
name: tc-writing-style
description: Draft, revise, and review applied transportation and low-altitude mobility papers, including travel behavior, demand forecasting, transport planning, UAM/eVTOL, GIS, infrastructure siting, survey/econometric analysis, optimization, and empirical case studies. Use when the paper must connect a real mobility or planning problem to defensible data, methods, findings, and stakeholder or policy implications; do not default to an ML-style task-model-benchmark narrative.
---

# Transportation and Low-Altitude Research Paper Writing

## Purpose

Write the paper as an applied transportation argument: a consequential mobility or planning problem motivates a researchable gap; the data and method are justified by that gap; results are interpreted as behavioral, spatial, operational, or policy evidence; and conclusions state where the evidence does and does not travel.

The narrative patterns in this skill were synthesized from two *Travel Behaviour and Society* papers listed in [references/narrative-logic.md](references/narrative-logic.md). Generalize their useful logic. Do not copy their wording, force their exact section structure, or reproduce their weaknesses.

## Format-Check Gate

At the start of **every invocation**, ask once whether the user wants the manuscript checked against the English submission template. Keep the question compact and offer exactly these choices:

1. **No format check** — continue the writing/revision task without loading the format specification. Recommend this when the user only needs content or argument work.
2. **Report only** — inspect formatting and return a location-specific noncompliance list; do not edit the manuscript.
3. **Auto-fix a copy** — let Codex correct formatting in a duplicate of the manuscript and return the revised file plus a change summary.

If the user has already explicitly requested one of these modes in the current message, do not ask again. If the user chooses no format check, do not read [references/submission-format.md](references/submission-format.md), inspect document layout, render pages, or spend tokens on format analysis. Continue the substantive task immediately.

Only after the user selects **Report only** or **Auto-fix a copy**, read [references/submission-format.md](references/submission-format.md) in full and follow its workflow. A complete layout audit or automatic repair requires an editable `.docx`; explain which checks are unavailable if the input is plain text or PDF. Never overwrite the source manuscript. When a journal's official author instructions conflict with this local template, flag the conflict and treat the journal instructions as controlling after the user confirms the target journal.

## Choose the Research Mode

Identify the dominant mode before editing. A paper may combine modes.

- **Travel behavior and demand:** choices, preferences, information use, acceptance, heterogeneity, surveys, stated/revealed preference, or econometric models.
- **Planning and infrastructure:** network or facility planning, vertiport/location selection, GIS, accessibility, coverage, cost, safety, noise, equity, or multi-objective optimization.
- **Emerging mobility and low-altitude systems:** UAM/eVTOL or other systems with sparse operational evidence, scenario-dependent demand, uncertain regulation, and strong ground-network or community interactions.

Read [references/narrative-logic.md](references/narrative-logic.md) to select the story shape. Then load only the section guide needed for the current request.

## Story Spine

Before sentence-level revision, write one line for each item:

1. **System context:** What transport system, behavior, or emerging service is changing?
2. **Decision problem:** Who must decide what, and why is the decision consequential?
3. **Knowledge gap:** What is unknown, weakly measured, fragmented, supply-driven, or empirically untested?
4. **Research questions:** What must be estimated, explained, compared, or optimized?
5. **Evidence strategy:** Why are these data, study area, measures, and methods fit for those questions?
6. **Findings:** What are the direction, magnitude, heterogeneity, trade-offs, and uncertainty?
7. **Contribution:** What new understanding, evidence, framework, or decision capability results?
8. **Implication and boundary:** Who can act on the finding, by what mechanism, and under what conditions?

If one item is missing, flag it instead of hiding the gap with polished prose.

## Core Writing Principles

1. Lead with the transport or planning problem, not the technique name.
2. Treat method choice as a consequence of the research question, data conditions, and decision setting. Method novelty is optional; fitness and transparency are required.
3. Organize literature by debates, approaches, decision factors, or evidence streams rather than by author chronology.
4. Make the study context part of the argument. Explain why the city, corridor, population, time period, or scenario is informative and what limits transferability.
5. Distinguish **observed**, **estimated**, **calibrated**, **borrowed**, **expert-assigned**, and **assumed/scenario** quantities. Never present prospective low-altitude demand as directly observed fact.
6. Interpret results beyond statistical significance or objective values: report magnitude, comparison, mechanism, heterogeneity or spatial pattern, uncertainty, and practical meaning when supported.
7. Use cautious causal language unless the design identifies causality. Prefer “is associated with,” “suggests,” or “is consistent with” for observational evidence.
8. Translate policy claims into an actor, action, mechanism, expected outcome, and boundary condition. Avoid generic calls for policymakers to “pay attention.”
9. Keep contribution claims proportional. A context-specific case study can provide valuable empirical or decision-support evidence without claiming universal validity.
10. Use one main message per paragraph, but vary paragraph structure naturally. A useful default is **message -> evidence -> interpretation -> link**.

## Evidence Discipline for Low-Altitude and Transport Studies

- Maintain an **assumption ledger** for forecast years, modal shares, price/cost inputs, noise or safety thresholds, expert weights, service radii, vehicle performance, and regulatory conditions.
- Explain how each consequential assumption was obtained and test sensitive or uncertain inputs where feasible.
- Separate technical feasibility, modeled desirability, market demand, public acceptance, regulatory permission, and real-world deployability; evidence for one does not establish the others.
- For integrated demand-location or demand-network models, show how demand enters candidate generation, objectives, constraints, capacity, coverage, or assignment. Do not call two disconnected stages “joint” without a real coupling mechanism.
- When discussing equity, accessibility, sustainability, safety, or social acceptance, state the operational measure. Do not infer these outcomes from efficiency alone.

## Workflow

1. Build or repair the story spine.
2. Reverse-outline the target section: paragraph role, claim, evidence, interpretation, and transition.
3. Load the relevant guide below and revise at the paragraph level.
4. Create a claim-evidence-implication map for major claims.
5. For prospective or parameter-heavy studies, create or update the assumption ledger.
6. Run the reviewer check in [references/domain-review.md](references/domain-review.md).
7. Weaken, qualify, relocate, or remove claims that outrun the evidence.
8. Run the format workflow only when the user opted in at the format-check gate.

Do not impose a full-paper rewrite when the user requests only diagnosis, polishing, or a single section. Preserve the user's substantive choices unless evidence or internal consistency requires a change, and explain such changes.

## Section Guides

- Abstract and Introduction: [references/abstract-introduction.md](references/abstract-introduction.md)
- Literature Review: [references/literature-review.md](references/literature-review.md)
- Study Design and Methods: [references/study-design-methods.md](references/study-design-methods.md)
- Results and Discussion: [references/results-discussion.md](references/results-discussion.md)
- Conclusion and Policy/Planning Implications: [references/conclusion-policy.md](references/conclusion-policy.md)
- Whole-paper and adversarial review: [references/domain-review.md](references/domain-review.md)
- Submission formatting and English mechanics (load only after opt-in): [references/submission-format.md](references/submission-format.md)

## Adaptive Output

Match the response to the request.

- **Draft or rewrite:** provide a compact story/section outline, the revised text, and a short claim-evidence-implication check.
- **Diagnose or review:** provide the reverse outline, prioritized issues, and concrete revision recommendations; do not rewrite everything unless asked.
- **Prospective UAM/eVTOL or parameterized planning study:** additionally provide an assumption ledger with `Input | Status | Source/rationale | Sensitivity/validation | Claim affected`.
- **Major empirical claims:** use `Claim | Evidence | Interpretation | Boundary | Status` where status is `supported`, `needs qualification`, or `needs evidence`.

Keep auxiliary analysis concise unless the user asks for a full audit.

For **Report only**, use `Location | Current formatting | Required formatting | Suggested fix | Severity | Confidence`, ordered from global/page-level problems to local issues. For **Auto-fix a copy**, preserve text, citations, fields, equations, comments, and tracked changes unless a specific correction requires otherwise; render and visually inspect every output page, then provide the revised `.docx`, a concise modification log, and any unresolved items requiring human judgment.
