---
title: Design and Analytic Considerations for Sequential, Multiple-Assignment Randomized
  Trials with Longitudinal Outcomes
authors:
- Nicholas Seewald
date: '2021-01-01'
publishDate: '2025-04-01T00:37:01.826812Z'
publication_types:
- thesis
doi: 10.7302/2671
abstract: Clinicians and researchers alike are increasingly interested in how best
  to personalize interventions. A dynamic treatment regimen (DTR) is a sequence of
  pre-specified decision rules which can be used to guide the delivery of a sequence
  of treatments or interventions that are tailored to the changing needs of the individual.
  The sequential multiple-assignment randomized trial (SMART) is a research tool which
  allows for the construction of effective DTRs. SMARTs are multi-stage randomized
  trials in which some or all participants are randomized more than once, with each
  randomization corresponding to an open scientific question which will aid in the
  development of a high-quality DTR. In this dissertation, we develop a suite of tools
  which aid investigators in the design and analysis of SMARTs with continuous, longitudinal
  outcomes which are collected throughout the multiple stages of the trial.  We begin
  by deriving easy-to-use formulae for computing the total sample size for three common
  two-stage SMART designs in which the primary aim is to compare mean end-of-study
  outcomes for two embedded DTRs which recommend different first-stage treatments.
  The formulae are derived in the context of a regression model which leverages information
  from a longitudinal outcome collected over the entire study. We show that the sample
  size formula for a SMART can be written as the product of the sample size formula
  for a standard two-arm randomized trial, a deflation factor that accounts for the
  increased statistical efficiency resulting from a longitudinal analysis, and an
  inflation factor that accounts for the design of a SMART. The SMART design inflation
  factor is typically a function of the anticipated probability of response to first-stage
  treatment. We review modeling and estimation for DTR effect analyses using a longitudinal
  outcome from a SMART, as well as the estimation of standard errors. We also present
  estimators for the covariance matrix for a variety of common working correlation
  structures. Methods are motivated using the ENGAGE study, a SMART aimed at developing
  a DTR for increasing motivation to attend treatments among alcohol- and cocaine-dependent
  patients. Randomized trials are often constrained by limited financial resources;
  SMARTs are no different. The longitudinal deflation factor we develop allows for
  reduction in sample size requirements via both within-person correlation and the
  repeated measurements of the outcome over time. We provide guidance on how to balance
  sample size and the number of measurement occasions to minimize total cost of recruitment
  and measurement while achieving a target power. Finally, we introduce a procedure
  to generate data from a longitudinal SMART that will achieve an arbitrary desired
  covariance structure on potential outcomes, averaged over response status. This
  procedure, as well as user-friendly sample size tools which solve the cost optimization
  problems, are available in an R package called longsmart.
---
