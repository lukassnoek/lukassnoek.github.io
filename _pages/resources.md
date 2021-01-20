---
permalink: /resources/
title: "Resources"
excerpt: "Resources"
author_profile: true
redirect_from: 
  - /resources.html
---

In addition to the material listed on the [teaching](teaching.md) page, I included some random teaching material and slide decks below that may be useful to others!

## Workshops/tutorials
I have developed several workshops/tutorials for students and/or scientists, often related to neuroimaging, software practices and tools, or statistics. You can find a selection below. 

### Python for (f)MRI analysis
Over the past years, I've almost completely transitioned to Python-only tools and packages for my (f)MRI analyses (where in the past I would use a combination of Python, Matlab, and FSL). I try to embed these Python tools in my [fMRI courses](https://lukas-snoek.com/NI-edu) as well.

If you are already familiar with the basics of (f)MRI preprocessing and analysis and just want to get an introduction to the Python tools available for (f)MRI, you can go through the set of notebooks I created for this purpose, outlined below. I recommend doing them in order (`python4fmri` first, then the Nilearn tutorial, and finally the Nistats tutorial).

Note that these notebooks are also included in the [NI-edu](https://lukas-snoek.com/NI-edu) courses.

### python4fmri
In the first week of our introductory (f)MRI course, we have students go through a Jupyter notebook about the basics of Python, numpy, matplotlib, and [nibabel](https://nipy.org/nibabel/), which prepares them for the rest of the course. I've published this notebook (with some example data) as a separate [Github repository](https://github.com/lukassnoek/python4mri), which can be run locally or online through Binder (click on the button below to get started right away).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lukassnoek/python4mri/master)

### Nilearn tutorial
[Nilearn](https://nilearn.github.io/) is an amazing Python package for (f)MRI data preprocessing and analysis. For the NI-edu courses, I developed a notebook with an introduction to the Nilearn package. Like the `python4fmri` tutorial, I created a standalone [Github repository](https://github.com/lukassnoek/nilearn-tutorial) with the materials, which can be run locally or online through Binder or Google Colab (click on one of the buttons below to get started right away). Note, this is not a simple "walkthrough" &mdash; you have to work for it! It contains plenty of exercises ("ToDos") to make you really interact with the material (instead of just passively running code cells).

[![Binder2](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lukassnoek/nilearn-tutorial/master)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lukassnoek/nilearn-tutorial/blob/master/nilearn.ipynb)

### Nilearn stats tutorial
[Nilearn](http://nilearn.github.io/) recently added functionality to run fMRI-specific GLMs, allowing you to  quickly and easily fit first-level and second-level (univariate) fMRI analyses. I use it often to estimate single-trial patterns for my own encoding and decoding analyses. Like I did for the generic Nilearn tutorial, I created a "stats" specific Nilearn tutorial that explains most of the stats-related functionality of the package. Again, it contains many exercises ("ToDos")! You can download the notebook from [Github](https://github.com/lukassnoek/nilearn-stats-tutorial). The tutorial can be run in Google Colab by clicking on the button below.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lukassnoek/nilearn-stats-tutorial/blob/master/nilearn_stats.ipynb)

### MVPA of fMRI data in Python
At the "International Conference of Cognitive Neuroscience" 2017, [Steven Miletic](https://scholar.google.com/citations?user=uH8UtcUAAAAJ&hl=en) and I organized a workshop on "MVPA of fMRI data in Python", which consisted of a short introduction on the topic and an extensive tutorial (as a Jupyter notebook, of course). For more information and how to get started, check out the workshop's website [here](https://lukas-snoek.com/ICON2017/). 

*Update*: the [decoding tutorial](https://lukas-snoek.com/NI-edu/fMRI-pattern-analysis/week_2/decoding_analyses.html) from the NI-edu course is an updated, more extensive version of the MVPA workshop!

### (Git)hub for scientists
I gave a short, introductory workshop on (Git)hub for the people of the [Conscious Brain Lab](https://www.consciousbrainlab.com/) (led by Simon van Gaal & Johannes Fahrenfort). Check out the slides below. 

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vS6n8wMm7U2nn-6b2TblA5UFCaXYJBhxdmMrDaRE-NvkReXGbHeJ_ajYB0rmlBdKzTRcqQzHK4p-HCf/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


### Docker workshop
I gave a workshop on [Docker](https://en.wikipedia.org/wiki/Docker_(software)) at the [OpenMR Benelux 2020](https://openmrbenelux.github.io/page-program/) event. All materials (slides, code, examples) can be found in the [corresponding Github repository](https://github.com/lukassnoek/docker-and-binder-workshop). The slides are embedded below.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQWX1FOzZFXP3Khs5OAYKM7_s4NQQbd3PAnoMM6I0CyR-zBpkLvGnFHgpBDB2rCdmFSkbIBgsIyOJe2/embed?start=true&loop=false&delayms=60000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


## Random presentations
Below, you can find a selection of presentations that I've given over the past years that may be interesting to others.

### "Theory-Testing in Psychology and Physics: A Methodological Paradox" (Meehl, 1967) discussion
For the [Theoretical Foundations of Brain & Cognition](https://bc-uva.github.io/TFBC/) journal club, I presented a paper from Paul Meehl ("Theory-Testing in Psychology and Physics: A Methodological Paradox", 1967). I can really recommend this (still!) incredibly relevant paper! The article is quite hard to read, though, so perhaps the slides below help in the process of making sense of the article. Additionally, I recommend [this blog post](https://www.barelysignificant.com/post/corroboration1/) by Ladislas Nalborczyk.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQQABbrZiYxvfEqez-SylLrCUcki7N9jbjcKWaZd4gB2UhbphRBO1RoG9L1E0cTUum8sSNZmjtx4RV1/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


### Flavors of modelling in cognitive neuroscience
Together with [Jolien Francken](https://jolienfrancken.com/) en [Lola Beerendonk](https://www.consciousbrainlab.com/lola-beerendonk), I organized a symposium on the topic "Computational cognitive neuroscience: What, why and how?". At this symposium, I gave a presentation about "Flavors of modelling in cognitive neuroscience".

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRoJKM--Gq0DZAdkcTZ86NeaPe2VOIrFqBWsA5wmYkzcoepypQ42O5tgLX5Q9Fx1Jv-sOkQoY9ceYQI/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="749" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


### Introduction to Multivariate Pattern Analysis
For the fMRI course at the [Spinoza Centre for Neuroimaging](https://www.spinozacentre.nl/opportunities/courses/fmri-course/), I gave a presentation about "Multivariate Pattern Analysis" (MVPA), which was adapted from the NI-edu (pattern analysis) course.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQEJ1ImL9rO42MBohhQwQvCTebRzy7I3JxN_5KaSb6aWdTHSrVYycvLcFYzX45Xs2oznjSOTNfeT62f/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


### Bayesian models of fMRI data
For the "Consciousness, Attention, & Perception" (CAP) meeting, I presented a [paper](https://www.sciencedirect.com/science/article/abs/pii/S1053811919302988) by Nunez-Elizalde, Huth, & Gallant (2018) on Bayesian encoding models of fMRI data. In addition to discussing the contents of the paper, my presentation contained a more general "crash course" on Bayesian encoding models in cognitive neuroscience.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRYz0MpG1_qphEdwXXb2M8x3GD1O-pvww0mbAudb0o0cG4qrnb1L19Y3Pk7UViDW7Wan_J3sIm_wv3r/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


### Het (on)meetbare brein (In Dutch)
I gave a popular science talk about the promises and pitfalls of neuroimaging at [Spui 25](https://www.spui25.nl/en).

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRTPyIjSR6sDW4JKzX95hSIw-bpq-K7v2AFKnL184gjDzhDhSexV2AGYcYvw-ONVnAxhqi9iXbOA2Y9/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
