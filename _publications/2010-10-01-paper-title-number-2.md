---
title: "MACRO: Incentivizing Multi-leader Game-based Pareto-efficient Crowdsourcing for Video Analytics"
collection: publications
category: conferences
permalink: /publication/icde24-macro
excerpt: 'We design an incentive mechanism for Multi-leader game-based video Analytics upon CROwdsourcing, named MACRO, to over-come the above situation. '
date: 2024-5-13
venue: 'IEEE ICDE 2024 - IEEE International Conference on Data Engineering'
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10598110'
citation: '@inproceedings{chen2024macro,
  title={MACRO: Incentivizing Multi-leader Game-based Pareto-efficient Crowdsourcing for Video Analytics},
  author={Chen, Yu and Zhang, Sheng and Zhou, Ziying and Wang, Xiaokun and Liang, Yu and Chen, Ning and Yan, Yuting and Xiao, Mingjun and Wu, Jie and Qian, Zhuzhong and others},
  booktitle={2024 IEEE 40th International Conference on Data Engineering (ICDE)},
  pages={289--302},
  year={2024},
  organization={IEEE}
}'
---
In recent years, many crowdsourcing platforms have emerged, using the resources of recruited workers to perform diverse outsourcing tasks, where the video analytics attracts much attention due to its practical implications. For maximum profits, platforms carefully choose the workers and determine the video analytics configurations to ensure accuracy; meanwhile, workers possess the flexibility to tailor the configurations for their indivi-dual gains, which makes it hard for platforms to optimize their profits considering the platform-worker conflicts. In this paper, we design an incentive mechanism for Multi-leader game-based video Analytics upon CROwdsourcing, named MACRO, to over-come the above situation. Under that mechanism, we first formu-late the utility optimization problems for platforms and workers, respectively. We then propose a dual ascent-based method to op-timally determine the video analytics configurations for a multi-platform game, ensuring Pareto efficiency. Moreover, in the context of a multi-leader game involving platform-worker conflicts, we design an incentive function with its incentive factor update strategy and propose an ADMM-based approach for maximizing incentives that motivate workers to contribute to the platforms' profits. Rigorous proofs demonstrate the linear convergence of the MACRO to the multi-leader Stackelberg equilibrium. Trace-driven experiments show that MACRO improves the Pareto efficiency by 26.3%, outperforming other approaches.
