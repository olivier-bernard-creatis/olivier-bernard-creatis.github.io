---
title: "Physics-informed deep learning for blood flow quantification"
excerpt: "We developped a physics-informed deep learning method to estimate vector flow mapping from color Doppler imaging. This strategy has the potential to facilitate the analysis of the blood flow during clinical exams. 
<br/><br/>
<img src='/images/research_physics_informed.png'>"
collection: research
---

This work is done by my PhD student <strong>Hang-Jung Ling</strong> and in collaboration with my colleague and friend <strong>Damien Garcia</strong>, researcher at the French institute INSERM.

We developped a physics-informed deep learning method to estimate vector flow mapping from color Doppler imaging.
Our solution is based on an nnU-Net architecture which outputs the radial and angular velocity map of the blood flow. The corresponding spatial derivatives are then automatically computed from an autograd layer to build a physical loss. This strategy generates vector flow mapping from color Doppler imaging, facilitating interpretation and analysis of blood flow.   

<br>
<img src='/images/research_physics_informed_full.png'>

