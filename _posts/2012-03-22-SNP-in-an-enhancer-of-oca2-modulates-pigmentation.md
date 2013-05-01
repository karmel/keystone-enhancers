---
layout: default
title: A SNP in an enhancer of OCA2 modulates pigmentation
category: examples
---

Visser M, Kayser M, Palstra RJ. HERC2 rs12913832 modulates human pigmentation by attenuating chromatin-loop formation between a long-range enhancer and the OCA2 promoter. _Genome Res_. 2012 Mar;22(3):446-55. <a class="pubmed-link" href="http://www.ncbi.nlm.nih.gov/pubmed/22234890" target="_blank">[Pubmed]</a>

### Summary
The authors find that a previously identified SNP that is highly correlated with Oca2 expression levels and thus pigmentation is located within an enhancer. The T-allele at this SNP results in more TF binding, more looping to the Oca2 promoter, and more Oca2 expression, thus elucidating how this SNP might be associated with variation in pigmentation in humans.

![Figure 1B-C]({{ site.baseurl}}/images/examples/2012-03-22-SNP-in-an-enhancer-of-oca2-modulates-pigmentation_fig1.png "Figure 1B-C")
### Notes on the paper
* A SNP highly correlated with Oca2 expression and therefore pigmentation was previously identified: rs12913832
* rs12913832 is located in an intron of Herc2, 21kb upstream of Oca2
* Previous studies had shown an association of rs12913832 with eye and skin color and proposed that rs12913832 was located within a regulatory region for Oca2, which was known to be involved in pigmentation (mutation causes albinism)
* Current study used two melanocyte lines, Human Epidermal Melanocytes of neonatal origin (HEMn) from a lightly-pigment donor (HEMn-LP) and a darkly-pigment donor (HEMn-DP)
* HEMn-DP has T-allele, HEMn-LP has C-allele
* HEMn-DP Oca2 >> HEMn-LP Oca2
* HEMn-DP RNA Pol at Oca2 promoter >> HEMn-LP RNA Pol at Oca2 promoter
* FAIRE-qPCR shows open chromatin in both, but not in negative control (MCF7). More open in HEMn-DP.
* H3Ac and H3K4me1 minimally enriched in HEMn-DP
* A melanocyte-specific enhancer: Cloned in rs12913832 region to luciferase reporter vector. No activity in HEK293, but has activity in G361 melanoma cells. HEMn-DP allele has 5x greater activity than HEMn-LP allele.
* 3C assay shows looping between the regulatory region and the Oca2 promoter in both DP and LP cells, but not in MCF7. More frequent looping in HEMn-DP than HEMn-LP.
* A second regulatory region is also enriched in 3C, but this one exists in MCF7 as well, so presumed to not be relevant to Oca2 expression variation.
* rs12913832 was previously hypothesized to disrupt a HLTF binding motif. The authors Chip-qPCR to show that there is less HLTF binding in HEMn-LP cells.
* Less HLTF correlates with reduced recruitment of cooperating TFs MITF and LEF1.
* Overexpression of HLTF increases Oca2 expression in HEMn-DP, but not HEMn-LP. 
* On the other hand, overexpression of MITF increases Oca2 expression in HEMn-LP but not HEMn-DP, implying MITF levels are not limiting in HEMn-DP, but that the reduced recruitment of MITF by HLTF in HEMn-DP is.
* A number of controls for other SNPs in the Herc/Oca2 region.

### Observations
* A single nucleotide change compromises the enhancer's efficiency and results in decreased gene expression: a keystone enhancer.
* The enhancer is melanocyte specific, and nearby enhancers are ruled out based on their existence in other cell types.
* 