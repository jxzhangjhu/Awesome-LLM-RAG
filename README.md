# Awesome-LLM-RAG

\
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)



This repo aims to record advanced papers of Retrieval Agumented Generation (RAG) in LLMs.

We strongly encourage the researchers that want to promote their fantastic work to the LLM RAG to make pull request to update their paper's information!


--- 

## Contents

- [Resources](#resources)
  - [Workshops and Tutorials](#workshops-and-tutorials)
- [Papers](#papers)
  - [Survey and Benchmark](#survey-and-benchmark)
  - [Retrieval-enhanced LLMs](#retrieval-enhanced-llms)
  - [RAG Instruction Tuning](#rag-instruction-tuning)
  - [RAG In-Context Learning](#rag-in-context-learning)
  - [RAG Embeddings](#rag-embeddings)
  - [RAG Search](#rag-search)
  - [RAG Long-text and Memory](#rag-long-text-and-memory)


--- 

# Resources 

## Workshops and Tutorials

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




# Papers 

## Survey and Benchmark 

**Benchmarking Large Language Models in Retrieval-Augmented Generation** \
*Jiawei Chen, Hongyu Lin, Xianpei Han, Le Sun* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2309.01431)][[Github](https://github.com/chen700564/RGB)] \
4 Sep 2023 


 
## Retrieval-enhanced LLMs

**Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language Models** \
*Wenhao Yu, Hongming Zhang, Xiaoman Pan, Kaixin Ma, Hongwei Wang, Dong Yu* \
arxiv - Nov 2023 [[Paper](https://arxiv.org/abs/2311.09210#:~:text=15%20Nov%202023%5D-,Chain%2Dof%2DNote%3A%20Enhancing%20Robustness,in%20Retrieval%2DAugmented%20Language%20Models&text=Retrieval%2Daugmented%20language%20models%20(RALMs,by%20leveraging%20external%20knowledge%20sources.)] 

**REST: Retrieval-Based Speculative Decoding** \
*Zhenyu He, Zexuan Zhong, Tianle Cai, Jason D Lee, Di He* \ 
arXiv - Nov 2023 [[Paper](https://arxiv.org/abs/2311.08252#:~:text=We%20introduce%20Retrieval%2DBased%20Speculative,certain%20common%20phases%20and%20patterns.)][[Github](https://github.com/fasterdecoding/rest)]


**Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection**  
*Anonymous*  
ICLR 24 – October 23 [[paper](https://openreview.net/forum?id=hSyW5go0v8)]


**Retrieval meets Long Context Large Language Models**  
*Anonymous*  
ICLR 24 – October 23 [[paper](https://openreview.net/forum?id=xw5nxFWMlo)]


**DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines**  
*Omar Khattab, Arnav Singhvi, Paridhi Maheshwari, Zhiyuan Zhang, Keshav Santhanam, Sri Vardhamanan, Saiful Haq, Ashutosh Sharma, Thomas T. Joshi, Hanna Moazam, Heather Miller, Matei Zaharia, Christopher Potts*  
arXiv – October 2023 [[paper](https://arxiv.org/abs/2310.03714)] [[code](https://github.com/stanfordnlp/dspy)]



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
ICLR 24 – October 23 [[paper](https://openreview.net/forum?id=22OTbutug9)]

**InstructRetro: Instruction Tuning post Retrieval-Augmented Pretraining**  
*Boxin Wang, Wei Ping, Lawrence McAfee, Peng Xu, Bo Li, Mohammad Shoeybi, Bryan Catanzaro* \
arXiv -  October 23 [[paper](https://openreview.net/forum?id=4stB7DFLp6)]


## RAG In-Context Learning 

**In-Context Retrieval-Augmented Language Models**  
*Ori Ram, Yoav Levine, Itay Dalmedigos, Dor Muhlgay, Amnon Shashua, Kevin Leyton-Brown, Yoav Shoham*  
AI21 Labs – Jan 2023 [[paper](https://uploads-ssl.webflow.com/60fd4503684b466578c0d307/63c6c20dec4479564db21819_NEW_In_Context_Retrieval_Augmented_Language_Models.pdf)] [[code](https://github.com/AI21Labs/in-context-ralm)]


## RAG Embeddings 

**Text Embeddings Reveal (Almost) As Much As Text** \
*John X. Morris, Volodymyr Kuleshov, Vitaly Shmatikov, Alexander M. Rush*  \
EMNLP 2023 - Oct 2023 [[Paper](https://arxiv.org/abs/2310.06816?ref=upstract.com)][[Github](https://github.com/jxmorris12/vec2text)] 

**Jina Embeddings 2: 8192-Token General-Purpose Text Embeddings for Long Documents** \
*Michael Günther, Jackmin Ong, Isabelle Mohr, Alaeddine Abdessalem, Tanguy Abel, Mohammad Kalim Akram, Susana Guzman, Georgios Mastrapas, Saba Sturua, Bo Wang, Maximilian Werk, Nan Wang, Han Xiao* \
arXiv - Oct 2023. [[Paper](https://arxiv.org/abs/2310.19923)][[Model](https://huggingface.co/jinaai/jina-embeddings-v2-small-en)] 



## RAG Search

## RAG Long-text and Memory 

**Understanding Retrieval Augmentation for Long-Form Question Answering** \
*Hung-Ting Chen, Fangyuan Xu, Shane A. Arora, Eunsol Choi* \
arXiv 2023 - Oct 2023 [[Paper](https://arxiv.org/abs/2310.12150)]




