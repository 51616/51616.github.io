--- 
title: "Generating Diverse Cooperative Agents by Learning Incompatible Policies" 
collection: publications 
permalink: /publication/lipo
excerpt: '' 
date: 2023-01-24
venue: '<i><b>ICLR 2023 (<font color="#00ab44">Spotlight</font>, <font color="#00ab44">5.65% accept rate</font>, <a href="https://papercopilot.com/statistics/iclr-statistics/iclr-2023-statistics/">tied for 24th highest rated paper</a>)<br>ICML 2022 AI4ABM Workshop (<font color="#00ab44">Spotlight</font>)</b></i>' 


paperurl:  
citation: '<b>Rujikorn Charakorn</b>, Poramate Manoonpong, and Nat Dilokthanakul' 
--- 

[Paper](https://openreview.net/forum?id=UkU05GOH7_6) | [Project Site](https://sites.google.com/view/iclr-lipo-2023) | [Code](https://github.com/51616/marl-lipo)

### Summary
In this work, we propose to learn diverse behaviors via policy compatibility. Conceptually, policy compatibility measures whether policies of interest can coordinate effectively. We theoretically show that incompatible policies are not similar. Thus, policy compatibility—which has been used exclusively as a measure of robustness—can be used as a proxy for learning diverse behaviors. Then, we incorporate the proposed objective into a population-based training scheme to allow concurrent training of multiple agents. Additionally, we use state-action information to induce local variations of each policy. Empirically, the proposed method consistently discovers more solutions than baseline methods across various multi-goal cooperative environments. Finally, in multi-recipe Overcooked, we show that our method produces populations of behaviorally diverse agents, which enables generalist agents trained with such a population to be more robust.

This work was also presented at <b>AI4ABM workshop @ ICML 2022 (spotlight)</b> [[pdf](https://openreview.net/pdf?id=a7vLnGKGIjY)] [[poster](/files/posters/LIPO_poster.pdf)]

### Citation
```
@inproceedings{
  charakorn2023generating,
  title={Generating Diverse Cooperative Agents by Learning Incompatible Policies},
  author={Rujikorn Charakorn and Poramate Manoonpong and Nat Dilokthanakul},
  booktitle={The Eleventh International Conference on Learning Representations },
  year={2023},
  url={https://openreview.net/forum?id=UkU05GOH7_6}
}
```

<!-- ### Citation
```
@inproceedings{charakorn2022generating,
  title={Generating Diverse Cooperative Agents by Learning Incompatible Policies},
  author={Charakorn, Rujikorn and Manoonpong, Poramate and Dilokthanakul, Nat},
  booktitle={ICML 2022 Workshop AI for Agent-Based Modelling}
  year={2022}
}
``` -->