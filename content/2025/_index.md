---
title: MannLabs @2025
description: The Year 2025 in Review
toc: true
---



## Technology Advances
On the technology front, we introduced several transformative [methods](#proteomics-methods). Our **SPEC (Solid-Phase Extraction Capture) workflow** enables proteomics sample preparation in nanoliter sample volumes resulting in unprecedented sensitivity. It enables the **nanoPhos** method which brings phosphoproteomics—traditionally requiring substantial material—to single-cell resolution in spatial contexts.

**AlphaDIA**, published in Nature Biotechnology, pioneers end to end deep learning and applies transfer learning to adjust to new conditions and PTM types, further extending our [Bioinformatics toolbox](#bioinformatics-and-software). In the [Rust rewrite](https://www.linkedin.com/posts/georg-wallmann-926433189_alphadia-20-is-out-today-we-are-activity-7391492479847583744-4veI?utm_source=share&utm_medium=member_desktop&rcm=ACoAADe7bvYBPclp6_FXHkb1VK3QDEMwV3MQg0Q) it has become blazingly fast. We also developed **ADAPT-MS**, an adaptive machine learning framework that enables clinical decision-making directly from discovery proteomics data without requiring fixed biomarker panels—a paradigm shift for clinical proteomics.

{{< citation-group heading="Proteomics Methods" >}}
{{< citation title="SPEC (Solid-Phase Extraction Capture)" authors="Heymann T, Oliinyk D, Henneberg L, et al." journal="bioRxiv" issue="2025.05.31.657165" url="https://doi.org/10.1101/2025.05.31.657165" summary="Nanoliter-volume workflow for fast, robust and ultrasensitive proteomics enabling unprecedented sensitivity from minimal sample input." >}}
{{< citation title="PCA-N Workflow for Plasma Proteomics" authors="Albrecht V, Müller-Reif JB, Brennsteiner V, Mann M" journal="Mol Cell Proteomics" issue="2025 Nov;24(11):101071" url="https://doi.org/10.1016/j.mcpro.2025.101071" summary="Simplified perchloric acid workflow enabling deep plasma proteomics at population scale with >10,000 samples per day throughput." >}}
{{< citation title="nanoPhos enables ultra-sensitive and cell-type resolved spatial phosphoproteomics" authors="Oliinyk D, Heymann T, Henneberg L, et al." journal="bioRxiv" issue="2025.05.29.656770" url="https://doi.org/10.1101/2025.05.29.656770" summary="Ultra-sensitive cell-type resolved spatial phosphoproteomics enabling signaling analysis at single-cell resolution in tissues." >}}
{{< citation title="PASEF Workflow Protocol" authors="Skowronek P, Wallmann G, Wahle M, Willems S, Mann M" journal="Nat Protoc" issue="2025 Jun;20(6):1700-1729" summary="Accessible step-by-step protocol for high-sensitivity proteomics using parallel accumulation-serial fragmentation." >}}
{{< citation title="Stellar MS for Biomarker Translation" authors="Wahle M, Remes PM, Albrecht V, et al., Mann M" journal="Mol Cell Proteomics" issue="2025 Sep;24(9):101050" summary="Novel hybrid high-speed mass spectrometer enables rapid translation from biomarker candidates to targeted clinical tests using 15N-labeled proteins." >}}
{{< citation title="Pre-Analytical Drivers of Bias in Plasma Proteomics" authors="Korff K, Müller-Reif JB, et al., Mann M, Geyer PE" journal="EMBO Mol Med" issue="2025 Nov;17(11):3174-3196" summary="Systematic evaluation of plasma proteomics workflows reveals susceptibility to cellular contamination and provides framework for quality control." >}}
{{< /citation-group >}}

{{< citation-group heading="Bioinformatics and Software" >}}
{{< citation title="AlphaDIA enables DIA transfer learning for feature-free proteomics" authors="Wallmann G, Skowronek P, Brennsteiner V, et al., Mann M" journal="Nat Biotechnol" issue="2025 Oct 21" url="https://doi.org/10.1038/s41587-025-02791-w" summary="End-to-end transfer learning enabling feature-free proteomics with dramatically improved identification rates." >}}
{{< citation title="An adaptive, continuous-learning framework for clinical decision-making from proteome-wide biofluid data" authors="Müller-Reif JB, Albrecht V, et al., Wewer Albrechtsen NJ, Mann M" journal="In press at Nature Communications" url="https://doi.org/10.1101/2025.05.02.25326901" summary="Adaptive diagnostic framework for clinical proteomics enabling personalized testing from plasma and CSF." >}}
{{< citation title="scPortrait integrates single-cell images into multimodal modeling" authors="Mädler SC, Schmacke NA, Palma A, et al., Theis FJ, Mann M" journal="bioRxiv" issue="2025.09.22.677590" url="https://doi.org/10.1101/2025.09.22.677590" summary="Software package for generation, storage and application of single-cell image datasets enabling multimodal analysis." >}}
{{< citation title="Tree-based quantification infers proteoform regulation in bottom-up proteomics data" authors="Ammar C, Thielert M, Weiss CAM, et al., Mann M" journal="bioRxiv" issue="2025.03.06.641844" url="https://doi.org/10.1101/2025.03.06.641844" summary="Novel computational approach to infer proteoform regulation from bottom-up proteomics data." >}}
{{< citation title="Multimodal AI agents for capturing and sharing laboratory practice" authors="Skowronek P, Nawalgaria A, Mann M" journal="Mol Syst Biol" issue="2025 Dec" url="https://doi.org/10.1101/2025.10.05.680425" summary="Multimodal AI agents for capturing and sharing tacit laboratory practice through video, speech, and text analysis." >}}
{{< /citation-group >}}

## High-Throughput Applications

Our [**Deep Visual Proteomics (DVP) platform**](#disease-biology-and-spatial-proteomics) continued to yield biological insights with clinical relevance. In collaboration with clinical partners, we revealed why some patients with alpha-1 antitrypsin deficiency develop severe liver disease while others remain healthy.

{{< citation-group heading="Disease Biology and Spatial Proteomics" >}}
{{< citation title="Deep Visual Proteomics maps proteotoxicity in a genetic liver disease" authors="Rosenberger FA, Mädler SC, et al., Mann M" journal="Nature" issue="2025 Apr 16" url="https://doi.org/10.1038/s41586-025-08885-4" summary="Deep Visual Proteomics reveals why some patients with the hereditary liver disease remain healthy while others develop severe pathology." >}}
{{< citation title="Single cell spatial proteomics maps human liver zonation patterns and their vulnerability to fibrosis" authors="Weiss CAM, Brown LA, Miranda L, et al., Rosenberger FA, Mann M" journal="bioRxiv" issue="2025.04.13.648568" url="https://doi.org/10.1101/2025.04.13.648568" summary="Single cell spatial proteomics maps human hepatocyte zonation patterns and their vulnerability to fibrosis." >}}
{{< citation title="Colon Organoid Models" authors="Post F, Hausmann A, et al., Mann M" journal="Cell Syst" issue="2025 Sep 17;16(9):101396" summary="DVP reveals in vivo-like phenotype upon xenotransplantation of human colon organoids." >}}
{{< citation title="Pancreatic Islet Cell Diversity" authors="Thielert M, Villalba A, et al., Mann M, Scharfmann R" journal="Commun Biol" issue="2025 Oct 17;8(1):1483" summary="Cell type-resolved proteomics and phosphoproteomics decode adult murine pancreatic islet cell diversity." >}}
{{< citation title="Signet Ring Cell Carcinoma" authors="Kabatnik S, Zheng X, et al., Mann M" journal="NPJ Precis Oncol" issue="2025 Feb 5;9(1):37" summary="DNA replication stress identified as a hallmark of signet ring cell carcinoma through DVP." >}}
{{< citation title="Tumor-Immune Crosstalk" authors="Zheng X, Mund A, Mann M" journal="Mol Cell" issue="2025 Mar 6;85(5):1008-1023.e7" summary="Deciphering functional tumor-immune crosstalk through highly multiplexed imaging and deep visual proteomics." >}}
{{< /citation-group >}}


We continue to work on bringing large-scale proteomics studies to the patients and into the [clinic](#clinical-and-population-proteomics). Beyond the ADAPT-MS framework, we also established a new framework for studying rare diseases. Our **ontology-guided clustering approach** enables meaningful proteomic analysis even when individual conditions affect only a handful of patients—opening the door to systematic study of the thousands of rare pediatric disorders that collectively affect millions of children worldwide.

{{< citation-group heading="Clinical and Population Proteomics" >}}
{{< citation title="Plasma proteome variation and its genetic determinants in children and adolescents" authors="Niu L, Stinson SE, Holm LA, et al., Mann M" journal="Nat Genet" issue="2025 Feb 19" url="https://doi.org/10.1038/s41588-025-02089-2" summary="Comprehensive proteomic profiling of 2,147 children revealing associations with age, sex, puberty, BMI, and genetics." >}}
{{< citation title="Ontology-guided clustering enables proteomic analysis of rare pediatric disorders" authors="Itang ECM, Albrecht V, et al., Mann M, Pangratz-Fuehrer S, Mueller-Reif JB" journal="EMBO Mol Med" issue="2025 Jul;17(7):1842-1867" url="https://doi.org/10.1038/s44321-025-00253-z" summary="Framework integrating clinical ontologies with proteomics enables analysis of 394 rare pediatric conditions from 1,140 patients." >}}
{{< /citation-group >}}

## Major Collaborations

We were involved in multiple successfull **collaborations**, contributing with our expertise in MS-technologies and bioinformatics. 
In particular, our long-standing [collaboration with Ernst Lengyel](#ovarian-cancer) at the University of Chicago produced multiple high-impact papers on ovarian cancer, including the identification of NNMT as a therapeutic target in cancer-associated fibroblasts (Nature) and comprehensive spatial mapping of serous tubal intraepithelial carcinomas (STICs), revealing that ovarian cancer precursors are far more common than previously recognized.

{{< citation-group heading="Ovarian Cancer" >}}
{{< citation title="Spatial proteo-transcriptomic profiling reveals the molecular landscape of borderline ovarian tumors and their invasive progression" authors="Schweizer L, Kenny HA, et al., Mann M, Lengyel E" journal="Cancer Cell" issue="2025 Jun 20"  url="https://doi.org/10.1016/j.ccell.2025.06.004" summary="Spatial proteo-transcriptomics reveals molecular landscape of borderline ovarian tumors. Identified 16 drug targets; combination therapy achieved significant tumor reduction." >}}
{{< citation title="Integration of cell-type resolved spatial proteomics and transcriptomics reveals novel mechanisms in early ovarian cancer" authors="Metousis A, Kenny HA, Shimizu A, et al., Mann M, Lengyel E" journal="medRxiv" issue="2025.08.25.25333715" url="https://doi.org/10.1101/2025.08.25.25333715" summary="Integration of cell-type resolved spatial proteomics and transcriptomics reveals novel mechanisms including SUMOylation activation and ATR signaling." >}}
{{< citation title="NNMT inhibition in cancer-associated fibroblasts restores antitumour immunity" authors="Heide J, Bilecz AJ, et al., Mann M, ..., Lengyel E" journal="Nature" issue="2025 Sep;645(8082):1051-1059" url="https://doi.org/10.1038/s41586-025-09303-5" summary="NNMT inhibitor reduces tumor burden by reprogramming cancer-associated fibroblasts and restoring immune checkpoint blockade efficacy." >}}
{{< citation title="3D Multi-omic Mapping of Fallopian Tubes (STIC)" authors="Metousis A, et al., Mann M, Lengyel E" journal="bioRxiv" issue="2025.09.21.677628" summary="Spatially resolved multi-omics framework identifies 99 STICs and precursors in cancer-free organ donors, revealing high incidence of ovarian cancer precursors." >}}
{{< /citation-group >}}

{{< citation-group heading="E3 ligases – Brenda Schulman (MPI of Biochemistry)" >}}

{{< citation title="C-terminal amides mark proteins for degradation via SCF-FBXO31" authors="Muhar MF#, Farnung J#, Cernakova M, Hofmann R, Henneberg LT, Pfleiderer MM, Denoth-Lippuner A, Kalčic F, Nievergelt AS, Peters Al-Bayati M, Sidiropoulos ND, Beier V, Mann M, Jessberger S, Jinek M, Schulman BA, Bode JW, Corn JE" journal="Nature" issue="2025 Feb;638(8050):519-527" url="https://doi.org/10.1038/s41586-024-08475-w" >}}

{{< citation title="Cysteine availability tunes ubiquitin signaling via inverse stability of LRRC58 E3 ligase and its substrate CDO1" authors="Andree GA#, Stier L#, Schmiederer K, Thielen A, Schmid L, Maiwald SA, Du J, von Gronau S, Strasser C, Mueller J, Henneberg LT, Guyot C, Kleiger G, Mann M, Murray PJ & Schulman BA" journal="bioRxiv" issue="2025.11.14.688510" url="https://doi.org/10.1101/2025.11.14.688510" >}}

{{< /citation-group >}}


{{< citation-group heading="Clinical Proteomics - Nicolai Wewer Albrechtsen (Copenhagen)" >}}
{{< citation title="Diagnostic potential of proteomics in Lyme disease" authors="Nielsen AB, Fjordside L, Drici L, et al." journal="Nat Commun" issue="16, 9322 (2025)" summary="This report highlights the potential of proteomics to inform Machine Learning-assisted diagnostics." >}}
{{< /citation-group >}}

{{< citation-group heading="Other Key Collaborations" >}}
{{< citation title="GPX4 and Ferroptosis in Neurodegeneration" authors="Lorenz SM, et al., Mann M, ..., Conrad M" journal="Cell" issue="2025 Dec (with Marcus Conrad, Helmholtz Munich)" summary="A fin-loop-like structure in GPX4 underlies neuroprotection from ferroptosis. Proteomics revealed Alzheimer's-like signatures." >}}
{{< citation title="LRRK2 and Crohn's Disease/Colitis" authors="Heaton GR, et al., Mann M, ..., Yue Z" journal="J Clin Invest" issue="2025 Oct (with Zhenyu Yue, Mount Sinai)" summary="Targeting specific LRRK2 kinase substrates rescues colitis severity caused by Crohn's disease-linked variant." >}}

{{< /citation-group >}}

## Clinical Impact Highlight

**JAK Inhibitors for Toxic Epidermal Necrolysis**

[Our 2024 _Nature_ publication (Nordmann TM et al.)](https://doi.org/10.1038/s41586-024-08061-0) on spatial proteomics identifying JAK inhibitors as treatment for toxic epidermal necrolysis (TEN) -- a lethal skin disease -- has had immediate clinical impact in 2025. Off-label use of JAK inhibitors in the first patients worldwide led to complete recovery.

>_"To our knowledge, this is the first time a spatial omics technology
has made an immediate and tangible impact in the clinic, by identifying
a treatment that has already changed people's lives for the good."_

-- Matthias Mann


## Training and Recognition
Our commitment to training the next generation of scientists was reflected in the **successful graduation of four PhD students** this year, each of whom made significant contributions to our research program and are now launching careers in academia and industry. 

The laboratory's contributions to science were recognized with Mattias Mann's **election to the United States National Academy of Sciences**, one of the highest honors in scientific research.


## Publication Summary by Journal

{{< centered-table >}}
| Journal | Count | Topics |
| --- | --- | --- |
| _Nature_ | 2 | Liver disease (DVP), Review |
| _Nature Biotechnology_ | 1 | AlphaDIA transfer learning |
| _Nature Genetics_ | 1 | Pediatric plasma proteome |
| _Nature Protocols_ | 1 | PASEF workflow |
| _Nature Communications_ | 1 | ADAPT-MS (in press) |
| _Cancer Cell_ | 1 | Ovarian cancer progression (w/ Lengyel) |
| _Cell Systems_ | 1 | Colon organoid DVP |
| _EMBO Mol Med_ | 2 | Rare pediatric disorders, Pre-analytical bias |
| _Molecular Cell_ | 1 | Tumor-immune crosstalk |
| _Mol Cell Proteomics_ | 2 | PCA-N plasma, Stellar MS |
| _Commun Biol_ | 1 | Pancreatic islet cells |
| _NPJ Precision Oncol_ | 1 | Signet ring cell carcinoma |
| _Mol Syst Biol_ | 1 | AI laboratory agents |
{{< /centered-table >}}
