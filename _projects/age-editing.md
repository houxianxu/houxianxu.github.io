---
layout: page
title: ""
permalink: project/age-editing
---

<center> <h2><b>Lifelong Age Transformation with a Deep Generative Prior</b></h2> </center>

<center> Xianxu Hou, Xiaokang Zhang, Hanbang Liang, Linlin Shen </center>
<div style="background-color:#f7f6f1">
<h4 style="padding:10px"><b>Abstract</b></h4>
<p  style="padding:10px">
In this paper, we consider the lifelong age progression and regression task, which requires to synthesize a person’s appearance across a wide range of ages. We propose a simple yet effective learning framework to achieve this by exploiting the prior knowledge of faces captured by well-trained generative adversarial networks (GANs). Specifically, we first utilize a pretrained GAN to synthesize face images with different ages, with which we then learn to model the conditional aging process in the GAN latent space. Moreover, we also introduce a cycle consistency loss in the GAN latent space to preserve a person’s identity. As a result, our model can reliably predict a person's appearance for different ages by modifying both shape and texture of the head. Both qualitative and quantitative experimental results demonstrate the superiority of our method over concurrent works. Furthermore, we demonstrate that our approach can also achieve high-quality age transformation for painting portraits and cartoon characters without additional age annotations.
</p>
</div>

<a href="https://ieeexplore.ieee.org/abstract/document/9726897"><img src='/assets/projects/age-editing/web_miniature.jpg' width="100%"></a>


<div style="background-color:#f7f6f1">
<h4 style="padding:10px"><b>Overview</b></h4>
</div>


<div><img src='/assets/projects/age-editing/overview.jpeg' width="100%"></div>


<div style="background-color:#f7f6f1">
	<h4 style="padding:10px"><b>Results</b></h4>
</div>

<li style="background-color:#fff"><b>Visual comparison of age transformation results on real faces </b></li>

<div style="background-color:#f7f6f1"><center><img src='/assets/projects/age-editing/real1_optimized.jpg' width="100%"></center></div>

<section id="Citation" width="60%">
                    <pre><code>
@article{hou2022lifelong,
  title={Lifelong Age Transformation with a Deep Generative Prior},
  author={Hou, Xianxu and Zhang, Xiaokang and Liang, Hanbang and Shen, Linlin and Ming, Zhong},
  journal={IEEE Transactions on Multimedia},
  year={2022},
  publisher={IEEE}
}
            </code></pre>
 </section>
