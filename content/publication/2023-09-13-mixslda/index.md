---
title: "Exploring Examinees’ Responses to Constructed Response Items with a Supervised Topic Model"
excerpt: "This study introduces a supervised topic model that incorporates finite-mixture modelling into supervised latent Dirichlet allocation. This model can detect latent groups of participants that have different relationships between their textual responses and associated scores."

featured: true
author: 
 Seohyun Kim,
 Zhenqiu Lu,
 Allan Cohen
date: '2023-09-13'

categories:
  - Research 
  - Topic modeling
  - Text analysis
  - latent group analysis
  - Bayesian estimation


links:
- icon: file-richtext-fill
  name: Publication
  url: https://doi.org/10.1111/bmsp.12319
filters:
  - lightbox
lightbox: auto 
---

## Abstract

Textual data are increasingly common in test data as many assessments include constructed response (CR) items as indicators of participants' understanding. The development of techniques based on natural language processing has made it possible for researchers to rapidly analyse large sets of textual data. One family of statistical techniques for this purpose are probabilistic topic models. Topic modelling is a technique for detecting the latent topic structure in a collection of documents and has been widely used to analyse texts in a variety of areas. The detected topics can reveal primary themes in the documents, and the relative use of topics can be useful in investigating the variability of the documents. Supervised latent Dirichlet allocation (SLDA) is a popular topic model in that family that jointly models textual data and paired responses such as could occur with participants' textual answers to CR items and their rubric-based scores. SLDA has an assumption of a homogeneous relationship between textual data and paired responses across all documents. This approach, while useful for some purposes, may not be satisfied for situations in which a population has subgroups that have different relationships. In this study, we introduce a new supervised topic model that incorporates finite-mixture modelling into the SLDA. This new model can detect latent groups of participants that have different relationships between their textual responses and associated scores. The model is illustrated with an example from an analysis of a set of textual responses and paired scores from a middle grades assessment of science inquiry knowledge. A simulation study is presented to investigate the performance of the proposed model under practical testing conditions.