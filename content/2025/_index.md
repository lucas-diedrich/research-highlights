---
title: MannLabs @2025
description: The Year 2025 in Review
toc: true
---



## Technology Advances
On the technology front, we introduced several transformative [methods](#proteomics-methods). Our **SPEC (Solid-Phase Extraction Capture) workflow** enables proteomics sample preparation in nanoliter sample volumes resulting in unprecedented sensitivity. It enables the **nanoPhos** method which brings phosphoproteomics—traditionally requiring substantial material—to single-cell resolution in spatial contexts.

**AlphaDIA**, published in Nature Biotechnology, pioneers end to end deep learning and applies transfer learning to adjust to new conditions and PTM types. In the [Rust rewrite](https://www.linkedin.com/posts/georg-wallmann-926433189_alphadia-20-is-out-today-we-are-activity-7391492479847583744-4veI?utm_source=share&utm_medium=member_desktop&rcm=ACoAADe7bvYBPclp6_FXHkb1VK3QDEMwV3MQg0Q) it has become blazingly fast. 

We also developed **ADAPT-MS**, an adaptive machine learning framework that enables clinical decision-making directly from discovery proteomics data without requiring fixed biomarker panels—a paradigm shift for clinical proteomics.

### Proteomics Methods

{{< citation title="SPEC (Solid-Phase Extraction Capture)" authors="Heymann T, Oliinyk D, Henneberg L, et al." journal="bioRxiv" issue="2025.05.31.657165" summary="Nanoliter-volume workflow for fast, robust and ultrasensitive proteomics enabling unprecedented sensitivity from minimal sample input." >}}

{{< citation title="PCA-N Workflow for Plasma Proteomics" authors="Albrecht V, Müller-Reif JB, Brennsteiner V, Mann M" journal="Mol Cell Proteomics" issue="2025 Nov;24(11):101071" summary="Simplified perchloric acid workflow enabling deep plasma proteomics at population scale with >10,000 samples per day throughput." >}}

{{< citation title="nanoPhos -- Spatial Phosphoproteomics" authors="Oliinyk D, Heymann T, Henneberg L, et al." journal="bioRxiv" issue="2025.05.29.656770" summary="Ultra-sensitive cell-type resolved spatial phosphoproteomics enabling signaling analysis at single-cell resolution in tissues." >}}

{{< citation title="PASEF Workflow Protocol" authors="Skowronek P, Wallmann G, Wahle M, Willems S, Mann M" journal="Nat Protoc" issue="2025 Jun;20(6):1700-1729" summary="Accessible step-by-step protocol for high-sensitivity proteomics using parallel accumulation-serial fragmentation." >}}

{{< citation title="Stellar MS for Biomarker Translation" authors="Wahle M, Remes PM, Albrecht V, et al., Mann M" journal="Mol Cell Proteomics" issue="2025 Sep;24(9):101050" summary="Novel hybrid high-speed mass spectrometer enables rapid translation from biomarker candidates to targeted clinical tests using 15N-labeled proteins." >}}

{{< citation title="Pre-Analytical Drivers of Bias in Plasma Proteomics" authors="Korff K, Müller-Reif JB, et al., Mann M, Geyer PE" journal="EMBO Mol Med" issue="2025 Nov;17(11):3174-3196" summary="Systematic evaluation of plasma proteomics workflows reveals susceptibility to cellular contamination and provides framework for quality control." >}}

### Bioinformatics & Software

{{< citation title="AlphaDIA -- Transfer Learning for DIA" authors="Wallmann G, Skowronek P, Brennsteiner V, et al., Mann M" journal="Nat Biotechnol" issue="2025 Oct 21" summary="End-to-end transfer learning enabling feature-free proteomics with dramatically improved identification rates." >}}

{{< citation title="ADAPT-MS Clinical Framework" authors="Müller-Reif JB, Albrecht V, et al., Wewer Albrechtsen NJ, Mann M" journal="In press at Nature Communications" summary="Adaptive diagnostic framework for clinical proteomics enabling personalized testing from plasma and CSF." >}}


{{< citation title="scPortrait -- Single-Cell Image Integration" authors="Mädler SC, Schmacke NA, Palma A, et al., Theis FJ, Mann M" journal="bioRxiv" issue="2025.09.22.677590" summary="Software package for generation, storage and application of single-cell image datasets enabling multimodal analysis." >}}

{{< citation title="Tree-based Proteoform Quantification" authors="Ammar C, Thielert M, Weiss CAM, et al., Mann M" journal="bioRxiv" issue="2025.03.06.641844" summary="Novel computational approach to infer proteoform regulation from bottom-up proteomics data." >}}

{{< citation title="AI Laboratory Agents" authors="Skowronek P, Nawalgaria A, Mann M" journal="Mol Syst Biol" issue="2025 Dec" summary="Multimodal AI agents for capturing and sharing tacit laboratory practice through video, speech, and text analysis." >}}

## High-Throughput Applications

Our [**Deep Visual Proteomics (DVP) platform**](#disease-biology--spatial-proteomics) continued to yield biological insights with clinical relevance. In collaboration with clinical partners, we revealed why some patients with alpha-1 antitrypsin deficiency develop severe liver disease while others remain healthy. 

Our long-standing [collaboration with Ernst Lengyel](#ovarian-cancer----ernst-lengyel-u-chicago) at the University of Chicago produced multiple high-impact papers on ovarian cancer, including the identification of NNMT as a therapeutic target in cancer-associated fibroblasts (Nature) and comprehensive spatial mapping of serous tubal intraepithelial carcinomas (STICs), revealing that ovarian cancer precursors are far more common than previously recognized.

We also established a new framework for studying rare diseases. Our **ontology-guided clustering approach** enables meaningful proteomic analysis even when individual conditions affect only a handful of patients—opening the door to systematic study of the thousands of rare pediatric disorders that collectively affect millions of children worldwide.


### Disease Biology & Spatial Proteomics

{{< citation title="Alpha-1 Antitrypsin Deficiency -- Liver Disease" authors="Rosenberger FA, Mädler SC, et al., Mann M" journal="Nature" issue="2025 Apr 16" summary="Deep Visual Proteomics reveals why some patients with the hereditary liver disease remain healthy while others develop severe pathology." >}}

{{< citation title="Liver Zonation and Fibrosis" authors="Weiss CAM, Brown LA, Miranda L, et al., Rosenberger FA, Mann M" journal="bioRxiv" issue="2025.04.13.648568" summary="Single cell spatial proteomics maps human hepatocyte zonation patterns and their vulnerability to fibrosis." >}}

{{< citation title="Colon Organoid Models" authors="Post F, Hausmann A, et al., Mann M" journal="Cell Syst" issue="2025 Sep 17;16(9):101396" summary="DVP reveals in vivo-like phenotype upon xenotransplantation of human colon organoids." >}}

{{< citation title="Pancreatic Islet Cell Diversity" authors="Thielert M, Villalba A, et al., Mann M, Scharfmann R" journal="Commun Biol" issue="2025 Oct 17;8(1):1483" summary="Cell type-resolved proteomics and phosphoproteomics decode adult murine pancreatic islet cell diversity." >}}

{{< citation title="Signet Ring Cell Carcinoma" authors="Kabatnik S, Zheng X, et al., Mann M" journal="NPJ Precis Oncol" issue="2025 Feb 5;9(1):37" summary="DNA replication stress identified as a hallmark of signet ring cell carcinoma through DVP." >}}

{{< citation title="Tumor-Immune Crosstalk" authors="Zheng X, Mund A, Mann M" journal="Mol Cell" issue="2025 Mar 6;85(5):1008-1023.e7" summary="Deciphering functional tumor-immune crosstalk through highly multiplexed imaging and deep visual proteomics." >}}


### Clinical & Population Proteomics

{{< citation title="Plasma Proteome in Children and Adolescents" authors="Niu L, Stinson SE, Holm LA, et al., Mann M" journal="Nat Genet" issue="2025 Feb 19" summary="Comprehensive proteomic profiling of 2,147 children revealing associations with age, sex, puberty, BMI, and genetics." >}}

{{< citation title="Ontology-guided Clustering for Rare Pediatric Disorders" authors="Itang ECM, Albrecht V, et al., Mann M, Pangratz-Fuehrer S, Mueller-Reif JB" journal="EMBO Mol Med" issue="2025 Jul;17(7):1842-1867" summary="Framework integrating clinical ontologies with proteomics enables analysis of 394 rare pediatric conditions from 1,140 patients." >}}

## Major Collaborations

### Ovarian Cancer -- Ernst Lengyel (U. Chicago)

{{< citation title="Borderline Ovarian Tumor Progression (LGSC)" authors="Schweizer L, Kenny HA, et al., Mann M, Lengyel E" journal="Cancer Cell" issue="2025 Jun 20" summary="Spatial proteo-transcriptomics reveals molecular landscape of borderline ovarian tumors. Identified 16 drug targets; combination therapy achieved significant tumor reduction." >}}

{{< citation title="Early Ovarian Cancer Mechanisms (HGSC)" authors="Metousis A, Kenny HA, Shimizu A, et al., Mann M, Lengyel E" journal="medRxiv" issue="2025.08.25.25333715" summary="Integration of cell-type resolved spatial proteomics and transcriptomics reveals novel mechanisms including SUMOylation activation and ATR signaling." >}}

{{< citation title="NNMT Inhibition Restores Antitumor Immunity" authors="Heide J, Bilecz AJ, et al., Mann M, ..., Lengyel E" journal="Nature" issue="2025 Sep;645(8082):1051-1059" summary="NNMT inhibitor reduces tumor burden by reprogramming cancer-associated fibroblasts and restoring immune checkpoint blockade efficacy." >}}

{{< citation title="3D Multi-omic Mapping of Fallopian Tubes (STIC)" authors="Metousis A, et al., Mann M, Lengyel E" journal="bioRxiv" issue="2025.09.21.677628" summary="Spatially resolved multi-omics framework identifies 99 STICs and precursors in cancer-free organ donors, revealing high incidence of ovarian cancer precursors." >}}

### Clinical Proteomics -- Nicolai Wewer Albrechtsen (Copenhagen)

{{< citation title="Diagnostic potential of proteomics in Lyme disease" authors="Nielsen AB, Fjordside L, Drici L, et al." journal="Nat Commun" issue="16, 9322 (2025)" summary="This report highlights the potential of proteomics to inform Machine Learning-assisted diagnostics." >}}

### Other Key Collaborations

{{< citation title="GPX4 and Ferroptosis in Neurodegeneration" authors="Lorenz SM, et al., Mann M, ..., Conrad M" journal="Cell" issue="2025 Dec (with Marcus Conrad, Helmholtz Munich)" summary="A fin-loop-like structure in GPX4 underlies neuroprotection from ferroptosis. Proteomics revealed Alzheimer's-like signatures." >}}

{{< citation title="LRRK2 and Crohn's Disease/Colitis" authors="Heaton GR, et al., Mann M, ..., Yue Z" journal="J Clin Invest" issue="2025 Oct (with Zhenyu Yue, Mount Sinai)" summary="Targeting specific LRRK2 kinase substrates rescues colitis severity caused by Crohn's disease-linked variant." >}}

{{< citation title="GID E3 Ligase Complex" authors="Schulman lab with Mann lab proteomics" journal="Multiple papers ongoing" summary="Continued collaboration on ubiquitin signaling including LRRC58/CDO1 cysteine availability studies." >}}

## Clinical Impact Highlight

**JAK Inhibitors for Toxic Epidermal Necrolysis**

[Our 2024 _Nature_ publication (Nordmann TM et al.)](https://doi.org/10.1038/s41586-024-08061-0) on spatial proteomics identifying JAK inhibitors as treatment for toxic epidermal necrolysis (TEN) -- a lethal skin disease -- has had immediate clinical impact in 2025. Off-label use of JAK inhibitors in the first patients worldwide led to complete recovery.

>_"To our knowledge, this is the first time a spatial omics technology
has made an immediate and tangible impact in the clinic, by identifying
a treatment that has already changed people's lives for the good."_

--- Matthias Mann

## 2025 Preprints (bioRxiv/medRxiv)

{{< citation title="SPEC workflow" authors="Heymann et al." journal="bioRxiv" issue="May 2025" summary="Solid-Phase Extraction Capture for ultrasensitive proteomics" >}}

{{< citation title="nanoPhos" authors="Oliinyk et al." journal="bioRxiv" issue="May 2025" summary="Cell-type resolved spatial phosphoproteomics" >}}

{{< citation title="Liver zonation" authors="Weiss et al." journal="bioRxiv" issue="Apr 2025" summary="Single cell spatial proteomics of hepatocyte zonation" >}}

{{< citation title="Tree-based proteoform quantification" authors="Ammar et al." journal="bioRxiv" issue="Mar 2025" summary="Inferring proteoform regulation from bottom-up data" >}}

{{< citation title="ADAPT-MS" authors="Müller-Reif et al." journal="medRxiv" issue="May 2025 (in press Nat Commun)" summary="Adaptive clinical diagnostics framework" >}}

{{< citation title="scPortrait" authors="Mädler et al." journal="bioRxiv" issue="Sep 2025" summary="Single-cell image integration for multimodal modeling" >}}

{{< citation title="Early ovarian cancer (HGSC)" authors="Metousis et al." journal="medRxiv" issue="Aug 2025" summary="Spatial proteomics/transcriptomics integration" >}}

{{< citation title="3D fallopian tube mapping (STIC)" authors="Metousis et al." journal="bioRxiv" issue="Sep 2025" summary="Multi-omic mapping revealing ovarian cancer precursors" >}}

{{< citation title="Pre-analytical bias" authors="Korff et al." journal="bioRxiv" issue="May 2025 (now published EMBO Mol Med)" summary="Bias in bead-enriched plasma proteomics" >}}

## Publication Summary by Journal

{{< centered-table >}}
| Journal | Count | Topics |
| --- | --- | --- |
| _Nature_ | 3 | Liver disease (DVP), Review, NNMT/CAFs (w/ Lengyel) |
| _Nature Biotechnology_ | 1 | AlphaDIA transfer learning |
| _Nature Genetics_ | 1 | Pediatric plasma proteome |
| _Nature Protocols_ | 1 | PASEF workflow |
| _Nature Communications_ | 1 | ADAPT-MS (in press) |
| _Cancer Cell_ | 1 | Ovarian cancer progression (w/ Lengyel) |
| _Cell_ | 1 | GPX4 ferroptosis (w/ Conrad) |
| _Cell Systems_ | 1 | Colon organoid DVP |
| _EMBO Mol Med_ | 2 | Rare pediatric disorders, Pre-analytical bias |
| _Molecular Cell_ | 1 | Tumor-immune crosstalk |
| _Mol Cell Proteomics_ | 2 | PCA-N plasma, Stellar MS |
| _Commun Biol_ | 1 | Pancreatic islet cells |
| _NPJ Precision Oncol_ | 1 | Signet ring cell carcinoma |
| _Mol Syst Biol_ | 1 | AI laboratory agents |
| _J Clin Invest_ | 1 | LRRK2 colitis (w/ Yue) |
{{< /centered-table >}}
