--- 
title: "Cleanba: A Reproducible and Efficient Distributed Reinforcement Learning Platform" 
collection: publications 
permalink: /publication/cleanba
excerpt: '' 
date: 2024-01-16
venue: '<i><b>ICLR 2024</b></i>' 
paperurl:  
# citation: '<b>Rujikorn Charakorn</b>, Poramate Manoonpong, and Nat Dilokthanakul' 
citation: 'Shengyi Huang, Jiayi Weng, <b>Rujikorn Charakorn</b>, Min Lin, Zhongwen Xu, Santiago Ontanon'
--- 

[Paper](https://openreview.net/forum?id=Diq6urt3lS) | [Code](https://github.com/vwxyzjn/cleanba)

### TL;DR
IMPALA has reproducibility issues; we propose a more reproducible architecture called Cleanba; our Atari-57 experiments shows Cleanba PPO and IMPALA variants outperform torchbeast and moolib's IMPALA.

### Abstract
Distributed Deep Reinforcement Learning (DRL) aims to leverage more computational resources to train autonomous agents with less training time. Despite recent progress in the field, reproducibility issues have not been sufficiently explored. This paper first shows that the typical actor-learner framework can have reproducibility issues even if hyperparameters are controlled. We then introduce Cleanba, a new open-source platform for distributed DRL that proposes a highly reproducible architecture. Cleanba implements highly optimized distributed variants of PPO and IMPALA. Our Atari experiments show that these variants can obtain equivalent or higher scores than strong IMPALA baselines in moolib and torchbeast and PPO baseline in CleanRL. However, Cleanba variants present 1) shorter training time and 2) more reproducible learning curves in different hardware settings.

### Citation
```
@inproceedings{
    huang2024cleanba,
    title={Cleanba: A Reproducible and Efficient Distributed Reinforcement Learning Platform},
    author={Huang, Shengyi and Weng, Jiayi and Charakorn, Rujikorn and Lin, Min and Xu, Zhongwen and Onta{\~n}{\'o}n, Santiago},
    booktitle={The Twelfth International Conference on Learning Representations},
    year={2024},
    url={https://openreview.net/forum?id=Diq6urt3lS}
}
```
