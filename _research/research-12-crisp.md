---
title: "Reliable uncertainty estimation for medical image segmentation"
excerpt: "We have developed a generic method for estimating aleatoric uncertainty based on contrastive modeling.
<br/><br/>
<img src='/images/research_crisp.png'>"
collection: research
---

This work has been done by <strong>Thierry Judge</strong>, a PhD student co-supervised with Pr. <strong>Pierre-Marc Jodoin</strong> at the university of Sherbrooke and expert in AI.

Accurate uncertainty estimation is a critical need for the medical imaging community. A variety of methods have been proposed, all direct extensions of classification uncertainty estimations techniques. The independent pixel-wise uncertainty estimates, often based on the probabilistic interpretation of neural networks, do not take into account anatomical prior knowledge and consequently provide sub-optimal results to many segmentation tasks. 

For this reason, we have developed CRISP a ContRastive Image Segmentation for uncertainty Prediction method. At its core, CRISP implements a contrastive method to learn a joint latent space which encodes a distribution of valid segmentations and their corresponding images. We use this joint latent space to compare predictions to thousands of latent vectors and provide anatomically consistent uncertainty maps. The diagram below shows the overall strategy of our method. 

<p style="text-align: center;">
  <img src="/images/research_crisp_full.png">
</p>

Comprehensive studies performed on four medical image databases involving different modalities and organs underlines the superiority of our method compared to state-of-the-art approaches. Code is available [here](https://github.com/ThierryJudge/CRISP-uncertainty). The image displayed below illustrates a collection of examples produced using our method (last row) in comparison to state-of-the-art methods (third row). The goal is to ensure that the uncertainty maps closely resemble the error maps presented in the second row.

<br>
<img src="/images/research_crisp_results.png">


