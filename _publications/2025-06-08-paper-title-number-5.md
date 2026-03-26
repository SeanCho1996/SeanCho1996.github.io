---
title: "MaCTG: Multi-Agent Collaborative Thought Graph for Automatic Programming"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
# excerpt: 'This paper is about a famous math equation, $$E=mc^2$$'
date: 2026-4-16
venue: 'ICSE 2026, Rio de Janeiro, Brazil'
paperurl: 'https://arxiv.org/pdf/2410.19245?'
citation: 'Zhao, Z., Sun, J., Hou, Z., Wei, Z., Cai, C. H., Qiao, M., & Dong, J. S. (2024). &quot;Mactg: Multi-agent collaborative thought graph for automatic programming.&quot; <i>arXiv preprint arXiv:2410.19245.</i>'
---

With the rapid advancement of Large Language Models (LLMs), LLM-based approaches have demonstrated strong problem-solving capabilities across various domains. However, in automatic programming, a single LLM is typically limited to function-level code generation, while multi-agent systems composed of multiple LLMs often suffer from inefficient task planning. This lack of structured coordination can lead to cascading hallucinations, where accumulated errors across agents result in suboptimal workflows and excessive computational costs. 
To overcome these challenges, we introduce MaCTG (Multi-Agent Collaborative Thought Graph), a novel multi-agent framework that employs a dynamic graph structure to facilitate precise task allocation and controlled collaboration among LLM agents. MaCTG autonomously assigns agent roles based on programming requirements, dynamically refines task distribution through context-aware adjustments, and systematically verifies and integrates project-level code, effectively reducing hallucination errors and improving overall accuracy. 
MaCTG enhances cost-effectiveness by implementing a hybrid LLM deployment, where proprietary models handle complex reasoning, while open-source models are used for routine coding and validation tasks.
%This strategy ensures efficient resource allocation while maintaining adaptability across various programming applications.  
To evaluate MaCTG’s effectiveness, we applied it to traditional image processing auto-programming tasks, achieving a state-of-the-art accuracy of 94.44\%. Additionally, by leveraging its hybrid LLM configuration, MaCTG significantly reduced operational costs by 89.09\% compared to existing multi-agent frameworks, demonstrating its efficiency, scalability, and real-world applicability. 
