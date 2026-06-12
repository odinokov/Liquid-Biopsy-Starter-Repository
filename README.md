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

* **Priming agents transiently reduce the clearance of cell-free DNA to improve liquid biopsies** — *Science* (2024).

  * Why it matters: Demonstrates experimentally that cfDNA abundance is governed not only by release but also by clearance through liver-resident macrophage uptake and circulating nuclease degradation.
  * Best for: Clearance biology, cfDNA half-life control, liver/spleen reticuloendothelial uptake, and why transient “priming” can increase ctDNA recovery before phlebotomy.
  * Link: https://www.science.org/doi/10.1126/science.adf2341

* **Saturating hepatic clearance drives elevated cfDNA and fragment shortening in cancer** — *bioRxiv* (2026 preprint).

  * Why it matters: Counterweight to the simple "more tumor = more short cfDNA" model — argues elevated cfDNA and fragment shortening can arise from saturated hepatic clearance and prolonged nuclease exposure, not only tumor shedding.
  * Best for: Clearance-limited kinetics, hepatic uptake saturation, plasma nuclease exposure, and why total cfDNA is not a clean proxy for tumor burden.
  * Link: https://www.biorxiv.org/content/10.64898/2026.03.04.709433v1

* **Genomic origin, fragmentomics, and transcriptional properties of long cell-free DNA molecules in human plasma** — *Genome Research* (2024).

  * Why it matters: Defines long cfDNA molecules (>500 bp) as a distinct biological population rather than simple contamination by high-molecular-weight genomic DNA.
  * Best for: Long-read cfDNA, euchromatin enrichment, transcription-linked fragment distributions, nuclease effects, and tissue-of-origin inference beyond canonical ~166-bp fragments.
  * Link: https://genome.cshlp.org/content/34/2/189

* **Dissecting cell-free DNA fragmentation variation in tumors using cell line-derived xenograft mouse** — *PLOS ONE* (2025).

  * Why it matters: Uses human cell line-derived xenograft (CDX) mice to separate human ctDNA from mouse host cfDNA, cleanly dissecting tumor- vs. host-derived fragmentomic variation.
  * Best for: Short-fragment enrichment, ctDNA vs. background decomposition, and evidence that host cfDNA shifts (likely hematopoietic) respond to systemic cancer signals — so tumor fragmentomics is a mixture phenotype, not pure ctDNA.
  * Link: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0327483

* **Unravelling the significance of extracellular vesicle-associated DNA in cancer biology and its potential clinical applications** — *Journal of Extracellular Vesicles* (2025).

  * Why it matters: Frames extracellular-vesicle-associated DNA as a biologically distinct DNA compartment, not just “free” cfDNA packaged differently.
  * Best for: EV-DNA topology, vesicle-associated DNA localization, cancer-associated genetic/epigenetic cargo, cGAS-STING signalling, and non-apoptotic DNA release biology.
  * Link: https://isevjournals.onlinelibrary.wiley.com/doi/10.1002/jev2.70047

* **Cell-free DNA: a metabolic byproduct with diagnostic and prognostic potential in rheumatic disorders** — *Frontiers in Pharmacology* (2025).

  * Why it matters: Useful cross-disease review of cfDNA release and clearance biology outside oncology, especially inflammatory and autoimmune settings.
  * Best for: Apoptosis, necrosis, NETosis, pyroptosis, extracellular vesicle secretion, DNase I/DNase1L3/DNase II clearance, oxidation, protein-complex stabilization, and immune activation.
  * Link: https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2025.1537934/full

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

* **Single duplex DNA sequencing with CODEC detects mutations with high sensitivity** — *Nature Genetics* (2023).

  * Why it matters: Introduces CODEC, a single-duplex sequencing strategy that physically links Watson and Crick strands to suppress errors while reducing the read-depth burden of classical duplex sequencing.
  * Best for: Duplex consensus logic, rare-mutation detection, liquid biopsy error suppression, genome-wide clonal hematopoiesis detection, and teaching duplex sequencing workflows.
  * Link: https://www.nature.com/articles/s41588-023-01376-0

* **Duplex-Repair enables highly accurate sequencing, despite DNA damage** — *Nucleic Acids Research* (2022).

  * Why it matters: Shows that conventional end-repair/dA-tailing can resynthesize damaged duplex DNA and create false duplex-supported mutations.
  * Best for: Library-preparation artefacts, cfDNA/FFPE damage, end-repair chemistry, duplex sequencing false positives, and practical error suppression before sequencing.
  * Link: https://academic.oup.com/nar/article/50/1/e1/6378434

* **Paired plus-minus sequencing is an ultra-high throughput and accurate method for dual strand sequencing of DNA molecules** — *bioRxiv* (2025 preprint).

  * Why it matters: Proposes a high-duplex-yield, genome-wide dual-strand sequencing method intended to make ultra-low-frequency mutation detection more scalable.
  * Best for: ppm-level ctDNA detection, duplex WGS, high-throughput dual-strand recovery, tumor-informed detection, and tumor-naive genome-wide signal extraction.
  * Link: https://www.biorxiv.org/content/10.1101/2025.08.11.669689v1

* **GeneBits: ultra-sensitive tumour-informed ctDNA monitoring of treatment response and relapse in cancer patients** — *Journal of Translational Medicine* (2025).

  * Why it matters: Practical tumor-informed workflow using 20–100 patient-specific SNVs, ultra-deep sequencing, UMIs, and computational error modeling for relapse monitoring.
  * Best for: Small personalized panels, MRD detection, umiVar error modeling, low-VAF monitoring, treatment-response kinetics, and cost-conscious tumor-informed assay design.
  * Link: https://link.springer.com/article/10.1186/s12967-025-06993-3

* **Error-Corrected Deep Targeted Sequencing of Circulating Cell-Free DNA from Colorectal Cancer Patients for Sensitive Detection of Circulating Tumor DNA** — *International Journal of Molecular Sciences* (2024).

  * Why it matters: Presents UMIseq, a fixed-panel ultra-deep targeted sequencing approach for sensitive ctDNA detection in colorectal cancer.
  * Best for: UMI consensus, panel-of-normals error modeling, CHIP exclusion, multi-variant-class integration, Bayesian ctDNA calling, and CRC-focused MRD assay design.
  * Link: https://www.mdpi.com/1422-0067/25/8/4252

* **Validation of a liquid biopsy assay with molecular and clinical profiling of circulating tumor DNA** — *npj Precision Oncology* (2021).

  * Why it matters: Practical example of assay validation with integrated molecular and clinical profiling.
  * Best for: Analytical validation logic, performance characterization, and tumor-fraction estimation using off-target reads from targeted panel sequencing.
  * Link: https://www.nature.com/articles/s41698-021-00202-2

* **Decoding the Dynamics of Circulating Tumor DNA in Liquid Biopsies** — *Cancers* (2024).

  * Why it matters: Pragmatic review of ctDNA detection modalities and their sensitivity tradeoffs across PCR, targeted NGS, WGS, and methylation-based approaches.
  * Best for: Method-selection logic, ddPCR vs. BEAMing vs. NGS, targeted vs. untargeted assays, analytical sensitivity ranges, and clinical monitoring concepts.
  * Link: https://www.mdpi.com/2072-6694/16/13/2432

* **Emerging Technologies for Detection of Cell-Free Tumor DNA and RNA in Serum: Towards Early Cancer Detection and Monitoring** — *Preprints.org* (2025 preprint).

  * Why it matters: Broad survey of emerging cfDNA and cfRNA detection technologies, including mutation, methylation, fragmentomic, and single-molecule approaches.
  * Best for: CAPP-Seq/iDES, ddPCR/BEAMing, shallow WGS tumor fraction, cfMeDIP-seq, fragmentomics, spike-ins, single-molecule sequencing, and absolute quantification logic.
  * Link: https://www.preprints.org/manuscript/202508.1357

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

* **Evaluation of automatic cell free DNA extraction metrics using different blood collection tubes** — *Scientific Reports* (2025).

  * Why it matters: Empirical comparison showing that tube chemistry and processing delay materially change cfDNA yield and can obscure cellular DNA contamination.
  * Best for: K2EDTA vs. preservative tubes, delayed plasma isolation, automated extraction, qPCR-based QC, capillary electrophoresis, and hidden gDNA contamination.
  * Link: https://www.nature.com/articles/s41598-025-03508-4

* **Standardized Workflow and Analytical Validation of Cell-Free DNA Extraction for Liquid Biopsy Using a Magnetic Bead-Based Cartridge System** — *Cells* (2025).

  * Why it matters: Focuses on extraction standardization and analytical validation for a cartridge-based magnetic-bead cfDNA workflow.
  * Best for: Automated extraction, spike-in reference materials, extraction recovery, sample stability, gDNA contamination control, and validation of pre-analytical workflows.
  * Link: https://www.mdpi.com/2073-4409/14/14/1062

* **International Society of Liquid Biopsy (ISLB) perspective on minimal requirements for ctDNA testing in solid tumors** — *The Journal of Liquid Biopsy* (2025).

  * Why it matters: Consensus-style minimum-requirements paper for reliable ctDNA testing across pre-analytical, analytical, and post-analytical phases.
  * Best for: EDTA vs. stabilizing tubes, time-to-processing, two-step centrifugation, plasma storage, extraction validation, QC documentation, and negative-result interpretation.
  * Link: https://www.journalofliquidbiopsy.com/article/S2950-1954%2825%2900017-7/fulltext

* **Circulating tumor DNA laboratory processes and clinical applications in nasopharyngeal carcinoma** — *Frontiers in Oncology* (2025).

  * Why it matters: Disease-specific review that still gives a useful practical map of ctDNA laboratory handling and pre-analytical constraints.
  * Best for: Plasma vs. serum, tube selection, two-step centrifugation, storage/freeze–thaw effects, extraction-method choice, and EBV-associated nasopharyngeal carcinoma workflows.
  * Link: https://www.frontiersin.org/journals/oncology/articles/10.3389/fonc.2025.1520733/full

* **Navigating the Translation Gap in Cell-Free DNA Diagnostics: A Critical Evidence Framework Across Oncology, Prenatal Medicine, and Transplant Surveillance** — *Research Square* (2026 preprint).

  * Why it matters: Frames pre-analytics, CHIP, clinical validation, and implementation evidence as linked bottlenecks rather than isolated technical problems.
  * Best for: Translation-readiness logic, collection-tube effects, processing delays, extraction-method variability, CHIP subtraction, regulatory readiness, and evidence-to-practice gaps.
  * Link: https://www.researchsquare.com/article/rs-9635682/v1

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

* **Molecular residual disease and efficacy of adjuvant chemotherapy in patients with colorectal cancer** — *Nature Medicine* (2023).

  * Why it matters: Landmark GALAXY/CIRCULATE-Japan analysis showing that postoperative ctDNA positivity is strongly prognostic and may identify patients more likely to benefit from adjuvant chemotherapy.
  * Best for: CRC MRD, postoperative risk stratification, adjuvant-therapy selection, prospective observational evidence, and clinical interpretation of ctDNA-positive vs. ctDNA-negative states.
  * Link: https://www.nature.com/articles/s41591-022-02115-4

* **ctDNA-based molecular residual disease and survival in resectable colorectal cancer** — *Nature Medicine* (2024).

  * Why it matters: Extended GALAXY analysis linking ctDNA MRD status and ctDNA clearance dynamics to disease-free and overall survival in a large resectable CRC cohort.
  * Best for: Serial MRD monitoring, ctDNA lead time before radiologic recurrence, adjuvant-treatment response, sustained clearance vs. transient clearance, and survival-linked ctDNA kinetics.
  * Link: https://www.nature.com/articles/s41591-024-03254-6

* **Whole-exome tumor-agnostic ctDNA analysis enhances minimal residual disease detection and reveals relapse mechanisms in localized colon cancer** — *Nature Cancer* (2025).

  * Why it matters: Shows how plasma whole-exome tumor-agnostic ctDNA analysis can improve MRD detection and expose relapse biology beyond fixed targeted panels.
  * Best for: Tumor-agnostic MRD, plasma WES, relapse evolution, plasma-exclusive mutations, copy-number signal, immune evasion, and post-treatment clonal selection.
  * Link: https://www.nature.com/articles/s43018-025-00960-z

* **Colorectal Cancer Recurrence Prediction Using a Tissue-Free Epigenomic Minimal Residual Disease Assay** — *Clinical Cancer Research* (2024).

  * Why it matters: Evaluates a plasma-only epigenomic MRD assay that does not require prior tumor tissue sequencing.
  * Best for: Tissue-free MRD, epigenomic ctDNA detection, recurrence prediction, serial sampling, lead-time analysis, and site-dependent sensitivity limits.
  * Link: https://aacrjournals.org/clincancerres/article/30/19/4377/748568/Colorectal-Cancer-Recurrence-Prediction-Using-a

* **Perioperative nivolumab and chemotherapy in locally advanced squamous cell carcinoma of the oesophagus: a randomized multicentre phase 2 study with circulating tumor DNA dynamics monitoring** — *Molecular Cancer* (2025).

  * Why it matters: Example of embedding ctDNA dynamics into an interventional perioperative immunochemotherapy trial.
  * Best for: ctDNA as an exploratory endpoint, MRD monitoring in oesophageal squamous cell carcinoma, perioperative immunotherapy, ctDNA clearance, and prognostic interpretation after treatment.
  * Link: https://link.springer.com/article/10.1186/s12943-025-02332-8

* **Circulating Tumor DNA Testing in Curatively Resected Colorectal Cancer and Salvage Resection** — *JAMA Network Open* (2024).

  * Why it matters: Important cautionary real-world study suggesting that adding serial ctDNA to standard imaging surveillance may have limited incremental benefit for enabling curative salvage intervention.
  * Best for: Evidence-aligned implementation, surveillance utility, ctDNA-positive/imaging-negative scenarios, reflex imaging, salvage surgery outcomes, and clinical-utility skepticism.
  * Link: https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2828499

* **Circulating tumor DNA: a biomarker for oncology drug development in phase I clinical trials?** — *Expert Review of Molecular Diagnostics* (2025).

  * Why it matters: Positions ctDNA as a pharmacodynamic and translational biomarker in early drug development.
  * Best for: Phase I trial integration, translational endpoints, response kinetics, and biomarker-readout strategy in first-in-human studies.
  * Link: https://www.tandfonline.com/doi/full/10.1080/14737159.2025.2531065

* **Minimal Residual Disease in Oncology: From Cure to Longitudinal Patient Management** — *Cancers* (2026).

  * Why it matters: Broad review placing MRD into longitudinal oncology management across hematologic malignancies and solid tumors.
  * Best for: MRD concepts, ctDNA-based surveillance, recurrence prediction, assay variability, CHIP confounding, actionability thresholds, and barriers to routine adoption.
  * Link: https://www.mdpi.com/2072-6694/18/7/1049

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

* **Navigating the Translation Gap in Cell-Free DNA Diagnostics: A Critical Evidence Framework Across Oncology, Prenatal Medicine, and Transplant Surveillance** — *Research Square* (2026 preprint).

  * Why it matters: Provides an implementation-focused evidence framework showing why strong analytical performance does not automatically become population-level clinical utility.
  * Best for: MCED positive predictive value, low-prevalence screening mathematics, CHIP confounding, pre-analytical standardization, regulatory readiness, implementation feasibility, and evidence-to-practice gaps.
  * Link: https://www.researchsquare.com/article/rs-9635682/v1

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

* **Cell type signatures in cell-free DNA fragmentation profiles reveal disease biology** — *Nature Communications* (2024).

  * Why it matters: Connects cfDNA fragmentation patterns to nucleosome organization, gene expression, and cell-of-origin deconvolution across disease states.
  * Best for: Nucleosome spacing, fragmentomic cell-type signatures, single-cell reference integration, ultra-low-coverage inference, colorectal cancer, breast cancer, multiple myeloma, and pregnancy/preeclampsia signals.
  * Link: https://www.nature.com/articles/s41467-024-46435-0

* **Genomic origin, fragmentomics, and transcriptional properties of long cell-free DNA molecules in human plasma** — *Genome Research* (2024).

  * Why it matters: Adds long-read fragmentomics as a distinct signal class and connects long-fragment distributions to chromatin state and nuclease activity.
  * Best for: Long cfDNA molecules, ONT/SMRT sequencing, euchromatin enrichment, gene-expression associations, nuclease genetics, and long-fragment tissue-of-origin inference.
  * Link: https://genome.cshlp.org/content/34/2/189

* **Cell-free DNA size deconvolution resolves nucleosomal origins and reveals tumor-associated fragmentomic alterations** — *Nature Communications* (2026).

  * Why it matters: Primary methods paper that decomposes cfDNA size profiles into ~10-bp periodic components and separates true ctDNA shortening from phagocytosis-driven shortening.
  * Best for: Fragment-length deconvolution, nucleosomal vs. sub-nucleosomal origins, and disentangling tumor signal from clearance/processing artefacts.
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

* **Unravelling the significance of extracellular vesicle-associated DNA in cancer biology and its potential clinical applications** — *Journal of Extracellular Vesicles* (2025).

  * Why it matters: EV-DNA is an orthogonal DNA compartment with distinct topology, vesicle association, and methodological requirements.
  * Best for: EV-DNA isolation, DNase/S1 nuclease treatment logic, vesicle-associated genetic cargo, larger DNA fragments, chromatinized EV-DNA, and biomarker complementarity to free cfDNA.
  * Link: https://isevjournals.onlinelibrary.wiley.com/doi/10.1002/jev2.70047

* **Advances in blood microsampling technology for cancer biomarker detection** — *Advances in Clinical Chemistry* (2025).

  * Why it matters: Reviews finger-prick, dried blood spot (DBS), and volumetric absorptive microsampling (VAMS) devices for decentralized biomarker workflows.
  * Best for: Volume constraints, analyte stability, and self-collection across biomarker classes (proteins, metabolites, glycans, lipids) — note the review's focus is these analytes, not ctDNA specifically.
  * Link: https://pubmed.ncbi.nlm.nih.gov/40645674/
