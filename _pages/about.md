---
permalink: /
title: "About me"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a third-year Ph.D. student at Tsinghua Shenzhen International Graduate School, Tsinghua University supervised by Prof. [Xiu Li](https://scholar.google.com/citations?user=Xrh1OIUAAAAJ&hl=en). I am now working as a group leader of Reinforcement Learning Group of Intelligent Computing Lab (ICLAB). I receive my bachelor’s degree from the Department of Engineering Physics, Tsinghua University in 2020.

I am fortunate to work closely with Prof. [Zongqing Lu](https://scholar.google.com/citations?user=k3IFtTYAAAAJ&hl=en) from Peking University. I am now an intern student at Game AI Research Center, Tencent IEG (Interactive Entertainment Group), supervised by Mr. Le Wan. Before that, I was an intern student at Pengcheng Lab (PCL) supervised by Prof. [Zongqing Lu](https://scholar.google.com/citations?user=k3IFtTYAAAAJ&hl=en).

My research interests lie in efficient decision-making with deep Reinforcement Learning, including offline RL, sample-efficient general online model-free RL, and model-based RL. Meanwhile, I am interested in deploying RL algorithms in real-world applications, such as robotics, traffic signal control, etc.

Publications
============
**Preprint**

- [Bias-reduced Multi-step Hindsight Experience Replay for Efficient Multi-goal Reinforcement Learning](https://arxiv.org/pdf/2102.12962). Rui Yang, **Jiafei Lyu**, Yu Yang, Jiangpeng Yan, Feng Luo, Dijun Luo, Lanqing Li, Xiu Li.

**Conference Paper**

- [Efficient Continuous Control with Double Actors and Regularized Critics](https://ojs.aaai.org/index.php/AAAI/article/view/20732/20491). **Jiafei Lyu**^*^，Xiaoteng Ma^*^, Jiangpeng Yan, Xiu Li. *AAAI Conference on Artificial Intelligence*, (AAAI), 2022. <font color=“red”>(Oral)</font>
- [Double Check Your State Before Trusting It: Confidence-Aware Bidirectional Offline Model-Based Imagination](https://openreview.net/forum?id=3e3IQMLDSLP). **Jiafei Lyu**, Xiu Li, Zongqing Lu. *Advances in Neural Information Processing Systems (NeurIPS)*, 2022. <font color=“red”>(Spotlight)</font>
- [Mildly Conservative Q-learning for Offline Reinforcement Learning](https://openreview.net/forum?id=VYYf6S67pQc). **Jiafei Lyu**^*^， Xiaoteng Ma^*^, Xiu Li, Zongqing Lu. *Advances in Neural Information Processing Systems (NeurIPS)*, 2022. <font color=“red”>(Spotlight)</font>
- [PRAG: Periodic Regularized Action Gradient for Efficient Continuous Control](https://link.springer.com/chapter/10.1007/978-3-031-20868-3_8). Xihui Li, Zhongjian Qiao, Aicheng Gong, **Jiafei Lyu**, Chenghui Yu, Jiangpeng Yan, Xiu Li.


**Journal Paper**

- [Value Activation for Bias Alleviation: Generalized-activated Deep Double Deterministic Policy Gradients](https://arxiv.org/pdf/2112.11216). **Jiafei Lyu**^*^, Yu Yang^*^, Jiangpeng Yan, Xiu Li. *Neurocomputing*, 2023. (IF=5.7)

**Workshop Paper**

- [State Advantage Weighting for Offline RL](https://openreview.net/forum?id=2rOD_UQfvl). **Jiafei Lyu**, Aicheng Gong, Le Wan, Zongqing Lu, Xiu Li. 3rd Offline RL Workshop: Offline RL as a ''Launchpad'' at NeurIPS, 2022.

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
