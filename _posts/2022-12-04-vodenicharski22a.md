---
section: Contributed Papers
title: Cell Anomaly Localisation using Structured Uncertainty Prediction Networks
abstract: This paper proposes an unsupervised approach to anomaly detection in bright-field
  or fluorescence cell microscopy, where our goal is to localise malaria parasites.
  This is achieved by building a generative model (a variational autoencoder) that
  describes healthy cell images, where we additionally model the structure of the
  predicted image uncertainty, rather than assuming pixelwise independence in the
  likelihood function. This provides a whitened residual representation, where the
  anticipated structured mistakes by the generative model are reduced, but distinctive
  structures that did not occur in the training distribution, e.g. parasites are highlighted.
  We employ the recently published Structured Uncertainty Prediction Networks approach
  to enable tractable learning of the uncertainty structure. Here, the residual covariance
  matrix is efficiently approximated using a sparse Cholesky parameterisation. We
  demonstrate that our proposed approach is more effective for detecting real and
  synthetic structured image perturbations compared to diagonal Gaussian likelihoods.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vodenicharski22a
month: 0
tex_title: Cell Anomaly Localisation using Structured Uncertainty Prediction Networks
firstpage: 1285
lastpage: 1300
page: 1285-1300
order: 1285
cycles: false
bibtex_author: Vodenicharski, Boyko and McDermott, Samuel and Webber, Katherine M.
  and Introini, Viola and Cicuta, Pietro and Bowman, Richard and Simpson, Ivor J.
  A. and Campbell, Neill D. F.
author:
- given: Boyko
  family: Vodenicharski
- given: Samuel
  family: McDermott
- given: Katherine M.
  family: Webber
- given: Viola
  family: Introini
- given: Pietro
  family: Cicuta
- given: Richard
  family: Bowman
- given: Ivor J. A.
  family: Simpson
- given: Neill D. F.
  family: Campbell
date: 2022-12-04
address:
container-title: Proceedings of The 5th International Conference on Medical Imaging
  with Deep Learning
volume: '172'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 12
  - 4
pdf: https://proceedings.mlr.press/v172/vodenicharski22a/vodenicharski22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
