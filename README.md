<img src="http://willfreyman.org/assets/img/onag_big1.jpg" width="350" />

# IB290: Topics in Phylogenetics
# UC Berkeley

* Grad Seminar 460
* Class Number 67082
* Fall, 2017
* Wednesdays 5:15 - 6:45 PM
* 1002 VLSB
* Class website: [https://wf8.github.io/IB290/](https://wf8.github.io/IB290/)

## Instructors

* Carl Rothfels -- crothfels@berkeley.edu
* John Huelsenbeck -- johnh@berkeley.edu
* Will Freyman -- freyman@berkeley.edu

## Format 

The instructors will lead a series of introductory sessions (lectures) for the first four or five meetings. Subsequent meetings will be student-led. Each student will be responsible for leading at least one session (potentially more, depending on enrollment and interest) on a topic of their choice, in consultation with the instructors. That student will be responsible for developing an annotated bibliography of the important papers on the topic, including both “classics” and the most recent works, for selecting two or so of the papers for the class to read, and for preparing a short (15min) presentation on the topic. The remainder of the session will be devoted to discussion.

## Course Texts 

There are no formal texts required for this seminar, but participants are encouraged to consult *Tree Thinking: An Introduction to Phylogenetic Biology* (Baum & Smith 2012) and also *Inferring Phylogenies* (Felsenstein 2004).

## Useful Info

Here are some useful links on statistics and phylogenetic software: [https://wf8.github.io/IB290/useful](https://wf8.github.io/IB290/useful)

## Possible Topics for Student Led Discussions

*Please consult an instructor before settling on a topic:*

modeling migration/hybridization/introgression (phylogenetic networks); state-dependent diversification models; fossil data (e.g. fossilized-birth-death process/tip dating vs node calibrations); modeling gene duplication and loss; polymorphism-aware (PoMo) models; covarion/hidden state models; model testing (e.g. Bayes factors, AIC); model adequacy (e.g. posterior predictive tests); demographic inference (e.g., inferring population size changes through time); the multispecies coalescent, genetrees/species tree; the BAMM controversy; divergence time dating; inferring selection from sequence alignments; alignment inference (alignment-phylogeny co-inference?); community phylogenetics; spatial phylogenetics; inferring phylogenies from morphological data; heterogeneous models, e.g., non-stationary base frequencies; ancestral state reconstruction; phylogenomics (strengths, pitfalls?); inferring correlated evolution of traits; assessing support; hypothesis testing of relationships; reconstructing morphological evolution on a phylogeny; ABC approaches; hidden Markov models; mixture models; species delimitation; microbial community analysis; quartet-based methods (e.g. SVDquartets); etc; etc;


## Schedule:

Our first meeting will be on Wednesday, August 30.

### August 30: Introductions

*Who are we, and want to do we want to get out of this seminar?*
* Outline of the course
* Outline of “phylogenetics”, i.e., introduction to trees—what is a phylogeny?—and tree thinking—what does this tree say?
* Discussion of topics to select for future class sessions
* Reading: chapters 1, 2, and 3 of Tree Thinking
* Slides: [Rothfels Intro Slides](https://wf8.github.io/IB290/lecture_slides/Mtg01_intro.ppt)

### September 6: Introduction to probability theory

*Introduction to probability, estimation, and inference:*
* Maximum likelihood
* Bayesian estimation
* MCMC
* Reading: [Coin Tossing - Diaconis et al 2007](https://wf8.github.io/IB290/readings/2007_Diaconis.pdf)

### September 13: Introduction to tree inference and Markov models of character change 

*Introduction to the application of Markov models to tree inference (Part 1):*
* What is a Markov model? 
* Properties and uses of Markov models
* Pruning algorithm
* Slides: [Huelsenbeck Likelihood Phylo Slides](https://wf8.github.io/IB290/lecture_slides/Mtg02_Huelsenbeck_Likelihood_Phylo.pdf)

### September 20: Introduction to tree inference and Markov models of character change

*Introduction to the application of Markov models to tree inference (Part 2):*
* More on Markov models 
* Substition models
* Slides: [Huelsenbeck Likelihood Phylo Slides](https://wf8.github.io/IB290/lecture_slides/Mtg03_Huelsenbeck_Likelihood_Phylo.pdf)

### September 27: Introduction to "tree models" and their uses

*Introduction to models of tree shape, topology, and branch lengths:*
* Uniform tree topologies
* Coalescent trees
* Birth-death processes and their application to:
  * Divergence time estimation
  * Diversification rate estimation
* Slides: [Freyman Coalescent & Birth-Death Slides](https://wf8.github.io/IB290/lecture_slides/Mtg04_Freyman_Coalescent_Birth_Death_Trees.pdf)

### October 4: Phylogenetics potpourri -- recap and misc. stuff that we didn't cover yet

*Phylogenetics potpourri:* 
* alignment
* MCMC
* bootstrapping
* gene trees versus species tree
* Slides: [Rothfels Phylo Potpourri](https://wf8.github.io/IB290/lecture_slides/Mtg05_Carl_misc/Mtg05_misc.ppt)

### October 11: Inferring hybridization, reticulation, and inosculation

Prahlada Papper & Virginia Tartaglio

* [Pease, J.B., Haak, D.C., Hahn, M.W., & Moyle, L.C. 2016. Phylogenomics reveals three sources of adaptive variation during a rapid radiation. PLoS Biology, 14(2), e1002379.](https://wf8.github.io/IB290/readings/Pease_et_al_2016.pdf)
* [Wen, D., Yu, Y., & Nakhleh, L. 2016. Bayesian inference of reticulate phylogenies under the multispecies network coalescent. PLoS Genetics, 12(5), e1006006.](https://wf8.github.io/IB290/readings/Wen_et_al_2016.pdf)
* [Blischak, P.D., Chifman, J., Wolfe, A.D., & Kubatko, L.S. 2017 [preprint]. HyDe: A Python package for genome-scale hybridization detection. bioRxiv preprint server, 188037.](https://wf8.github.io/IB290/readings/Blischak_et_al_2017.pdf)

* Prahlada and Virginia's [annotated bibliography](https://wf8.github.io/IB290/bibliographies/reticulationAnnotatedBibliography_VM_PP.pdf)

### October 18: Inferring correlated continuous trait evolution 

Emily King & Richelle Tanner

* [Khabbazian, M., Kriebel, R., Rohe, K., & Ané, C. (2016). Fast and accurate detection of evolutionary shifts in Ornstein–Uhlenbeck models. Methods in Ecology and Evolution, 7(7), 811-824.](https://wf8.github.io/IB290/readings/Khabbazian_et_al_2016.pdf)
* [Huey, R. B., & Bennett, A. F. (1987). Phylogenetic studies of coadaptation: preferred temperatures versus optimal performance temperatures of lizards. Evolution, 41(5), 1098-1115.](https://wf8.github.io/IB290/readings/Huey_and_Bennett_1987.pdf)

* Emily and Richelle's [annotated bibliography](https://wf8.github.io/IB290/bibliographies/IB290-ContinuousTraitEvolution.pdf)

### October 25: The fossilized birth-death process

Daniel Latorre

* [Heath, T.A., Huelsenbeck, J.P. & Stadler, T. (2014). The fossilized birth-death process for coherent calibration of divergence time estimates. PNAS](https://github.com/wf8/IB290/blob/master/readings/Heath_et_al_2014_PNAS_-_Fossilized_birth_death_process_for_calibration_of_divergence-time.pdf)
* [Law, J.C., Slater, G.J., Mehta, R.S. (2017). Lineage Diversity and Size Disparity in Musteloidea: Testing Patterns of Adaptive Radiation Using Molecular and Fossil-Based Methods. Syst. Biol.](https://github.com/wf8/IB290/blob/master/readings/Law_et_al_2017_Musteloidea_Phylogeny_SystBiol.pdf)

* [annotated bibliography](https://wf8.github.io/IB290/bibliographies/Fossilized_Birth-Death_Annotated_Bibliography.pdf)

### November 1: Evolution under the threshold model

Joyce Chery & Will Iles 

* [Revell, L. J. (2014). Ancestral character estimation under the threshold model from quantitative genetics. Evolution, 68(3), 743-759.](https://github.com/wf8/IB290/blob/master/readings/Revell-2014-Evolution.pdf)

* [annotated bibliography](https://wf8.github.io/IB290/bibliographies/Threshold_model_literature.pdf)

### November 8: Historical biogeographic models 

Jun Ying Lim and Isaac Marck

* [Matzke, N. J. 2014. Model selection in historical biogeography reveals that founder-event speciation is a crucial process in island clades. Systematic Biology, 63(6), 951-970.](https://wf8.github.io/IB290/readings/Matzke_2014.pdf)

* [annotated bibliography](https://wf8.github.io/IB290/bibliographies/Historical_Biogeography_Models.pdf)

### November 15: The Coalescent 

Carrie Tribble and Gabriel Damasco

* [Liu, L., Yu, L., Kubatko, L., Pearl, D. K., & Edwards, S. V. 2009. Coalescent methods for estimating phylogenetic trees. Molecular Phylogenetics and Evolution, 53(1), 320-328.](https://wf8.github.io/IB290/readings/Liu_et_al_2009.pdf)

* [Yang, Z. 2015. The BPP program for species tree estimation and species delimitation. Current Zoology, 61(5), 854-865.](https://wf8.github.io/IB290/readings/Yang_2015.pdf)

* [annotated bibliography](https://wf8.github.io/IB290/bibliographies/coalescent_annotated_bib.pdf)

### November 22: <span style="color:red">NO CLASS</span>

### November 29: State-dependent speciation and extinction models

Jesus Martinez-Gomez and Mick Song

* [O’Meara, B. C., & Beaulieu, J. M. (2016). Past, future, and present of state-dependent models of diversification. American journal of botany, 103(5), 792-795.](https://wf8.github.io/IB290/readings/OMeara_Beaulieu_2016.pdf)

* [Rabosky, D. L., & Goldberg, E. E. (2015). Model inadequacy and mistaken inferences of trait-dependent speciation. Systematic Biology, 64(2), 340-355.](https://wf8.github.io/IB290/readings/Rabosky_Goldberg_2015.pdf)

* [Maddison, W. P., Midford, P. E., & Otto, S. P. (2007). Estimating a binary character's effect on speciation and extinction. Systematic biology, 56(5), 701-710.](https://wf8.github.io/IB290/readings/Maddison_et_al_2007.pdf)

* [annotated bibliography](https://wf8.github.io/IB290/bibliographies/SSE_Annotated_Bibliography.pdf)

### December 6: Inferring selection

Betsabe Castro Escobar and Jenna Baughman


* [Yang, Z., & Nielsen, R. (2002). Codon-substitution models for detecting molecular adaptation at individual sites along specific lineages. Molecular biology and evolution, 19(6), 908-917.](https://wf8.github.io/IB290/readings/Yang_Nielsen_2002.pdf)

* [Pond, S. L. K., Frost, S. D., Grossman, Z., Gravenor, M. B., Richman, D. D., & Brown, A. J. L. (2006). Adaptation to different human populations by HIV-1 revealed by codon-based analyses. PLoS computational biology, 2(6), e62.](https://wf8.github.io/IB290/readings/kosakovsky_2006.pdf)

* [Wilson, D. J., Hernandez, R. D., Andolfatto, P., & Przeworski, M. (2011). A population genetics-phylogenetics approach to inferring natural selection in coding sequences. PLoS genetics, 7(12), e1002395.](https://wf8.github.io/IB290/readings/Wilson_et_al_2011.pdf)

* [annotated bibliography](https://wf8.github.io/IB290/bibliographies/JB_InferingSelection_AnnotatedBib.pdf)
