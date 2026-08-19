# Study Design and Methods

## Start with the Analytical Logic

Open the section by stating:

- the research object and unit of analysis;
- the relationship to be estimated or decision to be optimized;
- the main inputs and outputs;
- how the stages connect;
- why this design fits the research questions and data environment.

Show a framework figure before dense equations when the study has multiple stages. The figure should reveal information flow, not merely list boxes.

## Study Context and Data

Treat the study area and data as part of identification and transferability.

Report as relevant:

- city/region, study boundary, year and time period;
- transport supply, network, population, land use, and institutional context;
- sampling frame, recruitment, response, exclusions, and final sample;
- trip, traveler, household, traffic zone, OD pair, raster, or facility as the observational unit;
- variable definitions, scales, coding, missingness, and transformations;
- data provenance, access date/version, temporal alignment, and spatial resolution;
- representativeness or selection concerns;
- ethics/consent and privacy for human or trace data where applicable.

Explain why the location is analytically informative. “A large city” is not enough; name the features that affect the phenomenon and the conditions required for transfer.

## Survey and Behavioral Studies

Clarify:

- construct definitions and how items operationalize them;
- questionnaire or experiment structure and scenario framing;
- pilot testing, burden, comprehension, and choice-set design;
- sample size rationale and comparison with the target population;
- scale reliability/validity and whether dimension reduction is exploratory or confirmatory;
- model outcome, alternatives, reference categories, interactions, and heterogeneity;
- identification assumptions and treatment of repeated observations;
- fit, predictive/holdout checks when appropriate, uncertainty, and marginal effects.

For nonlinear choice models, equations and coefficient signs are not the final interpretation. State how probabilities, elasticities, willingness-to-pay, or marginal/partial effects answer the research question.

## Demand Forecasting for Emerging Modes

Define exactly what is forecast: person trips, vehicle trips, OD flows, adoption probability, market share, or covered demand. Then separate:

- observed base-year inputs;
- calibrated model quantities;
- parameters transferred from prior studies or other cities/modes;
- expert-assigned values;
- scenario assumptions;
- forecast outputs.

Explain why the chosen forecasting family fits the evidence constraints. Sparse historical UAM operations do not by themselves justify any particular method. Discuss alternatives and why their data or identification demands are or are not met.

Use scenario language when outcomes depend materially on uncertain future prices, regulation, technology, service levels, or modal shares. Provide ranges or sensitivity tests for decision-critical inputs.

## Spatial Planning and Optimization

Make the planning problem reproducible:

- candidate-site generation and exclusion criteria;
- demand representation and assignment;
- accessibility or service-radius definition;
- objective functions and their units/direction;
- hard constraints versus soft penalties;
- capacity, fleet, budget, safety, noise, airspace, terrain, and connectivity assumptions;
- weighting or Pareto selection and who supplies preferences;
- solver/algorithm, stopping criteria, runs/seeds, and hardware only when relevant;
- baselines and comparison methods;
- feasibility and optimality status.

For multi-objective models, explain why objectives conflict, how scales are normalized, how weights are derived, and how a final alternative is selected from trade-off solutions. A weighted sum is a decision rule, not neutral truth.

For integrated demand-location studies, specify the coupling: Does location change generalized cost or mode share? Does forecast demand enter coverage or capacity? Is there feedback or only one-way transfer? Use “joint,” “integrated,” and “endogenous” precisely.

## Assumption Ledger

Maintain this table during drafting:

| Input/assumption | Status | Source or rationale | Uncertainty/test | Claims affected |
|---|---|---|---|---|
| 2030 modal share | scenario | transferred study/expert range | vary across plausible levels | demand and facility count |
| service radius | assumed/calibrated | access-time or planning standard | alternative radii | coverage and accessibility |

If an assumption changes the preferred planning decision, highlight it in Results and Conclusion.

## Methods Check

- Can a reader trace every major output to data and assumptions?
- Are constructs and units consistent across stages?
- Is the method justified against realistic alternatives?
- Are borrowed parameters transferable in time, geography, and population?
- Are constraints and objective terms free from double-counting?
- Do validation claims match what was actually tested?
