---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Jide Wintoki is the Associate Dean of Graduate Studies, Capitol Federal Professor of Finance and Area Director of Analytics, Information, and Operations Management (AIO) at the University of Kansas School of Business. His research interests include empirical corporate finance, international finance and applied econometrics. Prior to joining KU in 2008, he taught at the Terry College of Business of the University of Georgia where he also obtained a Ph.D. in Finance. In addition to research, Jide teaches classes in Corporate Financial Policy, Business Investments, Business Finance and International Finance at the undergraduate and graduate level. Jide has also served as Visiting Financial Economist in the Division of Economic and Risk Analysis (DERA) of the U.S. Securities and Exchange Commission (S.E.C.).

Prior to his studies at Georgia, Jide completed his undergraduate studies in Electrical Engineering at the University of Lagos. He also worked in a variety of positions with ExxonMobil, Procter & Gamble, and NLNG (A Shell Gas/Agip/TotalFinaElf/NNPC Joint Venture).


A data-driven personal website
======
[Endogeneity and the Dynamics of Internal Corporate Governance](http://dx.doi.org/10.1016/j.jfineco.2012.03.005) 

Journal of Financial Economics, 105 (2012), 581 – 606 (with J. Linck and J. Netter)


Implications of Data Screens on Merger and Acquisition Analysis: A Large Sample Study of Mergers and Acquisitions from 1992–2009, Review of Financial Studies, 24 (2011), 2316 – 2357 (with J. Netter and M. Stegemoller)


Foreign Independent Directors and the Quality of Legal Institutions
Journal of International Business Studies, 48 (2017), 267 – 292 (with M. Miletkov and A. Poulsen)


Director Networks and Informed Traders 
Journal of Accounting & Economics, 62 (2016), 1 – 23 (with F. Akbas and F. Meschke)


Do CMO Incentives Matter? An Empirical Investigation of CMO Compensation and Its Impact on Firm Performance
Management Science, 63 (2017), 1993 – 2015 (with N. Bansal, K. Joseph and M. Ma)


Offshore Expertise for Onshore Companies: Director Connections to Island Tax Havens and Corporate Tax Policy 
Management Science, 64 (2018), 3241 – 3268 (with C. Jiang, T. Kubick and M. Miletkov)


Partisan Bias in Fund Portfolios 
Journal of Financial & Quantitative Analysis, forthcoming (with Y. Xi)


See complete list of publications...

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
