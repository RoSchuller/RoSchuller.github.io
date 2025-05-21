---
permalink: /
title: "Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Robert Schuller received his M.Sc. in Mechanical Engineering from the Technical University of Munich (TUM) in 2020. In the same year, he joined the Institute of Robotics and Mechatronics at the German Aerospace Center (DLR) as a research scientist. His research focuses on motion planning and control, particularly in the context of humanoid robotics and legged locomotion.

Interests
======
- Robotics
- Motion Planning
- Control
- Optimization
- Legged Robots


Publications
======

Journal papers
------
<p>
<strong>&#91;J1&#93;</strong>&nbsp;<strong>Robert Schuller</strong>, George&nbsp;Mesesan, Johannes Englsberger, Jinoh Lee, and Christian Ott, &quot;Online Centroidal Angular Momentum Reference Generation and Motion Optimization for Humanoid Push Recovery,&quot;&nbsp;<em>IEEE Robotics and Automation Letters &#40;RA-L&#41;</em>, vol. 6, no. 3, pp. 5689-5696, July 2021. &#91; <a href="https://ieeexplore.ieee.org/abstract/document/9435940">PDF@IEEEXplore</a> &#93;<a accesskey="4" href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9435940" id="123" lang="89" name="67" title="10" type="11"></a><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9435940" name="PDF@IEEEXplore"></a><p>

Conference papers
------
<p>
	<strong>&#91;C1&#93;</strong> Johannes Englsberger, Alessandro M. Giordano, Achraf Hiddane, <strong>Robert Schuller</strong>, Florian Loeffel, George Mesesan, Christian Ott, &quot;From Space to Earth - Relative-CoM-to-Foot &#40;RCF&#41; control yields high contact robustness&quot;, in <i>Proc. of the 20th IEEE-RAS International Conference on Humanoid Robots</i>, Munich, Germany, July 2021. &#91; <a href="https://elib.dlr.de/143111/1/Humanoids_2021_RCF.pdf">Draft </a>&#93;</p>
<p>
	<strong>&#91;C2&#93;</strong> <strong>Robert Schuller</strong>, George&nbsp;Mesesan, Johannes Englsberger, Jinoh Lee, and Christian Ott, &quot;Online Learning of Centroidal Angular Momentum Towards Enhancing DCM-Based Locomotion&quot;, in <i>Proc. of the IEEE International Conference on Robotics and Automation</i>, 10442-10448, Philadelphia, USA, Mai 2022 &#91; <a href="https://ieeexplore.ieee.org/abstract/document/9811708">PDF@IEEEXplore</a> &#93;.</p>
<p>
	<strong>&#91;C3&#93;</strong> Jean-Pascal Lutze, <strong>Robert Schuller</strong>, Hrishik Mishra, Ismael Rodriguez and Maximo A. Roa, &quot;<span lang="EN-US" style="mso-ansi-language:EN-US">Optimization of multi-arm robot locomotion to reduce satellite disturbances during in-orbit assembly</span>&quot;, in <i>Proc. of the IEEE Aerospace Conference</i>, 1-11, Big Sky, MT, USA, Mai 2022 &#91; <a href="https://ieeexplore.ieee.org/abstract/document/10115776">PDF@IEEEXplore</a> &#93;.</p>




Patents
======
<p>
	<strong>&#91;P1</strong><strong>&#93;</strong> <strong>Robert Schuller</strong>, George&nbsp;Mesesan, Johannes Englsberger, Jinoh Lee, Christian Ott, &quot;Verfahren zur Balancierung eines Roboters....&quot;, German patent application no. 10 2021112 485.9, filed on Mai 12, 2021.</p>
<p>
	<strong>&#91;P2</strong><strong>&#93;</strong> <strong>Robert Schuller</strong>, George&nbsp;Mesesan, Johannes Englsberger, Jinoh Lee, Christian Ott, &quot;Verfahren zur Gangsteuerung eines Roboters....&quot;, German patent application no. 10 2022 107 587.7, filed on March 30, 2022 &#40;under review&#41;.</p>

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
