---
title: "Investigating Partner Diversification Methods in Cooperative Multi-agent Deep Reinforcement Learning"
collection: publications
permalink: /publication/diversity
excerpt: ''
date: 2020-05-01
venue: '<i>The 27th International Conference on Neural Information Processing. <b>ICONIP 2020</b></i>' 
paperurl: 
citation: '<b>Rujikorn Charakorn</b>, Poramate Manoonpong, and Nat Dilokthanakul'
---


[Access the paper here](https://link.springer.com/chapter/10.1007/978-3-030-63823-8_46) ([pdf](/files/papers/diversity_ICONIP2020.pdf))


### Abstract
Overfitting to learning partners is a known problem, in multi-agent reinforcement learning (MARL), due to the co-evolution of learning agents. Previous works explicitly add diversity to learning partners for mitigating this problem. However, since there are many approaches for introducing diversity, it is not clear which one should be used under what circumstances. In this work, we clarify the situation and reveal that widely used methods such as partner sampling and population-based training are unreliable at introducing diversity under fully cooperative multi-agent Markov decision process. We find that generating pre-trained partners is a simple yet effective procedure to achieve diversity. Finally, we highlight the impact of diversified learning partners on the generalization of learning agents using cross-play and ad-hoc team performance as evaluation metrics.


### Citation
```
@inproceedings{charakorn2020investigating,
  title={Investigating Partner Diversification Methods in Cooperative Multi-agent Deep Reinforcement Learning},
  author={Charakorn, Rujikorn and Manoonpong, Poramate and Dilokthanakul, Nat},
  booktitle={International Conference on Neural Information Processing},
  pages={395--402},
  year={2020},
  organization={Springer}
}
```

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).

Test markdown equation

<center><img src="https://tex.s2cms.ru/svg/%5Cbegin%7Balign%7D%0Ax_%7B1%2C2%7D%20%26%3D%20%7B-b%5Cpm%5Csqrt%7Bb%5E2%20-%204ac%7D%20%5Cover%202a%7D%20%5Cnonumber%20%5C%5C%0Az_l%20%26%3D%20z_%7Blocal%7D.%20%5Cnonumber%0A%5Cend%7Balign%7D" alt="\begin{align}
x_{1,2} &amp;= {-b\pm\sqrt{b^2 - 4ac} \over 2a} \nonumber \\
z_l &amp;= z_{local}. \nonumber
\end{align}" /></center> -->