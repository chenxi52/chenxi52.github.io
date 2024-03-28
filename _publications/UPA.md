---
title: "Uncertainty-Aware Pseudo-Label Filtering for Source-Free Unsupervised Domain Adaptation"
collection: Neurocomputing 2024
permalink: /publication/UPA
excerpt: 'Soruce-free Domain Adaptation.'
date: 2024-03-07
venue: 'Neurocomputing'
paperurl: 'https://arxiv.org/pdf/2403.11256.pdf'
---
Source-free unsupervised domain adaptation (SFUDA) aims to enable the utilization of a pre-trained source model
in an unlabeled target domain without access to source data. Self-training is a way to solve SFUDA, where confident target samples are iteratively selected as pseudolabeled samples to guide target model learning. However, prior heuristic noisy pseudo-label filtering methods all involve introducing extra models, which are sensitive to model assumptions and may introduce additional errors or mislabeling. In this work, we propose a method called Uncertainty-aware Pseudo-label-filtering Adaptation (UPA) to efficiently address this issue in a coarse-to-fine manner. Specifically, we first introduce a sample selection module named Adaptive Pseudo-label Selection(APS), which is responsible for filtering noisy pseudo labels. The APS utilizes a simple sample uncertainty estimation method by aggregating knowledge from neighboring samples and confident samples are selected as clean pseudo-labeled. Additionally, we incorporate Class-Aware Contrastive Learning (CACL) to mitigate the memorization of pseudo-label noise by learning robust pair-wise representation supervised by pseudo labels. Through extensive experiments conducted on three widely used benchmarks, we demonstrate that our proposed method achieves competitive performance on par with state-of-the-art SFUDA methods. 
