---
layout: page
title: SparseH3D - Transformer based Human3D Segmentation Using Sparse Depth
description: A Human3D model-driven system that performs precise human instance segmentation on sparse LIDAR point clouds, overcoming data limitations through advanced 3D transfer learning techniques.
img: assets/img/project9.png
#redirect: https://mrsdprojects.ri.cmu.edu/2025teamg/
importance: 3
category: masters
---

Robust 3D human segmentation is crucial for the safe operation of mobile robots, such as autonomous vehicles and drones, in real-world environments. However, state-of-the-art segmentation models like Human3D are predominantly trained on dense, synthetic indoor datasets and struggle to generalize to outdoor settings, where robots rely on sparse depth data from sensors like LiDAR. In this work, we present Sparse-H3D, a framework that adapts transformer-based 3D human segmentation to operate effectively on sparse outdoor point clouds. Our approach combines two strategies:<br> 
(1) fine-tuning a Human3D transformer model on LiDAR-style downsampled data to enhance its performance on sparse inputs, and<br> 
(2) developing preprocessing pipelines to upsample and align sparse outdoor LiDAR data, making it more compatible with existing dense-data-trained models. 

Experiments across both synthetic (Egobody) and real-world (SynLiDAR) datasets demonstrate that these methods significantly improve segmentation accuracy in sparse, outdoor scenarios. Ablation studies further highlight the importance of input density and orientation alignment, and our results show that domain-specific fine-tuning, together with intelligent preprocessing, can bridge the gap between indoor-trained models and real-world outdoor applications.

<iframe src="https://drive.google.com/file/d/1Mc3yqiGlMR-2ZoZstpjQ0543jww-f3BU/preview" width="960" height="720" allow="autoplay"></iframe>

This project is still in progress, but the complete code will eventually be published in the below mentioned repository:

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% include repository/repo.liquid repository=site.data.repositories.github_repos.last %}
</div>


