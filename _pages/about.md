---
permalink: /
title: "Hossein Entezari Zarch"
excerpt: "Hossein Entezari Zarch"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I’m a 3rd-year Ph.D. student in Computer Science at the **University of Southern California**, advised by Prof. [Murali Annavaram](https://viterbi.usc.edu/directory/faculty/Annavaram/Murali) in the [SCIP Lab](https://scip-lab.usc.edu/) at the [USC Meta Research Center](https://realai.usc.edu/). I also earned my M.Sc. in Computer Science from USC and B.Sc. in Computer Engineering from the University of Tehran.

My research focuses on **efficient and scalable machine-learning systems**, particularly improving **large language model (LLM) serving and inference efficiency**. I work on topics such as **I/O-aware computation**, **KV-cache optimization**, **speculative decoding**, and **sparse attention mechanisms**, aiming to make LLMs more scalable, memory-efficient, and deployable in real-world environments. Here is a copy of my [CV](files/HosseinEntezariZarchCV.pdf)

News
======

* **11/06/2025**: Our preprint [*DuetServe: Harmonizing Prefill and Decode for LLM Serving via Adaptive GPU Multiplexing*](https://arxiv.org/abs/2511.04791) is now available on [arXiv].
* **10/10/2025**: Our preprint [*DELTA: Dynamic Layer-Aware Token Attention for Efficient Long-Context Reasoning*](https://arxiv.org/abs/2510.09883) is now available on [arXiv].
* **07/07/2025**: Our paper [*DEL: Context-Aware Dynamic Exit Layer for Efficient Self-Speculative Decoding*](https://arxiv.org/abs/2504.05598) has been accepted to [COLM](https://colmweb.org/) 2025.
* **05/22/2025**: Our preprint [*MARché: Fast Masked Autoregressive Image Generation with Cache-Aware Attention*](https://arxiv.org/abs/2506.12035) is now available on [arXiv].
* **05/15/2025**: Our paper [*KVPR: Efficient LLM Inference with I/O-Aware KV Cache Partial Recomputation*](https://arxiv.org/abs/2411.17089) has been accepted to [ACL](https://2025.aclweb.org/) Findings 2025.
* **12/10/2024**: Our paper *Efficient LLM Inference with I/O-Aware Partial KV Cache Recomputation* has been accepted to the AAAI [SEAS](https://seasworkshop.github.io/aaai25/) Workshop 2025.
* **09/20/2024**: Our paper [*CADC: Encoding User-Item Interactions for Compressing Recommendation Model Training Data*](https://arxiv.org/abs/2407.08108) has been accepted to the [LargeRecSys 2024 Workshop](https://largerecsys.github.io/) at ACM RecSys 2024.


<!-- A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
