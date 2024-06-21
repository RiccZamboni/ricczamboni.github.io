---
title: "Distributional Policy Evaluation: a Maximum Entropy approach to Representation Learning"
collection: publications
permalink: /publication/NeurIPS2023
excerpt: 'CONTENT'
date: 2023-12-1
venue: 'Advances in Neural Information Processing Systems 36 (NeurIPS)'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2023/file/2a98af4fea6a24b73af7b588ca95f755-Paper-Conference.pdf'
content: 'R. Zamboni, A. M. Metelli and M. Restelli. 2023. “Distributional Policy Evaluation: a Maximum Entropy approach to Representation Learning”. Advances in Neural Information Processing Systems 36 (NeurIPS)'
---

**Abstract**: The Maximum Entropy (Max-Ent) framework has been effectively employed in a variety of Reinforcement Learning (RL) tasks. In this paper, we first propose a novel Max-Ent framework for policy evaluation in a distributional RL setting, named Distributional Maximum Entropy Policy Evaluation (D-Max-Ent PE). We derive a generalization-error bound that depends on the complexity of the representation employed, showing that this framework can explicitly take into account the features used to represent the state space while evaluating a policy. Then, we exploit these favorable properties to drive the representation learning of the state space in a Structural Risk Minimization fashion. We employ state-aggregation functions as feature functions and we specialize the D-Max-Ent approach into an algorithm, named D-Max-Ent Progressive Factorization, which constructs a progressively finer-grained representation of the state space by balancing the trade-off between preserving information (bias) and reducing the effective number of states, i.e., the complexity of the representation space (variance). Finally, we report the results of some illustrative numerical simulations, showing that the proposed algorithm matches the expected theoretical behavior and highlighting the relationship between aggregations and sample regimes.
