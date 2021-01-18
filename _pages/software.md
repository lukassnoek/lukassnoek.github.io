---
permalink: /
title: "Software"
excerpt: "Software"
author_profile: true
redirect_from: 
  - /software/
  - /software.html
---

For my research and duties at the [Spinoza Centre for Neuroimaging](https://www.spinozacentre.nl/) (location Roeterseiland), I have developed several software packages (of which most using Python). You can find a selection below, but see my [personal Github](https://github.com/lukassnoek) and the [Spinoza Centre's Github](https://github.com/orgs/NILAB-UvA) for a complete overview.

### bidsify
Widespread sharing of neuroimaging data is, unfortunately, not common in the
neuroscience community. In the past years, some researchers have proposed a common format for MRI datasets - the Brain Imaging Data Structure ([BIDS](http://bids.neuroimaging.io/)) - which aims at improving data sharing, reproducibility, and transparency through providing a guidelines on how to organize your data (which can be, subsequently, be uploaded to [openneuro.org](https://openneuro.org/) very easily).

![bids](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fsdata.2016.44/MediaObjects/41597_2016_Article_BFsdata201644_Fig1_HTML.jpg?as=webp)
*Image from [https://www.nature.com/articles/sdata201644](https://www.nature.com/articles/sdata201644)*

Organizing your raw data into the required BIDS format, however, can be painstakingly time-consuming: you've to convert your files in the right format (e.g. Philips PAR/REC or DICOMs to compressed nifti), rename your files, and extract the necessary meta-data. I've written a small package that automatically converts your "raw" and unstructured dataset to BIDS, given a config file that you provide (such that the software "knows" which how to convert/format/rename your files). Recently, I also provide a [Docker image](https://hub.docker.com/r/lukassnoek/bidsify) so that you can run `bidsify` without worrying about dependencies. The package has been tested on several datasets recorded at the Philips 3T and 7T scanners from the [Spinoza Centre for Neuroimaging](https://www.spinozacentre.nl/), and is currenlty deployed at our MRI center to automatically convert all raw scanner data to BIDS (as part of the `nitools` package, see below).

The code can be found on [Github](https://github.com/NILAB-UvA/bidsify). The README should contain enough information to get started with `bidsify`.

### nitools
In order to automate the process of converting raw scanner data to BIDS and running it through a well-established preprocessing ([Fmriprep](https://fmriprep.readthedocs.io/)) and quality-control ([MRIQC](https://mriqc.readthedocs.io/)) pipeline, I developed the `nitools` package. It is currently deployed at our MRI center. While it is not as neatly packaged, you can check the code [here](https://github.com/NILAB-UvA/nitools).

### scanphyslog2bids
Ever tried to distill volume triggers from Philips physiology ("SCANPHYSLOG") files? Trust me, it's frustrating. I created a small package to do this using either trigger markers, or based on the scanner's gradients (if they're logged), or, if everything else fails, to interpolate volume triggers "counting backwards" from the offset of the acquisition. Check it out [here](https://github.com/lukassnoek/scanphyslog2bids).

<p align="center">
  <img src="/img/sub-xxxx_task-emorecognition_acq-seq_recording-respcardiac_physio_alignment.png" width="1000" height="300">
</p>

### exptools2
Many experimental paradigms in psychology/neuroscience are created programmatically in order to have strict control over the order, timing, and logging of stimuli and responses. Together with people from the lab of [Tomas Knapen](https://tknapen.github.io/), I developed the `exptools2` package, which is basically a wrapper around the software package [PsychoPy](https://www.psychopy.org/). With `exptools`, we provide a set of routines that ensure precise timing and logging of stimulus onset and responses (as well as Eyetracker integration), which is crucial for many neuroimaging experiments. Check out the [repository](https://github.com/VU-Cog-Sci/exptools2) (and especially the README) to get started!

### skbold: Utilities and tools for machine learning on BOLD-fMRI data
Inspired by the *scikit-learn* (often abbreviated as *sklearn*) machine learning package in Python, I created *skbold* - a package aimed at complementing *scikit-learn* in the organization, representation, and (pre)processing of fMRI data for machine learning ("decoding") analyses.
The package aims for flexibility in the sense that the annoying part of building decoding pipelines (such as getting it in the right format, keeping track of model performance) is taken care of, while the users can still build the actual pipelines using *scikit-learn* functionality.

![skbold](img/scope.png)

The code can be found on [Github](https://github.com/lukassnoek/skbold) and the
documentation on [ReadTheDocs](https://skbold.readthedocs.io).

### Porcupine
While working on Spynoza during the [BrainHack](https://piloubazin.github.io/amsterdam-brainhack2017/) organized by the Spinoza centre, I got to know [Tim van Mourik](http://www.ru.nl/english/people/mourik-t-van/) from the [Donders Institute](http://www.ru.nl/donders/), who was working on an open-source pipelining package with a graphical user interface named "Porcupine", which is short for “PORcupine Creates Ur PipelINE" - in Tim's words "the worst self-referencing acronym with bad capitalisation and annoying use of slang." Together with [Tomas Knapen](https://tknapen.github.io/), we started working together on [Porcupine](https://timvanmourik.github.io/Porcupine). 

In short, Porcupine is a graphical application that allows you build processing pipelines by defining "nodes" - that implement some function (such as an MRI-processing step) - and connections between them, and importantly then is able to generate the code that would be needed to actually run the pipeline as defined in Porcupine! For example, one framework Porcupine supports is the amazing [Nipype](http://nipype.readthedocs.io/en/latest/) framework. So, you could for example build a Porcupine-pipeline implementing an MRI-preprocessing pipeline based on "nodes" from different software packages (such as FSL, AFNI, and Freesurfer) and subsequenly let Porcupine generate the (Nipype-based) code that you can actually run!

![porcupine](img/porcupine_screenshot_nodes_only.png)

You can find extensive documentation and download links [here](https://timvanmourik.github.io/Porcupine).

### VoxelViz
For the VPS-competition ("Develop an original application for a virtual private server")
by [TransIp](https://www.transip.nl/), I've developed an online MRI-viewer - "VoxelViz". While it's offline now, the code can be viewed [here](https://github.com/lukassnoek/VoxelViz).

<p align="center">
  <img src="https://raw.githubusercontent.com/lukassnoek/VoxelViz/master/img/model.gif">
</p>
