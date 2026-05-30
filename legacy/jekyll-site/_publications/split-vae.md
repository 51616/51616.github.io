---
title: "An Explicit Local and Global Representation Disentanglement Framework with Applications in Deep Clustering and Unsupervised Object Detection"
collection: publications
permalink: /publication/split-vae
excerpt: ''
date: 2020-01-01
venue: '<b><i>Arxiv pre-print</i></b>'	
paperurl: 
citation: '<b>Rujikorn Charakorn</b>, Yuttapong Thawornwattana, Sirawaj Itthipuripat, Nick Pawlowski, Poramate Manoonpong, and Nat Dilokthanakul'
---


[Access the paper here](https://arxiv.org/abs/2001.08957)


### Abstract
Visual data can be understood at different levels of granularity, where global features correspond to semantic-level information and local features correspond to texture patterns. In this work, we propose a framework, called SPLIT, which allows us to disentangle local and global information into two separate sets of latent variables within the variational autoencoder (VAE) framework. Our framework adds generative assumption to the VAE by requiring a subset of the latent variables to generate an auxiliary set of observable data. This additional generative assumption primes the latent variables to local information and encourages the other latent variables to represent global information. We examine three different flavours of VAEs with different generative assumptions. We show that the framework can effectively disentangle local and global information within these models leads to improved representation, with better clustering and unsupervised object detection benchmarks. Finally, we establish connections between SPLIT and recent research in cognitive neuroscience regarding the disentanglement in human visual perception. The code for our experiments is at https://github.com/51616/split-vae


### Citation
```
@article{charakorn2020explicit,
  title={An explicit local and global representation disentanglement framework with applications in deep clustering and unsupervised object detection},
  author={Charakorn, Rujikorn and Thawornwattana, Yuttapong and Itthipuripat, Sirawaj and Pawlowski, Nick and Manoonpong, Poramate and Dilokthanakul, Nat},
  journal={arXiv preprint arXiv:2001.08957},
  year={2020}
}
```



<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).

Test markdown equation

<center><img src="https://tex.s2cms.ru/svg/%5Cbegin%7Balign%7D%0Ax_%7B1%2C2%7D%20%26%3D%20%7B-b%5Cpm%5Csqrt%7Bb%5E2%20-%204ac%7D%20%5Cover%202a%7D%20%5Cnonumber%20%5C%5C%0Az_l%20%26%3D%20z_%7Blocal%7D.%20%5Cnonumber%0A%5Cend%7Balign%7D" alt="\begin{align}
x_{1,2} &amp;= {-b\pm\sqrt{b^2 - 4ac} \over 2a} \nonumber \\
z_l &amp;= z_{local}. \nonumber
\end{align}" /></center> -->