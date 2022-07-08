---
permalink: /
title: "Hello, I'm Mayee!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student in Computer Science at Stanford University, advised by Prof. [Christopher Ré](https://cs.stanford.edu/~chrismre/) and part of the [Hazy Research Lab](https://hazyresearch.stanford.edu/).

<!--I'm interested in exploring fundamental questions behind tools in modern machine learning and using them to develop new, theoretically grounded methods.-->
I'm interested in using theoretical tools to understand and improve on modern machine learning techniques.
My current research is in understanding representation geometry and modeling data, explained in more detail below:

- **Representation Geometry**: Traditional generalization results for supervised learning do not fully explain the capabilities of deep neural networks. Instead, examining the geometry of last-layer representations provides a way to understand these models. What makes for good learned representations, and how do we induce them? What theoretical frameworks can we develop to better understand geometry in deep learning, and what are their limitations in practice? I have been looking at these questions for self-supervised and contrastive learning recently.

- **Data(-centric AI)**: Real data is noisy, biased, and expensive to label. There are also other imperfect sources of signal that are available, ranging from external knowledge bases to pre-trained representations. How can we best model and harness real data and these other signals throughout the machine learning pipeline? I have been looking at these questions through the lens of Weak Supervision and latent variable graphical models.


<!--My current interests revolve around how to encode and evaluate sources of supervision and side information throughout the ML pipeline (e.g. weakly/semi/self-supervised) through both information-theoretic and geometric lenses. In particular, my work in graduate school so far has applied this interest to latent variable graphical models, distribution shift, and representations learned via contrastive losses.-->

<!--My current interests revolve around how to evaluate sources of supervision (e.g., weakly, semi-supervised, and self-supervised) throughout the ML pipeline and the role of misspecified inductive biases.-->
<!--More fundamentally, I have been working on developing efficient and robust estimators in latent variable models and understanding their finite-sample generalization error in different applications. 
I also enjoy learning about information theory, optimization, and probability theory.-->

Previously, I graduated summa cum laude from Princeton University in 2019 with a concentration in Operations Research and Financial Engineering (ORFE) and a certificate in Applications of Computing.
I worked on my senior thesis on quantum machine learning with Prof. [Elad Hazan](https://www.cs.princeton.edu/~ehazan/) and completed junior independent work on modeling misinformation in social networks  with Prof. [Miklos Racz](https://mracz.princeton.edu/).
<!--My senior thesis, which was awarded the Ahmet S. Çakmak Prize, was on quantum computing with Professor Elad Hazan.
I also worked with Prof. Miklos Racz on understanding the spread of misinformation in social networks.
I took a broad range of courses in computer science, statistics and financial mathematics and completed internships in software engineering and quantitative finance.-->


Publications and Preprints
------

### Representation Geometry

- [Perfectly Balanced: Improving Transfer and Robustness of Supervised Contrastive Learning](https://arxiv.org/abs/2204.07596) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Daniel Y. Fu\*, Avanika Narayan, Michael Zhang, Zhao Song, Kayvon Fatahalian, and Christopher Ré. *International Conference on Machine Learning (ICML)*, 2022. </span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2204.07596.pdf) </span>


- [TABi: Type-Aware Bi-encoders for End-to-End Entity Retrieval](https://arxiv.org/abs/2204.08173) <br>
  <span style="font-size:4mm;">Megan E. Leszczynski, Daniel Y. Fu, **Mayee F. Chen**, and Christopher Ré. To Appear in the Findings of the Association for Computational Linguistics (ACL), 2022.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2204.08173.pdf) </span>

- [The Details Matter: Preventing Class Collapse in Supervised Contrastive Learning](https://www.mdpi.com/2813-0324/3/1/4) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Daniel Y. Fu\*, Michael Zhang, Kayvon Fatahalian, and Christopher Ré. *AAAI Workshop on Artificial Intelligence with Biased or Scarce Data*, 2022. **Best Paper Award.**</span> <br>
  <span style="font-size:4mm;"> [paper](https://www.mdpi.com/2813-0324/3/1/4/pdf) </span>


### Data Modeling

- [Shoring Up the Foundations: Fusing Model Embeddings and Weak Supervision](https://arxiv.org/abs/2203.13270) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Daniel Y. Fu\*, Dyah Adila, Michael Zhang, Frederic Sala, Kayvon Fatahalian, and Christopher Ré. *Uncertainty in Artificial Intelligence (UAI)*, 2022. **Oral Presentation.** </span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2203.13270.pdf) | [slides for Snorkel AI talk](https://mayeechen.github.io/files/Liger_Snorkel_Talk.pdf) </span>

- [Mandoline: Model Evaluation under Distribution Shift](https://arxiv.org/abs/2107.00643) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Karan Goel\*, Nimit Sohoni\*, Fait Poms, Kayvon Fatahalian, and Christopher Ré. *International Conference on Machine Learning (ICML)*, 2021.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2107.00643.pdf) | [code](https://github.com/HazyResearch/mandoline) | [slides](https://mayeechen.github.io/files/ICMLMandolineTalk.pdf) </span>

- [Comparing the Value of Labeled and Unlabeled Data in Method-of-Moments Latent Variable Estimation.](https://arxiv.org/abs/2103.02761) <br>
  <span style="font-size:4mm;">**Mayee F. Chen**\*, Benjamin Cohen-Wang\*, Steve Mussmann, Frederic Sala, and Christopher Ré. *Artificial Intelligence and Statistics (AISTATS)*, 2021.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2103.02761.pdf) | [slides](https://mayeechen.github.io/files/AISTATS2021talk.pdf) </span>

- [Fast and Three-rious: Speeding Up Weak Supervision with Triplet Methods.](https://arxiv.org/abs/2002.11955) <br>
  <span style="font-size:4mm;">Daniel Y. Fu\*, **Mayee F. Chen**\*, Frederic Sala, Sarah M. Hooper, Kayvon Fatahalian, and Christopher Ré. *International Conference on Machine Learning (ICML)*, 2020.</span> <br>
  <span style="font-size:4mm;"> [paper](https://arxiv.org/pdf/2002.11955.pdf) | [code](https://github.com/HazyResearch/flyingsquid) | [video](https://www.youtube.com/watch?v=pHadwUKCoNE) | [blog](https://hazyresearch.stanford.edu/flyingsquid) </span>


### Other

- [Reducing Reliance on Spurious Features in Medical Image Classification with Spatial Specificity.]() <br>
  <span style="font-size:4mm;">Khaled Saab, Sarah M. Hooper, **Mayee F. Chen**, Micahel Zhang, Daniel Rubin, Christopher Ré. *Machine Learning for Healthcare (MLHC)*, 2022. </span><br>

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

