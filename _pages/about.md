---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
**I am on the academic job market (2026–27).**

I am currently a [Founder’s Postdoctoral Fellow](https://stat.columbia.edu/founders-postdoctoral-fellowship/) in the [Department of Statistics](https://stat.columbia.edu/) at [Columbia University](https://www.columbia.edu/). During my postdoc, I have had the opportunity to collaborate with [Rina Foygel Barber](https://rinafb.github.io/), [Samory Kpotufe](https://www.columbia.edu/~skk2175/), [Edward Kennedy](https://www.ehkennedy.com/), [Sivaraman Balakrishnan](https://www.stat.cmu.edu/~siva/), and [Larry Wasserman](https://www.stat.cmu.edu/~larry/). 

I completed my PhD in Statistics at the [Department of Statistics and Data Science](https://statistics.wharton.upenn.edu/), [Wharton School](https://www.wharton.upenn.edu/) of the [University of Pennsylvania](https://www.upenn.edu/), where I was advised by [T. Tony Cai](http://www-stat.wharton.upenn.edu/~tcai/). During my PhD, I also worked closely with [Eugene Katsevich](https://ekatsevi.github.io/). Prior to that, I completed both my Bachelor’s and Master’s degrees at the [Indian Statistical Institute](https://www.isical.ac.in/).

My research centers on two broad themes:

- **Learning under privacy constraints**: I have worked extensively on privacy-accuracy tradeoffs for nonparametric problems in federated settings — [regression](https://arxiv.org/abs/2406.06755), [classification](https://academic.oup.com/jrsssb/advance-article/doi/10.1093/jrsssb/qkaf070/8321234), [hypothesis testing](https://arxiv.org/abs/2406.06749), and [functional data estimation](https://arxiv.org/abs/2412.18992) — as well as the [cost of adaptation under differential privacy](https://arxiv.org/abs/2512.14337). I have also studied privacy in other settings, such as when data on different variables is held by different parties (e.g., [estimating correlation](https://openreview.net/forum?id=36uy2GgAy6)), and in structured data problems including [network membership estimation](https://arxiv.org/abs/2406.02794), [peer effect estimation via Ising models](https://proceedings.mlr.press/v238/chakraborty24a/chakraborty24a.pdf), and [ranking from pairwise comparisons](https://www.tandfonline.com/doi/full/10.1080/01621459.2026.2612773). A related thread is [stability-accuracy tradeoffs](https://arxiv.org/abs/2601.11701), which are deeply connected to privacy.

- **Learning with auxiliary data**: How can we exploit auxiliary information to learn better? This includes [heterogeneous transfer learning and the cost of adaptation](https://arxiv.org/abs/2605.09471), learning from shared representations, transfer learning for unsupervised problems, and using black-box predictors for testing and inference. This is the focus of much of my current work.

I have also worked on problems in [multiple testing](https://arxiv.org/abs/2601.07764), [variable selection](https://arxiv.org/abs/2409.09512), and [conditional independence testing](https://projecteuclid.org/journals/annals-of-statistics/volume-52/issue-3/Reconciling-model-X-and-doubly-robust-approaches-to-conditional-independence/10.1214/24-AOS2372.full).

 
<!---

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons.

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

-->
