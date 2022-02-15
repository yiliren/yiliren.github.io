---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Yili Ren is a Ph.D. candidate in the [Department of Computer Science](https://www.cs.fsu.edu/) at [Florida State University](https://www.fsu.edu/), supervised by Prof. [Jie Yang](https://www.cs.fsu.edu/~jieyang/).

His research interests include Mobile Computing, Wireless Sensing, and Cyber Security.

Publications
======
[Winect: 3D Human Pose Tracking for Free-form Activity Using Commodity WiFi](https://yiliren.github.io/files/Winect2021.pdf).   
**Yili Ren**, Zi Wang, Sheng Tan, Yingying Chen Jie Yang.   
Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (UbiComp 2021). - top-tier [csrankings.org](http://csrankings.org/) conference.

[Liquid Level Sensing Using Commodity WiFi in a Smart Home Environment](https://yiliren.github.io/files/LiquidSense2020.pdf).   
**Yili Ren**, Sheng Tan, Linghan Zhang, Zi Wang, Zhi Wang, Jie Yang.   
Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (UbiComp 2020). - top-tier [csrankings.org](http://csrankings.org/) conference. 

[EarDynamic: An Ear Canal Deformation Based Continuous User Authentication Using In-Ear Wearables](https://yiliren.github.io/files/EarDynamic2021.pdf).   
Zi Wang, Sheng Tan, Linghan Zhang, **Yili Ren**, Zhi Wang, and Jie Yang.   
Proceedings of the ACM on Interactive, Mobile, Wearable, and Ubiquitous Computing (UbiComp 2021). - top-tier [csrankings.org](http://csrankings.org/) conference. 

[VibLive: A Continuous Liveness Detection for Secure Voice User Interface in IoT Environment](https://yiliren.github.io/files/VibLive2020.pdf).   
Linghan Zhang, Sheng Tan, Zi Wang, **Yili Ren**, Zhi Wang, Jie Yang.   
36th Annual Computer Security Applications Conference (ACSAC 2020).

[Tracking Free-form Activity Using WiFi Signals](https://yiliren.github.io/files/PosterWinect2021.pdf). (poster)   
**Yili Ren**, Zi Wang, Sheng Tan, Yingying Chen, Jie Yang.   
The 27th Annual International Conference on Mobile Computing and Networking (Mobicom 2021). - top-tier [csrankings.org](http://csrankings.org/) conference.

[3D Human Pose Estimation Using WiFi Signals](https://yiliren.github.io/files/PosterGoPose2021.pdf.pdf). (poster)   
**Yili Ren**, Zi Wang, Yichao Wang, Sheng Tan, Yingying Chen, Jie Yang.   
The 19th ACM Conference on Embedded Networked Sensor Systems (SenSys 2021). - top-tier [csrankings.org](http://csrankings.org/) conference.

[Earable Authentication via Acoustic Toothprint](https://yiliren.github.io/files/PosterToothSonic2021.pdf). (poster)   
Zi Wang, **Yili Ren**, Yingying Chen, Jie Yang.   
ACM Conference on Computer and Communications Security (CCS 2021)}. - top-tier [csrankings.org](http://csrankings.org/) conference.

[An Ear Canal Deformation Based Continuous User Authentication Using Earables](https://yiliren.github.io/files/PosterEarDynamic2021.pdf). (poster)   
Zi Wang, **Yili Ren**, Yingying Chen, Jie Yang.   
The 27th Annual International Conference on Mobile Computing and Networking (Mobicom 2021). - top-tier [csrankings.org](http://csrankings.org/) conference.

Getting started
======
//: 1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
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
