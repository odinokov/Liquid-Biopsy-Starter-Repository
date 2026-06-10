# Liquid Biopsy Starter Repository

Learning resources for LBx.

## 1) Core biology of cfDNA/ctDNA

* **Circulating tumor nucleic acids: biology, release mechanisms, and clinical relevance** — *Molecular Cancer* (2023).
  * Why it matters: Foundational review of ctDNA/ctRNA origin, release biology, and shedding heterogeneity.
  * Best for: Source biology, passive vs. active release, and why tumor shedding varies across patients and disease states.
  * Link: https://link.springer.com/article/10.1186/s12943-022-01710-w

* **The comings and goings of cell-free DNA: Biological and clinical implications** — *Med* (2026; ePub 2025).
  * Why it matters: Modern synthesis of cfDNA production, circulation, and clearance, extending beyond oncology into general cfDNA pathophysiology.
  * Best for: Kinetics, nuclease biology, clearance pathways, tissue-of-origin logic, and how cfDNA behavior constrains assay design.
  * Link: https://www.cell.com/med/fulltext/S2666-6340%2825%2900353-8

* **Saturating hepatic clearance drives elevated cfDNA and fragment shortening in cancer** — *bioRxiv* (2026 preprint).
  * Why it matters: Counterweight to the simple "more tumor = more short cfDNA" model — argues elevated cfDNA and fragment shortening can arise from saturated hepatic clearance and prolonged nuclease exposure, not only tumor shedding.
  * Best for: Clearance-limited kinetics, hepatic uptake saturation, plasma nuclease exposure, and why total cfDNA is not a clean proxy for tumor burden.
  * Link: https://www.biorxiv.org/content/10.64898/2026.03.04.709433v1

* **Dissecting cell-free DNA fragmentation variation in tumors using cell line-derived xenograft mouse** — *PLOS ONE* (2025).
  * Why it matters: Uses human cell line-derived xenograft (CDX) mice to separate human ctDNA from mouse host cfDNA, cleanly dissecting tumor- vs. host-derived fragmentomic variation.
  * Best for: Short-fragment enrichment, ctDNA vs. background decomposition, and evidence that host cfDNA shifts (likely hematopoietic) respond to systemic cancer signals — so tumor fragmentomics is a mixture phenotype, not pure ctDNA.
  * Link: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0327483

---

## 2) ctDNA quantification and detection methods

* **Circulating Tumor DNA detection in cancer: a comprehensive overview of current detection methods and prospects** — *The Oncologist* (2025).
  * Why it matters: Broad technical survey spanning PCR-based and NGS-based ctDNA detection.
  * Best for: ddPCR vs. targeted NGS vs. emerging approaches, plus method-selection logic by clinical use case.
  * Link: https://academic.oup.com/oncolo/article/30/9/oyaf204/8206301

* **Strategies for improving detection of circulating tumor DNA using next generation sequencing** — *Cancer Treatment Reviews* (2023).
  * Why it matters: Focuses on analytical sensitivity, low-allele-fraction detection, and NGS error suppression.
  * Best for: UMIs, background noise control, multi-locus strategies, and lower-limit-of-detection thinking.
  * Link: https://www.sciencedirect.com/science/article/pii/S0305737223000889

* **Validation of a liquid biopsy assay with molecular and clinical profiling of circulating tumor DNA** — *npj Precision Oncology* (2021).
  * Why it matters: Practical example of assay validation with integrated molecular and clinical profiling.
  * Best for: Analytical validation logic, performance characterization, and tumor-fraction estimation using off-target reads from targeted panel sequencing.
  * Link: https://www.nature.com/articles/s41698-021-00202-2

* **Monitoring and Assessment of Circulating Tumor DNA in Cancers Using Ultrarapid Sensitivity as an Innovative Practice** — *Health Science Reports* (2025).
  * Why it matters: Surveys emerging ultrasensitive detection approaches for the very-low-ctDNA regime (often < 0.1% of total cfDNA).
  * Best for: Structural-variant–based assays, nanomaterial/electrochemical and magnetic nano-electrode biosensors, and fragment-enriched libraries — closer in spirit to Section 7 than to clinical monitoring, and a lower-impact venue.
  * Link: https://pmc.ncbi.nlm.nih.gov/articles/PMC12550271/

---

## 3) Pre-analytical variables and standardization

* **The impact of preanalytical variables on the analysis of cell-free DNA from blood and urine samples** — *Frontiers in Cell and Developmental Biology* (2024).
  * Why it matters: Directly addresses collection, transport, processing, storage, and extraction variables across blood and urine.
  * Best for: Tube choice, processing delay, storage effects, matrix effects, and why pre-analytics dominate downstream reproducibility.
  * Link: https://pmc.ncbi.nlm.nih.gov/articles/PMC11111958/

* **The Effect of Preanalytical and Physiological Variables on Cell-Free DNA Fragmentation** — *Clinical Chemistry* (2022).
  * Why it matters: Empirical study of how collection tubes, processing time, and host physiology affect fragmentomic readouts — with the key finding that tube/time leave fragment size and tumor fraction largely intact but reshape genome-wide patterns and fragment-end sequences.
  * Best for: Fragmentation bias, fragment-end effects, collection-site batch effects, and why fragmentomics is especially pre-analytically sensitive.
  * Link: https://academic.oup.com/clinchem/article/68/6/803/6549200
    
* **Reporting of molecular test results from cell-free DNA analyses: expert consensus recommendations from the 2023 European Liquid Biopsy Society ctDNA Workshop** — *EBioMedicine* (2025).
  * Why it matters: Expert-consensus guidance on how ctDNA results should be reported — the standardization layer that pre-analytics ultimately feeds into.
  * Best for: ctDNA test-report content, handling tumour-fraction variability and unexpected findings, ISO 15189 alignment, and lab-to-oncologist communication.
  * Link: https://pmc.ncbi.nlm.nih.gov/articles/PMC11979934/

---

## 4) Clinical applications across cancer care

* **Liquid biopsies across the cancer care continuum** — *Nature Medicine* (2025).
  * Why it matters: High-level map of where liquid biopsy now fits across diagnosis, treatment selection, MRD, and longitudinal monitoring.
  * Best for: End-to-end clinical workflow and how different analytes map onto different oncology decisions.
  * Link: https://www.nature.com/articles/s41591-025-04093-9

* **Liquid Biopsy Approaches for Cancer Characterization, Residual Disease Detection, and Therapy Monitoring** — *ASCO Educational Book* (2025).
  * Why it matters: Clinically oriented review with strong utility for early-stage learners (examples skew thoracic/lung).
  * Best for: Actionable mutation profiling, residual disease detection, therapy monitoring, and trial-linked clinical framing.
  * Link: https://ascopubs.org/doi/10.1200/EDBK-25-481114

* **Circulating tumor DNA: a biomarker for oncology drug development in phase I clinical trials?** — *Expert Review of Molecular Diagnostics* (2025).
  * Why it matters: Positions ctDNA as a pharmacodynamic and translational biomarker in early drug development.
  * Best for: Phase I trial integration, translational endpoints, response kinetics, and biomarker-readout strategy in first-in-human studies.
  * Link: https://www.tandfonline.com/doi/full/10.1080/14737159.2025.2531065

---

## 5) Early detection / MCED

* **Promises and pitfalls of multi-cancer early detection using liquid biopsy tests** — *Nature Reviews Clinical Oncology* (2025).
  * Why it matters: Balanced treatment of the promise and limitations of MCED.
  * Best for: Sensitivity–specificity tradeoffs, prevalence effects, false-positive burden, overdiagnosis risk, and implementation barriers.
  * Link: https://www.nature.com/articles/s41571-025-01033-x

* **Liquid biopsy-based multi-cancer early detection: an exploration road from evidence to implementation** — *Science Bulletin* (2025).
  * Why it matters: Connects biomarker discovery and analytical validation to real-world implementation logic.
  * Best for: Evidence generation, trial design, endpoint selection, panel composition, and translational implementation planning.
  * Link: https://doi.org/10.1016/j.scib.2025.06.030

* **Clinical implementation of multi-cancer early detection tests: can we find a path forward?** — *Nature Reviews Clinical Oncology* (2026).
  * Why it matters: Policy- and implementation-focused complement to "Promises and pitfalls," written around the 2026 Medicare MCED coverage act and pending FDA decisions.
  * Best for: Reimbursement and coverage logic, regulatory status, trial-evidence gaps, and what real-world rollout actually requires.
  * Link: https://www.nature.com/articles/s41571-026-01158-7

---

## 6) Fragmentomics

* **Genomic and fragmentomic landscapes of cell-free DNA for early cancer detection** — *Nature Reviews Cancer* (2025).
  * Why it matters: High-value synthesis of mutation-derived and fragmentation-derived signals for early cancer detection; the natural "start here" anchor for fragmentomics.
  * Best for: How genomic and fragmentomic features complement each other in low-tumor-fraction settings.
  * Link: https://pubmed.ncbi.nlm.nih.gov/40038442/

* **Cell-free DNA fragmentomics in cancer** — *Cancer Cell* (2025).
  * Why it matters: Strong conceptual paper on fragmentomics as a signal class linked to chromatin architecture and cell-death biology.
  * Best for: Fragment-length spectra, end motifs, nucleosome footprints, and AI-enabled signal extraction.
  * Link: https://www.sciencedirect.com/science/article/pii/S1535610825003988

* **Cell-free DNA size deconvolution resolves nucleosomal origins and reveals tumor-associated fragmentomic alterations** — *Nature Communications* (2026).
  * Why it matters: Primary methods paper that decomposes cfDNA size profiles into ~10-bp periodic components and separates true ctDNA shortening from phagocytosis-driven shortening.
  * Best for: Fragment-length deconvolution, nucleosomal vs. sub-nucleosomal origins, and disentangling tumor signal from clearance/processing artefacts (validated in germline-TP53, radiotherapy, and liver-transplant cohorts).
  * Link: https://www.nature.com/articles/s41467-026-72925-4
  
---

## 7) Emerging assay technologies and next-generation signal classes

* **Extracting regulatory active chromatin footprint from cell-free DNA** — *Communications Biology* (2024).
  * Why it matters: Enriches regulatory-active chromatin fragments rather than treating cfDNA as passive nucleosomal debris.
  * Best for: How cfDNA can report enhancer, promoter, RNA Pol II, circadian, and transcriptional-state information.
  * Link: https://www.nature.com/articles/s42003-024-06769-3

* **Deep learning-based non-invasive profiling of tumor transcriptomes from cell-free DNA for precision oncology** — *bioRxiv* (2026 preprint).
  * Why it matters: Introduces Triton (fragmentomic/nucleosome profiling) and Proteus (deep-learning single-gene expression prediction from standard-depth cfDNA WGS).
  * Best for: Functional liquid biopsy, inferring tumor transcriptomic state from fragmentation and nucleosome positioning, and moving cfDNA beyond mutation detection.
  * Link: https://www.biorxiv.org/content/10.64898/2026.02.10.705188v1

* **Sensitive tumour detection and classification using plasma cell-free DNA methylomes** — *Nature* (2018).
  * Why it matters: Seminal cfMeDIP-seq paper; the standard starting point for enrichment-based cfDNA methylome profiling.
  * Best for: Low-input methylome enrichment, tissue-of-origin inference, and why methylation can outperform sparse mutation panels at low tumor fraction.
  * Link: https://www.nature.com/articles/s41586-018-0703-0

* **5-Hydroxymethylcytosine signatures in cell-free DNA provide information about tumor types and stages** — *Cell Research* (2017).
  * Why it matters: Establishes 5hmC as a distinct cfDNA epigenetic signal, not just a variant of 5mC methylation.
  * Best for: Hydroxymethylome biology, gene-body 5hmC, cancer-type classification, stage-related shifts, and low-input enrichment chemistry.
  * Link: https://www.nature.com/articles/cr2017106

* **Detection and localization of surgically resectable cancers with a multi-analyte blood test** — *Science* (2018).
  * Why it matters: CancerSEEK; canonical example of combining cfDNA mutations with circulating proteins rather than nucleic acids alone.
  * Best for: Multi-analyte assay logic, protein-plus-mutation integration, cancer localization, and early MCED classifier design.
  * Link: https://www.science.org/doi/10.1126/science.aar3247

* **Advances in blood microsampling technology for cancer biomarker detection** — *Advances in Clinical Chemistry* (2025).
  * Why it matters: Reviews finger-prick, dried blood spot (DBS), and volumetric absorptive microsampling (VAMS) devices for decentralized biomarker workflows.
  * Best for: Volume constraints, analyte stability, and self-collection across biomarker classes (proteins, metabolites, glycans, lipids) — note the review's focus is these analytes, not ctDNA specifically.
  * Link: https://pubmed.ncbi.nlm.nih.gov/40645674/
