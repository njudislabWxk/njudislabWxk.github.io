---
title: "VisFlow: Adaptive Content-Aware Video Analytics on Collaborative Cameras"
collection: publications
category: conferences
permalink: /publication/infocom24-visflow
excerpt: 'We propose a mechanism for content-aware analytics on collaborative cameras, denoted as VisFlow, to increase the quality of detections and achieve the latency requirement by fully utilizing camera resources.'
date: 2024-05-20
venue: 'IEEE INFOCOM 2024 - IEEE Conference on Computer Communications '
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10621148'
citation: '@inproceedings{yan2024visflow,
  title={VisFlow: Adaptive Content-Aware Video Analytics on Collaborative Cameras},
  author={Yan, Yuting and Zhang, Sheng and Wang, Xiaokun and Chen, Ning and Chen, Yu and Liang, Yu and Xiao, Mingjun and Lu, Sanglu},
  booktitle={IEEE INFOCOM 2024-IEEE Conference on Computer Communications},
  pages={2019--2028},
  year={2024},
  organization={IEEE}
}'
---

There is an increasing demand for analyzing live surveillance video streams via large-scale camera networks, particularly for applications in public safety and smart cities. To address the conflict between resource-intensive detection models and limited capabilities of cameras, a detection-with-tracking framework has gained prominence. However, since trackers are vulnerable to occlusions and new object appearances, frequent detections are required to calibrate the results, leading to varying detection demands that depends on video content. Consequently, we propose a mechanism for content-aware analytics on collaborative cameras, denoted as VisFlow, to increase the quality of detections and achieve the latency requirement by fully utilizing camera resources. We formulate such a problem as a non-linear, integer program with a long-term perspective, aimed at maximizing detection accuracy. An online mechanism, underpinned by a queue-based algorithm and randomized rounding, is then devised to dynamically orchestrate detection workloads among cameras, thus adapting to fluctuating detection demands. Via rigorous proof, both dynamic regret regarding overall accuracy and the transmission budget are ensured in the long run. The testbed experiments on Jetson Kits demonstrate that VisFlow improves accuracy by 18.3% over the baselines.
