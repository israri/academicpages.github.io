---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- <ul>{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts limit:3 %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}</ul> -->

<!-- About
====== -->
I am a computational science researcher and currently based at Universitas Syiah Kuala, Indonesia. I received all my degrees in Mechanical Engineering but my passion has always been all things computational science and especially Artificial Intelligence. I specialize in agent-based modeling (ABM), multi-physics modeling and scientific computing (think of DAE, FEA, data visualization, etc). I have utilized these methods for projects in computational biology and materials science. I personally have interests in widely different field (I went from a project on corrosion to inflammation), and I look forward to interdisciplinary research.

### Fun Fact!
I have a single name: I S R A R. But I got a bit of bureaucratic problem with a single name. And due to some occasion, I had to add my father's and my grandfather's name. So the name you see in some of my papers is the names of three generations of person in a family tree.

My Background and History
======
I received my Ph.D from the University of Georgia College of Engineering. I am a Fulbright alumni and I received my M.Sc from Virginia Commonwealth University thanks to the Fulbright Scholarship. I also received various scholarships to finish my B.Eng from Universitas Syiah Kuala as part of 2004 Indian Ocean Tsunami relief program. I survived the tsunami and I benefited from social programs.

My Research
======

Agent-Based Model (ABM)
------

ABM is a model of systems with many independent, interacting elements (think of schools of fish, flocks of bird, swarms of bee, or human crowd in a Caravan Palace's live in Paris). I developed an ABM tool originally for simulation of inflammatory response. This tool consists of four elements: 1) fixed agents (originally the epithelial cells), 2) mobile agents (originally the motile cells) 3) diffusion-reaction module (originally the cytokines dynamics) 4) elasticity and fiber module (originally represents fibrous protein, its growth, and the physics of elasticity). I currently attempt to co-opt this code for other problems, by repurposing each module. Latest attempt: simple cancer growth model.
I am also interested in investigating inflammation (and ABM in general) as an information processing system.

Materials Informatics
------

By Materials Informatics, I mean a venture to study materials science using the lens of informatics and machine learning.
For example, materials science deals with a lot of images of microstructure. These images contain a wide variety complex shapes, a lot of information to make sense of. How do we automate reasoning of these images? How do we automate translation of these images into a PDE/FEA model? Could these images tell us something about the environment that generates them?
My latest work is image-based Finite Element Analysis where it cuts off the need for rebuilding the models of microstructure shape with CAD software (i.e. "the middle man") to have an appropriate FEA model.

Materials science also involves a lot of inverse analysis because we cannot always probe a phenomenon due to physical barrier. This is the origin of Non-Destructive Evaluation (NDE). For example: investigation of corrosion in concrete wall or cracks in a bridge. Question arises as how much information is needed to properly decide the state of corrosion inside a wall, or progression of fractures inside a bridge. Informatics can help us determining and refining inverse analysis and NDE.

Materials science studies the mechanics occurring in and on a material. Interestingly, these mechanics have inspired machine learning: 1) Annealing is a staple of Materials Science 101, and due to its parallel with optimization, its simulation has been used to find local optima. 2) Mesh and network are staples in today's computer graphics and data science. Due to their spring-like form, Hooke's law is used for network's visualization. What other mechanics in materials could inspire machine learning?

<!-- Unconventional Methods in Materials Engineering Analysis
------

There are many underappreciated  

-->


<!-- Materials Informatics
------

By Materials Informatics, I mean a venture to study materials science with the lens of informatics and machine learning.
For example, materials science deals with a lot of images of microstructure. These images contain a wide variety complex shapes, a lot of information to make sense of. How do we automate reasoning of these images? How do we automate translation of these images into a PDE/FEA model? Could these images tell us something about the environment that generates them?
My latest work is image-based Finite Element Analysis where it cuts off the need for rebuilding the models of microstructure shape with CAD software (i.e. "the middle man") to have an appropriate FEA model.

Materials science also involves a lot of inverse analysis because we cannot always probe a phenomenon due to physical barrier. This is the origin of Non-Destructive Evaluation (NDE). For example: investigation of corrosion in concrete wall or cracks in a bridge. Question arises as how much information is needed to properly decide the state of corrosion inside a wall, or progression of fractures inside a bridge. Informatics can help us determining and refining inverse analysis and NDE.

Materials science studies the mechanics occurring in and on a material. Interestingly, these mechanics have inspired machine learning. Annealing is a staple of Materials Science 101, and due to its parallel with optimization, its simulation has been used to find local optima. Mesh and network are staples in today's computer graphics and data science. Due to their spring-like form, Hooke's law is used for network's visualization. What other mechanics in materials could inspire machine learning?


Elastic spring system > data visualization

Connection between materials science and machine learning, because mtr sci studies process occuring in materials, and some of the process has parallels with machine learning.

Moreover, some dynamical process in materials science can be represented as by circuit model, such as corrosion. Would

there are many dynamical processes in materials science

that potentially can be a computing substrate. Some processes can be

How do we make more sense of these images, extract more information?
I was also became aware of my colleague's library of SEM images of atmospheric corrosion products. These are minerals form by chemical interaction of metals (e.g. rebars) with atmospheric elements (e.g. air pollutants). Each mineral (e.g. Geothite) has their unique signature of shape and features.

I am currently developing an image-based PDE model

Does the pattern exhibited by materials microstructure give us information of

Machine learning + materials + complex shapes

Currently I am interested in automating the model preparation of Finite Element Analysis

This was started with a
This was started with a code that I developed to run elasticity analysis of microstructure images. The code needs to take 2D image,

This was started when I found it was difficult to import complex shapes of stainless steel phases (ferrite and austenite) into a Finite Element (FE) software that starts with an 'A' and ends with an 'S'. So I decided to make a tool that will directly take a 2D image (such as those from microscopy techniques), processes it and converts it into a model appropriate for FE modeling. This is especially feasible today because wide availability of image processing tools and symbolic computing tools that will solve PDEs through FE method.

My colleague has a library of SEM images of atmospheric corrosion products. The atmospheric corrosion products seem to

What I am interested in here is to apply informatics paradigm for materials science, to view materials in terms of information science.
Taking it a bit Further presents a question: can we model mechanics of materials in terms of information flow or as an information processing system? Most mechanics of materials models are based on continuum mechanics.

Multi-Physics Modeling
------


Multi-Physics Modeling
------ -->



<!-- My research attempts to frame analyses in Materials Science into information science paradigm. I -->

<!-- Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge. -->

<!-- Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).


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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
