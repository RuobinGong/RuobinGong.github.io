---
title: "Integer subspace differential privacy"
collection: publications_privacy
permalink: /publication/2023-02-01-integer-subspace
excerpt: ''
date: 2023-02-01
venue: 'Accepted at AAAI-23'
author: 'P Dharangutte, J Gao, R Gong, FY Yu'

---


[ArXiv](https://arxiv.org/abs/2212.00936)


We propose new differential privacy solutions for when external invariants and integer constraints are simultaneously enforced on the data product. These requirements arise in real world applications of private data curation, including the public release of the 2020 U.S. Decennial Census. They pose a great challenge to the production of provably private data products with adequate statistical usability. We propose integer subspace differential privacy to rigorously articulate the privacy guarantee when data products maintain both the invariants and integer characteristics, and demonstrate the composition and post-processing properties of our proposal. To address the challenge of sampling from a potentially highly restricted discrete space, we devise a pair of unbiased additive mechanisms, the generalized Laplace and the generalized Gaussian mechanisms, by solving the Diophantine equations as defined by the constraints. The proposed mechanisms have good accuracy, with errors exhibiting sub-exponential and sub-Gaussian tail probabilities respectively. To implement our proposal, we design an MCMC algorithm and supply empirical convergence assessment using estimated upper bounds on the total variation distance via L-lag coupling. We demonstrate the efficacy of our proposal with applications to a synthetic problem with intersecting invariants, a sensitive contingency table with known margins, and the 2010 Census county-level demonstration data with mandated fixed state population totals.