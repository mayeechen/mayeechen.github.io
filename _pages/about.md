---
permalink: /
title: "Hello, I'm Mayee!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final-year PhD student in Computer Science at Stanford University, advised by Prof. [Christopher Ré](https://cs.stanford.edu/~chrismre/) and part of the [Hazy Research Lab](https://hazyresearch.stanford.edu/).

<!--I'm interested in exploring fundamental questions behind tools in modern machine learning and using them to develop new, theoretically grounded methods.-->

<!--I'm interested in using a theoretical lens to improve modern machine learning techniques from the data side of things (what is often referred to as **data-centric AI**). Recently, I've been focusing on problems in data mixing, data labeling, and data representations, especially in the setting where there are multiple input signals or objectives. Moving forward, I am particularly excited about developing a more principled understanding of how models learn from data.-->

I'm interested in studying and improving the fundamentals of modern machine learning through data (often known as **data-centric AI**). On the model training side, I work on data mixing, curriculum learning, synthetic data, and data labeling. On the inference side, I work on techniques such as ensembling, routing, and verification. Currently, I am thinking about how to develop and operationalize a more principled understanding of how models learn from data (what skills does data teach the model? Does it matter if the data is synthetic or real?) I am currently a research intern at the [Allen Institute for Artificial Intelligence (AI2)](https://allenai.org/), driving data mixing efforts for their OLMo open-source language models.


<!--I'm interested in using theoretical tools to understand and improve on modern machine learning techniques.
Recently, I've been focused on **data-centric AI**, working on understanding the role of data through weak supervision and data selection, in particular for foundation models. I'm also interested in the **representation geometry** of neural networks and how to induce desirable geometries.-->


<!--understanding **representation geometry** of deep networks and how to provably induce desirable geometries. I am also work on various things revolving around  **data-centric AI**, where I focus on Weak Supervision and data selection.-->

<!--My current research is in understanding representation geometry and modeling data, explained in more detail below:-->

<!-- **Representation Geometry**: Examining the geometry of last-layer representations provides a way to understand modern deep models beyond traditional supervised generalization results. What makes for good learned representations, and how do we provably induce them? What theoretical frameworks can we develop to better understand geometry in deep learning, and what are their limitations in practice? I have been looking at these questions for contrastive learning recently.-->

<!-- **Data(-centric AI)**: Real data is noisy, biased, and expensive to label. There are also other imperfect sources of signal that are available, ranging from external knowledge bases to pre-trained representations. How can we best model and harness real data and these other signals throughout the machine learning pipeline? I have been looking at these questions through the lens of Weak Supervision and latent variable graphical models.-->


<!--My current interests revolve around how to encode and evaluate sources of supervision and side information throughout the ML pipeline (e.g. weakly/semi/self-supervised) through both information-theoretic and geometric lenses. In particular, my work in graduate school so far has applied this interest to latent variable graphical models, distribution shift, and representations learned via contrastive losses.-->

<!--My current interests revolve around how to evaluate sources of supervision (e.g., weakly, semi-supervised, and self-supervised) throughout the ML pipeline and the role of misspecified inductive biases.-->
<!--More fundamentally, I have been working on developing efficient and robust estimators in latent variable models and understanding their finite-sample generalization error in different applications. 
I also enjoy learning about information theory, optimization, and probability theory.-->

Previously, I graduated summa cum laude from Princeton University with a concentration in Operations Research and Financial Engineering (ORFE) and a certificate in Applications of Computing, where I worked with Prof. [Elad Hazan](https://www.cs.princeton.edu/~ehazan/) and Prof. [Miklos Racz](https://mracz.princeton.edu/).
<!--I worked on my senior thesis on quantum machine learning with Prof. [Elad Hazan](https://www.cs.princeton.edu/~ehazan/) and completed junior independent work on modeling misinformation in social networks  with Prof. [Miklos Racz](https://mracz.princeton.edu/).-->
<!--My senior thesis, which was awarded the Ahmet S. Çakmak Prize, was on quantum computing with Professor Elad Hazan.
I also worked with Prof. Miklos Racz on understanding the spread of misinformation in social networks.
I took a broad range of courses in computer science, statistics and financial mathematics and completed internships in software engineering and quantitative finance.-->



Please get in touch with me via email if you would like to chat about research or collaboration!


## Publications and Preprints
------

For a chronological order of my publications, please check out my [Google Scholar](https://scholar.google.com/citations?hl=en&user=dhgytncAAAAJ&view_op=list_works&sortby=pubdate)/[CV](https://mayeechen.github.io/files/MayeeChen_CV.pdf). 

### Training Data

- [Aioli: A Unified Optimization Framework for Language Model Data Mixing](https://arxiv.org/abs/2411.05735)<br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Michael Y. Hu\*, Nicholas Lourie, Kyunghyun Cho, Christopher Ré. *International Conference on Learning Representations (ICLR)*, 2025.</span><br>
<span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2411.05735) | [code](https://github.com/HazyResearch/aioli) | [data mixing tutorial for Data@CoRL2025 workshop](https://mayeechen.github.io/files/Data@CORL2025_Presentation.pdf)</span>

- [DataComp-LM: In search of the next generation of training sets for language models](https://arxiv.org/abs/2406.11794)<br>
  <span style="font-size:4mm;">Jeffrey Li, ..., Ludwig Schmidt, Vaishaal Shankar (59 authors, including **Mayee F. Chen**). *Conference on Neural Information Processing Systems (NeurIPS) Datasets and Benchmarks Track*, 2024.</span><br>
<span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2406.11794.pdf) | [code](https://github.com/mlfoundations/dclm) | [project page](https://www.datacomp.ai/dclm/)</span>

- [Cookbook: A framework for improving LLM generative abilities via programmatic data generating templates](https://arxiv.org/abs/2410.05224)<br>
  <span style="font-size:4mm;">Avanika Narayan\*, **Mayee F. Chen**\*, Kush Bhatia, Christopher Ré. *Conference on Language Modeling (COLM)*, 2024.</span><br>
  <span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2410.05224.pdf) </span>
  
- [Skill-it! A data-driven skills framework for understanding and training language models.](https://arxiv.org/abs/2307.14430)<br>
  <span style="font-size:4mm;">**Mayee F. Chen**, Nicholas Roberts, Kush Bhatia, Jue Wang, Ce Zhang, Frederic Sala, Christopher Ré. *Conference on Neural Information Processing Systems (NeurIPS)*, 2023. **Spotlight (top 3.1% of submissions).**</span><br>
  <span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2307.14430.pdf) | [AllenAI talk](https://mayeechen.github.io/files/allenai_talk.pdf) | [code](https://github.com/HazyResearch/skill-it) </span>

### Test-time Techniques

- [Shrinking the Generation-Verification Gap with Weak Verifiers](https://arxiv.org/abs/2506.18203)<br>
  <span style="font-size:4mm;">Jon Saad-Falcon\*, E. Kelly Buchanan\*, **Mayee F. Chen**\*,  Tzu-Heng Huang, Brendan McLaughlin, Tanvir Bhathal, Shang Zhu, Ben Athiwaratkun, Frederic Sala, Scott Linderman, Azalia Mirhoseini, Christopher R\'e. *Conference on Neural Information Processing Systems (NeurIPS)*, 2025.</span><br>
 <span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2506.18203) | [blog](https://hazyresearch.stanford.edu/blog/2025-06-18-weaver)</span>

- [Archon: An Architecture Search Framework for Inference-Time Techniques](https://arxiv.org/abs/2409.15254)<br>
  <span style="font-size:4mm;">Jon Saad-Falcon, Adrian Gamarra Lafuente, Shlok Natarajan, Nahum Maru, Hristo Todorov, Etash Kumar Guha, E. Kelly Buchanan, **Mayee F. Chen**, Neel Guha, Christopher Ré, Azalia Mirhoseini. *International Conference on Machine Learning (ICML)*, 2025.</span><br>
 <span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2409.15254)</span>

- [Smoothie: Label Free Language Model Routing](https://arxiv.org/abs/2412.04692)<br>
  <span style="font-size:4mm;">Neel Guha\*, **Mayee F. Chen**\*, Trevor Chow, Ishan S. Khare, Christopher Ré. *Conference on Neural Information Processing Systems (NeurIPS)*, 2024.</span><br>
  <span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2412.04692) | [code](https://github.com/HazyResearch/smoothie) | [blog](https://hazyresearch.stanford.edu/blog/2024-12-10-smoothie)</span>

- [Embroid: Unsupervised Prediction Smoothing Can Improve Few-Shot Classification.](https://arxiv.org/abs/2307.11031)<br>
  <span style="font-size:4mm;">Neel Guha\*, **Mayee F. Chen**\*, Kush Bhatia\*, Azalia Mirhoseini, Frederic Sala, Christopher Ré. *Conference on Neural Information Processing Systems (NeurIPS)*, 2023. </span><br>
  <span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2307.11031.pdf)</span>

- [Ask Me Anything: A simple strategy for prompting language models](https://arxiv.org/abs/2210.02441) <br>
  <span style="font-size:4mm;">Simran Arora\*, Avanika Narayan\*, **Mayee F. Chen**, Laurel J. Orr, Neel Guha, Kush Bhatia, Ines Chami, Frederic Sala, Christopher Ré. *International Conference on Learning Representations (ICLR)*, 2023. **Notable top 25% of acceptances.** </span><br>
  <span style="font-size:4mm;">[paper](https://arxiv.org/pdf/2210.02441.pdf) | [code](https://github.com/HazyResearch/ama_prompting)</span>



### Data Labeling

- [Shoring Up the Foundations: Fusing Model Embeddings and Weak Supervision](https://arxiv.org/abs/2203.13270) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Daniel Y. Fu\*, Dyah Adila, Michael Zhang, Frederic Sala, Kayvon Fatahalian, and Christopher Ré. *Uncertainty in Artificial Intelligence (UAI)*, 2022. **Best Student Paper Runner-Up Award, Oral Presentation.** </span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2203.13270.pdf) | [code](https://github.com/HazyResearch/liger) [slides](https://mayeechen.github.io/files/LigerUAITalk.pdf) | [blog](https://snorkel.ai/liger-fusing-foundation-model-embeddings-weak-supervision/) | [Snorkel talk](https://www.youtube.com/watch?v=rTpwOYXUuCk) </span>

- [Comparing the Value of Labeled and Unlabeled Data in Method-of-Moments Latent Variable Estimation.](https://arxiv.org/abs/2103.02761) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Benjamin Cohen-Wang\*, Steve Mussmann, Frederic Sala, and Christopher Ré. *Artificial Intelligence and Statistics (AISTATS)*, 2021.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2103.02761.pdf) | [slides](https://mayeechen.github.io/files/AISTATS2021talk.pdf) </span>

- [Fast and Three-rious: Speeding Up Weak Supervision with Triplet Methods.](https://arxiv.org/abs/2002.11955) <br>
  <span style="font-size:4mm;">Daniel Y. Fu\*, **Mayee F. Chen**\*, Frederic Sala, Sarah M. Hooper, Kayvon Fatahalian, and Christopher Ré. *International Conference on Machine Learning (ICML)*, 2020.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2002.11955.pdf) | [code](https://github.com/HazyResearch/flyingsquid) | [video](https://www.youtube.com/watch?v=pHadwUKCoNE) | [blog](https://hazyresearch.stanford.edu/flyingsquid) </span>


### Data Representations


- [Perfectly Balanced: Improving Transfer and Robustness of Supervised Contrastive Learning](https://arxiv.org/abs/2204.07596) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Daniel Y. Fu\*, Avanika Narayan, Michael Zhang, Zhao Song, Kayvon Fatahalian, and Christopher Ré. *International Conference on Machine Learning (ICML)*, 2022. </span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2204.07596.pdf) | [code](https://github.com/HazyResearch/thanos-code) | [blog](https://hazyresearch.stanford.edu/blog/2022-04-19-contrastive-2) </span>


- [TABi: Type-Aware Bi-encoders for End-to-End Entity Retrieval](https://arxiv.org/abs/2204.08173) <br>
  <span style="font-size:4mm;">Megan E. Leszczynski, Daniel Y. Fu, **Mayee F. Chen**, and Christopher Ré. To Appear in the Findings of the Association for Computational Linguistics (ACL), 2022.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2204.08173.pdf) | [code](https://github.com/HazyResearch/tabi) | [blog](https://hazyresearch.stanford.edu/blog/2022-04-19-contrastive-3) </span>
  

- [The Details Matter: Preventing Class Collapse in Supervised Contrastive Learning](https://www.mdpi.com/2813-0324/3/1/4) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Daniel Y. Fu\*, Michael Zhang, Kayvon Fatahalian, and Christopher Ré. *AAAI Workshop on Artificial Intelligence with Biased or Scarce Data*, 2022. **Best Paper Award.**</span> <br>
  <span style="font-size:4mm;"> [paper](https://www.mdpi.com/2813-0324/3/1/4/pdf) | [code](https://github.com/HazyResearch/thanos-code) </span>


### Science/Health Applications

- [A case for reframing automated medical image classification as segmentation.]()<br>
  <span style="font-size:4mm;">Sarah Hooper, **Mayee F. Chen**, Khaled Kamal Saab, Kush Bhatia, Curtis Langlotz, Christopher Ré. *Conference on Neural Information Processing Systems (NeurIPS)*, 2023. </span><br> 

- [Anomaly Detection with Multiple Reference Datasets](https://link.springer.com/article/10.1007/JHEP07(2023)188) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**, Benjamin Nachman, Frederic Sala. *Journal of High Energy Physics (JHEP)*, 2023. *Machine Learning and the Physical Sciences (ML4PS) Workshop at NeurIPS*, 2022. </span><br>
  <span style="font-size:4mm;">[paper](https://link.springer.com/article/10.1007/JHEP07(2023)188) | [code](https://github.com/mayeechen/anomaly-detection-multi)</span>

- [Reducing Reliance on Spurious Features in Medical Image Classification with Spatial Specificity.](https://static1.squarespace.com/static/59d5ac1780bd5ef9c396eda6/t/62e97a2961bc144a5d6a4cbb/1659468331136/126+MLHC_2022_Specificity_Robustness_cameraready.pdf) <br>
  <span style="font-size:4mm;">Khaled Saab, Sarah M. Hooper, **Mayee F. Chen**, Michael Zhang, Daniel Rubin, Christopher Ré. *Machine Learning for Healthcare (MLHC)*, 2022. </span><br>
  <span style="font-size:4mm;">[paper](https://static1.squarespace.com/static/59d5ac1780bd5ef9c396eda6/t/62e97a2961bc144a5d6a4cbb/1659468331136/126+MLHC_2022_Specificity_Robustness_cameraready.pdf) | [code](https://github.com/khaledsaab/spatial_specificity)</span>



### Model evaluation

- [Mandoline: Model Evaluation under Distribution Shift](https://arxiv.org/abs/2107.00643) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Karan Goel\*, Nimit Sohoni\*, Fait Poms, Kayvon Fatahalian, and Christopher Ré. *International Conference on Machine Learning (ICML)*, 2021.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2107.00643.pdf) | [code](https://github.com/HazyResearch/mandoline) | [slides](https://mayeechen.github.io/files/ICMLMandolineTalk.pdf) | [MedAI talk](https://www.youtube.com/watch?v=LmiNQio4db0) </span>


### Older


- [An Adversarial Model of Network Disruption: Maximizing Disagreement and Polarization in Social Networks.](https://arxiv.org/abs/2003.08377) <br>
  <span style="font-size:4mm;">**Mayee F. Chen** and Miklos Z. Racz. *IEEE Transactions on Network Science and Engineering (TNSE)*, 2021.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/abs/2003.08377.pdf) | [code](https://github.com/mayeechen/network-disruption) </span>

<!---
- Efficient Exploration in Linear MDPs with Nonlinear Confounding Rewards. <br>
  <span style="font-size:4mm;">**Mayee F. Chen**, Yao Liu, Evan Z. Liu, and Emma Brunskill. *Submitted*, 2020.</span> <br>
  <span style="font-size:4mm;"> [paper](https://mayeechen.github.io/files/Linear_MDP_with_Confounding_Rewards_Full.pdf) </span>
-->

<!---
- [Train and You'll Miss It: Interactive Model Iteration with Weak Supervision and Pre-Trained Embeddings.](https://arxiv.org/abs/2006.15168) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Daniel Y. Fu\*, Frederic Sala, Sen Wu, Ravi Teja Mullapudi, Fait Poms, Kayvon Fatahalian, and Christopher Ré. *arXiv preprint arXiv:2006.15168*, 2020.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2006.15168.pdf) | [code](https://github.com/HazyResearch/epoxy) | [video](https://www.youtube.com/watch?v=_d-mseTaYWY) </span>
-->

- [Effect of Rotational Grazing on Plant and Animal Production.](https://www.aimsciences.org/article/doi/10.3934/mbe.2018017) <br>
  <span style="font-size:4mm;">**Mayee F. Chen** and Junping Shi. *Journal of Mathematical Biosciences and Engineering*, vol. 15, no. 2. 2018.</span> <br>
  <span style="font-size:4mm;"> [paper](https://mayeechen.github.io/files/rotational.pdf) | [slides](https://mayeechen.github.io/files/rotational_presentation.pdf) </span>

- [Efficient GCD Computation for Big Integers on Xeon Phi Coprocessor.](https://ieeexplore.ieee.org/abstract/document/6923168) <br>
  <span style="font-size:4mm;">Jie Chen, William Watson, and **Mayee F. Chen**. *IEEE Conference on Networking, Architecture, and Storage (NAS)*. 2014.</span> <br>
  <span style="font-size:4mm;"> [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6923168) | [slides](https://mayeechen.github.io/files/nas2014talk.pdf) </span>

