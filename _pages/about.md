---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a fourth-year Ph.D. student majoring in Design Science at the College of Computer Science, Zhejiang University, China. My research primarily focuses on Human-Computer Interaction and Virtual Reality.

Education
======
- **University of Rochester, USA**  
  *Visiting Student, Bear Lab*  
  November 2024 – Present

- **Zhejiang University, China**  
  *Ph.D. Student in Design Science (M.S./Ph.D. Integrated Program)*  
  September 2021 – Present

- **Shanghai University, China**  
  *B.A. in Digital Media*  
  September 2017 – June 2021

Publications
======
- **Yang Lu**, Junxian Li, Zhitong Cui, Jiapeng Hu, Yanna Lin, Shijian Luo.  
  ["Designing Spatial Visualization and Interactions of Immersive Sankey Diagram in Virtual Reality"](https://dl.acm.org/doi/abs/10.1145/3664647.3681460).  
  *Proceedings of the 32nd ACM International Conference on Multimedia*, pp. 98–107, 2024.  
**Abstract**: Virtual reality (VR) is a revolutionary method of presenting data visualizations, which brings potential possibilities for enhancing analytical activities. However, applying this method to visualize complex data flows remains largely underexplored, especially the Sankey diagrams, which have an advantageous capacity to represent trends in data flows. In this work, we explored a novel design for the immersive Sankey diagram system within VR environments, utilizing a three-dimensional visual design and several interaction techniques that leveraged VR's spatial and immersive capabilities. Through two comparative user studies, we found the effectiveness of the VR Sankey diagram system in improving task performance and engagement and reducing cognitive workload in complex data analysis. We contribute an interactive, immersive Sankey diagram system in VR environments, empirical evidence of its advantages, and design lessons for future immersive visualization tools.
![Immersive Sankey Diagram in VR](assets/images/finalsystem.png)

- **Yao Wang**, **Yang Lu**, Cheng-Yi Shen, Shi-Jian Luo, Long-Yu Zhang.  
  ["Exploring Product Style Perception: A Comparative Eye-Tracking Analysis of Users across Varying Levels of Self-Monitoring"](https://www.sciencedirect.com/science/article/pii/S0141938224001549).  
  *Displays*, vol. 84, p. 102790, 2024.
  
For more publications, please see my [Google Scholar profile](https://scholar.google.com/citations?user=HHzZ_ZoAAAAJ&hl=en&authuser=1).
  
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
