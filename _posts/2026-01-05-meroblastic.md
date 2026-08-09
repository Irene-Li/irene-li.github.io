---
layout: post
author: Irene
title: Mechanics of non-canonical cell divisions
image: /assets/images/post-meroblastic.png
paper_url: "https://www.biorxiv.org/content/10.1101/2025.10.15.682552v1.abstract"
paper_title: "Read the paper — Tong & Li et al., Non-canonical cytokinesis driven by mechanical uncoupling via nematic flows and adhesion-based invagination"
summary: >-
 Holoblastic division is the textbook cytokinesis: a contractile ring is formed at the equator, which then constricts like a rubber band. In early stages of zebrafish embryo development (and many other fish, reptile and birds), meroblastic or partial division happens instead, where a contractile cable extends from the animal pole to the margin as it cuts the cell in halves. How is meroblastic cleavage achieved? 
---

Cleavage is a series of rapid cell divisions right after fertilization -- the process of going from one cell to many. Across animals, two principal modes of cleavage exist: complete (holoblastic) and incomplete (meroblastic) cleavage. While holoblastic cleavage resembles conventional cell divisions, the mechanisms underlying meroblastic cleavage have remained poorly understood. In this study, we ask the questions: how is meroblastic cleavage achieved mechanically and what sets it apart from conventional cell divisions? 

We first noticed that meroblastic cleavage proceeds through a distinct two-step mechanism. As shown in the video below, an actomyosin cable is first assembled from the animal pole to the margin. The cable then contracts while deforming the cell. However, this contractile alone is insufficient to divide the cell. A second invagination phase is required to fully divide the cell 

<video controls playsinline width="100%" style="max-width:300px; display:block; margin:1.6rem auto; border-radius:4px;">
  <source src="/assets/movies/post-meroblastic.mp4" type="video/mp4">
  Your browser doesn't support embedded video.
</video>

In particular, the transition between phase 1 and phase 2 depends on mechanical uncoupling of the contractile cable from the surrounding cortex. Through active gel theory[^gel], we demonstrate that such uncoupling arises from strongly anisotropic contraction of the actin cable, meaning that the cable pulls more strongly along the aligned direction. Furthemore, we were able to verify this anisotropy experimentally for the first time using laser-cut experiments. The directional contraction then stirs strong shear flows of the actin cortex that depletes actin on either side of the cable. 

<video controls playsinline width="100%" style="max-width:600px; display:block; margin:1.6rem auto; border-radius:4px;">
  <source src="/assets/movies/post-meroblastic2.mp4" type="video/mp4">
  Your browser doesn't support embedded video.
</video>

What happens after the decouping? And why is it necessary? To answer these questions, we wrote a macroscopic mechanical theory to understand the energy balance between classical division and invagination. It turns out that for large cells like the zebrafish embryo, the classical mode of division is extremely difficult as the energy cost scales with the size of the embryo (from having to bend the cortex). In contrast, invagination only introduces the cost of making new membranes, which the cell solves by E-cadherin-mediated membrane adhesions. 

![summary](/assets/images/cytokinesis.png)

 Together, these findings reveal that meroblastic cleavage is governed not by a single actomyosin-based event but by a sequential interplay between cytoskeletal contraction and cadherin-dependent adhesion, highlighting a mechanism fundamentally distinct from canonical cytokinesis.

[^gel]: Active gel theory is a mesoscopic (on scales larger than a single filament) theory of gel-like (between liquid and solid) substances such as the actomyosin cortex. If you are interested to learn beyond what's in the SI of our paper, I personally found [the review from Julicher & Salbreux](https://www.pks.mpg.de/fileadmin/user_upload/MPIPKS/group_pages/BiologicalPhysics/juelicher/HToAM2018.pdf) to be very useful. 