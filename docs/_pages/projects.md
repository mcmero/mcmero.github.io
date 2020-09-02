---
permalink: /projects/
title: "Projects"
---


{: style="color:gray; font-size: 80%"}
![MINTIE](https://raw.githubusercontent.com/Oshlack/MINTIE/master/img/mintie_logo.png){: style="max-width: auto; height: 80px;"}  
[code](https://github.com/Oshlack/MINTIE) | [preprint](https://www.biorxiv.org/content/10.1101/2020.06.03.131532v1.abstract) | A method for the identification of rare, novel RNA variants in cancer and rare disease.

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
