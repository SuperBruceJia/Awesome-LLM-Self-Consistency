# Awesome-LLM-Self-Consistency
Awesome-LLM-Self-Consistency: A Curated List of Self-consistency in Large Language Models

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/SuperBruceJia/Awesome-LLM-Self-Consistency) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/SuperBruceJia/Awesome-LLM-Self-Consistency)

This repository, called **Self-Consistency-LLMs**, contains a collection of resources and papers on **Self-Consistency** in **Large Language Models**. 

"*I can't see a path that guarantees safety. We're entering a period of great uncertainty where we're dealing with things we've never dealt with before, and we can't afford to get it wrong with these things because they might take over.*" - Geoffrey Hinton, Professor, Department of Computer Science, University of Toronto, October 5, 2023

*Welcome to share your papers, thoughts, and ideas by [submitting an issue](https://github.com/SuperBruceJia/Awesome-LLM-Self-Consistency/issues/new)!* 

## Contents
- [Presentations](#Presentations)
- [Benchmarks](#Benchmarks)
  - [Arithmetic Reasoning](#Arithmetic-Reasoning)
  - [Commonsense Reasoning](#Commonsense-Reasoning)
  - [Semantic Consistency](#Semantic-Consistency)
  - [Logical Consistency](#Logical-Consistency)
  - [Factual Consistency](#Factual-Consistency)
- [Papers](#Papers)
  - [Reasoning](#Reasoning)
  - [Semantics](#Semantics)
  - [Logicality](#Logicality)
  - [Factuality](#Factuality)

# Presentations 
**Teach Language Models to Reason** \
*Denny Zhou, Google DeepMind* \
[[Link](https://dennyzhou.github.io/LLMs-Reason-2023-Harvard-Yale.pdf)] \
Sept 2023

# Benchmarks
## Arithmetic Reasoning
**GSM8K**: \
**Training Verifiers to Solve Math Word Problems** \
*Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, Mark Chen, Heewoo Jun, Lukasz Kaiser, Matthias Plappert, Jerry Tworek, Jacob Hilton, Reiichiro Nakano, Christopher Hesse, John Schulman* \
arXiv 2021, [[Paper](https://github.com/openai/grade-school-math)] [[GitHub](https://github.com/openai/grade-school-math)] [[Blog Post]](https://openai.com/research/solving-math-word-problems)\
18 Nov 2021

**SingleEq**: \
**Parsing Algebraic Word Problems into Equations** \
*Rik Koncel-Kedziorski, Hannaneh Hajishirzi, Ashish Sabharwal, Oren Etzioni, Siena Dumas Ang* \
TACL 2015, [[Paper](https://aclanthology.org/Q15-1042.pdf)] [[Gitlab](https://gitlab.cs.washington.edu/ALGES/TACL2015)] \
24 June 2015

**AddSub**: \
**Learning to Solve Arithmetic Word Problems with Verb Categorization** \
*Mohammad Javad Hosseini, Hannaneh Hajishirzi, Oren Etzioni, Nate Kushman* \
EMNLP 2014, [[Paper](https://aclanthology.org/D14-1058.pdf)] [[Gitlab](https://www.cs.washington.edu/nlp/arithmetic)] \
25 Oct 2014

**MultiArith**: \
**Solving General Arithmetic Word Problems** \
*Subhro Roy, Dan Roth* \
EMNLP 2015, [[Paper](https://aclanthology.org/D15-1202.pdf)] [[Webpage](https://cogcomp.seas.upenn.edu/page/resource_view/98)] \
17 Sept 2015

**AQUA-RAT**: \
**Program Induction by Rationale Generation : Learning to Solve and Explain Algebraic Word Problems** \
*Wang Ling, Dani Yogatama, Chris Dyer, Phil Blunsom* \
ACL 2017, [[Paper](https://aclanthology.org/P17-1015.pdf)] [[GitHub](https://github.com/google-deepmind/AQuA)] \
30 July 2017

**SVAMP**: \
**Are NLP Models really able to Solve Simple Math Word Problems?** \
*Arkil Patel, Satwik Bhattamishra, Navin Goyal* \
NAACL 2021, [[Paper](https://aclanthology.org/2021.naacl-main.168.pdf)] [[GitHub](https://github.com/arkilpatel/SVAMP)] \
6 July 2021

**ASDiv**: \
**A Diverse Corpus for Evaluating and Developing English Math Word Problem Solvers** \
*Shen-yun Miao, Chao-Chun Liang, Keh-Yih Su* \
ACL 2020, [[Paper](https://aclanthology.org/2020.acl-main.92.pdf)] [[GitHub](https://github.com/chaochun/nlu-asdiv-dataset)] \
5 July 2020

## Commonsense Reasoning
**CSQA**: \
**CommonsenseQA: A Question Answering Challenge Targeting Commonsense Knowledge** \
*Alon Talmor, Jonathan Herzig, Nicholas Lourie, Jonathan Berant* \
NAACL 2019, [[Paper](https://arxiv.org/pdf/1811.00937.pdf)] [[Webpage](https://www.tau-nlp.sites.tau.ac.il/commonsenseqa)] \
15 Mar 2019

## Semantic Consistency
**BECEL**: \
**BECEL: Benchmark for Consistency Evaluation of Language Models** \
*Myeongjun Jang, Deuk Sin Kwon, Thomas Lukasiewicz* \
COLING 2022, [[Paper](https://aclanthology.org/2022.coling-1.324.pdf)] [[GitHub](https://github.com/MJ-Jang/BECEL)]\
12 Oct 2022

**Paraphrased SQuAD Questions**: \
**Improving the Robustness of Question Answering Systems to Question Paraphrasing** \
*Wee Chung Gan, Hwee Tou Ng* \
ACL 2019, [[Paper](https://aclanthology.org/P19-1610.pdf)] [[GitHub](https://github.com/nusnlp/paraphrasing-squad)]\
28 July 2019

## Logical Consistency
### Negational, Symmetric, Transitive, and Additive Consistency
**BECEL**: \
**BECEL: Benchmark for Consistency Evaluation of Language Models** \
*Myeongjun Jang, Deuk Sin Kwon, Thomas Lukasiewicz* \
COLING 2022, [[Paper](https://aclanthology.org/2022.coling-1.324.pdf)] [[GitHub](https://github.com/MJ-Jang/BECEL)]\
12 Oct 2022

### Hypothetical and Compositional Consistency
**Two Failures of Self-Consistency in the Multi-Step Reasoning of LLMs** \
*Angelica Chen, Jason Phang, Alicia Parrish, Vishakh Padmakumar, Chen Zhao, Samuel R. Bowman, Kyunghyun Cho* \
arXiv 2023, [[Paper](https://browse.arxiv.org/pdf/2305.14279.pdf)]\
2 Oct 2023

## Factual Consistency
**mParaRel**: \
**mParaRel: Factual Consistency of Multilingual Pretrained Language Models** \
*Constanza Fierro, Anders Søgaard* \
Findings of ACL: ACL 2022, [[Paper](https://aclanthology.org/2022.findings-acl.240.pdf)] [[GitHub](https://github.com/coastalcph/mpararel)]\
22 Mar 2022

**ParaRel**: \
**ParaRel:metal:: Measuring and Improving Consistency in Pretrained Language Models** \
*Yanai Elazar, Nora Kassner, Shauli Ravfogel, Abhilasha Ravichander, Eduard Hovy, Hinrich Schütze, Yoav Goldberg* \
TACL 2021, [[Paper](https://aclanthology.org/2021.tacl-1.60.pdf)] [[GitHub](https://github.com/yanaiela/pararel)] [[Presentation](https://yanaiela.github.io/presentations/consistency.pdf)]\
29 May 2021

# Papers
## Reasoning
**MetaMath: Bootstrap Your Own Mathematical Questions for Large Language Models** \
*Longhui Yu, Weisen Jiang, Han Shi, Jincheng Yu, Zhengying Liu, Yu Zhang, James T. Kwok, Zhenguo Li, Adrian Weller, Weiyang Liu* \
arXiv 2023, [[Paper](https://openreview.net/pdf?id=N8N0hgNDRt)] [[GitHub](https://github.com/meta-math/MetaMath)]\
9 Oct 2023

## Reasoning
**Large Language Models are Better Reasoners with Self-Verification** \
*Yixuan Weng, Minjun Zhu, Fei Xia, Bin Li, Shizhu He, Shengping Liu, Bin Sun, Kang Liu, Jun Zhao* \
EMNLP 2023 Findings, [[Paper](https://arxiv.org/pdf/2212.09561.pdf)] [[GitHub](https://github.com/WENGSYX/Self-Verification)]\
19 Oct 2023

**Large Language Models Can Be Easily Distracted by Irrelevant Context** \
*Freda Shi, Xinyun Chen, Kanishka Misra, Nathan Scales, David Dohan, Ed Chi, Nathanael Schärli, Denny Zhou* \
ICML 2023, [[Paper](https://proceedings.mlr.press/v202/shi23a/shi23a.pdf)] [[GitHub](https://github.com/google-research-datasets/GSM-IC)]\
6 Jun 2023

**Let's Sample Step by Step: Adaptive-Consistency for Efficient Reasoning with LLMs** \
*Pranjal Aggarwal, Aman Madaan, Yiming Yang, Mausam* \
arXiv 2023, [[Paper](https://browse.arxiv.org/pdf/2305.11860.pdf)] [[Website](http://sample-step-by-step.info/)] [[GitHub](https://github.com/Pranjal2041/AdaptiveConsistency)]\
19 May 2023

**Self-Consistency Improves Chain of Thought Reasoning in Language Models** \
*Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou* \
ICLR 2023, [[Paper](https://openreview.net/pdf?id=1PL1NIMMrw)]\
7 Mar 2023

## Semantics
**Semantic Consistency for Assuring Reliability of Large Language Models** \
*Harsh Raj, Vipul Gupta, Domenic Rosati, Subhabrata Majumdar* \
arXiv 2023, [[Paper](https://arxiv.org/pdf/2308.09138.pdf)]\
17 Aug 2023

**Measuring Reliability of Large Language Models through Semantic Consistency** \
*Harsh Raj, Domenic Rosati, Subhabrata Majumdar* \
ML Safety Workshop, NeurIPS 2022, [[Paper](https://arxiv.org/pdf/2211.05853.pdf)]\
28 Nov 2022

**Prompt Consistency for Zero-Shot Task Generalization** \
*Chunting Zhou, Junxian He, Xuezhe Ma, Taylor Berg-Kirkpatrick, Graham Neubig* \
Findings of ACL: EMNLP 2022, [[Paper](https://aclanthology.org/2022.findings-emnlp.192.pdf)] [[GitHub](https://github.com/violet-zct/swarm-distillation-zero-shot)]\
27 Dec 2022

**Accurate, Yet Inconsistent? Consistency Analysis on Language Understanding Models** \
*Myeongjun Jang, Deuk Sin Kwon, Thomas Lukasiewicz* \
arXiv 2021, [[Paper](https://arxiv.org/pdf/2108.06665.pdf)]\
15 Aug 2021

**Evolution of Semantic Similarity—A Survey** \
*Dhivya Chandrasekaran, Vijay Mago* \
ACM Computing Survey 2021, [[Paper](https://dl.acm.org/doi/abs/10.1145/3440755)]\
30 Jan 2021

## Logicality
**Enhancing Self-Consistency and Performance of Pre-Trained Language Models through Natural Language Inference** \
*Eric Mitchell, Joseph Noh, Siyan Li, Will Armstrong, Ananth Agarwal, Patrick Liu, Chelsea Finn, Christopher Manning* \
EMNLP 2022, [[Paper](https://aclanthology.org/2022.emnlp-main.115.pdf)] [[Website](https://ericmitchell.ai/emnlp-2022-concord/)] [[GitHub](https://github.com/eric-mitchell/concord)]\
21 Nov 2022

## Factuality
**RCOT: Detecting and Rectifying Factual Inconsistency in Reasoning by Reversing Chain-of-Thought** \
*Tianci Xue, Ziqi Wang, Zhenhailong Wang, Chi Han, Pengfei Yu, Heng Ji* \
arXiv 2023, [[Paper](https://arxiv.org/pdf/2305.11499.pdf)] \
2 Oct 2023

**P-Adapters: Robustly Extracting Factual Information from Language Models with Diverse Prompts** \
*Benjamin Newman, Prafulla Kumar Choubey, Nazneen Rajani* \
ICLR 2022, [[Paper](https://openreview.net/pdf?id=DhzIU48OcZh)] [[GitHub](https://github.com/salesforce/FactLM)]\
19 Apr 2022

**How Can We Know What Language Models Know?** \
*Zhengbao Jiang, Frank F. Xu, Jun Araki, Graham Neubig* \
TACL 2020, [[Paper](https://aclanthology.org/2020.tacl-1.28.pdf)] [[GitHub](https://github.com/jzbjyb/LPAQA)]\
3 May 2020
