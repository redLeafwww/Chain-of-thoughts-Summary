# Chain-of-thoughts-入门的材料

## 入门教程
- [Aston Zhang【论文讲解】Tree of Thoughts：如何使用大语言模型有意识地解决问题](https://www.bilibili.com/video/BV1td4y1f7YC/?spm_id_from=333.337.search-card.all.click&vd_source=368c715dd5961c302db542de40aa6e5f)

- [Cot的Demo](https://github.com/amazon-science/auto-cot/blob/main/run_demo.py)
- [Prompting的入门教程，更新很快](https://www.promptingguide.ai/techniques/cot)

## 文献整理

在Aston Zhang的上述教程的基础上，增加了一些新论文和观点


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

- [Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering](https://proceedings.neurips.cc/paper_files/paper/2022/file/11332b6b6cf4485b84afadb1352d3a9a-Paper-Conference.pdf)
    - NeuIPS'22

### 问题分解
- [Least-to-Most Prompting Enables Complex Reasoning in Large Language Models](https://arxiv.org/abs/2205.10625)

- [Measuring and Narowing the Compositionality Gap in Lanquage Models](https://arxiv.ora/abs/2210.03350)

- [SELF-CONSISTENCY IMPROVES CHAIN OF THOUGHT REASONING IN LANGUAGE MODELS](https://openreview.net/pdf?id=1PL1NIMMrw)
    - ICLR'23 Poster
    - 提出了一种self-consistency的decoding strategy

- [kNN PROMPTING: BEYOND-CONTEXT LEARNINGWITH CALIBRATION-FREE NEAREST NEIGHBOR INFERENCE](https://arxiv.org/pdf/2303.13824v1.pdf)
    - 解决2个问题：1.上下文学习容量有限；2.上下文学习性能对于bias比较敏感
    - 介绍的[文章](https://mp.weixin.qq.com/s/SnwqkXCCAv3QwN8-NmoWPw)
    - 可能有点关联？[Can language models learn from explanations in context?](https://arxiv.org/pdf/2204.02329.pdf)

- Reasoning的方法（NeurIPS'22）：[STaR: Self-Taught Reasoner
Bootstrapping Reasoning With Reasoning](https://proceedings.neurips.cc/paper_files/paper/2022/file/639a9a172c044fbb64175b5fad42e9a5-Paper-Conference.pdf)


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

- [GraphPrompt: Unifying Pre-Training and Downstream Tasks for Graph Neural Networks](https://arxiv.org/pdf/2302.08043.pdf)
    - 一个预训练的对于Graph的Prompting框架,针对下游任务。

- [ViperGPT: Visual Inference via Python Execution for Reasoning](https://arxiv.org/pdf/2303.08128.pdf)
    - 这个感觉挺好玩的，后续得看看

- [MM-REACT : Prompting ChatGPT for Multimodal Reasoning and Action](https://arxiv.org/pdf/2303.11381.pdf)
    - arxiv时间：2023.5
    
### 大模型背景
- [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/abs/2204.02311)
    - [PaLM-E: An Embodied Multimodal Language Model](https://arxiv.org/pdf/2303.03378.pdf)
        - 用PaLM做预训练模型+Embodied具象化的最新结果
- [Emergent Abilities of Large Lanquage Models](https://arxivora/abs/2206.07682)
- [Lanquage Model Cascades](https://arxiv.ora/abs/2207.10342)
