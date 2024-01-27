---
title: "Heterogeneous data fusion for continuous patient stratification"
excerpt: "We developed a transformer-based approach to efficiently merge information extracted from echocardiographic image sequences and data from electronic health records to learn the continuous representation of patients with hypertension.
<br/><br/>
<img src='/images/research-HT-stratification.png'>"
collection: research
---

This work was done by my PhD student <strong>Nathan Painchaud</strong> in co-supervision with Pr. <strong>Pierre-Marc Jodoin</strong> at the university of Sherbrooke and expert in AI.

We have developed an nnU-Net architecture that produces highly accurate segmentation scores within intra-observer variability. This pilot study demonstrated that our solution can reproduce with great fidelity the way in which an expert traces his or her contours during a clinical examination. These results have been validated using a CAMUS data set comprising echocardiographic images from 500 patients. The image below shows an example of what we can achieve in a fully automatic way.

<p style="text-align: center;">
  <img src="/images/research_segmentation_2.gif" width="300">
</p>

However, the problem of generalization remains entirely open. This corresponds to the ability of our method to produce the same quality of results, but on much larger databases with greater heterogeneity in terms of manufacturers, image quality and type of pathology. We are currently trying to solve the problem of generalization in segmentation through domain adaptation. To do this, we have access to a database with over 120,000 echocardiographic image sequences. We are currently investigating various solutions, one of the most promising being based on reinforcement learning.

<br>
<img src='/images/research_domain_adaptation_full.png'>

