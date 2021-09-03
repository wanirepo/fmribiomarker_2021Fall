# 2021 Fall "fMRI biomarker development 2" at SKKU IPHC (graduate course)

<br>

- Lecturer: Choong-Wan Woo, Ph.D. Assistant professor (GBME).
- Office: N-center, 86335
- Web: [Cocoan lab](http://cocoanlab.github.io)
- E-mail: waniwoo@skku.edu
- Class: Fri 12:00-2:45PM (online only)
- Office hours: Fri 15:00-16:00, you can book a time in advance through [https://choongwanwoo.youcanbook.me](https://choongwanwoo.youcanbook.me)

<br>

## Download
You can download the class materials using the following command line:

	$ git clone https://github.com/wanirepo/advancedfmrianalysis_2019fall

Once you clone the github repository, you can just type the following command to get the updated github repository:

	$ git pull
	
Or you can download the repository as a zip file or you can also use [GitHub Desktop](https://desktop.github.com). The class materials will be uploaded (e.g., lecture slides, assignments) before each class. 

There is a good github tutorial: [https://rogerdudler.github.io/git-guide/index.html](https://rogerdudler.github.io/git-guide/index.html)

## What are the aims of this course?

The functional neuroimaging, esp. functional Magnetic Resonance Imaging (fMRI), has revolutionalized how we study human brain functions, human cognition, and behaviors. It enables us to study fine-grained neural dynamics and representations that give rise to adaptive human behaviors and cognitions. The powerful imaging methods and neuroimaging data had called for better analysis methods and approaches, and thanks to recent advances in statistical and computational methods (including machine learning), more researchers are developing and applying more advanced analysis methods to neuroimaging data. However, using more advanced methods itself does not make the study better automatically, and sometimes advanced methods make research worse by sacrificing the interpretability, robustness, and reproducibility of the research findings. These advanced methods should be used very carefully with a critical mind to actually help make research better.

The idea of opening this class began with the 2019 OHBM meeting, where I saw a lot of advanced new analysis methods that I wasn't aware of, meaning that the field is rapidly changing (in terms of the analysis methodology), and we need to put efforts to know what kinds of analysis methods are being developed and used. We need to analyze them with critical eyes to know strengths and weaknesses of these new methods. Otherwise, we will stuck! Using them is one thing, but more importantly, we need to know the methods to understand the science behind the technology better and to know where the field is heading.

Let's do this process together! I believe in a collective intelligence, and through the class, I hope we can do it together.


## Course format and expectations

We will make a list of the analysis methods we want to cover in the first class, and each student will be assigned to each method. The leader student should provide: 1) key papers that used the methods, 2) video lecture links (if available), 3) presentation in the class (focused on the method), 4) example data and codes (these will be uploaded to our class github repository). 

Before the class, all students are required to read each week's key papers and watch the video lectures (if there is any). In the class, the leader student has to give a presentation first, and also provides a hands-on experience.

### Team meeting:

Each team should have a meeting with Wani few weeks before your week. Ideally, after the class. You should request the meetings in advance. 


## Evaluation

This class will use the absolute evaluation.

1. Attendance (30%)
2. Presentation/hands-on (40%)
5. Participation (30%)


## Schedule

Week  | Topic | Video lecture | Reading | Codes 
------| ----- | ----- | ----- | -------
Week 1 (9/3) | Class overview, Team assignment ||||
Week 2 (9/10) | Activity flow over resting-state networks (지웅, Juan Medrano)| | | |
Week 3 (9/17) | Introducing multiple parcellations and maps (백준호, Arpan Ghosh)  | | | |
Week 4 (9/24) | Intrinsic timescale (허권, 김준호) | | | |
Week 5 (10/1) | Temporal communities detection (지수, 형섭) | | | |
Week 6 (10/8) | Cross hierarchy propagation (노영, 최준현) | | | |
Week 7 (10/15) | Deep learning in fMRI (다솜, 박채정)  | | | |
Week 8 (10/22) | Connectopic mapping (Yutong Bai, 함홍기) | | | |
Week 9 (10/29) | Quasi-periodic pattern analysis (안예찬, 주경진) | | | |
Week 10 (11/5) | Variational autoencoder (VAE) in fMRI (성우, 혜빈) | | | |
Week 11 (11/12) | Successor Representation (제영, Nabih Pico) | | | |
Week 12 (11/19) | Personalized and surface-based parcellation methods (재중, 혜민) | | | |
Week 13 (11/26) | Graph neural network (지훈, 김수종) | | | |
Week 14 (12/3) | State space in fMRI (정우, 이은진) | | | |
Week 15 (12/10) | Final week | | | |

_Note._ Weekly plan described above can be adjusted as our class develops.

## Potential topics

We have 13 weeks! Here are the options:

1. Activity flow over resting-state networks ([Michael Cole lab](http://www.colelab.org/),  [github](https://github.com/ColeLab/ActflowToolbox) has multiple papers on this)
  - Ito, T., Hearne, L., Mill, R., Cocuzza, C., & Cole, M. W. (2020). Discovering the Computational Relevance of Brain Network Organization. Trends in Cognitive Sciences, 24(1), 25–38.
  - Cole, M. W., Ito, T., Bassett, D. S., & Schultz, D. H. (2016). Activity flow over resting-state networks shapes cognitive task activations. Nature Neuroscience, advance online publication. https://doi.org/10.1038/nn.4406
  - Hearne, L. J., Mill, R. D., Keane, B. P., Repovš, G., Anticevic, A., & Cole, M. W. (2021). Activity flow underlying abnormalities in brain activations and cognition in schizophrenia. Science Advances, 7(29). https://doi.org/10.1126/sciadv.abf2513
  - etc. search papers with "activity flow" in colelab papers
  - 지웅, Juan Medrano

2. Temporal communities detection
  - Thompson, W. H., Kastrati, G., Finc, K., Wright, J., Shine, J. M., & Poldrack, R. A. (2020). Time-varying nodal measures with temporal community structure: A cautionary note to avoid misinterpretation. Human Brain Mapping, 41(9), 2347–2356.
  - Thompson, W. H., Wright, J., Shine, J. M., & Poldrack, R. A. (2019). The identification of temporal communities through trajectory clustering correlates with single-trial behavioural fluctuations in neuroimaging data. bioRxiv, 617027, [github](https://github.com/wiheto/teneto))
  - 지수, 형섭

3. State space in fMRI 
  - Shine, J. M., Breakspear, M., Bell, P. T., Martens, K. A. E., Shine, R., Koyejo, O., Sporns, O., & Poldrack, R. A. (2019). Human cognition involves the dynamic integration of neural activity and neuromodulatory systems. Nature Neuroscience, 22(2), 289. [https://github.com/macshine/state_space](https://github.com/macshine/state_space))
  - 정우, 이은진

4. Seed-based mean co-activation patterns CAPs 
  - Bolton, T. A. W., Tuleasca, C., Wotruba, D., Rey, G., Dhanis, H., Gauthier, B., Delavari, F., Morgenroth, E., Gaviria, J., Blondiaux, E., Smigielski, L., & Van De Ville, D. (2020). TbCAPs: A toolbox for co-activation pattern analysis. NeuroImage, 211, 116621. [toolbox](https://c4science.ch/source/CAP_Toolbox/)
  - Gutierrez-Barragan, D., Basson, M. A., Panzeri, S., & Gozzi, A. (2019). Infraslow State Fluctuations Govern Spontaneous fMRI Network Dynamics. Current Biology: CB, 29(14), 2295–2306.e5. 

5. Quasi-periodic pattern analysis 
  - Yousefi, B., & Keilholz, S. (2021). Propagating patterns of intrinsic activity along macroscale gradients coordinate functional connections across the whole brain. NeuroImage, 231, 117827. [github](https://github.com/GT-EmoryMINDlab), [C-PAC link](https://fcp-indi.github.io/docs/latest/user/group_qpp))
  - 안예찬, 주경진

6. Cross hierarchy propagation 
  - Gu, Y., Sainburg, L. E., Kuang, S., Han, F., Williams, J. W., Liu, Y., Zhang, N., Zhang, X., Leopold, D. A., & Liu, X. (2021). Brain Activity Fluctuations Propagate as Waves Traversing the Cortical Hierarchy. Cerebral Cortex , 31(9), 3986–4005. [github](https://github.com/YamengGu/the-cross-hierarchy-propagation))
  - 노영, 최준현

7. Variational autoencoder (VAE) in fMRI 
  - Kim, J.-H., Zhang, Y., Han, K., Wen, Z., Choi, M., & Liu, Z. (2021). Representation learning of resting state fMRI with variational autoencoder. NeuroImage, 241, 118423. [link](https://www.sciencedirect.com/science/article/pii/S1053811921006984), [github](https://github.com/libilab/rsfMRI-VAE), 
  - Zhang, X., Maltbie, E., & Keilholz, S. (2021). Spatiotemporal Trajectories in Resting-state FMRI Revealed by Convolutional Variational Autoencoder. In bioRxiv (p. 2021.01.25.427841). https://doi.org/10.1101/2021.01.25.427841 [link](https://www.biorxiv.org/content/10.1101/2021.01.25.427841v1.abstract))
  - 성우, 혜빈

8. Deep learning in fMRI 
  - VanRullen, R., & Reddy, L. (2018). Reconstructing Faces from fMRI Patterns using Deep Generative Neural Networks. arXiv:1810.03856 [cs, Q-Bio]. http://arxiv.org/abs/1810.03856,
  - Horikawa, T., & Kamitani, Y. (2017). Generic decoding of seen and imagined objects using hierarchical visual features. Nature Communications, 8, ncomms15037.
  - Wen, H., Shi, J., Zhang, Y., Lu, K.-H., Cao, J., & Liu, Z. (n.d.). Neural Encoding and Decoding with Deep Learning for Dynamic Natural Vision. Cerebral Cortex , 1–25.
  - Zhang, Y., Han, K., Worth, R., & Liu, Z. (2020). Connecting concepts in the brain by mapping cortical representations of semantic relations. Nature Communications, 11(1), 1877. 
  - 다솜, 박채정

9. Personalized and surface-based parcellation methods:
  - Glasser, M. F., Coalson, T. S., Robinson, E. C., Hacker, C. D., Harwell, J., Yacoub, E., Ugurbil, K., Andersson, J., Beckmann, C. F., Jenkinson, M., Smith, S. M., & Van Essen, D. C. (2016). A multi-modal parcellation of human cerebral cortex. Nature, advance online publication. https://doi.org/10.1038/nature18933 
  - Gordon, E. M., Laumann, T. O., Gilmore, A. W., Newbold, D. J., Greene, D. J., Berg, J. J., Ortega, M., Hoyt-Drazen, C., Gratton, C., Sun, H., Hampton, J. M., Coalson, R. S., Nguyen, A. L., McDermott, K. B., Shimony, J. S., Snyder, A. Z., Schlaggar, B. L., Petersen, S. E., Nelson, S. M., & Dosenbach, N. U. F. (2017). Precision Functional Mapping of Individual Human Brains. Neuron, 95(4), 791–807.e7.
  - Ji, J. L., Spronk, M., Kulkarni, K., Repovš, G., Anticevic, A., & Cole, M. W. (2019). Mapping the human brain’s cortical-subcortical functional network organization. NeuroImage, 185, 35–57. Cole lab's [CAB-NP](https://github.com/ColeLab/ColeAnticevicNetPartition)
  - Dickie, E. W., Anticevic, A., Smith, D. E., Coalson, T. S., Manogaran, M., Calarco, N., Viviano, J. D., Glasser, M. F., Van Essen, D. C., & Voineskos, A. N. (2019). Ciftify: A framework for surface-based analysis of legacy MR acquisitions. NeuroImage, 197, 818–826. [ciftify](https://github.com/edickie/ciftify)
  - 재중, 혜민

10. Introducing multiple parcellations and maps 
  - [Canlab Neuroimaging_Pattern_Masks repository](https://github.com/canlab/Neuroimaging_Pattern_Masks)
  - SPM anatomy toolbox
  - [SUIT](http://www.diedrichsenlab.org/imaging/suit.htm) 
  - [Yeo group's atlases](https://github.com/ThomasYeoLab/CBIG/tree/master/stable_projects/brain_parcellation)
  - Constable group
  - Brainnetome
  - and more (what's more recent ones? please update me)
  - 백준호, Arpan Ghosh


11. Connectopic mapping
  - Haak, K. V., Marquand, A. F., & Beckmann, C. F. (2018). Connectopic mapping with resting-state fMRI. NeuroImage, 170, 83–94. [paper](https://www.sciencedirect.com/science/article/pii/S1053811917305463), [github](https://github.com/koenhaak/congrads)
  - Yutong Bai, 함홍기

12. Intrinsic timescale
  - Raut, R. V., Snyder, A. Z., & Raichle, M. E. (2020). Hierarchical dynamics as a macroscopic organizing principle of the human brain. Proceedings of the National Academy of Sciences of the United States of America, 117(34), 20890–20897.
  - Raut, R. V., Snyder, A. Z., Mitra, A., Yellin, D., Fujii, N., Malach, R., & Raichle, M. E. (2021). Global waves synchronize the brain’s functional systems with fluctuating arousal. Science Advances, 7(30), eabf2709.
  - [github](https://github.com/ryraut/arousal-waves)
  - 허권, 김준호


13. Topographical factor analysis (Jeremy Manning, [MIND2017](https://mindsummerschool.org/2017/08/13/multiscale-network-dynamics.html))

14. Successor Representation etc. (by Ida Momennejad at [MIND2017, 2018, 2019](https://mindsummerschool.org); this is not specifically about fMRI, but it has been addressed in MIND for three years, and at 2019, Dr. Momennejad provided a tutorial. I think we can learn about SR together and discuss how to implement this for fMRI)
  - 제영, Nabih Pico

15. Graph neural network 
  - Li, X., Zhou, Y., Dvornek, N., Zhang, M., Gao, S., Zhuang, J., Scheinost, D., Staib, L., Ventola, P., & Duncan, J. (2021). BrainGNN: Interpretable Brain Graph Neural Network for fMRI Analysis. In bioRxiv (p. 2020.05.16.100057). https://doi.org/10.1101/2020.05.16.100057 
  - there can be more in fMRI, and
  - there will be huge literature on GNN in computer science
  - 지훈, 김수종


Others (maybe save for future):

- RNN (e.g., [COSYNE 2021 tutorial](http://www.cosyne.org/c/index.php?title=Tutorial_2021))
- Harmonization methods
- Active inference (e.g., [Smith et al., 2021](https://psyarxiv.com/b4jm6/))
- Markov blanket feature selection
- Subspace analysis
- LFADS
- NIMH Macaque Template
- Monkey preprocessing [PREEMACS](https://www.sciencedirect.com/science/article/pii/S1053811920311563)
- NeMo (Network modification tool) [nitrc](https://www.nitrc.org/projects/brainnet_2013)
- Connectopic mapping
- RL in fMRI
- Neuroimaging analysis platforms: [Neuroscout](https://neuroscout.org/), [MRIQC](https://mriqc.readthedocs.io/en/stable/), [fMRIDenoise](https://github.com/nbraingroup/fmridenoise), [Neurolearn](http://neuro-learn.org/)


and more

(Covered topics)

- Basics of network analysis
- CanlabCORE tools [canlab tools](https://canlab.github.io/)
- Deep transfer learning
- Distance correlation and representational connectivity analysis
- Gradient mapping ([Hong et al. 2019](https://www.nature.com/articles/s41467-019-08944-1))
- Hidden Markov Model
- Hyperalignment [Manning's Hypertools](https://hypertools.readthedocs.io/en/latest/) 
- ICA/PCA
- Interpreting machine learning models [tutorial](https://github.com/cocoanlab/interpret_ml_neuroimaging)
- Inter-subject FC (ISFC) [Nastase et al., 2019](https://www.biorxiv.org/content/10.1101/741975v1)
- Linear dimension reduction methods
- Mediation analysis, predictive modeling [Woo et al. 2015](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002036) [Kohoutová et al., 2020](https://www.nature.com/articles/s41596-019-0289-5)
- Multilayer community detection [multilayer community detection](https://www.pnas.org/content/112/37/11678)
- Multivariate pattern dependence
- Nipype and fMRIprep
- NLP or Topic modeling
- Non-linear dimension reduction methods (t-sne)
- Representational similarity analysis [tutorial](https://github.com/cocoanlab/khbm2019_RSA_tutorial)
- Shared response model [Cameron Chen's slide](https://cameronphchen.github.io/files/20170215_SRM_Tutorial.pdf)



#### See some existing awesome tutorials

- [MIND2017](https://mindsummerschool.org/2017/08/13/multiscale-network-dynamics.html)
- [MIND2018](https://mindsummerschool.org/2018/07/30/narratives-and-naturalistic-contexts.html)
- [Neurohackademy2018](https://www.youtube.com/playlist?list=PLO3l0PnUGHYEqA7rFQT2jM6jxsaC2XiHh)
- [Neurohackademy2019](https://www.youtube.com/results?search_query=NeuroHackademy+2019)
- [Mumfordbrainstats](https://www.youtube.com/channel/UCZ7gF0zm35FwrFpDND6DWeA)
- OHBM on demand
- Neuromatch academy
- CCN


## Full references

TBA

<!--### Week 3

Kriegeskorte, N., Mur, M., & Bandettini, P. (2008). Representational similarity analysis - connecting the branches of systems neuroscience. Frontiers in Systems Neuroscience, 2(November), 4.

Nili, H., Wingfield, C., Walther, A., Su, L., Marslen-Wilson, W., & Kriegeskorte, N. (2014). A Toolbox for Representational Similarity Analysis. PLoS Computational Biology, 10(4), e1003553.

### Week 4

Kohoutová, L., Heo, J., Cha, S., Moon, T., Lee, S., Wager, T. D., & Woo, C. -W. (under review) Interpreting machine learning models in neuroimaging: Towards a unified framework
-->
