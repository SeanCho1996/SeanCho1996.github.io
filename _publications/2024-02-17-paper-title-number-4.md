---
title: "Towards Fully Automated Medical Imaging Code Generation via Validation-based Context Engineering"
collection: publications
category: conferences
permalink: /publication/AutoMedImg
# excerpt: 'This paper is about fixing template issue #693.'
date: 2026-06-19
venue: 'ASE 2026, Munich, Germany'
paperurl: 'https://arxiv.org/abs/2608.29016'
citation: 'Zhao, Z., Sun, J., Hou, Z., Cai, C. H., Liu, Q., Li, M., ... & Dong, J. S. (2026). &quot;Towards Fully Automated Medical Imaging Code Generation via Validation-based Context Engineering.&quot; <i>arXiv preprint arXiv:2608.29016.</i>.'
---

Large language models (LLMs) have demonstrated considerable promise in program generation for small-scale and conventional application development; however, they remain limited when applied to complex, domain-specific tasks such as medical image processing. General-purpose models lack explicit domain knowledge and robust validation mechanisms to ensure correctness, often requiring substantial human intervention to produce reliable processing pipelines. To address these limitations, we propose AutoMedImg, a multi-agent framework for fully automated medical image processing code generation. AutoMedImg orchestrates specialised agents across two phases: a Planning Phase that performs dataset analysis and architecture design with semantic and formal verification, and a Coding Phase that generates modules in parallel with static checking, execution testing, and assembly validation. This multi-stage validation mitigates error propagation throughout generation, while comprehensive auto-context engineering combining domain-specific knowledge bases, shared memory, and validation feedback automates context construction without manual prompting. A cross-project adaptive pipeline synthesis mechanism further accumulates validated pipelines and retrieves proven components for new tasks based on project similarity, enhancing generation efficiency through cross-project learning. Extensive evaluation across six diverse and well-established medical imaging datasets with five backbone LLMs demonstrates that AutoMedImg achieves zero human intervention, with Dice scores of up to 0.90 for segmentation tasks and 99% accuracy for classification.
