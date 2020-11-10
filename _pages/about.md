---
permalink: /
title: "Hello, I'm Mayee!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second year PhD student in Computer Science at Stanford University, advised by [Christopher Ré](https://cs.stanford.edu/~chrismre/) and part of the [Hazy Research Lab](https://hazyresearch.stanford.edu/).

I'm interested in understanding the fundamental theoretical questions behind tools in modern machine learning and using them to develop new practical methods.
My current interests revolve around how to evaluate sources of supervision, such as in weakly, semi-supervised, and self-supervised learning, and how to address model misspecification in these settings.
<!--More fundamentally, I have been working on developing efficient and robust estimators in latent variable models and understanding their finite-sample generalization error in different applications. 
I also enjoy learning about information theory, optimization, and probability theory.-->

Previously, I graduated summa cum laude from Princeton University in 2019 with a concentration in Operations Research and Financial Engineering (ORFE) and a certificate in Applications of Computing. I worked on my senior thesis with Professor Elad Hazan and completed junior independent work with Professor Miklos Racz.
<!--My senior thesis, which was awarded the Ahmet S. Çakmak Prize, was on quantum computing with Professor Elad Hazan.
I also worked with Professor Miklos Racz on understanding the spread of misinformation in social networks.
I took a broad range of courses in computer science, statistics and financial mathematics and completed internships in software engineering and quantitative finance.-->


Publications and Preprints
------
- Comparing the Value of Labeled and Unlabeled Data in Method-of-Moments Latent Variable Estimation.
  <span style="font-size:4em;">Mayee F. Chen\*, Benjamin Cohen-Wang\*, Steve Mussmann, Frederic Sala, and Christopher Ré. *In submission*, 2020.</span>

- Efficient Exploration in Linear MDPs with Nonlinear Confounding Rewards
  Mayee F. Chen, Yao Liu, Evan Z. Liu, and Emma Brunskill. *In submission*, 2020.

- Network Disruption: Maximizing Disagreement and Polarization in Social Networks.
  Mayee F. Chen and Miklos Z. Racz. *In submission*, 2020.

- Train and You'll Miss It: Interactive Model Iteration with Weak Supervision and Pre-Trained Embeddings.
  Mayee F. Chen\*, Daniel Y. Fu\*, Frederic Sala, Sen Wu, Ravi Teja Mullapudi, Fait Poms, Kayvon Fatahalian, and Christopher Ré. *arXiv preprint arXiv:2006.15168*, 2020.

- Fast and Three-rious: Speeding Up Weak Supervision with Triplet Methods.
  Mayee F. Chen\*, Daniel Y. Fu\*, Frederic Sala, Sarah M. Hooper, Kayvon Fatahalian, and Christopher Ré. *International Conference on Machine Learning (ICML)*, 2020.

- Effect of Rotational Grazing on Plant and Animal Production.
  Mayee F. Chen and Junping Shi. *Journal of Mathematical Biosciences and Engineering*, vol. 15, no. 2. 2018.

- Efficient GCD Computation for Big Integers on Xeon Phi Coprocessor.
  Jie Chen, William Watson, and Mayee F. Chen. *IEEE Conference on Networking, Architecture, and Storage (NAS)*. 2014

<!--This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).-->

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
