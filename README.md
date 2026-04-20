<div align="center">
    <h1>Awesome LLM RAG</h1>
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg"/></a>
</div>

\
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)



This repo aims to record advanced papers on Retrieval Augmented Generation (RAG) in LLMs.

We strongly encourage the researchers that want to promote their fantastic work to the LLM RAG to make pull request to update their paper's information!


--- 

## Contents

- [Bernstein](https://github.com/chernistry/bernstein) - Multi-agent orchestrator with RAG-enhanced task planning. Decomposes goals using context from codebase analysis.
- [Resources](#resources)
  - [Workshops and Tutorials](#workshops-and-tutorials)
  - [Books](#books)
- [Papers](#papers)
  - [Survey and Benchmark](#survey-and-benchmark)
  - [Retrieval-enhanced LLMs](#retrieval-enhanced-llms)
  - [RAG Instruction Tuning](#rag-instruction-tuning)
  - [RAG In-Context Learning](#rag-in-context-learning)
  - [RAG Embeddings](#rag-embeddings)
  - [RAG Simulators](#rag-simulators)
  - [RAG Search](#rag-search)
  - [RAG Long-text and Memory](#rag-long-text-and-memory)
  - [RAG Evaluation](#rag-evaluation)
  - [RAG Optimization](#rag-optimization)
  - [RAG Application](#rag-application)



--- 

# Resources 

- [guardian-agent-prompts](https://github.com/milkomida77/guardian-agent-prompts) - 49 production-tested AI agent system prompts for Claude Code multi-agent orchestration with retrieval-augmented generation patterns. MIT licensed.
- [CCHub](https://github.com/Moresl/cchub) - A desktop control panel for the Claude Code / Codex / Gemini CLI ecosystem. Manage MCP servers, config profiles, agent skills, CLAUDE.md, hooks, and workflow templates from a single Tauri app (Windows / macOS / Linux).
## Workshops and Tutorials


- [Agent Shadow Brain](https://github.com/theihtisham/agent-shadow-brain) - Self-evolving AI coding intelligence with infinite memory (TurboQuant), genetic algorithm self-evolution, predictive bug detection, PageRank knowledge graphs, swarm intelligence, and adversarial defense.
- [Omni Skills Forge](https://github.com/theihtisham/omni-skills-forge) - 50,000+ curated AI agent skills for Claude Code, Cursor, Copilot, Windsurf, Cline. Visual dashboard, one-click install, skill doctor, auto-update.
**Personalized Generative AI**  
*Zheng Chen, Ziyan Jiang, Fan Yang, Zhankui He, Yupeng Hou, Eunah Cho, Julian McAuley, Aram Galstyan, Xiaohua Hu, Jie Yang*  
CIKM 23 – Oct 2023 [[link](https://sites.google.com/view/pgai2023/home)]

**First Workshop on Recommendation with Generative Models**  
*Wenjie Wang, Yong Liu, Yang Zhang, Weiwen Liu, Fuli Feng, Xiangnan He, Aixin Sun*  
CIKM 23 – Oct 2023 [[link](https://rgm-cikm23.github.io/)]

**First Workshop on Generative Information Retrieval**  
*Gabriel Bénédict, Ruqing Zhang, Donald Metzler*  
SIGIR 23 – Jul 2023 [[link](https://coda.io/@sigir/gen-ir)]

**Retrieval-based Language Models and Applications**  
*Akari Asai,	Sewon Min,	Zexuan Zhong,	Danqi Chen*  
ACL 23 – Jul 2023 [[link](https://acl2023-retrieval-lm.github.io/)]

**Become a Generative AI Developer**
*Richie Cotton, Olivier Mertens, Korey Stegared-Pace, James Briggs, Vincent Vankrunkelsven, Alara Dirik, Jacob Marquez, Priyanka Asnani*
DataCamp [[link](https://www.datacamp.com/ai-code-alongs)]

## Books

**Build a Large Language Model (From Scratch)**  
*Sebastian Raschka*  
Manning Publications - Sep 2024 [[link](https://www.manning.com/books/build-a-large-language-model-from-scratch)]

**Build a Reasoning Model (From Scratch)**  
*Sebastian Raschka*  
Manning Publications - Aug 2025 [[link](https://www.manning.com/books/build-a-reasoning-model-from-scratch)]

**Retrieval Augmented Generation, The Seminal Papers**  
*Ben Auffarth*  
Manning Publications - Mar 2026 [[link](https://www.manning.com/books/retrieval-augmented-generation-the-seminal-papers)]

**A Simple Guide to Retrieval Augmented Generation**  
*Abhinav Kimothi*  
Manning Publications - Jun 2025 [[link](https://www.manning.com/books/a-simple-guide-to-retrieval-augmented-generation)]

**Build an Advanced RAG Application (From Scratch)**  
*Hamza Farooq*  
Manning Publications - Oct 2024 [[link](https://www.manning.com/books/build-an-advanced-rag-application-from-scratch)]

**Enterprise RAG**  
*Tyler Suard and Darshil Modi*  
Manning Publications - Mar 2025 [[link](https://www.manning.com/books/enterprise-rag)]

**Essential GraphRAG**  
*"Tomaž Bratanič and Oskar Hane"*  
Manning Publications - Jul 2025 [[link](https://www.manning.com/books/essential-graphrag)]

# Papers 

## Survey and Benchmark 

**Benchmarking Large Language Models in Retrieval-Augmented Generation** \
*Jiawei Chen, Hongyu Lin, Xianpei Han, Le Sun* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2309.01431)][[Github](https://github.com/chen700564/RGB)] \
4 Sep 2023 


 
## Retrieval-enhanced LLMs

<!-- 
**Active Retrieval Augmented Generation** \
*Zhengbao Jiang, Frank F. Xu, Luyu Gao, Zhiqing Sun, Qian Liu, Jane Dwivedi-Yu, Yiming Yang, Jamie Callan, Graham Neubig* \
EMNLP 2023 - May 2023 [[Paper](https://arxiv.org/abs/2305.06983)][[Github](https://github.com/jzbjyb/flare)] \
 -->

**Improving Retrieval Augmented Language Model with Self-Reasoning** \
Yuan Xia, Jingbo Zhou, Zhenhui Shi, Jun Chen, Haifeng Huang \  
AAAI 25 – Mar 2025 [[paper](https://arxiv.org/abs/2407.19813)]

**Adaptive Retrieval without Self-Knowledge? Bringing Uncertainty Back Home**  \
Viktor Moskvoretskii, Maria Lysyuk, Mikhail Salnikov, Nikolay Ivanov, Sergey Pletenev, Daria Galimzianova, Nikita Krayko, Vasily Konovalov, Irina Nikishina, Alexander Panchenko \
arxiv – Jan 2025 [[paper](https://arxiv.org/abs/2501.12835)]
 
**DFA-RAG: Conversational Semantic Router for Large Language Model with Definite Finite Automaton**  \
Yiyou Sun, Junjie Hu, Wei Cheng, Haifeng Chen \
ICML 24 – Feb 2024 [[paper](https://arxiv.org/abs/2402.04411)]

**Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language Models** \
*Wenhao Yu, Hongming Zhang, Xiaoman Pan, Kaixin Ma, Hongwei Wang, Dong Yu* \
arxiv - Nov 2023 [[Paper](https://arxiv.org/abs/2311.09210)] 

**REST: Retrieval-Based Speculative Decoding** \
*Zhenyu He, Zexuan Zhong, Tianle Cai, Jason D Lee, Di He* \
arXiv - Nov 2023 [[Paper](https://arxiv.org/abs/2311.08252)][[Github](https://github.com/fasterdecoding/rest)]


**Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection**  
*Anonymous*  
ICLR 24 – Oct 2023 [[paper](https://openreview.net/forum?id=hSyW5go0v8)]

**Self-Knowledge Guided Retrieval Augmentation for Large Language Models** \
*Yile Wang, Peng Li, Maosong Sun, Yang Liu* \
arXiv - Oct 2023 [[Ppaer](https://arxiv.org/abs/2310.05002)]


**Retrieval meets Long Context Large Language Models** \
*Peng Xu, Wei Ping, Xianchao Wu, Lawrence McAfee, Chen Zhu, Zihan Liu, Sandeep Subramanian, Evelina Bakhturina, Mohammad Shoeybi, Bryan Catanzaro* \
arxiv - Oct 2023 [[Paper](https://arxiv.org/abs/2310.03025)]


**DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines**  
*Omar Khattab, Arnav Singhvi, Paridhi Maheshwari, Zhiyuan Zhang, Keshav Santhanam, Sri Vardhamanan, Saiful Haq, Ashutosh Sharma, Thomas T. Joshi, Hanna Moazam, Heather Miller, Matei Zaharia, Christopher Potts*  
arXiv – Oct 2023 [[paper](https://arxiv.org/abs/2310.03714)] [[code](https://github.com/stanfordnlp/dspy)]

**Adaptive Chameleon  or Stubborn Sloth: Revealing the Behavior of Large Language Models in Knowledge Conflicts**  
*Jian Xie, Kai Zhang, Jiangjie Chen, Renze Lou, Yu Su*  
ICLR 24 – May 2023 [[paper](https://arxiv.org/abs/2305.13300)] [[code](https://github.com/OSU-NLP-Group/LLM-Knowledge-Conflict)]

**Active Retrieval Augmented Generation**  
*Zhengbao Jiang, Frank F. Xu, Luyu Gao, Zhiqing Sun, Qian Liu, Jane Dwivedi-Yu, Yiming Yang, Jamie Callan, Graham Neubig*  
arXiv – May 2023 [[paper](https://arxiv.org/abs/2305.06983)] [[code](https://github.com/jzbjyb/FLARE)]


**REPLUG: Retrieval-Augmented Black-Box Language Models**  
*Weijia Shi, Sewon Min, Michihiro Yasunaga, Minjoon Seo, Rich James, Mike Lewis, Luke Zettlemoyer, Wen-tau Yih*  
arXiv – Jan 2023 [[paper](https://arxiv.org/abs/2301.12652)]


**Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks** 
*Patrick Lewis, Ethan Perez, Aleksandra Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela* 
NeurIPS 2020 - May 2020 [[Paper](https://arxiv.org/abs/2005.11401)]



## RAG Instruction Tuning 

**RA-DIT: Retrieval-Augmented Dual Instruction Tuning**  
*Anonymous*  
ICLR 24 – Oct 23 [[paper](https://openreview.net/forum?id=22OTbutug9)]

**InstructRetro: Instruction Tuning post Retrieval-Augmented Pretraining**  
*Boxin Wang, Wei Ping, Lawrence McAfee, Peng Xu, Bo Li, Mohammad Shoeybi, Bryan Catanzaro* \
arXiv -  Oct 23 [[paper](https://openreview.net/forum?id=4stB7DFLp6)]


## RAG In-Context Learning 

**In-Context Retrieval-Augmented Language Models**  
*Ori Ram, Yoav Levine, Itay Dalmedigos, Dor Muhlgay, Amnon Shashua, Kevin Leyton-Brown, Yoav Shoham*  
AI21 Labs – Jan 2023 [[paper](https://uploads-ssl.webflow.com/60fd4503684b466578c0d307/63c6c20dec4479564db21819_NEW_In_Context_Retrieval_Augmented_Language_Models.pdf)] [[code](https://github.com/AI21Labs/in-context-ralm)]


## RAG Embeddings 

**RegaVAE: A Retrieval-Augmented Gaussian Mixture Variational Auto-Encoder for Language Modeling** \
*Jingcheng Deng, Liang Pang, Huawei Shen, Xueqi Cheng* \
EMNLP 2023 - Oct 2023 [[Paper](https://arxiv.org/abs/2310.10567)][[Github](https://github.com/TrustedLLM/RegaVAE)] 

**Text Embeddings Reveal (Almost) As Much As Text** \
*John X. Morris, Volodymyr Kuleshov, Vitaly Shmatikov, Alexander M. Rush*  \
EMNLP 2023 - Oct 2023 [[Paper](https://arxiv.org/abs/2310.06816?ref=upstract.com)][[Github](https://github.com/jxmorris12/vec2text)] 

**Jina Embeddings 2: 8192-Token General-Purpose Text Embeddings for Long Documents** \
*Michael Günther, Jackmin Ong, Isabelle Mohr, Alaeddine Abdessalem, Tanguy Abel, Mohammad Kalim Akram, Susana Guzman, Georgios Mastrapas, Saba Sturua, Bo Wang, Maximilian Werk, Nan Wang, Han Xiao* \
arXiv - Oct 2023. [[Paper](https://arxiv.org/abs/2310.19923)][[Model](https://huggingface.co/jinaai/jina-embeddings-v2-small-en)] 

## RAG Simulators

**KAUCUS: Knowledge Augmented User Simulators for Training Language Model Assistants** \
*Kaustubh D. Dhole* \
Simulation of Conversational Intelligence in Chat, EACL 2024 [[Paper](https://arxiv.org/abs/2401.16454)]

## RAG Search

## RAG Long-text and Memory

**ComoRAG: A Cognitive-Inspired Memory-Organized RAG for Stateful Long Narrative Reasoning** \                    
*Juyuan Wang, Rongchen Zhao, Wei Wei, Yufeng Wang, Mo Yu, Jie Zhou, Jin Xu, Liyan Xu* \                            
AAAI 2026 - Aug 2025 [[paper](https://arxiv.org/abs/2508.10419)] [[GitHub](https://github.com/EternityJune25/ComoRAG)]

- [Cortex](https://github.com/SKULLFIRE07/cortex-memory) - Persistent AI memory for coding assistants. Auto-captures decisions, patterns, and context. VSCode extension + CLI + MCP server. Free.
- [Agent Brain](https://github.com/kaderosio/agent-brain) - 7-layer cognitive memory system for AI agents with perception gate, dream cycle, and predictive capabilities. Built with FastAPI, PostgreSQL/pgvector. Self-hostable.

**HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models** \
*Bernal Jiménez Gutiérrez, Yiheng Shu, Yu Gu, Michihiro Yasunaga, Yu Su* \
arXiv - May 2024 [[paper](https://arxiv.org/abs/2405.14831)] [[GitHub](https://github.com/OSU-NLP-Group/HippoRAG)]

**Understanding Retrieval Augmentation for Long-Form Question Answering** \
*Hung-Ting Chen, Fangyuan Xu, Shane A. Arora, Eunsol Choi* \
arXiv - Oct 2023 [[Paper](https://arxiv.org/abs/2310.12150)]

## RAG Evaluation

**ARES: An Automated Evaluation Framework for Retrieval-Augmented Generation Systems** \
*Jon Saad-Falcon, Omar Khattab, Christopher Potts, Matei Zaharia* \
arXiv - Nov 2023. [[Paper](https://arxiv.org/abs/2311.09476)] [[Github](https://github.com/stanford-futuredata/ares)]

**Evaluation and Alignment, The Seminal Papers** \
*Hanchung Leea* \
Manning - Mar 2026. [[Book](https://www.manning.com/books/evaluation-and-alignment-the-seminal-papers)] 


## RAG Optimization

**Learning to Filter Context for Retrieval-Augmented Generation** \
*Zhiruo Wang, Jun Araki, Zhengbao Jiang, Md Rizwan Parvez, Graham Neubig* \
arxiv- Nov 2023 [[Paper](https://arxiv.org/abs/2311.08377)][[Github](https://github.com/zorazrw/filco)] 


**Large Language Models Can Be Easily Distracted by Irrelevant Context** \
*Freda Shi, Xinyun Chen, Kanishka Misra, Nathan Scales, David Dohan, Ed Chi, Nathanael Schärli, Denny Zhou* \
ICML 2023 - Jan 2023 [[Paper](https://arxiv.org/abs/2302.00093)][[Github](https://github.com/google-research-datasets/GSM-IC)] 


**Evidentiality-guided Generation for Knowledge-Intensive NLP Tasks** \
*Akari Asai, Matt Gardner, Hannaneh Hajishirzi* \
NAACL 2022 - Dec 2021 [[Paper](https://arxiv.org/abs/2112.08688)][[Github](https://github.com/akariasai/evidentiality_qa)] 

**When Not to Trust Language Models: Investigating Effectiveness of Parametric and Non-Parametric Memories** \
*Alex Mallen, Akari Asai, Victor Zhong, Rajarshi Das, Daniel Khashabi, Hannaneh Hajishirzi* \
ACL 2023 - Dec 2022 [[Paper](https://arxiv.org/abs/2212.10511)][[Github](https://github.com/alextmallen/adaptive-retrieval)] 



## RAG Application

**Deficiency of Large Language Models in Finance: An Empirical Examination of Hallucination** \
*Haoqiang Kang, Xiao-Yang Liu* \
arXiv - Nov 2023 [[Paper](https://arxiv.org/abs/2311.15548)] 


**Clinfo.ai: An Open-Source Retrieval-Augmented Large Language Model System for Answering Medical Questions using Scientific Literature** \
*Alejandro Lozano, Scott L Fleming, Chia-Chun Chiang, Nigam Shah* \
arXiv - Oct 2023. [[Paper](https://arxiv.org/abs/2310.16146v1)] 

**PEARL: Personalizing Large Language Model Writing Assistants with Generation-Calibrated Retrievers** \
*Sheshera Mysore, Zhuoran Lu, Mengting Wan, Longqi Yang, Steve Menezes, Tina Baghaee, Emmanuel Barajas Gonzalez, Jennifer Neville, Tara Safavi* \
arXiv - Nov 2023. [[Paper](https://arxiv.org/abs/2311.09180)] 



