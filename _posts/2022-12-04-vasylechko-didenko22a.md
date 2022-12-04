---
section: Contributed Papers
title: 'SynthMap: a generative model for synthesis of 3D datasets for quantitative
  MRI parameter mapping of myelin water fraction'
abstract: 'We present a generative model for synthesis of large scale 3D datasets
  for quantitative MRI parameter mapping of myelin water fraction (MWF). Training
  robust neural networks for estimation of quantitative MRI parameters requires large
  amounts of data. Conventional approaches to tackling data scarcity use spatial augmentations,
  which may not capture a broad range of possible variations when only a very small
  initial dataset is available. Furthermore, conventional non linear least squares
  (NNLS) based methods for MWF estimation are highly sensitive to noise, which means
  that high quality ground truth MWF parameters are not available for supervised training.
  Instead of using the noisy NNLS based estimates of MWF parameters from limited real
  data, we propose to leverage the biophysical model that describes how the MRI signals
  arise from the underlying tissue parameters to synthetically generate a wide variety
  of high quality data of the corresponding signals and corresponding parameters for
  training any CNN based architecture. Our model samples parameter values from a range
  of naturally occurring prior values for each tissue type. To capture spatial variation,
  the generative signal decay model is combined with a generative spatial model conditioned
  on generic tissue segmentations. We demonstrate that our synthetically trained neural
  network provides superior accuracy over conventional NNLS based methods under the
  constraints of naturally occuring noise as well as on synthetic low SNR images.
  Our source code is available at: https://github.com/sergeicu/synthmap.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vasylechko-didenko22a
month: 0
tex_title: 'SynthMap: a generative model for synthesis of 3D datasets for quantitative
  MRI parameter mapping of myelin water fraction'
firstpage: 1268
lastpage: 1284
page: 1268-1284
order: 1268
cycles: false
bibtex_author: Vasylechko Didenko, Serge and Warfield, Simon and Kurugol, Sila and
  Afacan, Onur
author:
- given: Serge
  family: Vasylechko Didenko
- given: Simon
  family: Warfield
- given: Sila
  family: Kurugol
- given: Onur
  family: Afacan
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
pdf: https://proceedings.mlr.press/v172/vasylechko-didenko22a/vasylechko-didenko22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
