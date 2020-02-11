---
title: "Personalized Prognostic Models for Oncology: A Machine Learning Approach"
collection: publications
permalink: /publication/prognstic_models
excerpt: 'We have applied a little-known data transformation to subsets of the Surveillance,
Epidemiology, and End Results (SEER) publically available data of the National Cancer
Institute (NCI) to make it suitable input to standard machine learning classifiers.'
date: 2016-06-22
venue: 'arXiv.org'

---

[Download paper here](http://angelabaltes.github.io/files/PPMO.pdf)

Abstract: We have applied a little-known data transformation to subsets of the Surveillance,
Epidemiology, and End Results (SEER) publically available data of the National Cancer
Institute (NCI) to make it suitable input to standard machine learning classifiers. This
transformation properly treats the right-censored data in the SEER data and the
resulting Random Forest and Multi-Layer Perceptron models predict full survival curves.
Treating the 6, 12, and 60 months points of the resulting survival curves as 3 binary
classifiers, the 18 resulting classifiers have AUC values ranging from .765 to .885.
Further evidence that the models have generalized well from the training data is
provided by the extremely high levels of agreement between the random forest and
neural network models predictions on the 6, 12, and 60 month binary classifiers.

citation: 'Dooling D, Kim A, McAneny B, et al. (2016). &quot;Personalized Prognostic Models for Oncology: A Machine Learning Approach.&quot; <i>arXiv.org</i>. 1606(07369).'


