---
title: "Realistic simulations of echocardiographic sequences"
excerpt: "We have developed a simulation pipeline to generate realistic synthetic echocardiographic sequences. This pipeline is currently being used to generate a large-scale cohort of virtual patients to feed deep learning methods.
<br/><br/>
<img src='/images/research_realistic_simulation.png'>"
collection: research
---

This work is done by my PhD student <strong>Thierry Judge</strong> and my postdoc <strong>Khuram Faraz</strong> and in collaboration with my colleague and friend <strong>Damien Garcia</strong>, researcher at the French institute INSERM and specialist in ultrasound imaging and fluid dynamics.

The pipeline is based on the physical ultrasound simulator called Simus, developed by Damien Garcia. Based on this simulator, we have designed a simulation pipeline that takes a real sequence as input and generates its digital twin with a reference myocardial motion field during the cardiac cycle. The image below shows an example of a sequence with simulated with our pipeline.

<p style="text-align: center;">
  <img src="/images/research_realistic_simulation_example.gif" width="500">
</p>

Using this pipeline, we are currently building a large-scale cohort of virtual patients, with the aim of simulating 100,000 echocardiographic image sequences. This dataset will be made public and serve as an input for deep learning motion estimation methods. The diagram below shows the overall strategy of our pipeline. 

<br>
<img src='/images/research_realistic_simulation_full.png'>

