---
title: 'You Only Derive Once (YODO): Automatic Differentiation for Efficient Sensitivity
  Analysis in Bayesian Networks'
abstract: Sensitivity analysis measures the influence of a Bayesian network’s parameters
  on a quantity of interest defined by the network, such as the probability of a variable
  taking a specific value. In particular, the so-called sensitivity value measures
  the quantity of interest’s partial derivative with respect to the network’s conditional
  probabilities. However, finding such values in large networks with thousands of
  parameters can become computationally very expensive. We propose to use automatic
  differentiation combined with exact inference to obtain all sensitivity values in
  a single pass. Our method first marginalizes the whole network once using e.g. variable
  elimination and then backpropagates this operation to obtain the gradient with respect
  to all input parameters. We demonstrate our routines by ranking all parameters by
  importance on a Bayesian network modeling humanitarian crises and disasters, and
  then show the method’s efficiency by scaling it to huge networks with up to 100’000
  parameters. An implementation of the methods using the popular machine learning
  library PyTorch is freely available.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ballester-ripoll22a
month: 0
tex_title: 'You Only Derive Once ({YODO}): Automatic Differentiation for Efficient
  Sensitivity Analysis in {B}ayesian Networks'
firstpage: 169
lastpage: 180
page: 169-180
order: 169
cycles: false
bibtex_author: Ballester-Ripoll, Rafael and Leonelli, Manuele
author:
- given: Rafael
  family: Ballester-Ripoll
- given: Manuele
  family: Leonelli
date: 2022-09-19
address:
container-title: Proceedings of The 11th International Conference on Probabilistic
  Graphical Models
volume: '186'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 9
  - 19
pdf: https://proceedings.mlr.press/v186/ballester-ripoll22a/ballester-ripoll22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
