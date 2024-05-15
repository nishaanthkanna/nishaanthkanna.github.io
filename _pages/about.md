---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me

I'm an ML Engineer and an Independent Researcher. Previously I collaborated with [Sara Hooker](https://scholar.google.com/citations?user=2xy6h3sAAAAJ&hl=en), [Ferdinando Fioretto](https://scholar.google.com/citations?user=ASf9Q04AAAAJ&hl=en) and [Beyza Ermis](https://scholar.google.com/citations?user=v2cMiCAAAAAJ&hl=en) at Cohere For AI as a Community Researcher. 

My current research interests are based on overcoming the deficiencies in current Foundational models that are limiting their usage. More specifically, my research interests are in:

- **Robustness**: The real world is not a fixed static distribution [2]. How can we train models that learn robust features, generalize **Out-of-Distribution** and are **Adversarially Robust** as well?
- **Trustworthy and Fairness**: For ML models to be widely adopted without much human intervention, they need to align with human values, be truthful, and be fair [1] even if the training dataset is biased.
- **Acquire New Knowledge/Skills on the Fly**: The hallmark of human intelligence is the ability to adapt to new scenarios by learning new skills and building upon previously acquired knowledge. Though current foundational models display this to an extent with the help of **In-Context Learning** [3], Chain-of-Thought Prompting, etc., there is a limitation to the complexity of the particular skill they can learn and they are limited by the context length. How can we design systems to learn complex skills in a few-shot setting and not be limited by context length?

Working towards this goal I have studied recently, how [hardware choice affects fairness in ML systems](https://arxiv.org/abs/2312.03886) (ICML 2024), [how LLMs handle distrubtion shift in continual pre-training](https://arxiv.org/abs/2402.17400) and [using LLMs to generate currcicula for OOD generalization in RL](https://proceedings.neurips.cc/paper_files/paper/2023/file/9ca22870ae0ba55ee50ce3e2d269e5de-Paper-Datasets_and_Benchmarks.pdf) (NeurIPS 2023).


## Recent Updates

- **May '24**: We're thrilled to have our work accepted at [ICML 2024](https://icml.cc/Conferences/2024/CallForPapers)! Our work demonstrates how the choice of GPU affects the fairness of underrepresented groups from a theoretical perspective supported by empirical experiments. We propose a mitigation solution that helps alleviate the unfairness caused. This is my first first-author paper in a major conference!

- **Jan '24**: I completed my Master in Computer Science at UNB, and would be joining as an ML Engineer at a startup in Canada.

- **Sept '23**: Our work on a new version of Neural MMO got accepted at [NeurIPS 2023 D&B](https://neurips.cc/virtual/2023/poster/73652). I worked on automated curriculum generation for RL agents, to help them learn new skills using **In-Context Learning**, LLMs and QD Algorithms. 

## Publications
(* - Denotes equal contribution)
- **On The Fairness Impacts of Hardware Selection in Machine Learning** \
    Shree Harsha Nelaturu\*, **Nishaanth Kanna Ravichandran\***, Cuong Tran, Sara Hooker, Ferdinando Fioretto \
    (to appear) **ICML '24** \
    [[arXiv](https://arxiv.org/abs/2312.03886)]

- **Investigating Continual Pretraining in Large Language Models: Insights and Implications** \
    Çağatay Yıldız, **Nishaanth Kanna Ravichandran**, Prishruit Punia, Matthias Bethge, Beyza Ermis \
    (submitted to) **CoLLAs '24** \
    [[arXiv](https://arxiv.org/abs/2402.17400)]  

- **Neural MMO 2.0: A Massively Multi-task Addition to Massively Multi-agent Learning** \
    Joseph Suarez, David Bloomin, Kyoung Whan Choe, Hao Xiang Li, Ryan Sullivan, **Nishaanth Kanna Ravichandran**, Daniel Scott, Rose Shuman, Herbie Bradley, Louis Castricato, Phillip Isola, Chenghui Yu, Yuhao Jiang, Qimai Li, Jiaxin Chen, Xiaolong Zhu \
    **NeurIPS 2023 Datasets and Benchmarks** \
    [[neurips.cc](https://proceedings.neurips.cc/paper_files/paper/2023/hash/9ca22870ae0ba55ee50ce3e2d269e5de-Abstract-Datasets_and_Benchmarks.html)]
