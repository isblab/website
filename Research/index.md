---
title: Research  
layout: default
group: Research
---

## Integrative structures of protein assemblies

<p class="text-justify">
Structures of several large protein complexes and assemblies are difficult to obtain using a single experimental or computational method. Integrative structure determination fills this gap; various types of experimental data are combined along with principles from physics, statistical inference, and prior models to obtain the structure. The different sources of input information may span multiple scales; for example, X-ray data is at the atomic scale, while FRET distances are at the domain scale. However, these sources can be complementary; for example, EM maps may provide the shape of a complex while chemical crosslinks may provide the orientation of binding interfaces. We have used structural, biochemical, biophysical, cell biological, genetic, and in-silico bioinformatics information for deducing the structure of assemblies.
</p>

<p class="text-justify">
Of late, AI-based methods have enabled amazing advances in structural biology and it is an exciting, fast-paced field! For us, simulation and analysis of large macromolecular assemblies leads us to interesting opportunities for developing new modeling methods. We develop rigorous methods and software to make integrative structure determination more accurate and efficient by improving upon approaches that are ad hoc, semi-automated, based on trial-and-error, and/or require manual expert intervention. We use algorithms from computational statistics, statistical physics, machine learning and optimization, computer vision, and graph theory.  
</p>

### Areas of integrative structure determination <br>

<p class="text-justify">
Opportunities exist in our group to work on several such assemblies. Example areas include assemblies involved in regulating gene expression, including chromatin remodelers, and mitochondrial assemblies. We collaborate closely with other cell and structural biologists to validate predictions from our models and generate data for the modeling. For more information, please read two recent reviews ([**1**](https://arxiv.org/abs/2407.00566),[**2**](https://arxiv.org/abs/2401.17894)) on integrative structural modeling from our group.

</p>

### Chromatin remodelers
<p class="text-justify">
We recently determined the structures of sub-complexes of the Nucleosome Remodeling and Deacetylase, [**NuRD complex**](https://doi.org/10.1002/pro.4387), a chromatin-modifying assembly that regulates gene expression and is conserved across plant and animal species. Using Bayesian integrative structure determination, we combined information from SEC-MALLS, DIA-MS, XLMS, negative stain EM, X-ray crystallography, and NMR spectroscopy, secondary structure, and homology predictions. The integrative structures were further validated by independent cryo-EM maps, biochemical assays, and known cancer-associated mutations. Based on the structures, we proposed a model showing how the two enzymatic modules in the assembly maybe connected by MBD.  
</p>

![NuRD two-states](/static/img/researchpics/two_states_nurd.png){:style="display: block; margin-left: auto; margin-right: auto; max-height=40%; max-width=40%"}
<p class="text-center">*Two-state model of MBD3 binding in NuRD*</p>


### Cell-cell junctions
<p class="text-justify">
We recently characterized the molecular architecture of the [**desmosomal outer dense plaque (ODP)**](https://doi.org/10.1002/pro.5217) using Bayesian integrative structural modeling via the Integrative Modeling Platform. Starting principally from the structural interpretation of a cryo-electron tomography (cryo-ET) map of the ODP, we integrated information from x-ray crystallography, an immuno-electron microscopy study, biochemical assays, in silico predictions of trans-membrane and disordered regions, homology modeling, and stereochemistry information. The integrative structure was validated by information from imaging, tomography, and biochemical studies that were not used in modeling. We refined previous protein-protein interactions between desmosomal proteins and provided possible structural hypotheses for defective cell-cell adhesion in several diseases by mapping disease-related mutations on the structure. Finally, we point to structure features that could confer resilience to mechanical stress.
</p>

![Desmosomal ODP](/static/img/researchpics/desmosome.png){:style="display: block; margin-left: auto; margin-right: auto; max-height=40%; max-width=40%"}
<p class="text-center">*Desmosomal outer dense plaque (ODP) model*</p>


### Optimizing multi-scale coarse-grained model representations
<p class="text-justify">

We recently developed a method to optimize the multi-scale coarse-grained representation for modeling assemblies in [**IMP**](https://integrativemodeling.org). Nested sampling for Optimizing Representation, i.e. [**NestOR**](https://academic.oup.com/bioinformatics/article-abstract/doi/10.1093/bioinformatics/btae106/7613065?utm_source=etoc&utm_campaign=bioinformatics&utm_medium=email) uses Bayesian model selection to identify the optimal coarse-grained representation for a given integrative modeling setup. The Nested Sampling method is used to efficiently compute the model evidence for a representation.

</p>

![NestOR](/static/img/researchpics/nestor.png){:style="display: block; margin-left: auto; margin-right: auto; max-height=40%; max-width=30%"}

<p class="text-center">*Bayesian model selection-based optimal representation for the integrative models*</p>

### Frontiers in integrative structural modeling
<p class="text-justify">
We noticed two recurrent modeling challenges across a range of studies. One was the need to develop methods for incorporating disordered regions in these assemblies and another was to better utilize information from cryo-electron tomography, a timely challenge as structural biology is moving towards in situ characterization. We are currently focusing our method development in these two areas.
</p>

![Schematic](/static/img/researchpics/qrb.png){:style="display: block; margin-left: auto; margin-right: auto; max-height=40%; max-width=30%"}
<p class="text-center">*Schematic describing integrative structure determination for the nucleosome remodeling and deacetylase complex (orange box) and the desmosomal outer dense plaque (green box) combining data from multiple sources. Low-resolution cryo-EM and cryo-ET maps (green) and intrinsically disordered regions (yellow) in both complexes are highlighted as emerging areas for method development.*</p>

#### Disobind
<p class="text-justify">
We recently developed [**Disobind**](https://doi.org/10.1101/2024.12.19.629373), a deep-learning method that predicts inter-protein contact maps and interface residues for an IDR and a partner protein, leveraging sequence embeddings from a protein language model. Several current methods, in contrast, provide partner-independent predictions, require the structure of either protein, and/or are limited by the MSA quality. Disobind performs better than AlphaFold-multimer and AlphaFold3. Combining the Disobind and AlphaFold-multimer predictions further improves the performance.
</p>

![Disobind](/static/img/researchpics/disobind.png){:style="display: block; margin-left: auto; margin-right: auto; max-height=2%; max-width=2%"}

<p class="text-center">*A deep-learning method to predict inter-protein contact maps and interface residues for an IDR and a partner protein from their sequences*</p>

<!-- #### We thank journals for highlighting our integrative modeling studies in their cover.
![NuRD cover](/static/img/researchpics/nurdCover.png){:style="display: block; margin-left: auto; margin-right: auto; max-height=40%; max-width=30%"}
![Desmosome cover](/static/img/researchpics/desmosomeCover.png){:style="display: block; margin-left: auto; margin-right: auto; max-height=40%; max-width=30%"} -->
