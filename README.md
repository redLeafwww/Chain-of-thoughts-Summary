# Chain-of-thoughts-Summary

## 入门教程
- [Aston Zhang【论文讲解】Tree of Thoughts：如何使用大语言模型有意识地解决问题](https://www.bilibili.com/video/BV1td4y1f7YC/?spm_id_from=333.337.search-card.all.click&vd_source=368c715dd5961c302db542de40aa6e5f)

- [Prompting的入门教程，更新很快](https://www.promptingguide.ai/techniques/cot)

## 文献整理

在Aston Zhang的上述教程的基础上，增加了一些新论文，并且加入了我自己的文献笔记
另一个Chain of thoughts相关的paper list:https://github.com/Timothyxxx/Chain-of-ThoughtsPapers

### 基础论文
- [Chain of Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)

- [Large Language Models are Zero-Shot Reasoners](https://arxiv.org/abs/2205.11916)

- [Automatic Chain of Thought Prompting in Large Language Models](https://arxiv.orq/abs/2210.03493)
    - ICLR'23 

- [Tree of Thoughts: Deliberate Problem Solving with Large Language Models](https://arxiv.org/pdf/2305.10601.pdf)
    - 比CoT更通用的frame：Tree of Thoughts
    - arxiv时间：2023.05
    - 一个Youtuber对于文章的[解读](https://www.bilibili.com/video/BV1td4y1f7YC/?spm_id_from=333.337.search-card.all.click), 作者给出的[github repo](https://github.com/princeton-nlp/tree-of-thought-llm)

### 问题分解
- [Least-to-Most Prompting Enables Complex Reasoning in Large Language Models](https://arxiv.org/abs/2205.10625)

- [Measuring and Narowing the Compositionality Gap in Lanquage Models](https://arxiv.ora/abs/2210.03350)

- [SELF-CONSISTENCY IMPROVES CHAIN OF THOUGHT REASONING IN LANGUAGE MODELS](https://openreview.net/pdf?id=1PL1NIMMrw)
    - ICLR'23 Poster
    - 提出了一种self-consistency的decoding strategy

### 融合预测
- [Self-Consistency lmproves Chain of Thouaht Reasoning in Lanquage Models](https://arxiv.org/abs/2203.11171)
- [Rationale-Augmented Ensembles in Language Models](https://arxiv.org/abs/2207.00747)

### 生成-校验
- [STaR: Self-Taught Reasoner Bootstrapping Reasoning With Reasoning](https://arxiv.org/abs/2203.14465)
- [On the Advance of Making Lanquage Models Better Reasoners](https://arxivora/abs/2206.02336)

### 多语言or多模态
- [ Language Models are Multilingual Chain-of-Thought Reasoners](https://arxiv.orq/abs/2210.03057)
- [Multimodal Chain-of-Thought Reasoning in Language Models](https://arxiv.org/pdf/2302.00923.pdf)
    - 来自auto-cot的aston zhang 和 zhuosheng zhang
    - arxiv时间: 2023.2
- [Prompting Large Language Models with Answer Heuristics for Knowledge-based Visual Question Answering](https://arxiv.org/pdf/2303.01903.pdf)
    - Prophet, 有关介绍的[文章](https://zhuanlan.zhihu.com/p/613601646)
    - [Github repo](https://github.com/MILVLG/prophet)

### 大模型背景
- [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/abs/2204.02311)
- [Emergent Abilities of Large Lanquage Models](https://arxivora/abs/2206.07682)
- [Lanquage Model Cascades](https://arxiv.ora/abs/2207.10342)
