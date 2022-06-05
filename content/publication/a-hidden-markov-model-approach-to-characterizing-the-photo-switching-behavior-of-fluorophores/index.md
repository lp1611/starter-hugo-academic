---
title: A hidden Markov model approach to characterizing the photo-switching
  behavior of fluorophores
publication_types:
  - "2"
authors:
  - L. Patel
  - N. Gustafsson
  - Y. Lin
  - R. Ober
  - R. Henriques and E. Cohen
doi: 10.1214/19-AOAS1240
publication: Annals of Applied Statistics
publication_short: Annals of Applied Statistics
abstract: Fluorescing molecules (fluorophores) that stochastically switch
  between photon-emitting and dark states underpin some of the most celebrated
  advancements in super-resolution microscopy. While this stochastic behavior
  has been heavily exploited, full characterization of the underlying models can
  potentially drive forward further imaging methodologies. Under the assumption
  that fluorophores move between fluorescing and dark states as continuous time
  Markov processes, the goal is to use a sequence of images to select a model
  and estimate the transition rates. We use a hidden Markov model to relate the
  observed discrete time signal to the hidden continuous time process. With
  imaging involving several repeat exposures of the fluorophore, we show the
  observed signal depends on both the current and past states of the hidden
  process, producing emission probabilities that depend on the transition rate
  parameters to be estimated. To tackle this unusual coupling of the transition
  and emission probabilities, we conceive transmission (transition-emission)
  matrices that capture all dependencies of the model. We provide a scheme of
  computing these matrices and adapt the forward-backward algorithm to compute a
  likelihood which is readily optimized to provide rate estimates. When
  confronted with several model proposals, combining this procedure with the
  Bayesian Information Criterion provides accurate model selection.
draft: false
featured: true
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2019-01-01T18:31:37.191Z
---
