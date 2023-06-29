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



### 更新一波
以chain of thoughts作为关键词搜索arxiv.org+ 引用Jason的CoT文章（前10页），根据题目筛选了一轮（去掉完全不相关+去重），目前还没有分类和整理


1. Investigating Prompting Techniques for Zero- and Few-Shot Visual Question Answering 

[[pdf]](https://arxiv.org/pdf/2306.09996.pdf)

2. Boosting Language Models Reasoning with Chain-of-Knowledge Prompting 

[[pdf]](https://arxiv.org/pdf/2306.06427.pdf)


3. Learning Multi-Step Reasoning by Solving Arithmetic Tasks 

*Tianduo Wang and Wei Lu*, Singapore University of Technology and Design, [[pdf]](https://arxiv.org/pdf/2306.01707.pdf)

4. CHAIN OF THOUGHT PROMPTING UNDER STREAMING BATCH: A CASE STUDY 

[[pdf]](https://arxiv.org/pdf/2306.00550.pdf)

5. Code Prompting: a Neural Symbolic Method for Complex Reasoning in Large Language Models 

*Yi Hu Haotong Yang Zhouchen Lin Muhan Zhang* [[pdf]](https://arxiv.org/pdf/2305.18507.pdf)

6. Tab-CoT: Zero-shot Tabular Chain of Thought

*Ziqi Jin and Wei Lu* [[pdf]](https://arxiv.org/pdf/2305.17812.pdf)

7. MultiTool-CoT: GPT-3 Can Use Multiple External Tools with Chain of Thought Prompting

*Tatsuro Inaba Hirokazu Kiyomaru Fei Cheng Sadao Kurohashi* Kyoto University, [[pdf]](https://arxiv.org/pdf/2305.16896.pdf)

8. Beyond Chain-of-Thought, Effective Graph-of-Thought Reasoning in Large Language Models

*Yao Yao, Zuchao Liand Hai Zhao*, Shanghai Jiaotong Univ., [[pdf]](https://arxiv.org/pdf/2305.16582.pdf)

9. EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought

*Yao Mu, Qinglong Zhang, Yu Qiao, Ping Luo*, Univ. of Hong Kong, Shanghai AI Lab, [[pdf]](https://arxiv.org/pdf/2305.15021.pdf)

10. ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models

*Zhipeng Chen, Kun Zhou,...,Ji-Rong Wem*, Remin Univ. of China, [[pdf]](https://arxiv.org/pdf/2305.14323.pdf)

11. The CoT Collection: Improving Zero-shot and Few-shot Learning of Language Models via Chain-of-Thought Fine-Tuning

*Seungone Kim,...,Minjoon Seo*, KAIST,  [[pdf]](https://arxiv.org/pdf/2305.14045.pdf)

12. Let’s Think Frame by Frame: Evaluating Video Chain of Thought with Video Infilling and Prediction

*Vaishnavi Himakunthala, William Yang Wang*, Univ. of California, Santa Barbara, USA, [[pdf]](https://arxiv.org/pdf/2305.13903.pdf)

13. “Is the Pope Catholic?” Applying Chain-of-Thought Reasoning to Understanding Conversational Implicatures

*Zae Myung Kim,Dongyeop Kang *,University of Minnesota Twin Cities, [[pdf]](https://arxiv.org/pdf/2305.13826.pdf)

14. Element-aware Summarization with Large Language Models: Expert-aligned Evaluation and Chain-of-Thought Method

*Yiming Wang, Zhuosheng Zhang, Rui Wang*, Shanghai Jiaotong Univ., [[pdf]](https://arxiv.org/pdf/2305.13412.pdf)

15. LogiCoT: Logical Chain-of-Thought Instruction-Tuning Data Collection

*Hanmeng Liu, Yue Zhang*, Westlake Univ., [[pdf]](https://arxiv.org/pdf/2305.12147.pdf)

16. Chain-of-thought prompting for responding to in-depth dialogue questions with LLM

*Hongru Wang, Rui Wang,.. Kam-Fai Wong*, CUHK, [[pdf]](https://arxiv.org/pdf/2305.11792.pdf) 

17. Reprompting: Automated Chain-of-Thought Prompt Inference Through Gibbs Sampling

*Weijia Xu, Andrzej Banburski-Fahey, Nebojsa Jojic*, Microsoft Research USA, [[pdf]](https://arxiv.org/pdf/2305.09993.pdf)

18. Improving ChatGPT Prompt for Code Generation

*Chao Liu, ..., Xiaohong Zhang, Meng Yan*, Chongqing Univ., [[pdf]](https://arxiv.org/pdf/2305.08360.pdf)

19. Language Models Don’t Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting

*Miles Turpin,...,Samuel R. Bowman*, NYU Alignment Research Group, [[pdf]](https://arxiv.org/pdf/2305.04388.pdf)

20. An automatically discovered chain-of-thought prompt generalizes to novel models and datasets

*Konstantin Hebenstreit, Matthias Samwald*, Medical University of Vienna, Austria, [[pdf]](https://arxiv.org/pdf/2305.02897.pdf)

21. Visual Chain of Thought: Bridging Logical Gaps with Multimodal Infillings

*Daniel Rose,Vaishnavi Himakunthala,Diba Mirza, William Yang Wang*, University of California, Santa Barbara, [[pdf]](https://arxiv.org/pdf/2305.02317.pdf)

22. Federated Prompting and Chain-of-Thought Reasoning for Improving LLMs Answering

*Xiangyang Liu, Tianqi Pang, and Chenyou Fan*, South China Normal University, [[pdf]](https://arxiv.org/pdf/2304.13911.pdf)

23. Text-to-Audio Generation using Instruction-Tuned LLM and Latent Diffusion Model

*Deepanway Ghosal, ..., Soujanya Poria*, Singapore University of Technology and Design, [[pdf]](https://arxiv.org/pdf/2304.13731.pdf)\

24. Answering Questions by Meta-Reasoning over Multiple Chains of Thought

*Ori Yoran, Jonathan Berant*, Tel Aviv University, [[pdf]](https://arxiv.org/pdf/2304.13007.pdf)

25. Enhancing Chain-of-Thoughts Prompting with Iterative Bootstrapping in Large Language Models

*Jiashuo Sun, Nan Duan*, Xiamen Univ.& Microsoft Research Asia, [[pdf]](https://arxiv.org/pdf/2304.11657.pdf)

26. Divide and Prompt: Chain of Thought Prompting for Text-to-SQL

*Xiping Liu, Zhao Tan*, Jiangxi University of Finance and Economics, [[pdf]](https://arxiv.org/pdf/2304.11556.pdf)

27. Chain of Thought Prompt Tuning for Vision-Language Model

*Jiaxin Ge, ..., Shanghang Zhang*, Peking Univ., [[pdf]](https://arxiv.org/pdf/2304.07919.pdf)


28. When do you need Chain-of-Thought Prompting for ChatGPT?

*Jiuhai Chen, Tianyi Zhou*,University of Maryland, [[pdf]](https://arxiv.org/pdf/2304.03262.pdf)

29.Chain-of-Thought Predictive Control

*Zhiwei Jia 1 Fangchen Liu 2 Vineet Thumuluri 1 Linghao Chen 3 Zhiao Huang 1 Hao Su 1*, UC San Diego, [[pdf]](https://arxiv.org/pdf/2304.00776.pdf)

30. Visual Chain-of-Thought Diffusion Models

*William Harvey,Frank Wood *, University of British Columbia, [[pdf]](https://arxiv.org/pdf/2303.16187.pdf)

31. ART: Automatic multi-step reasoning and tool-use for large language models

*Bhargavi Paranjape,...,Marco Tulio Ribeiro*, University of Washington & Meta AI, [[pdf]](https://arxiv.org/pdf/2303.09014.pdf)

32. Automatic Prompt Augmentation and Selection with Chain-of-Thought from Labeled Data

*KaShun Shum, Tong Zhang*,The Hong Kong University of Science and Technology, [[pdf]](https://arxiv.org/pdf/2302.12822.pdf)

33. Multimodal Chain-of-Thought Reasoning in Language Models

*Zhuosheng Zhang, ..., Alex Smola*, Shanghai Jiaotong Univ., [[pdf]](https://arxiv.org/pdf/2302.00923.pdf)

34. Faithful Chain-of-Thought Reasoning

*Qing Lyu, ..., Chris Callison-Burch*, University of Pennsylvania, Philadelphia, [[pdf]](https://arxiv.org/pdf/2301.13379.pdf)

35. Causal Reasoning About Entities and Events in Procedural Texts

*Li Zhang, ..., Chris Callison-Burch*, ♣University of Pennsylvania , [[pdf]](https://arxiv.org/pdf/2301.10896.pdf)

36. LAMBADA: Backward Chaining for Automated Reasoning in Natural Language

*Mehran Kazemi, Najoung Kim, Deepti Bhatia, Xin Xu, Deepak Ramachandran*, Google Research, [[pdf]](https://arxiv.org/pdf/2212.13894.pdf)

37. Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions

*Harsh Trivedi, ..., Ashish Sabharwal*, Stony Brook University, USA, [[pdf]](https://arxiv.org/pdf/2212.10509.pdf)

38. Large Language Models Are Reasoning Teachers

*Namgyu Ho, Laura Schmid, Se-Young Yun*, KAIST, [[pdf]](https://arxiv.org/pdf/2212.10071.pdf)

39. Towards Understanding Chain-of-Thought Prompting: An Empirical Study of What Matters

*Boshi Wang, ..., You Wu*, The Ohio State University & Google Research, [[pdf]](https://arxiv.org/pdf/2212.10001.pdf)

40. Large Language Models are Better Reasoners with Self-Verification

*Yixuan Weng,..., Jun Zhao*, CAS & Hunan Univ., [[pdf]](https://arxiv.org/pdf/2212.09561.pdf)

41. MURMUR: Modular Multi-Step Reasoning for Semi-Structured Data-to-Text Generation

*Swarnadeep Saha, Asli Celikyilmaz*, UNC Chapel Hill & Meta AI, [[pdf]](https://arxiv.org/pdf/2212.08607.pdf)

42. Constitutional AI: Harmlessness from AI Feedback (这个题目感觉很神圣……)

*Yuntao Bai, .., Jackson Kernion*, ??, [[pdf]](https://arxiv.org/pdf/2212.08073.pdf)

43. Teaching Small Language Models to Reason

*Lucie Charlotte Magister,..., Aliaksei Severyn*, Univ. of Cambridge & Google Research, [[pdf]](https://arxiv.org/pdf/2212.08410.pdf)

44. Chaining Simultaneous Thoughts for Numerical Reasoning

*Zhihong Shao, Fei Huang, Minlie Huang*, Tsinghua Univ., [[pdf]](https://arxiv.org/pdf/2211.16482.pdf)

45. Reasoning Circuits: Few-shot Multihop Question Generation with Structured Rationales

*Saurabh Kulshreshtha and Anna Rumshisky*, University of Massachusetts Lowell,[[pdf]](https://arxiv.org/pdf/2211.08466.pdf)

46. LARGE LANGUAGE MODELS CAN SELF-IMPROVE

*Jiaxin Huang, ..., Jiawei Han*, University of Illinois at Urbana-Champaign, [[pdf]](https://arxiv.org/pdf/2210.11610.pdf)

47. Challenging BIG-Bench tasks and whether chain-of-thought can solve them

*Mirac Suzgun,...,  Sebastian Gehrmann*, Stanford University & Google Research, [[pdf]](https://arxiv.org/pdf/2210.09261.pdf)

48. Large Language Models are few(1)-shot Table Reasoners

*Wenhu Chen*, University of Waterloo, Vector Institute, [[pdf]](https://arxiv.org/pdf/2210.06710.pdf)

49. LANGUAGE MODELS ARE GREEDY REASONERS:A SYSTEMATIC FORMAL ANALYSIS OF CHAIN-OF-THOUGHT

*Abulhair Saparov & He He*, New York University, New York,[[pdf]](https://arxiv.org/pdf/2210.01240.pdf)

50. Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering, 

[[pdf]](https://arxiv.org/pdf/2209.09513.pdf)

51. SELF-CONSISTENCY IMPROVES CHAIN OF THOUGHT REASONING IN LANGUAGE MODELS

*Xuezhi Wang†‡ Jason Wei†, ..., Denny Zhou*, Google Research, Brain Team, [[pdf]](https://arxiv.org/pdf/2203.11171.pdf)

52. Iteratively Prompt Pre-trained Language Models for Chain of Thought

*Boshi Wang, Xiang Deng and Huan Sun*, The Ohio State University, Columbus, OH, [[pdf]](https://arxiv.org/pdf/2203.08383.pdf)
 
53. ChatGPT is not Enough: Enhancing Large Language Models with Knowledge Graphs for Fact-aware Language Modeling

*Linyao Yang, Hongyang Chen, Zhao Li, Xiao Ding, Xindong Wu*,Zhejiang Lab, [[pdf]](https://arxiv.org/pdf/2306.11489.pdf)

54. Investigating Prompting Techniques for Zero- and Few-Shot Visual Question Answering

*Rabiul Awal, Le Zhang, Aishwarya Agrawal*, [[pdf]](https://arxiv.org/abs/2306.09996)

55. Encyclopedic VQA: Visual questions about detailed properties of fine-grained categories

*Thomas Mensink, Jasper Uijlings, Lluis Castrejon, Arushi Goel, Felipe Cadar, Howard Zhou, Fei Sha, André Araujo, Vittorio Ferrari*, [[pdf]](https://arxiv.org/abs/2306.09224)

56. [[A Prompting Framework for Natural Language Processing in the Medical Field: Assessing the Potential of Large Language Models for Swedish Healthcare]](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1766791&dswid=7571)

57. TART: A plug-and-play Transformer module for task-agnostic reasoning

*Kush Bhatia, Avanika Narayan, Christopher De Sa, Christopher Ré*, [[pdf]](https://arxiv.org/abs/2306.07536)

58. BoardgameQA: A Dataset for Natural Language Reasoning with Contradictory Information

*Mehran Kazemi, Quan Yuan, Deepti Bhatia, Najoung Kim, Xin Xu, Vaiva Imbrasaite, Deepak Ramachandran*, [[pdf]](https://arxiv.org/abs/2306.07934)

59. Human-in-the-Loop through Chain-of-Thought

*Zefan Cai, Baobao Chang, Wenjuan Han*, [[pdf]](https://arxiv.org/abs/2306.07932)

60. An Approach to Solving the Abstraction and Reasoning Corpus (ARC) Challenge

*Tan John Chong Min*, [[pdf]](https://arxiv.org/abs/2306.03553)

61. Deductive Verification of Chain-of-Thought Reasoning

*Zhan Ling, Yunhao Fang, Xuanlin Li, Zhiao Huang, Mingu Lee, Roland Memisevic, Hao Su*, [[pdf]](https://arxiv.org/abs/2306.03872)

62. Certified Reasoning with Language Models

*Gabriel Poesia, Kanishk Gandhi, Eric Zelikman, Noah D. Goodman*, [[pdf]](https://arxiv.org/abs/2306.04031)

63. A Study of Situational Reasoning for Traffic Understanding

*Jiarui Zhang, Filip Ilievski, Kaixin Ma, Aravinda Kollaa, Jonathan Francis, Alessandro Oltramari*, [[pdf]](https://arxiv.org/abs/2306.02520)

64. Large Language Models Are Not Abstract Reasoners

*Gaël Gendron, Qiming Bao, Michael Witbrock, Gillian Dobbie*, [[pdf]](https://arxiv.org/abs/2305.19555)

65. Dissecting Chain-of-Thought: A Study on Compositional In-Context Learning of MLPs

*Yingcong Li, Kartik Sreenivasan, Angeliki Giannou, Dimitris Papailiopoulos, Samet Oymak*, [[pdf]](https://arxiv.org/abs/2305.18869)

66. NavGPT: Explicit Reasoning in Vision-and-Language Navigation with Large Language Models

*Gengze Zhou, Yicong Hong, Qi Wu*, [[pdf]](https://arxiv.org/abs/2305.16986)

67. Language Models Can Improve Event Prediction by Few-Shot Abductive Reasoning

*Xiaoming Shi, Siqiao Xue, Kangrui Wang, Fan Zhou, James Y. Zhang, Jun Zhou, Chenhao Tan, Hongyuan Mei*, [[pdf]](https://arxiv.org/abs/2305.16646)

68. Chain-of-Thought Hub: A Continuous Effort to Measure Large Language Models' Reasoning Performance

*Yao Fu, Litu Ou, Mingyu Chen, Yuhao Wan, Hao Peng, Tushar Khot*, [[pdf]](https://arxiv.org/abs/2305.17306)

69. Improving accuracy of GPT-3/4 results on biomedical data using a retrieval-augmented language model

*David Soong, Sriram Sridhar, Han Si, Jan-Samuel Wagner, Ana Caroline Costa Sá, Christina Y Yu, Kubra Karagoz, Meijian Guan, Hisham Hamadeh, Brandon W Higgs*, [[pdf]](https://arxiv.org/abs/2305.17116)


70. CAN LARGE LANGUAGE MODELS REASON ABOUT MEDICAL QUESTIONS?

*Valentin Liévin, Christoffer Egeberg Hother, Ole Winther*

[[pdf]](https://arxiv.org/pdf/2207.08143.pdf), [code](https://github.com/vlievin/medical-reasoning)