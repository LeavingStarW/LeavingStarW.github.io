---
layout: archive
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<font size=3>Hello, my name is Zhipeng Wang (王志鹏). I am a third-year Computer Science and Technology student at Hangzhou Dianzi University, supervised by Prof. Ruiquan Ge (葛瑞泉) from Hangzhou Dianzi University and Prof. Changmiao Wang (王昌淼) from Shenzhen Research Institute of Big Data.</font>


Competition News
======
+ 2024.12: We won the National Bronze Medal in the China International College Students' Innovation Competition 2024.
+ 2024.05: We won the Finalist Prize (National First Prize) in the 2024 Mathmatical Contest In Modeling.
+ 2024.05: We won the Provincial Second Prize in the Zhejiang Province Challenge Cup Competition.
+ 2023.12: We won the National Bronze Medal in the China International College Students' Innovation Competition 2023.
+ 2023.12: We won the International Third Prize in the 2023 Asia and Pacific Mathematical Contest in Modeling.
+ 2023.06: We won the Provincial Third Prize in the 2023 Service Outsourcing and Entrepreneurship Innovation Competition.

Publications
======
+ <img align="left" src=""/> [GCINet: global convolution interaction network with a pre-trained reversible normalization method for long-term time series forecasting](https://link.springer.com/article/10.1007/s00521-024-10692-3)
Jin Fan, Baoshun Yang, Danfeng Sun, Jie Liu, Qikai Chen, Zhipeng Wang, Jia Wu

+ <img align="left" src=""/> [CCLNet: Causal and Contrastive Learning Framework for Enhanced Pulmonary Embolism Detection](https://ieeexplore.ieee.org/document/10821899)
Zhipeng Wang, Ruiquan Ge^*^, Jianxun Yu, Feiwei Qin, Yuan Tian, Nannan Li, Wenwen Min, Ahmed Elazab, Changmiao Wang^*^

+ <img align="left" src=""/> [PE-MVCNET: MULTI-VIEW AND CROSS-MODAL FUSION NETWORK FOR PULMONARY EMBOLISM PREDICTION](https://ieeexplore.ieee.org/document/10635747)
Zhaoxin Guo, Zhipeng Wang, Ruiquan Ge^*^, Jianxun Yu, Feiwei Qin^*^, Yuan Tian, Yuqing Peng, Yonghong Li, Changmiao Wang

#+ <img align="left" src=""/> [A Novel Fusion Network for Apple Image Classification and Quantity Recognition]
#(https://dl.acm.org/doi/10.1145/3653781.3653794)
#Hanyu Jiang, Zhipeng Wang, Jiahan Chen, Guanyuan Pan, Yudie Jin



Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
