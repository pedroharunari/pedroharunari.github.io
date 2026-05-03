---
layout: ../layouts/MiscellaneaLayout.astro
title: Miscellanea
---

## (Post)Modern Thermodynamics

<div class="misc-side-by-side">
<div class="misc-side-text">

In December 2022, we organized a school and workshop that gathered 130 participants in Luxembourg. The website can still be viewed [here](https://postmodernthermo.wordpress.com/).

The school consisted of 10 courses lectured by different experts on the basics and recent unfoldings of nonequilibrium thermodynamics. We prepared lecture notes (published in [SciPost Physics Lecture Notes](https://scipost.org/SciPostPhysLectNotes.80)) that form a great resource for students and researchers interested in the field.

</div>
<div class="misc-side-img">
<img src="/photo_PMT.webp" alt="(Post)Modern Thermodynamics workshop" />
</div>
</div>


## Kullback-Leibler estimation

<div class="misc-side-by-side">
<div class="misc-side-text">

At the core of information theory, time series analysis, and even thermodynamics, is the Kullback-Leibler divergence $D_\text{KL}(P \vert\vert Q)$. It measures how distinct two distributions are through their relative entropy and is used to calculate entropy production.

Although important, it can be tricky to empirically compute divergences from finite data. The most natural approach would be calculating histograms for $P$ and $Q$ and directly evaluate the formula, maybe with some Kernel density estimation on top. This approach usually yield biased convergence, which can defeat the purpose: if you are looking for a lower bound, a convergence that is biased from above is a serious problem.

For continuous random-variables (with decently overlapping support), I wrote an out-of-the-box code that computes Kullback-Leibler divergences based on Fernando Pérez-Cruz's paper "Kullback-Leibler Divergence Estimation of Continuous Distributions" (DOI:10.1109/ISIT.2008.4595271).

- [Open-source code for KLD estimation](https://github.com/pedroharunari/KLD_estimation)

</div>
<div class="misc-side-img">
<img src="/distributions.png" alt="Distributions" />
<img src="/KLD.png" alt="KLD estimation" />
</div>
</div>

## Other Interests

I am a fan of initiatives like arXiv, Linux, SciPost, and Lichess.

I also like the Oxford comma. LLMs made me stop using em dashes.

---

*About this site:* All content by me, all code by vibe.
