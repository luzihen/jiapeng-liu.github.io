---
title: "The Gaussian process distribution of relaxation times: A machine learning tool for the analysis and prediction of electrochemical impedance spectroscopy data"
collection: publications
permalink: /publication/2019-GP-DRT-Acta
excerpt: ''
date: 2020-11-20
venue: 'Electrochimica Acta'
paperurl: 'http://www.sciencedirect.com/science/article/pii/S0013468619321887'
citation: '<u><b>Jiapeng Liu</b></u>, and Francesco Ciucci*. (2020). &quot;The Gaussian process distribution of relaxation times: A machine learning tool for the analysis and prediction of electrochemical impedance spectroscopy data.&quot; <i><b>Electrochimica Acta</b></i>, 331, 135316.'
---
Electrochemical impedance spectroscopy (EIS) is one of the most important techniques in electrochemistry. However, analyzing the EIS data is not a simple task. The distribution of relaxation times (DRT) method offers an elegant solution to this considerable challenge. In addition to that, the DRT method can be used to obtain the time characteristics of the electrochemical system under study. Though, deconvolving the DRT from the EIS data is an ill-posed problem, which is particularly sensitive to experimental errors. Several well-known approaches, including ridge regularization, can overcome this issue but they all require the use of ad hoc hyperparameters. Furthermore, most methods are not probabilistic and therefore do not provide any uncertainty on the estimated DRT. In this work, by assuming that the DRT is a Gaussian process (GP), it is not only possible to obtain the DRT mean and covariance from the EIS data but also to predict both the DRT and the imaginary part of the impedance at frequencies not previously measured. One important point to note is that, unlike other methods, the parameters that define the GP-DRT model can be selected rationally by maximizing the experimental evidence. The GP-DRT approach is tested using synthetic experiments for analyzing the consistency of the method and “real” experiments to gauge its performance for real data. The GP-DRT model is shown to be able to manage considerable noise, overlapping timescales, truncated data, and inductive features. Considering the GP-DRT framework developed and the results of the simulations, the GP-DRT will likely inspire further studies on using a probabilistic approach to interpret EIS data.

[Download paper here](http://jiapeng-liu.github.io/files/JP-Liu_2019_GP-DRT_Elec-Acta.pdf)

Recommended citation: Liu, J. and Ciucci, F., 2020. The Gaussian process distribution of relaxation times: A machine learning tool for the analysis and prediction of electrochemical impedance spectroscopy data. <i>Electrochimica Acta</i>, 331, 135316.
