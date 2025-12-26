---
permalink: /
title: "Welcome to join XFAN lab at HKUST(GZ) "
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<h2> Where are my wings? </h2>

The Wright brothers dawned the aviation age from keen observation of bird flight. Now in 2024, five decades after the moon landing, with interplanetary travel on the horizon, there is still no aerial robots that remotely compete with birds or bats. The irony of rocket science outpacing the seemingly simpler science of animal flight casts an unsatisfying shadow over the progress we have made.
The reality is that birds and bats have deceived us all by their effortless grace, as bio-inspired mimicry and mechanics are highly interdisciplinary and challenging studies. It demands a fundamental understanding of unsteady aerodynamics, robust robotic design and flight control, and the appreciation towards reduced-order modeling for nonlinear dynamics, which lends itself to data-driven approaches. To make matter more complicated, all these efforts are deeply coupled, and need to weave together to create faithful bio-inspired, autonomous robots. 


<h2> Bio-inspired jet propulsion </h2>

Wing articulation is critical for efficient flight of bird- and bat-sized animals. Inspired by the flight of Cynopterus
brachyotis, the lesser short-nosed fruit bat, we built a three-degree-of-freedom flapping wing platform with variable
wing folding and twisting capability. In late upstroke, the wings ”clap” and produce an air jet that significantly increases lift
production, with a positive peak matched to that produced in downstroke. We used multiple
approaches – quasi-steady modeling, direct force/power measurement, and PIV experiments in a wind tunnel –
to understand critical aspects of lift/power variation in relation to wing folding magnitude over Strouhal numbers
between 𝑆𝑡 = 0.2 − 0.4. While lift increases monotonically with folding amplitude in that range, power economy
(ratio of lift/power) is more nuanced. At 𝑆𝑡 = 0.2 − 0.3, it increase with wing folding amplitude monotonically.
At 𝑆𝑡 = 0.3 − 0.4, it features two maxima – one at medium folding amplitude (∼ 30◦), and the other at maximum
folding. These findings illuminate two strategies available to flapping wing animals and robots – symmetry-breaking
lift augmentation and appendage-based jet propulsion.
(This work is in revision as requested by Journal of Royal Society Interface, arXiv link: http://arxiv.org/abs/2411.01434)
<iframe 
        src="https://www.youtube.com/embed/I1HGdiYmNOQ" 
        title="Flapparoo Visualization" frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>

Subsequently, we found this jet can be directed by controlling the wing twist at the moment of clapping, which leads to greatly enhanced cycle-averaged thrust, especially at high 𝑆𝑡 or low flight speeds. Additional benefits of more thrust and less negative lift are gained during upstroke using wing twist. Remarkably, less total actuating force, or less total power, is required during upstroke with wing twist. These findings emphasize the benefits of critical wing articulation for the future flapping wing/fin robots and for an accurate test platform to study natural flapping wing flight or underwater vehicles.
(This work is presented at IROS 2024, with the my talk recording below. The arXiv link: https://www.arxiv.org/abs/2408.15577)

<iframe src="https://www.youtube.com/embed/kts0CTea0kM?si=HP1NF9UalNNsIG3N" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe 
        src="https://www.youtube.com/embed/MIdfsCfT98Y?si=Sw4RMePMmbL9MeDi" 
        title="IROS 2024 talk -- bio-inspired jet propulsion" frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture;"
        allowfullscreen>
</iframe>


<h2>Flapping wing robot Kestrel </h2>

The plan of the ornithopter, called kestrel, was patented by an inventor called Andrew Kinkade, in the 2001. 
I built it as a hobby.
It weighs around 430 grams, and mounts a BLDC motor that drives the wing flapping up and down via a four-bar linkage mechanism.
There are two servos that controls the tail to pitch and roll

This video was taken on August, 25th, 2018, in front of a lawn of the stadium in Sichuan University, China
In this video, right after launching, Kestrel started to descend, then I immediately increased the throttle, which effectively increased the flapping frequency.
It started to ascend, albeit slowly.

Then, I steered it to the right by controling the tail surface to roll to right. 
Towards the end of the video, the carbon rod snapped from the shoulder joint, potentially due to siginificant shear force at the base of the wing root.

<iframe       
        src="https://www.youtube.com/embed/NRsVKKc83Hs" 
        title="Kestrel test flight" 
        frameborder="0" 
        allow="accelerometer;  
               autoplay; 
               clipboard-write; 
               encrypted-media; 
               gyroscope; 
               picture-in-picture" 
        allowfullscreen>
</iframe>


<h2> Computational fluid dynamics on flapping flight </h2>

The kinematics of hipposiderid bats (Hipposideros pratti) in straight and level flight has been deconstructed into a series of modes using proper orthogonal decomposition, to determine the relative importance of each mode in the overall force dynamics.


<iframe 
        src="https://www.youtube.com/embed/iJbCfhohoUc" 
        title="LES simulation of a straight flying bat, Hipposideros Pratti" frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>







<!----

This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 


--->
