# Narrative Logic Derived from the Two Reference Papers

## Source Papers

This guide synthesizes transferable patterns from:

1. Tang, Ho, Hensher, and Zhang, “Investigating traveller's overall information needs: What, when and how much is required by urban residents,” *Travel Behaviour and Society* 28 (2022), 155-169. DOI: 10.1016/j.tbs.2022.03.006.
2. Tang et al., “City Fly: Modeling demand and vertiport location jointly for urban commuting,” *Travel Behaviour and Society* 42 (2026), 101142. DOI: 10.1016/j.tbs.2025.101142.

These papers are references for argument architecture, not templates to copy.

## Shared Style

Both papers use a formal, applied-empirical style with five recurring qualities:

- **Decision relevance comes early.** The reader learns why the problem matters to travelers, service providers, planners, operators, or policymakers before receiving technical detail.
- **The gap is relational.** It is framed as a mismatch: system capability versus understanding of user needs; theoretical location models versus practical deployment; supply-side feasibility versus demand-side service; or operational efficiency versus social and environmental objectives.
- **Methods answer a problem-specific obstacle.** Inter-related survey items motivate dimension reduction and ordered choice modeling; sparse UAM history motivates a lower-data forecasting approach; multiple planning objectives motivate multi-objective optimization.
- **The case study carries the argument.** Chengdu is not a decorative example. Its population, transport system, spatial data, market conditions, and data availability define what can be estimated and how results should be interpreted.
- **Results become domain meaning.** Tables and model outputs are translated into traveler heterogeneity, information-service design, infrastructure scale, spatial coverage, operating trade-offs, noise exposure, and implementation limits.

The prose frequently uses explicit contrast and reader guidance: current capability **however** leaves an unresolved question; one stream of research addresses part of the issue **but** not the integrated decision; a descriptive pattern **suggests** an interpretation that a model then tests. Use this logic without overusing signposting words.

## Pattern A: Travel Behavior and Information/Demand Studies

The 2022 paper follows this argument chain:

1. Establish the capability and relevance of the transport information system.
2. Identify what remains poorly understood at the traveler level: the amount, type, timing, and heterogeneity of information demand.
3. Explain why the missing knowledge matters to both commercial/service actors and transport demand management.
4. State research questions and objectives in observable terms.
5. Review adjacent evidence streams: behavioral effects of information, attitudes or willingness to pay, and direct attempts to classify information needs.
6. Show why existing classifications or binary measures do not capture the full choice structure or intensity of demand.
7. Introduce a data and modeling design that reduces inter-related items and estimates preference differences.
8. Present diagnostics and descriptive patterns before model interpretation.
9. Translate nonlinear model results into marginal/partial effects and behavioral explanations rather than discussing coefficient signs alone.
10. End with service-design and policy implications, followed by limitations in measurement, population segmentation, and geographic transferability.

Use this shape for surveys, stated/revealed preference, acceptance, information use, mode choice, adoption, and traveler heterogeneity papers.

## Pattern B: Emerging Mobility and Infrastructure Planning Studies

The 2025 paper follows this argument chain:

1. Introduce the emerging mode and its plausible transport advantages.
2. Expand from the vehicle to urban-system consequences: commuting, land use, networks, and low-altitude services.
3. Identify an R&D imbalance: vehicle technology receives attention, while deployment, regulation, network integration, and infrastructure planning remain unresolved.
4. Focus on the planning object, here the vertiport, and explain why its location mediates service and social outcomes.
5. Develop two linked gaps: limited multi-objective treatment and insufficient integration of precise demand with site selection.
6. Reframe the decision from “where is construction feasible?” to “where is service needed, and how should feasibility and social costs shape provision?”
7. Organize literature into demand estimation and location selection, then subdivide location work by influencing factors and methods.
8. Synthesize the review into design requirements for the proposed framework.
9. Present the framework before equations, showing how demand forecasting and location optimization connect.
10. Use an empirical case to instantiate candidate sites, parameters, objectives, constraints, and solution choices.
11. Compare alternatives and vary uncertain parameters before claiming robustness or practical value.
12. Conclude with infrastructure implications and limitations tied to capacity dynamics, transfers, multimodal integration, and long-run feedback.

Use this shape for UAM/eVTOL, vertiports, emerging mobility, transport infrastructure siting, GIS-based planning, accessibility, and multi-objective network design.

## Combined Story for Mixed Studies

When a paper combines behavior/demand with planning/optimization, use this bridge:

`User or trip need -> demand representation -> spatial/temporal distribution -> planning decision -> operational/social trade-offs -> stakeholder outcome`

The paper should make every arrow explicit. If a survey estimate becomes an optimization input, explain aggregation and transfer. If demand is borrowed from another mode or city, label it as an analogy and test its influence. If a location decision changes generalized cost and therefore demand, discuss whether the model captures or omits that feedback.

## What to Preserve and What to Improve

Preserve:

- problem-first framing;
- stakeholder-specific motivation;
- literature organized into approach streams;
- method justification grounded in data and domain conditions;
- empirical interpretation, comparisons, and sensitivity analysis;
- limitations that point to concrete model or data extensions.

Improve rather than imitate:

- Do not repeat “novel,” “transformative,” or “significant contribution” without a precise comparator and evidence.
- Do not turn expected future demand into a factual forecast without scenario and uncertainty language.
- Do not claim broad generalizability from one city; identify the contextual features required for transfer.
- Do not offer speculative behavioral explanations as established mechanisms. Label them as possible interpretations and connect them to literature or additional tests.
- Do not equate an algorithm comparison with full empirical validation.
- Do not let long technical descriptions displace construct validity, data provenance, or planning meaning.

## Paragraph-Level Voice

Use a measured, explanatory voice:

- First sentence: the paragraph's domain claim or function.
- Middle: evidence, contrast, or mechanism.
- End: why the point matters for the research question or what the next paragraph must resolve.

Prefer concrete nouns such as “commuters,” “candidate vertiports,” “peak-period trips,” “noise-exposed residents,” and “demand coverage” over vague placeholders such as “this issue” or “the problem.” Define whether “demand” means trips, persons, willingness to use, latent utility, market share, or covered OD flows.
