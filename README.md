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

## Core and Near-Core Papers

The main survey-facing paper set currently contains 87 papers:

- Core wearable FM: 58
- Near-core candidate: 29

The papers below are organized by sensing substrate and annotated with year, survey tier, coupling type, and application cluster.

### General Wearable / Systems

- Beyond Sensor Data: Foundation Models of Behavioral Data from Wearables Improve Health Predictions | 2025 | Core wearable FM | Core time-series pretraining | Risk / disease prediction
- PAPAGEI: OPEN FOUNDATION MODELS FOR OPTICAL PHYSIOLOGICAL SIGNALS | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- SCALING WEARABLE FOUNDATION MODELS | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Self-supervised Learning for Incomplete Multimodal Wearable Sensor Data | 2025 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- SensorLM: Learning the Language of Wearable Sensors | 2025 | Core wearable FM | Sensor-language / agentic | Foundation / benchmark / transfer
- LARGE-SCALE TRAINING OF FOUNDATION MODELS FOR WEARABLE BIOSIGNALS | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- NormWear: Foundation Model for Multivariate Wearable Physiological Signals | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Toward Foundation Model for Multivariate Wearable Sensing | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Efficient Personalized Adaptation for Physiological Signal Foundation Model | 2025 | Near-core candidate | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- HiMAE: Hierarchical Masked Autoencoders Discover Resolution-Specific Structure in Wearable Time Series | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- Towards on-device foundation models for raw wearable signals | 2025 | Near-core candidate | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- Transforming label-efficient decoding of healthcare wearables with self-supervised learning and embedded medical domain expertise | 2025 | Near-core candidate | Adaptation / personalization / deployment | Monitoring / estimation

### Behavior / Activity / Mobility

- FM-FoG: A Real-Time Foundation Model-based Wearable System for Freezing-of-Gait Mitigation. | 2025 | Core wearable FM | Adaptation / personalization / deployment | Recognition / context understanding
- Multimodal Foundation Model for Cross-Modal Retrieval and Activity Recognition Tasks | 2025 | Core wearable FM | Multimodal / cross-modal | Recognition / context understanding
- RELCON: RELATIVE CONTRASTIVE LEARNING FOR A MOTION FOUNDATION MODEL FOR WEARABLE DATA | 2025 | Core wearable FM | Core time-series pretraining | Recognition / context understanding
- Towards Customizable Foundation Models for HAR with Wearable Devices | 2025 | Core wearable FM | Adaptation / personalization / deployment | Recognition / context understanding
- A Novel Human Activity Recognition Framework Based on Pre-Trained Foundation Model | 2024 | Core wearable FM | Core time-series pretraining | Recognition / context understanding
- Solving the sensor-based activity recognition problem (SOAR): self-supervised, multi-modal recognition of activities from wearable sensors. | 2024 | Core wearable FM | Multimodal / cross-modal | Recognition / context understanding
- Wearable Accelerometer Foundation Models for Health via Knowledge Distillation | 2024 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- FM-Fi 2.0: Foundation Model for Cross-Modal Multi-Person Human Activity Recognition | 2026 | Near-core candidate | Multimodal / cross-modal | Recognition / context understanding
- AI foundation models for wearable movement data in mental health research | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- Federated fine-tuning of foundation models for human activity recognition using wearable data | 2025 | Near-core candidate | Adaptation / personalization / deployment | Recognition / context understanding
- Foundation Models for Wearable Movement Data in Mental Health Research | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- Detecting Daily Living Gait Amid Huntington's Disease Chorea using a Foundation Deep Learning Model | 2024 | Near-core candidate | Core time-series pretraining | Recognition / context understanding
- Is Attention All You Need For Actigraphy? Foundation Models of Wearable | 2024 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- Self-supervised learning for human activity recognition using 700,000 person-days of wearable data | 2024 | Near-core candidate | Core time-series pretraining | Recognition / context understanding
- Self-supervised learning of wrist-worn daily living accelerometer data improves the automated detection of gait in older adults. | 2024 | Near-core candidate | Core time-series pretraining | Recognition / context understanding
- IMU2CLIP: language-grounded motion sensor translation with multimodal contrastive learning | 2023 | Near-core candidate | Sensor-language / agentic | Recognition / context understanding

### Cardiovascular / Hemodynamic

- Cardiac health assessment across scenarios and devices using a multimodal foundation model pretrained on data from 1.7 million individuals | 2026 | Core wearable FM | Multimodal / cross-modal | Monitoring / estimation
- Wavelet-Driven Masked Multiscale Reconstruction for PPG Foundation Models | 2026 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- A robust PPG foundation model using multimodal physiological supervision | 2025 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- AnyECG-Lab: An Exploration Study of Fine-tuning an ECG Foundation Model to Estimate Laboratory Values from Single-Lead ECG Signals | 2025 | Core wearable FM | Adaptation / personalization / deployment | Monitoring / estimation
- BenchECG and xECG: a benchmark and baseline for ECG foundation models. | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- CLEF: Clinically-Guided Contrastive Learning for Electrocardiogram Foundation Models | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- ECGFM: A foundation model for ECG analysis trained on a multi-center million-ECG dataset | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Foundation model embeddings enable cardiovascular screening for people living with HIV in Vietnam using wearable signals | 2025 | Core wearable FM | Core time-series pretraining | Screening / detection / diagnosis
- Ppg-distill: Efficient photoplethysmography signals analysis via foundation model distillation | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- Pulse-PPG: An open-source field-trained PPG foundation model for wearable applications | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Self-DANA: A Resource-Efficient Channel-Adaptive Self-Supervised Approach for ECG Foundation Models | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- Vision4PPG: Emergent PPG Analysis Capability of Vision Foundation Models for Vital Signs like Blood Pressure | 2025 | Core wearable FM | Core time-series pretraining | Monitoring / estimation
- AnyECG: Foundational Models for Multitask Cardiac Analysis | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Foundation models for cardiovascular disease detection via biosignals from digital stethoscopes | 2024 | Core wearable FM | Core time-series pretraining | Screening / detection / diagnosis
- HeartBERT: A Self-Supervised ECG Embedding Model for Efficient and Effective Medical Signal Analysis | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- STP: Self-supervised transfer learning based on transformer for noninvasive blood pressure estimation using photoplethysmography. | 2024 | Core wearable FM | Core time-series pretraining | Monitoring / estimation
- SiamQuality: a ConvNet-based foundation model for photoplethysmography signals | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Wearable-Echo-FM: An ECG-Echo Foundation Model for Single Lead Electrocardiography | 2024 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- Zero-Shot Forecasting for ECG Time Series Data Using Generative Foundation Models | 2024 | Core wearable FM | Core time-series pretraining | Monitoring / estimation
- AnyPPG: An ECG-Guided PPG Foundation Model | 2025 | Near-core candidate | Multimodal / cross-modal | Foundation / benchmark / transfer
- Continuous Cardiac Arrest Prediction in ICU using PPG Foundation Model | 2025 | Near-core candidate | Core time-series pretraining | Risk / disease prediction
- ECG-MoE: Mixture-of-expert electrocardiogram foundation model | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- FairTune: A Bias-Aware Fine-Tuning Framework Towards Fair Heart Rate | 2025 | Near-core candidate | Adaptation / personalization / deployment | Monitoring / estimation
- Fusion of ECG Foundation Model Embeddings to Improve Early Detection of Acute Coronary Syndromes | 2025 | Near-core candidate | Adaptation / personalization / deployment | Screening / detection / diagnosis
- Leveraging Pretrained ECG-PPG Model for Continuous Blood Pressure Estimation | 2025 | Near-core candidate | Multimodal / cross-modal | Monitoring / estimation
- Adapting a generative pretrained transformer for PPG assessment | 2024 | Near-core candidate | Core time-series pretraining | Monitoring / estimation
- Foundation model of ECG diagnosis: Diagnostics and explanations of any form and rhythm on ECG | 2024 | Near-core candidate | Core time-series pretraining | Screening / detection / diagnosis
- ECGBERT: Understanding hidden language of ECGs with self-supervised learning | 2023 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- Wavelet-based masked multiscale reconstruction for ppg foundation models | ER  -JO - arXiv | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer

### Neuro / Sleep

- A multimodal sleep foundation model for disease prediction | 2026 | Core wearable FM | Multimodal / cross-modal | Risk / disease prediction
- FEMBA on the Edge: Physiologically-Aware Pre-Training, Quantization, and Deployment of a Bidirectional Mamba EEG Foundation Model on an Ultra-low Power Microcontroller | 2026 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- BrainPro: Towards Large-scale Brain State-aware EEG Representation Learning | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- FEMBA: Efficient and Scalable EEG Analysis with a Bidirectional Mamba Foundation Model | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Finetuning and Quantization of EEG-Based Foundational BioSignal Models | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- Foundation Models Reveal Untapped Health Information in Human Polysomnographic Sleep Data | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Foundation Models on Wearable EEG using Self-Supervised Learning | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- LEAD: Large Foundation Model for EEG-Based Alzheimer's Disease Detection | 2025 | Core wearable FM | Core time-series pretraining | Screening / detection / diagnosis
- Large cognition model: Towards pretrained eeg foundation model | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- REVE: A Foundation Model for EEG--Adapting to Any Setup with Large-Scale Pretraining on 25,000 Subjects | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- ST-CoG-XAI: A Spectro-Temporal Contrastive Generation Foundation Model for Explainable EEG Decoding | 2025 | Core wearable FM | Core time-series pretraining | Monitoring / estimation
- Sound-Based Sleep Staging using Pretrained Speech Foundation Models | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Toward Foundational Model for Sleep Analysis Using a Multimodal Hybrid Self-Supervised Learning Framework | 2025 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- EEGPT: Unleashing the potential of EEG generalist foundation model by autoregressive pre-training | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Eegformer: Towards transferable and interpretable large-scale eeg foundation model. | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Neuro-gpt: Towards a foundation model for eeg | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- NeuroLM: A universal multi-task foundation model for bridging the gap between language and EEG signals. | 2024 | Core wearable FM | Sensor-language / agentic | Foundation / benchmark / transfer
- Self-supervised transformer model training for a sleep-EEG foundation model | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- Multimodal foundation models are better simulators of the human brain | 2022 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- A generative foundation model for five-class sleep staging with arbitrary sensor input | ER  -JO - arXiv | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- Eeg-fm-bench: A comprehensive benchmark for EEG foundation models | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- SingLEM: Single-Channel Large EEG Model | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer

### Metabolic / Affective

- A foundation model for electrodermal activity data | 2026 | Core wearable FM | Core time-series pretraining | Recognition / context understanding
- A large sensor foundation model pretrained on continuous glucose monitor data for diabetes management | 2025 | Core wearable FM | Core time-series pretraining | Intervention / coaching / assistive
- Let Curves Speak: A CGM-based Large Sensor Foundation Model | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- A pretrained transformer model for decoding individual glucose dynamics from continuous glucose monitoring data | 2025 | Near-core candidate | Core time-series pretraining | Monitoring / estimation
- From glucose patterns to health outcomes: A generalizable foundation model for CGM data | 2024 | Near-core candidate | Core time-series pretraining | Risk / disease prediction
- Transformer-based self-supervised multimodal representation learning for wearable emotion recognition. | 2023 | Near-core candidate | Multimodal / cross-modal | Recognition / context understanding

### Emerging / Niche Modalities

- TinyMyo: a Tiny Foundation Model for Flexible EMG Signal Processing at the Edge | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- M-BEST-RQ: A Multi-Channel Speech Foundation Model for Smart Glasses | 2025 | Near-core candidate | Multimodal / cross-modal | Foundation / benchmark / transfer

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
