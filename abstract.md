---
title: "Forward Modeling and Machine Learning as Tools for Making Meaningful Comparisons Between  Observations and Simulations"
subtitle: Loops IX Workshop, University of St Andrews
author: Will Barnes
---
Any successful model of coronal heating in non-flaring active region core loops must be able to reproduce the full range of observational signatures. These signatures, or observables, include, but are not limited to, the slope of the emission measure distribution below the peak temperature in log-log space, the time delay which maximizes the cross-correlation between narrow-band intensities, and the presence of "very hot" (> 8 MK) plasma. Quantitatively assessing agreement between models and observations in the context of these observables is critical to constraining the parameter space of possible coronal heating mechanisms. In this talk, I will discuss the importance of forward modeling and machine learning in making meaningful comparisons between observations and simulations. In particular, I will highlight the results of a recent investigation into the frequency of energy deposition in active region NOAA 11158 and discuss how machine learning, specifically random forest classification, is used to assess agreement between observations and forward models of low-, intermediate-, and high-frequency heating.

## Brainstorming

- Translating from model results ($n,v,T,p,B$) to something that looks like an observation
- Don't aim to reproduce every "bump and wiggle;" Instead, how does your model compare to the *distribution* of observables?
- Using machine learning to *quantitatively* assess agreement in context of *multiple* observables
- Compare with a large sample of observations! Multiple ARs, multiple events, multiple loops (highlight need for better tools for working with large amounts of data) because things are spatially dependent (e.g. multiple heating frequencies in different pixels, different ARs), time-dependent (e.g. AR age)
  - Can also go the opposite way! Compare one model with multiple observations. Does it fit anywhere?
- Open question: closing the loop on model comparison and parameter selection, i.e. can we turn our whole forward modeling pipeline into a "fitting function?"
  - Similar to the idea of the simulation as a generative model
  - Can a NN learn the pipeline?
- Overarching question: what is the mapping between a heating input (total energy, time distribution, spatial distribution) and the resulting emission? resulting observable?
