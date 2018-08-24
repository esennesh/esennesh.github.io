---
title: "Combinators for Modeling and Inference"
collection: publications
permalink: /publication/2018-10-04-combinators-modeling-inference
date: 2018-10-04
venue: 'First International Conference on Probabilistic Programming'
paperurl: 'http://esennesh.github.io/files/probprog_2018_combinators.pdf'
citation: 'Sennesh, E., Wu, H., & van de Meent, J.-W. (2018). Combinators for Modeling and Inference.'
---
We develop a combinator library for the Probabilistic Torch framework. Combinators are functions accept and return models. Combinators enable compositional interleaving of modeling and inference operations, which streamlines model design and enables model-specific inference optimizations. Model combinators define a static graph from (possibly dynamic) model components. Examples of patterns that can be expressed as combinators are mixtures, state-space models, and models with global and local variables. Inference combinators preserve model structure, but alter model evaluation. Operations that we can represent as combinators include enumeration, importance sampling, resampling, and Markov chain Monte Carlo transitions. We validate our approach on variational methods for hidden Markov models.

[Download paper here](http://esennesh.github.io/files/probprog_2018_combinators.pdf)

Recommended citation: Sennesh, E., Wu, H., & van de Meent, J.-W. (2018). Combinators for Modeling and Inference.
