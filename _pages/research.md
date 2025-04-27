---
title: "Research Projects"
permalink: /research/
layout: single
author_profile: true
taxonomy: category
type: research
toc: true
toc_sticky: true
toc_label: "Sections"
---

For the past year and a half, I have being working as a research assistant at the [Institute of Engineering and Computational Mechanics (ITM)](https://www.itm.uni-stuttgart.de/en/) at the University of Stuttgart, Germany. My research work is primarily in the [Uncertainties](https://www.itm.uni-stuttgart.de/en/research/uncertainties/) and [Mechatronics](https://www.itm.uni-stuttgart.de/en/research/) branches of the ITM. Working in uncertainties brach gives me the opportunity to improve my knowledge in a multitude of fields such as control systems, machine learning, modal analysis, and structural dynamics. I am also involved in the development and maintenance of the uncertainty quantification software package [FAMOUS](https://www.itm.uni-stuttgart.de/en/software/famous/).

<div class="note-box">
  <strong>Note:</strong> All the source codes belong in the Github enterprise account of ITM, and are not publicly available.
</div>

### Possibilistic Filtering and Control

<div id="project-description" markdown="1">
This is the research that went onto my master's thesis. The gial was to use possibility theory, which is a broader framework than probability theory, to incorporate both conventional stochastic noise and non-stochastic (deterministic) uncertainties like modeling errors or imprecise parameters into the state estimation and control parts of a system.

<figure>
  <img src="/assets/videos/possfilterAnimation.gif" alt="Position Filter Animation" style="width: 100%; border-radius: 8px; margin-bottom: 1rem;">
  <figcaption style="text-align: center; font-style: italic; margin-top: 0.5rem;">Evolution of the possibilistic filter in the 2D state space, with the red particle indicating the chosen particle by the min-max MPC controller.</figcaption>
</figure>

A robust min-max controller was developed witch approximates the upper bound of the worst-case cost function to complement this filter. This was the first instance of such the so called "possibilistic filter" was implemented real-time on a real system. The filter+controller combination faired well compared to the conventional Kalman filter working with nominal controllers such as LQR and MPC.
 
<figure>
  <img src="/assets/videos/BoW_experiment.gif" alt="Position Filter Animation" style="width: 100%; border-radius: 8px; margin-bottom: 1rem;">
</figure>
</div>


### Investigation of Parametric Uncertainties 

![Fuzzy Control](/assets/videos/fuzzyControl.gif){: width="100%" style="border-radius: 8px; margin-bottom: 1rem;"}

<div id="project-description" markdown="1">
- Investigated control responses of mechanical systems (2-arm planer manipulator) in the presence of parameter-
based uncertainty (mass, lengths, etc.) with fuzzy-valued parameters.
- This provided valuable insights from a robust control perspective, especially in the context of model-based
controllers such as LQR and MPC.
</div>

### Imprecise Fast Fourier Transform (FFT)

<div id="project-description" markdown="1">
The fast Fourier Transform (FFT) is a widely used algorithm for the transformation of time domain samples to the frequency domain and is a key component in many signal processing and image processing applications. The goal in this project was incorporating fuzzy valued parameters into processes such as Fast Fourier transform
(FFT) and neural networks to investigate the effects of imprecise parameters on the frequency domain representation of signals.

![Fuzzy Control](/assets/videos/fuzztFFtPlot.gif){: width="100%" style="border-radius: 8px; margin-bottom: 1rem;"}

</div>

### Modal parameter Identification

<div id="project-description" markdown="1">
Somewhat of a continuation of the imprecise FFT project, where the goal is to identify the modal parameters of a system using imprecise signals. This project, which I am currently working on, aims to not only identify potential bounds for the modal parameters, but also to provide a possibilistic confidence interval for the identified parameters.

</div>