---
title: NewLEADS
summary: New directions in learning dynamical systems.
tags:
- Learning
date: "2019-05-29T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "https://www.kth.se/adbiopro/adbiopro-1.776678"

image:
  caption: Photo by rawpixel on Unsplash
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

Computational resources have become cheap and powerful, at the same time as there have been rapid advances in micro- and nano-technology, opening up for new inexpensive sensors and actuators. Together with the emerging Internet-Of-Things era, this fast-paced development has enabled the construction of ``intelligent'' machines that are able to perform  complex tasks in a physical environment by integrating the  dynamics of physical systems with sensing, actuation and information processing, as well as the interconnection of such devices. Systems like self-learning personal robots, self-driving vehicles, smart buildings optimizing energy and climat, and autonomous Unmanned Aerial Vechicles (UAVs) are starting to appear. Dynamical models of the environment and the systems themselves form an integral part of such devices as they are needed to predict the outcome of future actions, e.g. an UAV needs a dynamical model of its body and load to control its motors. Being at the core of the functionality of many devices, such models need to be sufficiently accurate for their use and therefore  have to adapt to changes in the environment in a reliable way. In this proposal we aim to create a sustainable research environment for data-driven learning of complex dynamical systems.

This area lies at the intersection between engineered systems (which we can design) and the real world (to which we have to adapt). It is evident that the complexity of real world behaviour has to be dealt with in a robust and largely autonomous way. For example, in process industry economical considerations limit manual plant model recalibration, while for massively deployed personal devices it is simply infeasible to require expert intervention.

A key observation is that it is both futile and unnecessary to attempt to completely capture the dynamics of a complex system. Instead our focus is on parsimonious learning, i.e. learning models that capture the system properties that are essential for the application at hand in a data - and computationally efficient manner. We address the challenges of doing so through three themes: 

Fundamental techniques: A major challenge is how to cope with disturbances and noise, in particular for non-linear systems and systems with feedback, which are known to be particularly susceptible to such data corruption.
  
Active and on-line learning: By optimizing the stimulii used when generating the measurements, data-efficiency can be increased signficantly. Unfortunately the optimal excitation depends on the unknown system, leading to sequential learning techniques. Here the challenge is how to deal with sequential decisions of actions under uncertainty for dynamical systems. 
  
Dynamical networked systems: The power-grid is an example of a spatially distributed interconnected dynamical system. The future hosts an increasing number of such systems with increasing complexity, e.g. transportation systems. Learning networked dynamical systems is still in its infancy and many open challenges exists. 

