---
title: "Representation learning for gold standard segmentation generation"
excerpt: "We have developed a strategy based on learning the representation of plausible cardiac shapes to efficiently generate gold standard annotations. This pipeline has been successfully applied to two other tasks: the simulation of realistic echocardiographic sequences and the generalization of segmentation tools.  
<br/><br/>
<img src='/images/research_representation_learning_shapes.png'>"
collection: research
---

This work was done by my PhD student <strong>Nathan Painchaud</strong> in co-supervision with Pr. <strong>Pierre-Marc Jodoin</strong> at the university of Sherbrooke and expert in AI.

We have developed a post-processing pipeline utilizing attribute-regularized variational auto-encoders. This framework creates an efficient latent space to represent cardiac shapes with dimensions closely tied to cardiac attributes like left ventricular surface area, left ventricular basal plane length, myocardial surface area, and more. Our approach was employed to generate precise segmentations of cardiac structures throughout the entire cardiac cycle. This achievement was made possible by identifying and rectifying temporal inconsistencies in the segmentation sequence within the latent space, facilitating a more meaningful analysis of cardiac shapes. The diagram below shows the overall strategy of our approach. 

<br>
<img src='/images/research_representation_learning_shapes_full.png'>


