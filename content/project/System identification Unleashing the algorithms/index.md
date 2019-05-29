---
title: System identification: Unleashing the algorithms
summary: 
tags:
- Ongoing
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
slides: ""
---
*Motivation.* During the last decades there have been impressive advances in control
theory, offering new means for industry to meet the
challenges of today's society. For example, nonlinear and economic MPC
together with distributed networked control opens up for large
improvements in efficiency and flexibility in process
industry. However, technology shifts in this type of industry is
notoriously difficult, involving huge investments and training of a
wide palette of personell, not to mention the business side. Since long it
has been recognized that adequate dynamic process models are necessary
to be able benefit from this new technology and that acquiring such models
is in general very costly and time-consuming, also requiring highly
skilled personnel, thus severely hampering the introduction and maintenance of advanced
control. Encouraged by the spectacular success of applying
machine learning tools for sequential decision making and control of dynamical
systems, the industry is now turning to this area in hope that it will accomodate their needs. 

The main paradigm in machine learning for sequential decision making
is to combine reinforcement learning with a very flexible function
approximator, e.g. a deep learning network, thus requiring huge data
sets for the training. While this works well in,
e.g., board and video games, where lots of data from a wide variety
of scenaria can be obtained almost instantaneously and virtually at no cost, the
situation is vastly different in process industry. Here, while huge
data bases of historical data are continuously expanding, these data are
mainly collected during well controlled operating conditions, offering
limited information in regards to process dynamics outside a rather narrow
envelope. {\em Highly flexible black-box models trained using this type of
data run a large risk of exhibiting unexpected behaviour in
operating regimes where advanced control is critical, potentially
leading to catastrophic behaviour of the control}. Collecting
additional data is very costly and time-consuming. Industry seems to 
gradually becoming aware of this issue, resulting in a more guarded stance
regarding what the new technology can offer.

*Aim and significance.*  The purpose of this project is to
tackle the above problem by

*developing autonomous learning methods where physical system properties are incorporated in flexible black-box models such as deep learning networks, in a reliable and modularized way.*

We believe that by enforcing a model to maintain basic physical
relationships such as conservation laws, e.g. mass and energy
balances, the model behaviour becomes much more predictable and
realistic also in operating regions where training data are
scarce. For example, for a paper machine the produced amount of
paper should correspond to the material fed into the machine. However,
we intend to go one step beyond this notion (that closely relates to
classical gray-box modeling), in that algorithms should also be able to
automatically detect and infer such fundamental relationships. From a
user's perspective, the interpretability of the model this offers will
be important when it comes to building confidence in a model. 

At the same time, the strengths of the new types of 
(machine-learning) black-box algorithms that are emerging should be acknowledged and
exploited. Clearly these methods are able to extract complex nonlinear
relationships and this ability should be used to model remaining
constitutive relationships. 

A third important tenet in the research programme we outline below is
that such a learning framework should be modular. Physical processes
typically consist of interconnected ``units'', each one equipped with
various sensors and actuators, effectively forming an interconnected
system. For example, a paper machine can be split into wet-end,
press section and drying section. For each unit there are often some
well known fundamental physical laws that govern the overall process
behaviour but the more precise process characteristics is usually very
complicated and not easy to derive from physics. Returning to
the paper machine, both the impact of the press- and drying sections
on the paper quality are very difficult to model. To benefit from this
type of structural and physical knowledge while at the same time
allowing model flexibility to account for complex nonlinearities, one
is led to a module based modeling framework where each module can be
subject to physical laws but with otherwise rich flexibility. 

In summary, with such a framework available the resources
required for employing advanced control can be
significantly reduced. In particular, the autonomy means less demands
on high-skilled (read PhDs) personnel and also allows for much
easier maintenance. Above we have used 
process industry as example, but we believe such a framework will
be highly beneficial in many industrial applications where model based
control is used, e.g. robotics and vehicle technology. 

## Project team

* [Prof. Håkan Hjalmarsson](https://www.kth.se/profile/hjalmars) 

## Project funding and duration
 
