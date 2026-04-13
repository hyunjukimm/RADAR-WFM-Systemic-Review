# Wearable Foundation Model Survey

This repository is a working survey hub for foundation models in wearable sensing, physiological time series, and ubiquitous computing. It is designed as a living companion to a literature review: a place to organize screened papers, expose the survey taxonomy, and keep the outline aligned with the evidence in the corpus.

The current outline is based on a post-eligibility pool of 250 papers and a taxonomy that separates:

- A backbone for survey framing
- Reader-facing overlays for application, method, architecture, and translation
- A clear boundary between core wearable foundation modeling and adjacent sensor-language work

## At a Glance

- Post-eligibility corpus: 250 papers
- Core wearable FM papers: 58
- Near-core candidates: 29
- Adjacent foundation-enabled sensing papers: 163
- Core + near-core shortlist for the main survey narrative: 87 papers

Two high-level patterns stand out from the current materials:

- Cardiovascular and neuro-sleep papers carry the strongest core evidence.
- Sensor-language and agentic work is growing quickly, but most of it sits in the adjacent layer rather than the signal-native core.

## Survey Goal

The goal of this repository is not only to list papers, but to support a survey that answers four questions:

1. What should count as a wearable foundation model?
2. Which sensing domains currently have the strongest evidence?
3. How should we organize the field so UbiComp readers can navigate it?
4. Where is the field moving next, especially around multimodality, deployment, and language interfaces?

## Taxonomy Design

The survey uses a backbone-plus-overlays structure.

### Backbone

The backbone keeps the main survey logic stable:

- Survey tier
  - Core wearable FM
  - Near-core candidate
  - Adjacent foundation-enabled sensing
- Level 1 sensing substrate
  - General wearable / systems
  - Behavior / activity / mobility
  - Cardiovascular / hemodynamic
  - Neuro / sleep
  - Metabolic / affective
  - Emerging / niche modalities
- Level 2 foundation-model coupling
  - Core time-series pretraining
  - Multimodal / cross-modal
  - Adaptation / personalization / deployment
  - Sensor-language / agentic

### Overlays

These overlays help readers find papers without replacing the backbone:

- Application cluster
- Method family
- Architecture family
- Openness status
- Real-world and validation cues

This framing keeps the core survey centered on signal-native wearable foundation models while still giving space to decision support, language interfaces, and translational concerns.

## Proposed Survey Outline

### 1. Introduction

- Why wearable foundation models matter now
- How wearable sensing differs from vision- and language-first foundation model settings
- Why UbiComp needs a systems-aware taxonomy instead of a model-only taxonomy

### 2. What Counts as a Wearable Foundation Model?

- Working definition of a wearable foundation model
- Inclusion boundary for wearable sensor data and signal-native pretraining
- Distinction between core wearable FMs and adjacent foundation-enabled sensing

### 3. Screening and Review Pipeline

- Eligibility logic for wearable sensor × foundation model papers
- Separation of exclusion criteria, inclusion criteria, and prioritization scores
- Role of borderline papers in shaping near-core discussion

### 4. Backbone View of the Literature

- Survey tiers: core, near-core, adjacent
- Level 1 sensing substrate landscape
- Level 2 FM coupling landscape
- Why the backbone is a stable organizing axis for the manuscript

### 5. Core Domain Chapters

These chapters should likely anchor the main survey:

- Cardiovascular / hemodynamic foundation models
- Neuro / sleep foundation models
- General wearable and multimodal physiological pretraining

These areas appear to have the clearest signal-native FM story and the strongest candidates for comparison tables.

### 6. Context and Boundary Chapters

These topics are important, but they should not displace the core narrative:

- Behavior / activity / mobility
- General wearable systems papers that are more enabling than foundational
- Sensor-language / agentic wearable health papers

A good writing move is to treat sensor-language work as a boundary or synthesis chapter: important, fast-growing, and worth analyzing, but mostly adjacent under the current wearable FM definition.

### 7. Overlay Views for Reader Navigation

These sections can cut across the backbone:

- Application pathways
  - Foundation / benchmark / transfer
  - Monitoring / estimation
  - Recognition / context understanding
  - Decision support / QA / reporting
- Method families
  - General self-supervised pretraining
  - Multimodal alignment / fusion
  - Generative / autoregressive / forecasting
  - Benchmark / evaluation
  - Language alignment / instruction tuning
- Architecture families
  - Transformer encoders
  - CNN-RNN or hybrid stacks
  - Dual-encoder or multimodal fusion setups
  - Architecture not clearly reported in title or abstract

### 8. Translation and Systems Questions

This section should foreground the UbiComp angle:

- Openness and reproducibility
- Validation beyond offline benchmarks
- Real-world deployment cues
- Personalization, transfer, and robustness to missingness
- Edge and on-device constraints

The current materials suggest that translational signals remain thinner than the overall paper count might imply, which is important to state plainly.

### 9. Gaps and Future Directions

- Strong concentration in cardiovascular and neuro-sleep domains
- Heavy adjacent growth in language-mediated wearable health work
- Sparse evidence in emerging modalities such as EMG, smart glasses, rings, audio, and pressure sensing
- Need for better reporting of architecture, openness, and real-world validation
- Need for broader corpora, cross-device robustness, and clinically meaningful evaluation

## Suggested Repository Structure

```text
.
├── README.md
├── CONTRIBUTING.md
├── data/
├── notes/
├── papers/
├── figures/
└── tables/
```

## Recommended Paper Metadata

For each paper, it is useful to track:

- Title
- Authors
- Venue and year
- Survey tier
- Level 1 sensing substrate
- Level 2 coupling type
- Application cluster
- Method family
- Architecture family
- Openness status
- Real-world or validation cues
- Key limitations

## How To Use This Repository

- Use the backbone taxonomy to structure the main manuscript.
- Use the overlays to build figures, comparison tables, and reviewer-friendly navigation.
- Keep core and adjacent papers visible at the same time, but do not blur the boundary between them.
- Update taxonomy tags as full-text synthesis becomes more precise.

## Contribution

Contributions are welcome for:

- Adding newly screened papers
- Refining taxonomy labels
- Building comparison tables
- Improving figures and survey narrative
- Updating code, dataset, and openness links

Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for contribution guidance.
