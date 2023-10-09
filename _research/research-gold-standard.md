---
title: "Representation learning for gold standard segmentation generation"
excerpt: "We have developed a strategy based on learning the representation of plausible cardiac shapes to efficiently generate gold standard annotations. This pipeline has been successfully applied to two other tasks: the simulation of realistic echocardiographic sequences and the generalization of segmentation tools.  
<br/><br/>
<img src='/images/research_representation_learning_shapes.png'>"
collection: research
---

This work was done by my PhD student <strong>Nathan Painchaud</strong> in co-supervision with Pr. <strong>Pierre-Marc Jodoin</strong> at the university of Sherbrooke and expert in AI.

We developped a framework to learn the 2D+time apical long-axis cardiac shape such that the segmented sequences can benefit from temporal and anatomical consistency constraints. Our method is a post-processing that takes as input segmented echocardiographic sequences produced by any state-of-the-art method and processes it in two steps to (i) identify spatio-temporal inconsistencies according to the overall dynamics of the cardiac sequence and (ii) correct the inconsistencies. The image below shows an example of this correction on a real sequence.

<br>
<img src='/images/research_temporal_correction.gif'>

The identification and correction of cardiac inconsistencies relies on a constrained autoencoder trained to learn a physiologically interpretable embedding of cardiac shapes, where we can both detect and fix anomalies. The diagram below shows the overall strategy of our approach. 

<br>
<img src='/images/research_representation_learning_shapes_full.png'>


