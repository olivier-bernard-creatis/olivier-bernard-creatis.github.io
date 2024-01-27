---
title: "Heterogeneous data fusion for continuous patient stratification"
excerpt: "We developed a transformer-based approach to efficiently merge information extracted from echocardiographic image sequences and data from electronic health records to learn the continuous representation of patients with hypertension.
<br/><br/>
<img src='/images/research-HT-stratification.png'>"
collection: research
---

This work was done by my PhD student <strong>Nathan Painchaud</strong> in co-supervision with Pr. <strong>Pierre-Marc Jodoin</strong> at the university of Sherbrooke and expert in AI.

We developed a transformer-based approach to efficiently merge information extracted from echocardiographic image sequences and data from electronic health records to learn the continuous representation of patients with hypertension. Our method first projects each variable into its own representation space using modality-specific approaches. These standardized representations of multimodal data are then fed to a transformer encoder, which learns to merge them into a comprehensive representation of the patient through a fine-tuning task of predicting a clinical rating. This fine-tuning task is formulated as an ordinal classification to enforce a pathological continuum in the representation space. 

<p style="text-align: center;">
  <img src="/images/research-HT-stratification-full.png">
</p>

We observe the major trends along this continuum for a cohort of 239 hypertensive patients to describe, with unprecedented gradation, the effect of hypertension on a number of cardiac function descriptors. Our analysis shows that i) pretrained weights from a foundation model allow to reach good performance (83% accuracy) even with limited data (less than 200 training samples), ii) trends across the population are reproducible
between trainings, and iii) for descriptors whose interactions with hypertension are well documented, patterns are consistent with prior physiological knowledge.

<br>
<img src='/images/research-HT-stratification-result-1.png'>

<br>
<img src='/images/research-HT-stratification-result-2.png'>

<br>
<img src='/images/research-HT-stratification-result-3.png'>

<br>
<img src='/images/research-HT-stratification-result-4.png'>


