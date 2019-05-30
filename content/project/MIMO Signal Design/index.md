---
title: MIMO signal design
summary: Performance oriented training signal design for MIMO communication systems
tags:
- Past
date: "2019-05-29T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Wireless communication systems employing multiple antennas have many
attractive properties such as high spectral efficiency and research in
this field has seen an explosive development in the last decade; the
introduction of space-time coding being one driving source \cite{Tarokh:98}.
A limiting factor for the efficiency is the accuracy of the information
regarding the channel characteristics available at both transmitter
and receiver ends. Such information can be
available in the form of statistics and/or estimates based on
measurements. Estimation can be performed in two ways: blind
estimation where the transmitted signal is unknown, or using a known training (or pilot) signal. The training signal can also be superimposed on
transmit data. 

Optimal design of the training signal is a way to improve the
channel estimate in training based methods. Maintaining efficiency
requires these signals to be short. Despite the fact that
there is by now a significant body of literature on this problem for
various scenarios  
we have identified several directions which we believe are of
importance for the further developments of this field: 

1. *Performance oriented training.* Almost all contributions 
  base the training signal design on a lumped measure of the quality
  of the channel estimate that only indirectly accounts for the
  quality of the reconstructed signal at the receiver side. A
  frequently used measure is the mean-squared error (MSE) of the channel
  matrix estimate. It would be more appropriate to consider the impact
  the training signal has on the quality of the reconstructed signal,
  e.g. measured  by its MSE or by  the bit error rate.  

2. *Convexification of optimal training signal design programs.* For certain communication scenarios it has been shown that 
    there exist explicit solutions to optimal training
    signal design problems. However, existing cases are restricted
    to certain structures, e.g. flat fading channels subject to noise
    possessing a certain Kronecker structure, and to certain
    performance measures, such as the MSE of the estimated channel matrix. We
    believe that significant progress can be achieved by asymptotic
    (in the training signal length) approximation of the problem and
    using recent advances in convex optimization and experiment design
    for dynamical systems. We believe that this approach also will
    allow to develop simplified design techniques for many common scenarios. 

3. *Benefit analysis.* With much of current efforts having been
  devoted to algorithmic developments, we believe that it is now
  important to analyse for which scenarios training signal design
  really makes a difference. Also here we believe that asymptotic
  approximation can be useful. 

## Project team

**Division of Decision and Control Systems KTH**

* [Prof. Håkan Hjalmarsson](https://www.kth.se/profile/hjalmars) 
* [Assistant Prof. Dimitrios Katselis](http://katselis.web.engr.illinois.edu) 
* [Assoc. Prof. Cristian Rojas](https://www.kth.se/profile/crro) 

**Division of Signal Processing KTH**

* [Prof. Mats Bengtsson](https://www.kth.se/profile/matben) 
* [Prof. Magnus Jansson](https://www.kth.se/profile/janssonm) 
* [Prof. Björn Ottersten](https://www.kth.se/profile/otterste) 

## Project funding and duration

This project is funded by the [Swedish Research Council](https://www.vr.se/english.html) with duration 2011--2013.

