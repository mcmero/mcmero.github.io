---
permalink: /projects/
title: "Projects"
---

{: style="color:gray; font-size: 80%"}
**WEHI-SODA-Hub/sp_segment** 
[code](https://github.com/WEHI-SODA-Hub/sp_segment) | [poster](https://wehi-soda-hub.github.io/assets/images/soda-sp-segment-poster.pdf) | Segmentation pipeline for spatial proteomics.

{: style="color:gray; font-size: 80%"}
**Summary**: Spatial proteomics instruments, such as the Lunaphore COMET, can identify proteins at sub-cellular resolution. Such data requires accurate cell segmentation to correctly identify cell phenotypes for downstream analysis, however can be difficult to segment due to large image sizes and complex workflows. The sp_segment pipeline was developed as a user-friendly, robust and computationally efficient pipeline for cell segmentation, built using the nf-core template using Nextflow best practices. The pipeline performs background subtraction, highly-parallelised cell segmentation and resolution of cell compartments with intensity and shape measurements. This project was undertaken as part of [WEHI's Spatial Omics Data Analytics Hub](https://wehi-soda-hub.github.io/), which aims to support and streamline spatial omics analysis at the institute.

---

{: style="color:gray; font-size: 80%"}
**Nanopore Transfer Automation** 
[code](https://github.com/WEHIGenomicsRnD/nanopore-transfer-automation/) | [blog](/blog/The-promethion-task-of-data-automation/) | Data transfer automation tool for Oxford Nanopore Technologies' (ONT) sequencers.

{: style="color:gray; font-size: 80%"}
**Summary**: Data transfer of ONT sequencers is a non-trivial problem and is often made more complex due to network security restrictions that allow sequencing machines only limited access to internal networks. The Nanopore Transfer Automation pipeline is designed to streamline the process of packaging and moving ONT data in a robust and error-tolerant way from the sequencing computer to the destination via an automatable snakemake pipeline that interfaces with Globus for data transfers.

---

{: style="color:gray; font-size: 80%"}
![MINTIE](https://raw.githubusercontent.com/Oshlack/MINTIE/master/img/mintie_logo.png){: style="max-width: auto; height: 80px;"}  
[code](https://github.com/Oshlack/MINTIE) | [paper](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-021-02507-8) | A method for the identification of rare, novel RNA variants in cancer and rare disease.

{: style="color:gray; font-size: 80%"}
**Summary**: Rearrangements of DNA can modify gene function by altering transcript sequences, and have been shown to be key driver events in cancers and rare diseases. Transcriptomic variants may involve gene fusions, both the regular gene-to-gene variety and irregular fusions, bridged by non-gene sequence, or they may involve single genes, such as duplications, inversions and deletions. Apart from standard fusions, these kinds of transcriptomic variants are difficult to detect in RNA-seq, and not many methods exist to discover them. We’ve developed a method to detect all kinds of transcriptional variants in cancer and rare disease. We validated our approach using 1,500 simulated variants and found that MINTIE could detect more variant types at higher recall than any other method, while maintaining a low false positive rate. We applied MINTIE to a large B-cell Acute Lymphoblastic Leukaemia cohort and found a recurrent irregular fusion in the tumour suppressor gene RB1, as well as other variants in other genes associated with the disease (such as ETV6 splice variants, and duplications within IKZF1 and PAX5). We also applied our method to a rare muscle disease cohort and found a previously undetected irregular fusion in the muscle-disease associated DMD gene, in an undiagnosed patient. We anticipate MINTIE will uncover new disease variants across a range of diseases and cancer types.

---

{: style="color:gray; font-size: 80%"}
![SVclone](https://raw.githubusercontent.com/mcmero/SVclone/master/img/svclone_logo.png){: style="max-width: auto; height: 70px;"}  
[code](https://github.com/mcmero/SVclone) | [paper](https://www.nature.com/articles/s41467-020-14351-8) | A method for inferring the cancer cell fraction of tumour structural variation from whole-genome sequencing data.

{: style="color:gray; font-size: 80%"}
**Summary:** Cancer arises through DNA mutations in the genome. As populations of cancer cells divide, they continue to mutate and pass on their mutations to their daughter cells. Subpopulations of similar cells (called clones) can be identified by the proportions of mutations from bulk-sequenced tissue. Tracking these clones allows us to obtain valuable information about the tumour’s evolution. For example, we may identify mutations in certain clones that may confer resistance to particular treatments, allowing us to target treatment most effectively. Most approaches that identify clones look at single-nucleotide mutations, which are the most common mutation type we observe in cancers. Large rearrangements of DNA, called structural variation (SV), also occur and can have significant effects on the tumour genome, however, currently we lack approaches to characterise the SVs specific to certain clones. To address this, we developed a probabilistic model, called SVclone, that takes the SVs we have detected in our tumour sequencing sample and uses this information to identify clones. We applied our approach to a cohort of over 2,600 sequenced tumour samples across 38 tumour types and found distinct patterns across different cancer types. We identified one particular subset of samples with clones containing a characteristic set of rearrangements. Patients with these clones had reduced overall survival, suggesting that finding patterns such as this may help identify clinically relevant subtypes of cancers, ultimately leading to better monitoring and treatment.

---

{: style="color:gray; font-size: 80%"}
**EC DTU pipe**  
[code](https://github.com/Oshlack/ec-dtu-pipe) | [paper](https://f1000research.com/articles/8-265/v2) | A pipeline for performing differential transcript usage (DTU) analysis using equivalence classes, transcript quantifications and/or exon counts.

---

{: style="color:gray; font-size: 80%"}
**Perfect Phylogeny**  
[code](https://github.com/mcmero/perfect_phylogeny) | [blog 1](/blog/Perfect-phylogeny/) | [blog 2](/blog/The-problem-with-perfect-phylogenies/) | An implementation of the perfect phylogeny and incomplete phylogeny algorithms, for building and inferring phylogenetic trees.
