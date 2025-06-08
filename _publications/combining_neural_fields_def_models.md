---
title: "Combining Neural Fields and Deformation Models for Non-Rigid 3D Motion Reconstruction from Partial Data"
collection: publications
permalink: /publication/combining_neural_fields_def_models
excerpt: 'Representation of moving 3D shapes as neural fields undergoing a near-isomteric surface deformation by borrowing from mesh deformation modeling.'
date: 2024-12-11
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2412.08511'
---

[**Aymen Merrouche**](https://aymenmer.github.io/), [Stefanie Wuhrer](https://swuhrer.gitlabpages.inria.fr/website/), [Edmond Boyer](https://morpheo.inrialpes.fr/people/Boyer/).


[Arxiv Preprint](https://arxiv.org/abs/2412.08511)


<p float="left">
  <img src="../images/nf3dm_sample_result_2.png" width="40%" />
  <img src="../images/nf3dm_sample_result_1.png" width="50%" />
</p>

*Figure: Sample Results.*

![Method Diagram](../images/nf3dm_overview.png)  
*Figure: Overview of our approach. Given Truncated Signed Distance Field grids representing partial observations of a moving 3D shape (leftmost), the method achieves detailed reconstructions with dense tracking (rightmost). During Feature-Fusion Based Completion (purple module), the TSDFs are encoded in a latent space where self-attention allows to fuse and complete the observed information. The fused latent features are decoded into coarse shapes and then refined where this coarse surface locates. During Inter-Frame Deformation Estimation (green module), the fusion is further constrained by fitting the  reconstructions to a patch-wise near-rigid mesh deformation model that implements a near-isometric deformation assumption promoting their consistency.*
