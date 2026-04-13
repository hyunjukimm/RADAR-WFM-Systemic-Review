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

- [Beyond Sensor Data: Foundation Models of Behavioral Data from Wearables Improve Health Predictions](https://scholar.google.com/scholar?q=Beyond%20Sensor%20Data%3A%20Foundation%20Models%20of%20Behavioral%20Data%20from%20Wearables%20Improve%20Health%20Predictions) | 2025 | Core wearable FM | Core time-series pretraining | Risk / disease prediction
- [PAPAGEI: OPEN FOUNDATION MODELS FOR OPTICAL PHYSIOLOGICAL SIGNALS](https://scholar.google.com/scholar?q=PAPAGEI%3A%20OPEN%20FOUNDATION%20MODELS%20FOR%20OPTICAL%20PHYSIOLOGICAL%20SIGNALS) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [SCALING WEARABLE FOUNDATION MODELS](https://scholar.google.com/scholar?q=SCALING%20WEARABLE%20FOUNDATION%20MODELS) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Self-supervised Learning for Incomplete Multimodal Wearable Sensor Data](https://openreview.net/forum?id=eOATzq7NvI) | 2025 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- [SensorLM: Learning the Language of Wearable Sensors](https://scholar.google.com/scholar?q=SensorLM%3A%20Learning%20the%20Language%20of%20Wearable%20Sensors) | 2025 | Core wearable FM | Sensor-language / agentic | Foundation / benchmark / transfer
- [LARGE-SCALE TRAINING OF FOUNDATION MODELS FOR WEARABLE BIOSIGNALS](https://scholar.google.com/scholar?q=LARGE-SCALE%20TRAINING%20OF%20FOUNDATION%20MODELS%20FOR%20WEARABLE%20BIOSIGNALS) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [NormWear: Foundation Model for Multivariate Wearable Physiological Signals](https://scholar.google.com/scholar?q=NormWear%3A%20Foundation%20Model%20for%20Multivariate%20Wearable%20Physiological%20Signals) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Toward Foundation Model for Multivariate Wearable Sensing](https://scholar.google.com/scholar?q=Toward%20Foundation%20Model%20for%20Multivariate%20Wearable%20Sensing) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Efficient Personalized Adaptation for Physiological Signal Foundation Model](https://scholar.google.com/scholar?q=Efficient%20Personalized%20Adaptation%20for%20Physiological%20Signal%20Foundation%20Model) | 2025 | Near-core candidate | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [HiMAE: Hierarchical Masked Autoencoders Discover Resolution-Specific Structure in Wearable Time Series](https://scholar.google.com/scholar?q=HiMAE%3A%20Hierarchical%20Masked%20Autoencoders%20Discover%20Resolution-Specific%20Structure%20in%20Wearable%20Time%20Series) | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- [Towards on-device foundation models for raw wearable signals](https://scholar.google.com/scholar?q=Towards%20on-device%20foundation%20models%20for%20raw%20wearable%20signals) | 2025 | Near-core candidate | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [Transforming label-efficient decoding of healthcare wearables with self-supervised learning and embedded medical domain expertise](https://scholar.google.com/scholar?q=Transforming%20label-efficient%20decoding%20of%20healthcare%20wearables%20with%20self-supervised%20learning%20and%20embedded%20medical%20domain%20expertise) | 2025 | Near-core candidate | Adaptation / personalization / deployment | Monitoring / estimation

### Behavior / Activity / Mobility

- [FM-FoG: A Real-Time Foundation Model-based Wearable System for Freezing-of-Gait Mitigation.](https://scholar.google.com/scholar?q=FM-FoG%3A%20A%20Real-Time%20Foundation%20Model-based%20Wearable%20System%20for%20Freezing-of-Gait%20Mitigation.) | 2025 | Core wearable FM | Adaptation / personalization / deployment | Recognition / context understanding
- [Multimodal Foundation Model for Cross-Modal Retrieval and Activity Recognition Tasks](https://scholar.google.com/scholar?q=Multimodal%20Foundation%20Model%20for%20Cross-Modal%20Retrieval%20and%20Activity%20Recognition%20Tasks) | 2025 | Core wearable FM | Multimodal / cross-modal | Recognition / context understanding
- [RELCON: RELATIVE CONTRASTIVE LEARNING FOR A MOTION FOUNDATION MODEL FOR WEARABLE DATA](https://scholar.google.com/scholar?q=RELCON%3A%20RELATIVE%20CONTRASTIVE%20LEARNING%20FOR%20A%20MOTION%20FOUNDATION%20MODEL%20FOR%20WEARABLE%20DATA) | 2025 | Core wearable FM | Core time-series pretraining | Recognition / context understanding
- [Towards Customizable Foundation Models for HAR with Wearable Devices](https://scholar.google.com/scholar?q=Towards%20Customizable%20Foundation%20Models%20for%20HAR%20with%20Wearable%20Devices) | 2025 | Core wearable FM | Adaptation / personalization / deployment | Recognition / context understanding
- [A Novel Human Activity Recognition Framework Based on Pre-Trained Foundation Model](https://doi.org/10.1109/BIBM62325.2024.10822159) | 2024 | Core wearable FM | Core time-series pretraining | Recognition / context understanding
- [Solving the sensor-based activity recognition problem (SOAR): self-supervised, multi-modal recognition of activities from wearable sensors.](https://scholar.google.com/scholar?q=Solving%20the%20sensor-based%20activity%20recognition%20problem%20%28SOAR%29%3A%20self-supervised%2C%20multi-modal%20recognition%20of%20activities%20from%20wearable%20sensors.) | 2024 | Core wearable FM | Multimodal / cross-modal | Recognition / context understanding
- [Wearable Accelerometer Foundation Models for Health via Knowledge Distillation](https://scholar.google.com/scholar?q=Wearable%20Accelerometer%20Foundation%20Models%20for%20Health%20via%20Knowledge%20Distillation) | 2024 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [FM-Fi 2.0: Foundation Model for Cross-Modal Multi-Person Human Activity Recognition](https://doi.org/10.1109/TMC.2025.3593406) | 2026 | Near-core candidate | Multimodal / cross-modal | Recognition / context understanding
- [AI foundation models for wearable movement data in mental health research](https://scholar.google.com/scholar?q=AI%20foundation%20models%20for%20wearable%20movement%20data%20in%20mental%20health%20research) | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- [Federated fine-tuning of foundation models for human activity recognition using wearable data](https://scholar.google.com/scholar?q=Federated%20fine-tuning%20of%20foundation%20models%20for%20human%20activity%20recognition%20using%20wearable%20data) | 2025 | Near-core candidate | Adaptation / personalization / deployment | Recognition / context understanding
- [Foundation Models for Wearable Movement Data in Mental Health Research](https://scholar.google.com/scholar?q=Foundation%20Models%20for%20Wearable%20Movement%20Data%20in%20Mental%20Health%20Research) | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- [Detecting Daily Living Gait Amid Huntington's Disease Chorea using a Foundation Deep Learning Model](https://scholar.google.com/scholar?q=Detecting%20Daily%20Living%20Gait%20Amid%20Huntington%27s%20Disease%20Chorea%20using%20a%20Foundation%20Deep%20Learning%20Model) | 2024 | Near-core candidate | Core time-series pretraining | Recognition / context understanding
- [Is Attention All You Need For Actigraphy? Foundation Models of Wearable](https://scholar.google.com/scholar?q=Is%20Attention%20All%20You%20Need%20For%20Actigraphy%3F%20Foundation%20Models%20of%20Wearable) | 2024 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- [Self-supervised learning for human activity recognition using 700,000 person-days of wearable data](https://scholar.google.com/scholar?q=Self-supervised%20learning%20for%20human%20activity%20recognition%20using%20700%2C000%20person-days%20of%20wearable%20data) | 2024 | Near-core candidate | Core time-series pretraining | Recognition / context understanding
- [Self-supervised learning of wrist-worn daily living accelerometer data improves the automated detection of gait in older adults.](https://scholar.google.com/scholar?q=Self-supervised%20learning%20of%20wrist-worn%20daily%20living%20accelerometer%20data%20improves%20the%20automated%20detection%20of%20gait%20in%20older%20adults.) | 2024 | Near-core candidate | Core time-series pretraining | Recognition / context understanding
- [IMU2CLIP: language-grounded motion sensor translation with multimodal contrastive learning](https://scholar.google.com/scholar?q=IMU2CLIP%3A%20language-grounded%20motion%20sensor%20translation%20with%20multimodal%20contrastive%20learning) | 2023 | Near-core candidate | Sensor-language / agentic | Recognition / context understanding

### Cardiovascular / Hemodynamic

- [Cardiac health assessment across scenarios and devices using a multimodal foundation model pretrained on data from 1.7 million individuals](https://doi.org/10.1038/s42256-026-01180-5) | 2026 | Core wearable FM | Multimodal / cross-modal | Monitoring / estimation
- [Wavelet-Driven Masked Multiscale Reconstruction for PPG Foundation Models](https://doi.org/10.48550/arXiv.2601.12215) | 2026 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [A robust PPG foundation model using multimodal physiological supervision](https://openreview.net/forum?id=ZmGfCj1n2P) | 2025 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- [AnyECG-Lab: An Exploration Study of Fine-tuning an ECG Foundation Model to Estimate Laboratory Values from Single-Lead ECG Signals](https://scholar.google.com/scholar?q=AnyECG-Lab%3A%20An%20Exploration%20Study%20of%20Fine-tuning%20an%20ECG%20Foundation%20Model%20to%20Estimate%20Laboratory%20Values%20from%20Single-Lead%20ECG%20Signals) | 2025 | Core wearable FM | Adaptation / personalization / deployment | Monitoring / estimation
- [BenchECG and xECG: a benchmark and baseline for ECG foundation models.](https://scholar.google.com/scholar?q=BenchECG%20and%20xECG%3A%20a%20benchmark%20and%20baseline%20for%20ECG%20foundation%20models.) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [CLEF: Clinically-Guided Contrastive Learning for Electrocardiogram Foundation Models](https://scholar.google.com/scholar?q=CLEF%3A%20Clinically-Guided%20Contrastive%20Learning%20for%20Electrocardiogram%20Foundation%20Models) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [ECGFM: A foundation model for ECG analysis trained on a multi-center million-ECG dataset](https://scholar.google.com/scholar?q=ECGFM%3A%20A%20foundation%20model%20for%20ECG%20analysis%20trained%20on%20a%20multi-center%20million-ECG%20dataset) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Foundation model embeddings enable cardiovascular screening for people living with HIV in Vietnam using wearable signals](https://scholar.google.com/scholar?q=Foundation%20model%20embeddings%20enable%20cardiovascular%20screening%20for%20people%20living%20with%20HIV%20in%20Vietnam%20using%20wearable%20signals) | 2025 | Core wearable FM | Core time-series pretraining | Screening / detection / diagnosis
- [Ppg-distill: Efficient photoplethysmography signals analysis via foundation model distillation](https://scholar.google.com/scholar?q=Ppg-distill%3A%20Efficient%20photoplethysmography%20signals%20analysis%20via%20foundation%20model%20distillation) | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [Pulse-PPG: An open-source field-trained PPG foundation model for wearable applications](https://scholar.google.com/scholar?q=Pulse-PPG%3A%20An%20open-source%20field-trained%20PPG%20foundation%20model%20for%20wearable%20applications) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Self-DANA: A Resource-Efficient Channel-Adaptive Self-Supervised Approach for ECG Foundation Models](https://scholar.google.com/scholar?q=Self-DANA%3A%20A%20Resource-Efficient%20Channel-Adaptive%20Self-Supervised%20Approach%20for%20ECG%20Foundation%20Models) | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [Vision4PPG: Emergent PPG Analysis Capability of Vision Foundation Models for Vital Signs like Blood Pressure](https://scholar.google.com/scholar?q=Vision4PPG%3A%20Emergent%20PPG%20Analysis%20Capability%20of%20Vision%20Foundation%20Models%20for%20Vital%20Signs%20like%20Blood%20Pressure) | 2025 | Core wearable FM | Core time-series pretraining | Monitoring / estimation
- [AnyECG: Foundational Models for Multitask Cardiac Analysis](https://scholar.google.com/scholar?q=AnyECG%3A%20Foundational%20Models%20for%20Multitask%20Cardiac%20Analysis) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Foundation models for cardiovascular disease detection via biosignals from digital stethoscopes](https://scholar.google.com/scholar?q=Foundation%20models%20for%20cardiovascular%20disease%20detection%20via%20biosignals%20from%20digital%20stethoscopes) | 2024 | Core wearable FM | Core time-series pretraining | Screening / detection / diagnosis
- [HeartBERT: A Self-Supervised ECG Embedding Model for Efficient and Effective Medical Signal Analysis](https://scholar.google.com/scholar?q=HeartBERT%3A%20A%20Self-Supervised%20ECG%20Embedding%20Model%20for%20Efficient%20and%20Effective%20Medical%20Signal%20Analysis) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [STP: Self-supervised transfer learning based on transformer for noninvasive blood pressure estimation using photoplethysmography.](https://scholar.google.com/scholar?q=STP%3A%20Self-supervised%20transfer%20learning%20based%20on%20transformer%20for%20noninvasive%20blood%20pressure%20estimation%20using%20photoplethysmography.) | 2024 | Core wearable FM | Core time-series pretraining | Monitoring / estimation
- [SiamQuality: a ConvNet-based foundation model for photoplethysmography signals](https://doi.org/10.1088/1361-6579/ad6747) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Wearable-Echo-FM: An ECG-Echo Foundation Model for Single Lead Electrocardiography](https://doi.org/10.1161/circ.150.suppl_1.4145351) | 2024 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- [Zero-Shot Forecasting for ECG Time Series Data Using Generative Foundation Models](https://scholar.google.com/scholar?q=Zero-Shot%20Forecasting%20for%20ECG%20Time%20Series%20Data%20Using%20Generative%20Foundation%20Models) | 2024 | Core wearable FM | Core time-series pretraining | Monitoring / estimation
- [AnyPPG: An ECG-Guided PPG Foundation Model](https://scholar.google.com/scholar?q=AnyPPG%3A%20An%20ECG-Guided%20PPG%20Foundation%20Model) | 2025 | Near-core candidate | Multimodal / cross-modal | Foundation / benchmark / transfer
- [Continuous Cardiac Arrest Prediction in ICU using PPG Foundation Model](https://scholar.google.com/scholar?q=Continuous%20Cardiac%20Arrest%20Prediction%20in%20ICU%20using%20PPG%20Foundation%20Model) | 2025 | Near-core candidate | Core time-series pretraining | Risk / disease prediction
- [ECG-MoE: Mixture-of-expert electrocardiogram foundation model](https://scholar.google.com/scholar?q=ECG-MoE%3A%20Mixture-of-expert%20electrocardiogram%20foundation%20model) | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- [FairTune: A Bias-Aware Fine-Tuning Framework Towards Fair Heart Rate](https://scholar.google.com/scholar?q=FairTune%3A%20A%20Bias-Aware%20Fine-Tuning%20Framework%20Towards%20Fair%20Heart%20Rate) | 2025 | Near-core candidate | Adaptation / personalization / deployment | Monitoring / estimation
- [Fusion of ECG Foundation Model Embeddings to Improve Early Detection of Acute Coronary Syndromes](https://scholar.google.com/scholar?q=Fusion%20of%20ECG%20Foundation%20Model%20Embeddings%20to%20Improve%20Early%20Detection%20of%20Acute%20Coronary%20Syndromes) | 2025 | Near-core candidate | Adaptation / personalization / deployment | Screening / detection / diagnosis
- [Leveraging Pretrained ECG-PPG Model for Continuous Blood Pressure Estimation](https://scholar.google.com/scholar?q=Leveraging%20Pretrained%20ECG-PPG%20Model%20for%20Continuous%20Blood%20Pressure%20Estimation) | 2025 | Near-core candidate | Multimodal / cross-modal | Monitoring / estimation
- [Adapting a generative pretrained transformer for PPG assessment](https://scholar.google.com/scholar?q=Adapting%20a%20generative%20pretrained%20transformer%20for%20PPG%20assessment) | 2024 | Near-core candidate | Core time-series pretraining | Monitoring / estimation
- [Foundation model of ECG diagnosis: Diagnostics and explanations of any form and rhythm on ECG](https://scholar.google.com/scholar?q=Foundation%20model%20of%20ECG%20diagnosis%3A%20Diagnostics%20and%20explanations%20of%20any%20form%20and%20rhythm%20on%20ECG) | 2024 | Near-core candidate | Core time-series pretraining | Screening / detection / diagnosis
- [ECGBERT: Understanding hidden language of ECGs with self-supervised learning](https://scholar.google.com/scholar?q=ECGBERT%3A%20Understanding%20hidden%20language%20of%20ECGs%20with%20self-supervised%20learning) | 2023 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- [Wavelet-based masked multiscale reconstruction for ppg foundation models](https://scholar.google.com/scholar?q=Wavelet-based%20masked%20multiscale%20reconstruction%20for%20ppg%20foundation%20models) | ER  -JO - arXiv | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer

### Neuro / Sleep

- [A multimodal sleep foundation model for disease prediction](https://doi.org/10.1038/s41591-025-04133-4) | 2026 | Core wearable FM | Multimodal / cross-modal | Risk / disease prediction
- [FEMBA on the Edge: Physiologically-Aware Pre-Training, Quantization, and Deployment of a Bidirectional Mamba EEG Foundation Model on an Ultra-low Power Microcontroller](https://doi.org/10.48550/arXiv.2603.26716) | 2026 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [BrainPro: Towards Large-scale Brain State-aware EEG Representation Learning](https://scholar.google.com/scholar?q=BrainPro%3A%20Towards%20Large-scale%20Brain%20State-aware%20EEG%20Representation%20Learning) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [FEMBA: Efficient and Scalable EEG Analysis with a Bidirectional Mamba Foundation Model](https://doi.org/10.1109/EMBC58623.2025.11252697) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Finetuning and Quantization of EEG-Based Foundational BioSignal Models](https://scholar.google.com/scholar?q=Finetuning%20and%20Quantization%20of%20EEG-Based%20Foundational%20BioSignal%20Models) | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [Foundation Models Reveal Untapped Health Information in Human Polysomnographic Sleep Data](https://scholar.google.com/scholar?q=Foundation%20Models%20Reveal%20Untapped%20Health%20Information%20in%20Human%20Polysomnographic%20Sleep%20Data) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Foundation Models on Wearable EEG using Self-Supervised Learning](https://doi.org/10.1109/EMBC58623.2025.11254670) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [LEAD: Large Foundation Model for EEG-Based Alzheimer's Disease Detection](https://scholar.google.com/scholar?q=LEAD%3A%20Large%20Foundation%20Model%20for%20EEG-Based%20Alzheimer%27s%20Disease%20Detection) | 2025 | Core wearable FM | Core time-series pretraining | Screening / detection / diagnosis
- [Large cognition model: Towards pretrained eeg foundation model](https://scholar.google.com/scholar?q=Large%20cognition%20model%3A%20Towards%20pretrained%20eeg%20foundation%20model) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [REVE: A Foundation Model for EEG--Adapting to Any Setup with Large-Scale Pretraining on 25,000 Subjects](https://scholar.google.com/scholar?q=REVE%3A%20A%20Foundation%20Model%20for%20EEG--Adapting%20to%20Any%20Setup%20with%20Large-Scale%20Pretraining%20on%2025%2C000%20Subjects) | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [ST-CoG-XAI: A Spectro-Temporal Contrastive Generation Foundation Model for Explainable EEG Decoding](https://doi.org/10.1109/JFLEX.2025.3620380) | 2025 | Core wearable FM | Core time-series pretraining | Monitoring / estimation
- [Sound-Based Sleep Staging using Pretrained Speech Foundation Models](https://doi.org/10.1109/EMBC58623.2025.11253429) | 2025 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Toward Foundational Model for Sleep Analysis Using a Multimodal Hybrid Self-Supervised Learning Framework](https://scholar.google.com/scholar?q=Toward%20Foundational%20Model%20for%20Sleep%20Analysis%20Using%20a%20Multimodal%20Hybrid%20Self-Supervised%20Learning%20Framework) | 2025 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- [EEGPT: Unleashing the potential of EEG generalist foundation model by autoregressive pre-training](https://scholar.google.com/scholar?q=EEGPT%3A%20Unleashing%20the%20potential%20of%20EEG%20generalist%20foundation%20model%20by%20autoregressive%20pre-training) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Eegformer: Towards transferable and interpretable large-scale eeg foundation model.](https://scholar.google.com/scholar?q=Eegformer%3A%20Towards%20transferable%20and%20interpretable%20large-scale%20eeg%20foundation%20model.) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Neuro-gpt: Towards a foundation model for eeg](https://scholar.google.com/scholar?q=Neuro-gpt%3A%20Towards%20a%20foundation%20model%20for%20eeg) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [NeuroLM: A universal multi-task foundation model for bridging the gap between language and EEG signals.](https://scholar.google.com/scholar?q=NeuroLM%3A%20A%20universal%20multi-task%20foundation%20model%20for%20bridging%20the%20gap%20between%20language%20and%20EEG%20signals.) | 2024 | Core wearable FM | Sensor-language / agentic | Foundation / benchmark / transfer
- [Self-supervised transformer model training for a sleep-EEG foundation model](https://scholar.google.com/scholar?q=Self-supervised%20transformer%20model%20training%20for%20a%20sleep-EEG%20foundation%20model) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [Multimodal foundation models are better simulators of the human brain](https://scholar.google.com/scholar?q=Multimodal%20foundation%20models%20are%20better%20simulators%20of%20the%20human%20brain) | 2022 | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- [A generative foundation model for five-class sleep staging with arbitrary sensor input](https://scholar.google.com/scholar?q=A%20generative%20foundation%20model%20for%20five-class%20sleep%20staging%20with%20arbitrary%20sensor%20input) | ER  -JO - arXiv | Core wearable FM | Multimodal / cross-modal | Foundation / benchmark / transfer
- [Eeg-fm-bench: A comprehensive benchmark for EEG foundation models](https://scholar.google.com/scholar?q=Eeg-fm-bench%3A%20A%20comprehensive%20benchmark%20for%20EEG%20foundation%20models) | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer
- [SingLEM: Single-Channel Large EEG Model](https://doi.org/10.48550/arXiv.2509.17920) | 2025 | Near-core candidate | Core time-series pretraining | Foundation / benchmark / transfer

### Metabolic / Affective

- [A foundation model for electrodermal activity data](https://doi.org/10.48550/arXiv.2603.16878) | 2026 | Core wearable FM | Core time-series pretraining | Recognition / context understanding
- [A large sensor foundation model pretrained on continuous glucose monitor data for diabetes management](https://scholar.google.com/scholar?q=A%20large%20sensor%20foundation%20model%20pretrained%20on%20continuous%20glucose%20monitor%20data%20for%20diabetes%20management) | 2025 | Core wearable FM | Core time-series pretraining | Intervention / coaching / assistive
- [Let Curves Speak: A CGM-based Large Sensor Foundation Model](https://scholar.google.com/scholar?q=Let%20Curves%20Speak%3A%20A%20CGM-based%20Large%20Sensor%20Foundation%20Model) | 2024 | Core wearable FM | Core time-series pretraining | Foundation / benchmark / transfer
- [A pretrained transformer model for decoding individual glucose dynamics from continuous glucose monitoring data](https://scholar.google.com/scholar?q=A%20pretrained%20transformer%20model%20for%20decoding%20individual%20glucose%20dynamics%20from%20continuous%20glucose%20monitoring%20data) | 2025 | Near-core candidate | Core time-series pretraining | Monitoring / estimation
- [From glucose patterns to health outcomes: A generalizable foundation model for CGM data](https://scholar.google.com/scholar?q=From%20glucose%20patterns%20to%20health%20outcomes%3A%20A%20generalizable%20foundation%20model%20for%20CGM%20data) | 2024 | Near-core candidate | Core time-series pretraining | Risk / disease prediction
- [Transformer-based self-supervised multimodal representation learning for wearable emotion recognition.](https://scholar.google.com/scholar?q=Transformer-based%20self-supervised%20multimodal%20representation%20learning%20for%20wearable%20emotion%20recognition.) | 2023 | Near-core candidate | Multimodal / cross-modal | Recognition / context understanding

### Emerging / Niche Modalities

- [TinyMyo: a Tiny Foundation Model for Flexible EMG Signal Processing at the Edge](https://doi.org/10.48550/arXiv.2512.15729) | 2025 | Core wearable FM | Adaptation / personalization / deployment | Foundation / benchmark / transfer
- [M-BEST-RQ: A Multi-Channel Speech Foundation Model for Smart Glasses](https://doi.org/10.1109/ICASSP49660.2025.10890482) | 2025 | Near-core candidate | Multimodal / cross-modal | Foundation / benchmark / transfer

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
