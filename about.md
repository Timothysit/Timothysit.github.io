---
layout: page
title: About
permalink: /about/
---

I am a PhD student at the Sainsbury Welcome Centre, working in the Cortex Lab led by Kenneth Harris and Matteo Carandini.

## Research

I am currently focused on audio-visual stimulus represetation and learning as a form of multisensory integration. In practice that means (1) I play videos to mice and see what happens in their brain and (2) I look at what happens in their brain when they've learn to turn a wheel based on some flashes of black and white bars and some clicking sounds.


### Mouse frontal cortex mediates additive multisensory decisions

For all the details, see the [biorxiv preprint](https://www.biorxiv.org/content/10.1101/2021.04.26.441250v2).

In this study, we want to understand the role of the cortex in multisensory decision making. To do this, [Pip](https://scholar.google.com/citations?user=lfUg7wkAAAAJ&hl=en&oi=ao) trained mice to turn a steering wheel to the left or to the right based whether flashes and/or clicking sounds appear on the left or right of the mice. By using optogenetic techniques to inactivate a lot of areas in the cortex, he found that only inactivating the secondary motor cortex (MOs) affected mice's response in all stimulus conditions. When I looked at the neural activity in MOs, I find different neurons with activities that correlate with (1) the location of the sound, (2) the location of the flashes, and (3) whether the mouse is going / have chosen to turn the wheel left/right, and that these correlates are stronger compared to other neighbouring regions recorded. When looking at the neural activity as a population, we find that it can be summarised by an *additive model* where the response can be modelled as a weighted sum of the response to the sounds and response to the flashes. When we looked at the mice's choices, we also see that it is captured well by an additive rule: the (log) probability of going right for a given stimulus condition can be modelled as the sum of the auditory stimuli and visual stimuli. To see whether the neural activity that we observed can give rise to such behaviour, we trained an *accumulator model* to do the task by taking a weighted sum of the stimulus-related activity and accumulating this activity over time, reaching either a left/right decision depending when it crosses either a positive/negative threshold. Even though the model has never seen the mice's behaviour (it was trained to do the task as good as it could - ie. it is a *normative model*, given the neural activity available), we find that the model's decisions, and even the time of these decisions, matches the mice well (!). 


### Behavioral origin of sound-evoked activity in visual cortex

For all the details, see the [biorxiv preprint](https://www.biorxiv.org/content/10.1101/2021.07.01.450721v1.abstract).





## Other projects

### Sciplotlib

[Sciplotlib](https://github.com/Timothysit/sciplotlib) is a Python library with extensions and convinient functions based on matplotlib to quickly alter the styling of plots so they match the standards of scientific publication (or at least my opinion of what is standard).


## Talks, Dataclubs, Journal clubs


 - [2020-05-01: Journal Club on Williams et al 2018: Unsupervised discovery of demixed, low-dimensional neural dynamics across multiple timscale through tensor component analysis](https://timothysit.github.io/williams2018unsupervised-journal-club/)
 - [2020-03-04: Dataclub at the Sainsbury Welcome Center: audiovisual activity in the mouse cortex](https://timothysit.github.io/swc-dataclub-march-2020/#/)
    - A talk on what I've done in the first few months of my PhD and what I plan to do in the next 3 years
 - [2020-02-04: Journal club on Kobak 2016: Demixed principal component analysis of neural population data](https://timothysit.github.io/dPCA-journal-club/#/)


## Contact me

[tim (dot) sit (dot) 18  (at) ucl.ac.uk](mailto:email@domain.com)
