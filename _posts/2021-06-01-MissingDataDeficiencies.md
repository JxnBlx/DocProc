---
title: Addressing Deficiencies from Missing Data in Electronic Health Records
author: TianZh
date: 2021-06-01
categories: [Electronic Health Records]
tags: []     # TAG names should always be lowercase
---

Electronic health records (EHRs) contain a wealth of data that can be used to improve patient-centered outcomes. In particular, EHRs have been used for disease prediction, data-driven clinical decision support, patient trajectory modeling, etc. However, it is common that EHRs data contain substantial missing information that could make the clinical prediction tasks more challenging if left unaddressed. This thesis focuses on the problem of multivariate data imputation in patients’ ICU EHRs, where the source of missing information comes mostly from the time-series data. The key challenge is to design flexible models that model the time-series and non-time-series data jointly such that accurate time-series imputation can be achieved. To this purpose, a multi-modal neural network for sequential regression, to accurately estimate the missing values in the time series from EHRs is proposed. Specifically, the model is trained by using a self-supervised regression objective, namely, the masked value regression task, which mimics missing data situations at test time and optimizes a supervised regression loss in each learning episode. Additionally, an adversarial training procedure is employed to further improve the proposed system, similarly as the conditional generative adversarial networks. Empirical results on the MIMIC-III dataset show that the proposed system achieves superior performance against several strong baseline methods. The proposed imputation system can also address the deficiencies from the missing data of EHR as it enables robust clinical prediction over a variety of missing rates, on two large-scale clinical prediction tasks.

[Read more](https://hdl.handle.net/1721.1/139587)