---
title: Research
layout: default
group: Research
---

## Integrative structures of protein assemblies
<hr>
<p class="text-justify">
An integrative structure determination approach combines diverse experimental data with physical principles, statistics of previous structures, and prior models for structure determination, making it a powerful method for studying macromolecular assemblies that are challenging to resolve using any single experimental method.
</p>
<p class="text-justify">
Over the past few years, several advancements in computational and experimental methods have sparked renewed enthusiasm for integrative modeling. AI-based structure prediction methods, such as AlphaFold, have transformed protein structure prediction. Whereas rapid advances in experimental techniques such as cryo-electron tomography (cryo-ET) now enable structural characterization of assemblies in their native cellular context at higher throughput and larger scales than before.
Our research follows two synergistic tracks.
<!--
Structures of several large protein complexes and assemblies are difficult to obtain using a single experimental or computational method. Integrative structure determination fills this gap; various types of experimental data are combined along with principles from physics, statistical inference, and prior models to obtain the structure. The different sources of input information may span multiple scales; for example, X-ray data is at the atomic scale, while FRET distances are at the domain scale. However, these sources can be complementary; for example, EM maps may provide the shape of a complex while chemical crosslinks may provide the orientation of binding interfaces. <strong> We have used structural, biochemical, biophysical, cell biological, genetic, and in-silico bioinformatics information for deducing the structure of assemblies.</strong> For more information, please read two recent reviews ([**1**](https://arxiv.org/abs/2407.00566),[**2**](https://arxiv.org/abs/2401.17894)) on integrative structural modeling from our group. -->
</p>

### Integrative structure determination applied to biological systems
<hr>
<p class="text-justify">
One track involves determining integrative structures of specific biological systems to gain insights into their function through close collaborations with experimentalists. We determined the structures of chromatin-associated assemblies, such as the nucleosome remodeling and deacetylase complex, and cell-cell junctions, such as the epithelial desmosomal outer dense plaque, combining diverse biophysical and biochemical data at various scales. Together, these integrative structures reveal mechanisms by which these complex molecular machines function and assemble; they also enabled us to rationalize mutations from cancers, epithelial, and cardiac diseases.
<!--
Of late, AI-based methods have enabled amazing advances in structural biology and it is an exciting, fast-paced field! For us, simulation and analysis of large macromolecular assemblies leads us to interesting opportunities for developing new modeling methods. <strong> We develop rigorous methods and software to make integrative structure determination more accurate and efficient by improving upon approaches that are ad hoc, semi-automated, based on trial-and-error, and/or require manual expert intervention. </strong> We use algorithms from computational statistics, statistical physics, machine learning and optimization, computer vision, and graph theory.   -->
</p>

![modeled systems](/static/img/researchpics/research_pic_apps.jpeg){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 90%; text-align: center;"}
<p class="text-center">***Integrative structures** characterized recently are shown, along with the information that was incorporated (<span style="background-color: #e7f9bdff">green</span> background), and the insights derived (<span style="background-color: #fee8b9ff">orange</span> background).*</p>

<!-- ### Areas of integrative structure determination -->
### Method development in integrative structural biology
<hr>
<p class="text-justify">
<!-- Opportunities exist in our group to work on several such assemblies. Example areas include assemblies involved in regulating gene expression, including chromatin remodelers, and mitochondrial assemblies. We collaborate closely with other cell and structural biologists to validate predictions from our models and generate data for the modeling. -->
A second research track involves developing broadly applicable, cutting-edge modeling methods, using algorithms from statistical inference, machine learning, computer vision, and related fields.  We develop rigorous methods and software to make integrative structure determination more accurate and efficient by improving upon approaches that are ad hoc, semi-automated, based on trial-and-error, and/or require manual expert intervention. All our methods are available as open-source software. (See <a href="https://isblab.ncbs.res.in/Software/">Software & Resources</a>).
</p>

![isblab methods](/static/img/researchpics/research_pic_methods.jpeg){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 75%; text-align: center;"}
<p class="text-center">***Integrative modeling methods** and software developed by our group are shown. The text color indicates the corresponding stage of integrative modeling (center).*</p>

<p class="text-justify">
Usually, these method development directions emerge from recurrent themes identified across multiple modeling studies. Recent examples include **Disobind**, a deep learning method for identifying binding sites of intrinsically disordered regions (IDRs), and **PickET**, an unsupervised method for localizing macromolecules in cryo-ET data.
</p>

![disobind](/static/img/researchpics/research_pic_disobind.jpeg){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 93%; text-align: center;"}
<p class="text-center">***Disobind**: a deep learning method for predicting interface residues and inter-protein contact maps for an IDR and its partner, given their sequences. Method architecture (top) and representative examples (bottom) are shown.*</p>
<hr>
![picket](/static/img/researchpics/research_pic_picket.jpeg){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 90%; text-align: center;"}
<p class="text-center">***PickET**: a workflow for unsupervised localization in tomograms (left) along with representative segmentations (right) for two real tomograms (CZI-DS-10001, gallium FIB milled S. pombe lamella: top row, CZI-DS-10301, plasma FIB milled C. reinhardtii lamella: bottom row). See <a href="https://doi.org/10.1101/2025.08.20.671250">PickET </a> for more details.*</p>

<!-- ### Chromatin remodelers
<hr>
<p class="text-justify">
We recently determined the structures of sub-complexes of the [**Nucleosome Remodeling and Deacetylase (NuRD)**](https://doi.org/10.1002/pro.4387) complex, a chromatin-modifying assembly that regulates gene expression and is conserved across plant and animal species. Using Bayesian integrative structure determination, we combined information from SEC-MALLS, DIA-MS, XLMS, negative stain EM, X-ray crystallography, and NMR spectroscopy, secondary structure, and homology predictions. The integrative structures were further validated by independent cryo-EM maps, biochemical assays, and known cancer-associated mutations. Based on the structures, we proposed a model showing how the two enzymatic modules in the assembly maybe connected by MBD.
</p>

![NuRD two-states](/static/img/researchpics/two_states_nurd.png){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 70%; text-align: center;"}
<p class="text-center">*Two-state model of MBD3 binding in NuRD*</p>


### Cell-cell junctions
<hr>
<p class="text-justify">
We recently characterized the molecular architecture of the [**desmosomal outer dense plaque (ODP)**](https://doi.org/10.1002/pro.5217) using Bayesian integrative structural modeling via the Integrative Modeling Platform. Starting principally from the structural interpretation of a cryo-electron tomography (cryo-ET) map of the ODP, we integrated information from x-ray crystallography, an immuno-electron microscopy study, biochemical assays, in silico predictions of trans-membrane and disordered regions, homology modeling, and stereochemistry information. The integrative structure was validated by information from imaging, tomography, and biochemical studies that were not used in modeling. We refined previous protein-protein interactions between desmosomal proteins and provided possible structural hypotheses for defective cell-cell adhesion in several diseases by mapping disease-related mutations on the structure. Finally, we point to structure features that could confer resilience to mechanical stress.
</p>

![Desmosomal ODP](/static/img/researchpics/desmosome_lpd.png){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 60%; text-align: center;"}
<p class="text-center">*Desmosomal outer dense plaque (ODP) model*</p> -->


<!-- ### Optimizing multi-scale coarse-grained model representations
<hr>
<p class="text-justify">

We recently developed <strong>a method to optimize the multi-scale coarse-grained representation</strong> for modeling assemblies in [**IMP**](https://integrativemodeling.org). Nested sampling for Optimizing Representation, i.e. [**NestOR**](https://academic.oup.com/bioinformatics/article-abstract/doi/10.1093/bioinformatics/btae106/7613065?utm_source=etoc&utm_campaign=bioinformatics&utm_medium=email) uses Bayesian model selection to identify the optimal coarse-grained representation for a given integrative modeling setup. The Nested Sampling method is used to efficiently compute the model evidence for a representation.

</p>

![NestOR](/static/img/researchpics/nestor.png){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 90%; text-align: center;"}

<p class="text-center">*Bayesian model selection-based optimal representation for the integrative models*</p>

### Annotating precision for integrative models
<hr>
[**PrISM**](https://doi.org/10.1093/bioinformatics/btac400) is our recently developed <strong>method to identify high and low precision regions</strong> in an ensemble of integrative models of large macromolecular assemblies. It is now used in the pipeline for validating integrative models deposited in the [wwPDB (worldwide Protein Data Bank)](https://www.wwpdb.org/)! 

### Frontiers in integrative structural modeling
<hr>
<p class="text-justify">
We noticed two recurrent modeling challenges across a range of studies. One was the need to develop methods for incorporating <strong>disordered regions</strong> in these assemblies and another was to better utilize information from <strong>cryo-electron tomography</strong>, a timely challenge as structural biology is moving towards in situ characterization. We are currently focusing our method development in these two areas.
</p>

![Schematic](/static/img/researchpics/qrb.png){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 85%; text-align: center;"}
<p class="text-center">*Schematic describing integrative structure determination for the nucleosome remodeling and deacetylase complex (orange box) and the desmosomal outer dense plaque (green box) combining data from multiple sources. Low-resolution cryo-EM and cryo-ET maps (green) and intrinsically disordered regions (yellow) in both complexes are highlighted as emerging areas for method development.*</p>

### Disobind
<hr>
<p class="text-justify">
We recently developed [**Disobind**](https://doi.org/10.1101/2024.12.19.629373), a deep-learning method that <strong>predicts inter-protein contact maps and interface residues for an IDR and a partner protein</strong>, leveraging sequence embeddings from a protein language model. Several current methods, in contrast, provide partner-independent predictions, require the structure of either protein, and/or are limited by the MSA quality. Disobind performs better than AlphaFold-multimer and AlphaFold3. Combining the Disobind and AlphaFold-multimer predictions further improves the performance.
</p>

![Disobind](/static/img/researchpics/disobind.png){:style="display: block; margin-left: auto; margin-right: auto; max-height: 50%; max-width: 90%; text-align: center;"}

<p class="text-center">*A deep-learning method to predict inter-protein contact maps and interface residues for an IDR and a partner protein from their sequences*</p> -->

<hr>

###### We thank the following journals for highlighting our integrative modeling studies in their cover.

<!-- <div style="align-items: center; align-content: center;" > -->

<div style="display: flex; justify-content: center; align-items: center; align-content: center;">
<p style="text-align: center;">
<img src="/static/img/researchpics/nurdCover.jpg" style="max-height: 20%; max-width: 28%;" alt="NuRD cover">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="/static/img/researchpics/desmosomeCover.jpg" style="max-height: 20%; max-width: 28%;" alt="Desmosome cover">
</p>
</div>

<!-- </div> -->