--- 
title: "Generating Diverse Cooperative Agents by Learning Incompatible Policies" 
collection: publications 
permalink: /publication/lipo
excerpt: '' 
date: 2022-07-23
venue: '<i><b>ICML 2022 Workshop AI for Agent-Based Modelling (AI4ABM)</b></i>' 
paperurl:  
citation: '<b>Rujikorn Charakorn</b>, Poramate Manoonpong, and Nat Dilokthanakul' 
--- 

 
[pdf](https://openreview.net/pdf?id=a7vLnGKGIjY)


### Abstract
Effectively training a robust agent that can cooperate with unseen agents requires diverse training partner agents. Nonetheless, obtaining cooperative agents with diverse behaviors is a challenging task. Previous work proposes learning a diverse set of agents by diversifying the state-action distribution of the agents. However, without information about the task's goal, the diversified behaviors are not motivated to find other important, albeit non-optimal, solutions, resulting in only local variations of a solution. In this work, we propose to learn diverse behaviors by looking at policy compatibility while using state-action information to induce local variations of behaviors. Conceptually, policy compatibility measures whether policies of interest can collectively solve a task. We posit that incompatible policies can be behaviorally different. Based on this idea, we propose a novel objective to learn diverse behaviors. We theoretically show that our novel objective can generate a dissimilar policy, which we incorporate into a population-based training scheme. Empirically, the proposed method outperforms the baselines in terms of the number of discovered solutions given the same number of agents.


### Citation
```
@inproceedings{charakorn2022generating,
  title={Generating Diverse Cooperative Agents by Learning Incompatible Policies},
  author={Charakorn, Rujikorn and Manoonpong, Poramate and Dilokthanakul, Nat},
  booktitle={ICML 2022 Workshop AI for Agent-Based Modelling}
  year={2022}
}
```