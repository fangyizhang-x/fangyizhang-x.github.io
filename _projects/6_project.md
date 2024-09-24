---
layout: page
title: Deep Learning and Its Utility for Data Mining and Computer Vision 
description: This is the research I did at the Alibaba DAMO Academy.
img: assets/img/project_6.png
importance: 3
category: work
related_publications: true
---
<!-- Project title and date -->
<h3><strong>Deep Learning and Its Utility for Data Mining and Computer Vision</strong></h3>
<p>November 11, 2021</p>

<!-- Project picture -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project_6.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<!-- Content -->
<p>These are the works I did, co-led, or supervised at the <a href="https://damo.alibaba.com/" target="_blank" rel="noopener">Alibaba DAMO Academy</a>.</p>

<p class="mt-3"> Research Highlights</p>
<ul>
  <li> Aiming to learn better visual representations/embeddings for diverse downstream tasks, we introduced a new attention mechanism (B-Attention) for more robust grasph structure learning via multiple statistical tests {% cite wang2022robust %}. The effectiveness of multiple tests for graph structure learning is verified both theoretically and empirically on multiple clustering and ReID benchmark datasets.</li>
  <li> Aiming for learning better visual representations/embeddings with less noisy graphs using Graph Convolutional Neural Networks (GCNs), we proposed a method (Ada-NETS) to adaptively remove noisy nodes in graphs {% cite wang2022adanets %}. Experiments on multiple public clustering datasets show that Ada-NETS significantly outperforms current state-of-the-art methods, proving its superiority and generalization.</li>
  <li> To better understand the data imbalance problem in training GCNs, we conducted an empirical study on GCN-based clustering with imbalanced datasets, yielding valuable insights into the issue {% cite yang2021gcn %}.</li>
  <li> To tackle the problems of tail shadow and background distortion in learning-based video compression, we introduced a new method for more accurate motion prediction, which surpassed the state-of-the-art rate-distortion performance in most video compression datasets {% cite z9746149 %}.</li>
  <li>To enable variable-rate control without sacrificing the performance, we proposed an efficient Interpolation Variable-Rate (IVR) network, by introducing a handy Interpolation Channel Attention (InterpCA) module in the compression network {% cite z10.1145/3474085.3475698 %}. The method achieves a fine PSNR interval of 0.001 dB and a fine rate interval of 0.0001 Bits-Per-Pixel (BPP) with 9000 rates in the IVR network. Experimental results demonstrate that the IVR network is the first variable-rate learned method that outperforms VTM 9.0 (intra) in PSNR and Multiscale Structural Similarity (MS-SSIM).</li>
</ul>

<!-- part 1
<h4 id="learning-planar-reaching-in-simulation"><strong>Learning Planar Reaching in Simulation</strong></h4>
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://www.youtube.com/embed/6cz-mcM4Qkc" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen title="YouTube Video"></iframe>
</div>

<!-- part 2 -->
<!-- <h4 class="mt-3" id="robotic-planar-reaching-in-the-real-world"><strong>Robotic Planar Reaching in the Real World</strong></h4>
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://www.youtube.com/embed/ybuFdsE6AjY" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen title="YouTube Video"></iframe>
</div> -->

<!-- part 3 -->
<!-- <h4 class="mt-3" id="learning-table-top-object-reaching-with-a-7-dof-robotic-arm-from-simulation"><strong>Learning Table-top Object Reaching with a 7 DoF Robotic Arm from Simulation</strong></h4>
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe src="https://www.youtube.com/embed/bVIw1DeuuYg" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" allowfullscreen title="YouTube Video"></iframe>
</div> -->

<!-- part 4 -->





<!-- <header class="post-header">
  <h1 class="post-title">{{ page.title }}</h1>
  <p class="post-description">{{ page.description }}</p>
</header> -->