---
permalink: /
title: "Reading Psychoanalysis on Love"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Psychoanalysis has been an interesting topic in many different fields, including philosophy and film theories. The notion of love is always an important concept in psychoanalysis, and love, especially “romantic love,” is vital in our life. In our society today emphasizing “safety-first love” or “some comfort zones limited by regulated pleasures,” we believe there is an urgent need to rethink love. Therefore, in the Reading Psychoanalysis on Love series of events, we are going to explore the essential ideas of Sigmund Freud, Jacques Lacan (by Slavoj Žižek and Bruce Fink) and Alain Badiou on the topic of Love.

精神分析一直是横跨许多不同领域的一个有趣的主题，这些领域包括哲学和电影理论。而爱则是精神分析中 一个重要的概念。与此同时，爱，特别是爱情，在人们的生活中始终是不可或缺的。然而在当今强调着某种 “安全第一的爱” 或者是要有 “某种限制快感的舒适区” 的社会，我们相信人们迫切地需要重新思考爱。因此在 阅读关于爱情的精神分析系列活动中，我们将探讨西格蒙德·弗洛伊德、雅克·拉康(斯拉沃热·齐泽克和布 鲁斯·芬克)和阿兰·巴迪欧关于爱情的重要思想。


What is Psychoanalysis?
======
The primary definition of psychoanalysis is given by Sigmund Freud (Freud et al., 2016): psychoanalysis is a method of treating nervous patients medically. In the further development by French psychoanalyst Jacques Lacan, he innovated philosophical ideas into clinical psychoanalysis. For philosopher Slavoj Žižek, psychoanalysis is more than clinical treatments: it is also a way to read texts and decipher ideology in critical theories (Žižek et al., 2007).

What is psychoanalysis in critical theories? Critical Theory: The Key Concepts gives the following definition (Felluga, 2015):

Psychoanalytical Criticism aims to show that a literary or cultural work is always structured by complex and often contradictory human desires. Whereas New Historicism and Marx-inspired Cultural Materialism analyze public power structures in terms of the culture as a whole, psycho- analysis analyzes microstructures of power within the individual and within small-scale domestic environments. That is, it analyzes the interiority of the self as well as the self’s kinship systems. By analyzing the formation of the individual, psychoanalysis also helps us to understand the formation of ideology at large—and can therefore be extended to the analysis of various cultural and societal phenomena. Indeed, for this reason, psychoanalysis has been especially influential over the last three decades in cultural studies, film studies, and Marxist criticism.

Why Love?
======
Love is a central theme in many people’s life, insofar as I know from past experience as a lover or a beloved. The notion of lover and beloved can be found in Plato’s famous text Symposium (Plato et al., 2003). The reading and the re-reading of this text always shed light on love in today’s society. The interactions of this idea from Plato with the psychoanalytic theories create space for us to rethink and even re-invent love, to put it in Alain Badiou’s term (Badiou et al., 2012).

There is another reason to introduce love from a psychoanalytic persepctive. In the clinical setting (possibly even in political theory) of Lacanian psychoanalysis, love is an indispensible concept in (Lacanian) psycho- analysis. Lacan once claimed (Lacan et al., 1999), “the only thing that we do in the analytic discourse is speak about love.” Thus we hope we will have an opportunity to glimpse this important notion of love and the elaboration of love from a psychoanalytic perspective, so that we can be motivated to at least think about love again.
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
