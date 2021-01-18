---
permalink: /
title: "Teaching"
excerpt: "Teaching"
author_profile: true
redirect_from: 
  - /teaching/
  - /teaching.html
---

As part of my PhD, I co-teach two courses about (functional) MRI analyses at the Research Master Psychology (U. of Amsterdam), which I love doing! In addition to teaching about MRI, I give lectures about the brain basis of emotion, cognitive computational neuroscience (e.g., the use of deep learning as computational models of the mind and brain), statistics, and (Python) programming. I try to make my teaching materials (programming notebooks, slides, etc.) publicly available as much as possible, as listed below.

## Courses
A large part of the two (f)MRI analysis courses that I co-teach (with [Noor Seijdel](http://www.noorseijdel.com/) and [Steven Scholte](https://www.uva.nl/profiel/s/c/h.s.scholte/h.s.scholte.html)) consists of programming tutorials/exercises in the form of [Jupyter notebooks](https://jupyter.org/). These notebooks walk students through the most important concepts of the course's topics by showing how certain ideas, operations, and models can be implemented in (and visualized with) Python code. Importantly, these notebooks contain many excersises ("ToThinks" and "ToDos") to make students actively engage with the material. Before the end of my PhD, I aim to make the notebooks from the two courses publicly available.

#### 1. Introduction to (f)MRI
In this eight-week (6 EC) course, we discuss the process of (functional) MRI data analysis and interpretation. The course consists of weekly lectures, computer labs (with Python-based Jupyter notebooks), and interactive seminars. The course has a practical focus (i.e., how you implement analyses) and is centered around my favorite statistical model, the general linear model (GLM), and how it is applied in the context of (functional) MRI data analysis.

We are in the process of fully open-sourcing the material. For more information, check the [NI-edu website](https://neuroimaging-uva.github.io/NI-edu). To check out the notebooks directly, check the associated [Github repository](https://github.com/Neuroimaging-UvA/NI-edu).

#### 2. Pattern analysis
In this four-week (3 EC) course, we discuss a specific subset of neuroimaging analyses: pattern analyses (also known as MVPA or information-based analysis). We mainly focus on machine-learning based analyses ("decoding") and representational similarity analysis (RSA). We aim to release the materials sometime mid-2020 (on the same [website](https://neuroimaging-uva.github.io/NI-edu) and [Github repository](https://github.com/Neuroimaging-UvA/NI-edu)).

## Workshops/tutorials
I have developed several workshops/tutorials for students and/or scientists, often related to neuroimaging, software practices and tools, or statistics. You can find a selection below. 

### Python for (f)MRI analysis
Over the past years, I've almost completely transitioned to Python-only tools and packages for my (f)MRI analyses (where in the past I would use a combination of Python, Matlab, and FSL). I try to embed these Python tools in my fMRI courses as well. I'm working on publishing those two courses (Introduction to fMRI & Pattern Analysis; see above) in full; I expect them to be fully online sometime in summer 2020. 

In addition to getting students to know the neuroimaging-related Python packages, these courses also contain a lot of theoretical and statistical content (What is image registration? Why use prewhitening in GLMs applied to fMRI data, etc.). If you are already familiar with the basics of (f)MRI preprocessing and analysis and just want to get an introduction to the Python tools available for (f)MRI, you can go through the set of notebooks I created for this purpose, outlined below. I recommend doing them in order (`python4fmri` first, then the Nilearn tutorial, and finally the Nistats tutorial).

#### 1. python4fmri
In the first week of our introductory (f)MRI course, we have students go through a Jupyter notebook about the basics of Python, numpy, matplotlib, and [nibabel](https://nipy.org/nibabel/), which prepares them for the rest of the course. I've published this notebook (with some example data) as a separate [Github repository](https://github.com/lukassnoek/python4mri), which can be run locally or online through Binder (click on the button below to get started right away).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lukassnoek/python4mri/master)

#### 2. Nilearn tutorial
[Nilearn](https://nilearn.github.io/) is an amazing Python package for (f)MRI data preprocessing and analysis. For our pattern analysis course, I developed a notebook with an introduction to the Nilearn package. Like the `python4fmri` tutorial, I created a standalone [Github repository](https://github.com/lukassnoek/nilearn-tutorial) with the materials, which can be run locally or online through Binder (click on the button below to get started right away). Note, this is not a simple "walkthrough" &mdash; you have to work for it! It contains plenty of exercises ("ToDos") to make you really interact with the material (instead of just passively running code cells).

[![Binder2](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lukassnoek/nilearn-tutorial/master)

#### 3. Nilearn stats tutorial
[Nilearn](http://nilearn.github.io/) recently added functionality to run fMRI-specific GLMs, allowing you to  quickly and easily fit first-level and second-level (univariate) fMRI analyses. I use it often to estimate single-trial patterns ("betas") for my own encoding and decoding analyses. Like I did for the generic Nilearn tutorial, I created a "stats" specific Nilearn tutorial that explains most of the stats-related functionality of the package. Again, it contains many exercises ("ToDos")! You can download the notebook from [Github](https://github.com/lukassnoek/nilearn-stats-tutorial). The online Binder version does not work yet, because the notebook uses to much RAM. (I'm trying to think of a solution.)

### MVPA of fMRI data in Python
At the "International Conference of Cognitive Neuroscience" 2017, [Steven Miletic](https://scholar.google.com/citations?user=uH8UtcUAAAAJ&hl=en) and I organized a workshop on "MVPA of fMRI data in Python", which consisted of a short introduction on the topic and an extensive tutorial (as a Jupyter notebook, of course). For more information and how to get started, check out the workshop's website [here](https://lukas-snoek.com/ICON2017/). To get an idea about the workshop's contents, check out the slides below!

<style> .responsive-wrap iframe{ max-width: 100%;} </style>
<iframe src="https://docs.google.com/presentation/d/1bgK1sv-VmnvAR_HgTiWsU0vQkyjz6oO1zQ5ly4laPkw/embed?start=false&loop=false&delayms=120000" frameborder="0" width="900" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


### (Git)hub for scientists
I gave a short, introductory workshop on (Git)hub for the people of the [Conscious Brain Lab](https://www.consciousbrainlab.com/) (led by Simon van Gaal & Johannes Fahrenfort). Check out the slides below. 

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vS6n8wMm7U2nn-6b2TblA5UFCaXYJBhxdmMrDaRE-NvkReXGbHeJ_ajYB0rmlBdKzTRcqQzHK4p-HCf/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


### Docker workshop
I ga a workshop on [Docker](https://en.wikipedia.org/wiki/Docker_(software)) at the [OpenMR Benelux 2020](https://openmrbenelux.github.io/page-program/) event. All materials (slides, code, examples) can be found in the [corresponding Github repository](https://github.com/lukassnoek/docker-and-binder-workshop).

## Random presentations
Below, you can find a selection of presentations that I've given over the past years.

#### "Theory-Testing in Psychology and Physics: A Methodological Paradox" (Meehl, 1967) discussion
For the [Theoretical Foundations of Brain & Cognition](https://bc-uva.github.io/TFBC/) journal club, I presented a paper from Paul Meehl ("Theory-Testing in Psychology and Physics: A Methodological Paradox", 1967). I can really recommend this (still!) incredibly relevant paper! The article is quite hard to read, though, so perhaps the slides below help in the process of making sense of the article. Additionally, I recommend [this blog post](https://www.barelysignificant.com/post/corroboration1/) by Ladislas Nalborczyk.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQQABbrZiYxvfEqez-SylLrCUcki7N9jbjcKWaZd4gB2UhbphRBO1RoG9L1E0cTUum8sSNZmjtx4RV1/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

#### Flavors of modelling in cognitive neuroscience
Together with [Jolien Francken](https://jolienfrancken.com/) en [Lola Beerendonk](https://www.consciousbrainlab.com/lola-beerendonk), I organized a symposium on the topic "Computational cognitive neuroscience: What, why and how?". At this symposium, I gave a presentation about "Flavors of modelling in cognitive neuroscience".

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRoJKM--Gq0DZAdkcTZ86NeaPe2VOIrFqBWsA5wmYkzcoepypQ42O5tgLX5Q9Fx1Jv-sOkQoY9ceYQI/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="749" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

#### Introduction to Multivariate Pattern Analysis
For the fMRI course at the [Spinoza Centre for Neuroimaging](https://www.spinozacentre.nl/opportunities/courses/fmri-course/), I gave a presentation about "Multivariate Pattern Analysis" (MVPA).

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQEJ1ImL9rO42MBohhQwQvCTebRzy7I3JxN_5KaSb6aWdTHSrVYycvLcFYzX45Xs2oznjSOTNfeT62f/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

#### Bayesian models of fMRI data
For the "Consciousness, Attention, & Perception" (CAP) meeting, I presented a [paper](https://www.sciencedirect.com/science/article/abs/pii/S1053811919302988) by Nunez-Elizalde, Huth, & Gallant (2018) on Bayesian encoding models of fMRI data. In addition to discussing the contents of the paper, my presentation contained a more general "crash course" on Bayesian encoding models in cognitive neuroscience.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRYz0MpG1_qphEdwXXb2M8x3GD1O-pvww0mbAudb0o0cG4qrnb1L19Y3Pk7UViDW7Wan_J3sIm_wv3r/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

#### Het (on)meetbare brein (In Dutch)
I gave a popular science talk about the promises and pitfalls of neuroimaging at [Spui 25](https://www.spui25.nl/en).

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRTPyIjSR6sDW4JKzX95hSIw-bpq-K7v2AFKnL184gjDzhDhSexV2AGYcYvw-ONVnAxhqi9iXbOA2Y9/embed?start=true&loop=false&delayms=120000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
