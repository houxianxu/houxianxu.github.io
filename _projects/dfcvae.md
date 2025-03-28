---
layout: page
title: ""
permalink: assets/project/dfcvae
---

<center> <h2><b>Deep Feature Consistent Variational Autoencoder</b></h2> </center>

<center> Xianxu Hou, Linlin Shen, Ke Sun, Guoping Qiu </center>
<div style="background-color:#f7f6f1">
<h4 style="padding-top:10px"><b>Abstract</b></h4>
<p >We present a novel method for constructing Variational Autoencoder (VAE). Instead of using pixel-by-pixel loss, we enforce deep feature consistency between the input and the output of a VAE, which ensures the VAE's output to preserve the spatial correlation characteristics of the input, thus leading the output to have a more natural visual appearance and better perceptual quality. Based on recent deep learning works such as style transfer, we employ a pre-trained deep convolutional neural network (CNN) and use its hidden features to define a feature perceptual loss for VAE training. Evaluated on the CelebA face dataset, we show that our model produces better results than other methods in the literature. We also show that our method can produce latent vectors that can capture the semantic information of face expressions and can be used to achieve state-of-the-art performance in facial attribute prediction.
</p>
</div>

<a href="https://arxiv.org/abs/1610.00291"><img src='/assets/projects/dfcvae/web_miniature.png' width="100%"></a>

<div style="background-color:#f7f6f1">
<h4 style="padding-top:10px"><b>Code</b></h4>
<li>Code is available on <a href="https://github.com/houxianxu/DFC-VAE">Github</a></li>
</div>


<div style="background-color:#f7f6f1">
<h4 style="padding-top:10px"><b>Example Results</b></h4>

<li>Face Image Generation</li>
</div>
<img src='/assets/projects/dfcvae/web_faces.png' width="100%">

<li style="background-color:#f7f6f1">Linear Interpolation of Latent Space</li>

<center style="background-color:#f7f6f1"><img src='/assets/projects/dfcvae/combined.gif' width="37%"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src='/assets/projects/dfcvae/random.gif' width="30%"></center>

<li style="background-color:#f7f6f1">Face image visualization based on latent vectors by <a href="https://lvdmaaten.github.io/tsne/">t-SNE</a></li>

<img src='/assets/projects/dfcvae/web_tsne.png' width="100%">


