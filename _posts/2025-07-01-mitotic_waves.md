---
layout: post
author: Irene
title : Mitotic waves
image: /assets/images/post-mitotic-waves.png
paper_url: "https://www.biorxiv.org/content/10.1101/2025.02.03.636134v1"
paper_title: "Read the paper — Mishra, Li, Hannezo, Heisenberg, Geometry-driven asymmetric cell divisions (Nature Physics)"

summary: >-
  The timing of early embryonic cell divisions organises into travelling "mitotic waves" that originates at the top of the embryo ambryo and propagages towards the yolk. Is this regulated top-down or self-organised? Some back-of-envolope calculations and perturbation experiments would tell us the answer. 
---

Post-fertilisation, a single-celled oocyte becomes an early embryo in a process termed "cleavage", consisting of several rounds of rapid mitotic cell divisions, partitioning the large volume of the oocyte into thousands of somatic-sized cells and specifying the blueprint for subsequent embryo developments. Remarkably, the timing of early embryonic cell divisions organises into travelling waves, known as "mitotic waves". The waves emanate from the animal pole, the top of the embryo shown in the image above, and travels towards the vegetal pole at the bottom. 

Mitotic wave can arise in two ways: pre-patterned via a gradient of cell cycle periods or self-organised from a combination of noise and interactions. As shown in the figure below, if it's via the former, we expect the division timings to become further apart in the later rounds[^timing]. In other words, we expect the wave velocity $v$ to slow down as $1/n$, where $n$ is the number of rounds. On the other hand, if the wave arises from strong interactions, we may expect the pattern to be phase-locked and therefore a constant wave velocity. In summary, our back-of-envelope calculation tells us that we just need to measure the wave velocity. 

![theory](/assets/images/post-mitotic-waves3.png){:width="80%"}

So we did, and found (to our great surprise) that the first scenario is true: a fixed gradient of cell cycle periods. Since it was so surprising, we verified it with a perturbation experiment: desyncing a subgroup of cells to see if they re-synchronise. And the result pointed in the same direction of no interactions! 

What's more, increasing coupling reorients waves to originate at one side of the margin. This was achieved by inhibiting cytokinesis and creating syncytial embryos where cells remain connected with each other after division. As shown below, syncytial embryos exhibit the same wave pattern (modulo the randomness in where the wave originates) as simulations where we turn up interactions. 

![theory_v_experiments](/assets/images/post-mitotic-waves2.webp){:width="40%"} 

Thus far, we have confirmed that the mitotic waves arise from pre-existing gradients in cell cycle periods from AP to margin. This sent us on a *looooong* and arduous hunt for the mysterious factor X that causes this gradient. After many failed attempts, we found an extremely simple answer: it comes from the dome-like shape of the embryo. Curvature of the blastodisc causes asymmetric divisions (via Hertwig's rule), producing a robust cell-size gradient. This cell-volume gradient directly generates mitotic waves, as it's well-known that cells of different sizes have different cell cycle lengths. 

Crucially, the same geometry-driven gradients also pattern zygotic genome activation: transcript starts earlier in the smaller marginal cells that later contribute to mesendoderm. This may be the first symmetry-breaking in an embryo that's required to perform its subsequent gastulation and development into a full fish. 


[^timing]: You can do this calculation in your head. Let's say period at AP is 1, and period at Margin is 2. First round, we have divisions at times 1, 2. Second round we have 2, 4. Third round 3, 6. You can see that the gap between the division times is increasing. 

See also: 

- [Press release from ISTA](https://ista.ac.at/en/news/geometry-shapes-life/) : there are many photos of Nikil and I looking at fishes with mild amusement. 
- [Commentary from our referees at Nature Physics](https://www.nature.com/articles/s41567-025-03136-9) : where the lovely summary figure comes from! 