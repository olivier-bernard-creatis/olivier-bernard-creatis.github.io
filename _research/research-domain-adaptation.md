---
title: "Domain adaptation for the quantification of clinical indices"
excerpt: "We are exploring domain adaptation strategies using reinforcement learning to enhance the generalizability of our segmentation models on echocardiographic images
<br/><br/>
<img src='/images/research_domain_adaptation.png'>"
collection: research
---

This work is currently under investigation by <strong>Arnaud Judge</strong>, a master student co-supervised with Pr. <strong>Pierre-Marc Jodoin</strong> at the university of Sherbrooke and expert in AI.

We have developed an nnU-Net architecture that produces highly accurate segmentation scores within intra-observer variability. This pilot study demonstrated that our solution can reproduce with great fidelity the way in which an expert traces his or her contours during a clinical examination. These results have been validated using a CAMUS data set comprising echocardiographic images from 500 patients. However, the problem of generalization remains entirely open. This corresponds to the ability of our method to produce the same quality of results, but on much larger databases with greater heterogeneity in terms of manufacturers, image quality and type of pathology. 

We are currently trying to solve the problem of generalization in segmentation through domain adaptation. To do this, we have access to a database with over 120,000 echocardiographic image sequences. We are currently investigating various solutions, one of the most promising being based on reinforcement learning.

<br>

<p float="left">
  <img src="/images/research_segmentation_1.gif" width="100" />
  <img src="/images/research_segmentation_2.gif" width="100" />
</p>


