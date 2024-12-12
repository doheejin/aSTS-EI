# aSTS-EI
This repository is for the dataset of aSTS-EI, introduced in the paper, Aspect-based Semantic Textual Similarity for Educational Test Items (AIED 2024).

> Our dataset is based on the open source, [https://github.com/iamyuanchung/TOEFL-QA](https://github.com/iamyuanchung/TOEFL-QA) (Bo-Hsiang Tseng & Yu-An Chung).

## Task Overview
Below is an example illustrating aspect-wise similarity between two test items, where they are similar in the *Question* aspect but differ in the *Story* and *Options* aspects. Thus, the example emphasizes the need for aspect-wise comparison over holistic approaches.

![plot](aSTS_overview.png)


## Citation
Please cite our paper if you find this repository helpful.
```
@InProceedings{10.1007/978-3-031-64299-9_30,
author="Do, Heejin
and Lee, Gary Geunbae",
editor="Olney, Andrew M.
and Chounta, Irene-Angelica
and Liu, Zitao
and Santos, Olga C.
and Bittencourt, Ig Ibert",
title="Aspect-Based Semantic Textual Similarity for Educational Test Items",
booktitle="Artificial Intelligence in Education",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="344--352",
abstract="In the educational domain, identifying the similarity among test items provides various advantages for exam quality management and personalized student learning. Existing studies mostly relied on student performance data, such as the number of correct or incorrect answers, to measure item similarity. However, nuanced semantic information within the test items has been overlooked, possibly due to the lack of similarity-labeled data. Human-annotated educational data demands high-cost expertise, and items comprising multiple aspects, such as questions and choices, require detailed criteria. In this paper, we introduce a task of aspect-based semantic textual similarity for educational test items (aSTS-EI), where we assess the similarity by specific aspects within test items and present an LLM-guided benchmark dataset. We report the baseline performance by extending the STS methods, setting the groundwork for future aSTS-EI tasks. In addition, to assist data-scarce settings, we propose a progressive augmentation (ProAug) method, which generates step-by-step item aspects via recursive prompting. Experimental results imply the efficacy of existing STS methods for a shorter aspect while underlining the necessity for specialized approaches in relatively longer aspects. Nonetheless, markedly improved results with ProAug highlight the assistance of our augmentation strategy to overcome data scarcity.",
isbn="978-3-031-64299-9"
}
```
