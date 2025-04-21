
# Awesome-Social-Agent [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

### 🔥🔥🔥 


## 📢 News
[04/20/2025]

📢 

✨ 

🚀 **What's New in This Update**:
<br>✅ Updated to include around 100 additional Vid-LLMs and 15 new benchmarks as of June 2024.

Multiple minor updates will follow this major update. And the GitHub repository will be gradually updated soon. We welcome your reading and feedback ❤️

<font size=5><center><b> Table of Contents </b> </center></font>
- [Awesome-LLMs-for-Video-Understanding ](#awesome-llms-for-video-understanding-)
    - [🔥🔥🔥 Video Understanding with Large Language Models: A Survey](#-video-understanding-with-large-language-models-a-survey)
  - [Why we need Vid-LLMs?](#why-we-need-vid-llms)
  - [😎 Vid-LLMs: Models](#-vid-llms-models)
    - [📑 Citation](#-citation)
      - [🗒️ Taxonomy 1](#️-taxonomy-1)
        - [🕹️ Video Analyzer × LLM](#️-video-analyzer--llm)
          - [LMM as Summarizer](#lmm-as-summarizer)
          - [LLM as Manager](#llm-as-manager)
        - [👾 Video Embedder × LLM](#-analyzer--embedder--llm)
          - [LLM as Text Decoder](#llm-as-text-decoder)
          - [LLM as Regressor](#llm-as-regressor)
          - [LLM as Hidden Layer](#llm-as-hidden-layer)
        - [🧭 (Analyzer + Embedder) × LLM](#-analyzer--embedder--llm)
          - [LLM as Manager](#llm-as-manager-1)
          - [LMM as Summarizer](#lmm-as-summarizer-1)
          - [LLM as Text Decoder](#llm-as-text-decoder-1)
          - [LLM as Regressor](#llm-as-regressor-1)
          - [LLM as Hidden Layer](#llm-as-hidden-layer-1)
      - [🗒️ Taxonomy 2](#️-taxonomy-2)
        - [🤖 LLM-based Video Agents](#-llm-based-video-agents)
        - [🎥 Vid-LLM Pretraining](#-vid-llm-pretraining)
        - [👀 Vid-LLM Instruction Tuning](#-vid-llm-instruction-tuning)
          - [Fine-tuning with Connective Adapters](#fine-tuning-with-connective-adapters)
          - [Fine-tuning with Insertive Adapters](#fine-tuning-with-insertive-adapters)
          - [Fine-tuning with Hybrid Adapters](#fine-tuning-with-hybrid-adapters)
        - [🦾 Hybrid Methods](#-hybrid-methods)
        - [Training-free Methods](#-training-free-methods)
  - [Tasks, Datasets, and Benchmarks](#tasks-datasets-and-benchmarks)
      - [Recognition and Anticipation](#recognition-and-anticipation)
      - [Captioning and Description](#captioning-and-description)
      - [Grounding and Retrieval](#grounding-and-retrieval)
      - [Question Answering](#question-answering)
      - [Video Instruction Tuning](#video-instruction-tuning)
        - [Pretraining Dataset](#pretraining-dataset)
        - [Fine-tuning Dataset](#fine-tuning-dataset)
      - [Video-based Large Language Models Benchmark](#video-based-large-language-models-benchmark)
  - [Contributing](#contributing)
    - [🌟 Star History](#-star-history)
    - [♥️ Contributors](#️-contributors)

## Why we need Vid-LLMs?

![image](./img/tasks.png)


## 😎 Vid-LLMs: Models 

![image](./img/timeline.png)

### 📑 Citation

If you find our survey useful for your research, please cite the following paper:

```bibtex
@article{vidllmsurvey,
      title={Video Understanding with Large Language Models: A Survey}, 
      author={Tang, Yunlong and Bi, Jing and Xu, Siting and Song, Luchuan and Liang, Susan and Wang, Teng and Zhang, Daoan and An, Jie and Lin, Jingyang and Zhu, Rongyi and Vosoughi, Ali and Huang, Chao and Zhang, Zeliang and Zheng, Feng and Zhang, Jianguo and Luo, Ping and Luo, Jiebo and Xu, Chenliang},
      journal={arXiv preprint arXiv:2312.17432},
      year={2023},
}
```

### 🗒️ Taxonomy 1

#### 🕹️ Video Analyzer × LLM

##### LLM as Summarizer
| Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**Seeing the Unseen: Visual Metaphor Captioning for Videos**](https://arxiv.org/html/2406.04886v1) |   GIT-LLaVA   | 06/2024 |      [code]()       | arXiv |


##### LLM as Manager
| Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**DrVideo: Document Retrieval Based Long Video Understanding**](https://arxiv.org/abs/2406.12846) |   DrVideo   | 06/2024 |      [code]()       | arXiv |


#### 👾 Video Embedder × LLM

##### LLM as Text Decoder

| Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**AuroraCap: Efficient, Performant Video Detailed Captioning and a New Benchmark**](https://arxiv.org/abs/2410.03051) |   AuroraCap   | 10/2024 |      [project page](https://rese1f.github.io/aurora-web/)       | arXiv |


##### LLM as Regressor

| Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**Holmes-VAD: Towards Unbiased and Explainable Video Anomaly Detection via Multi-modal LLM**](https://arxiv.org/abs/2406.12235) |   Holmes-VAD   | 06/2024 |      [code](https://holmesvad.github.io/)       | arXiv |


##### LLM as Hidden Layer
 | Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**VTG-LLM integrating timestamp knowledge into video LLMs for enhanced video temporal grounding**](https://arxiv.org/abs/2405.13382) |   VTG-LLM   | 05/2024 |      [code](https://github.com/gyxxyg/VTG-LLM)       | arXiv |


#### 🧭 (Analyzer + Embedder) × LLM

##### LLM as Manager
 | Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**MM-VID: Advancing Video Understanding with GPT-4V(ision)**](https://arxiv.org/abs/2310.19773) |       MM-VID        | 10/2023 |                              -                               | arXiv |
##### LLM as Summarizer
 | Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**Shot2Story20K a new benchmark for comprehensive understanding of multi-shot videos**](https://arxiv.org/abs/2312.10300) |   SUM-shot   | 12/2023 |      [code](https://mingfei.info/shot2story/)       | arXiv |
##### LLM as Regressor
 | Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**Vript: A Video Is Worth Thousands of Words**](https://arxiv.org/abs/2406.06040) |   Vriptor   | 06/2024 |      [code](https://github.com/mutonix/Vript)       | NeurIPS |

##### LLM as Text Decoder
 | Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**Contextual AD Narration with Interleaved Multimodal Sequence**](https://arxiv.org/abs/2403.12922) |   Uni-AD   | 03/2024 |      [code](https://github.com/MCG-NJU/Uni-AD)       | arXiv |

##### LLM as Hidden Layer
 | Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**PG-Video-LLaVA: Pixel Grounding Large Video-Language Models**](https://arxiv.org/abs/2311.13435v2)[![Star](https://img.shields.io/github/stars/mbzuai-oryx/video-llava.svg?style=social&label=Star)](https://github.com/mbzuai-oryx/video-llava) |   PG-Video-LLaVA    | 11/2023 |      [code](https://github.com/mbzuai-oryx/video-llava)      | arXiv |
### 🗒️ Taxonomy 2

#### 🤖 LLM-based Video Agents

| Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language**](https://arxiv.org/abs/2204.00598) |   Socratic Models   | 04/2022 |      [project page](https://socraticmodels.github.io/)       | arXiv |



#### 🎥 Vid-LLM Pretraining

| Title                                                        |  Model  |  Date   |                        Code                        |  Venue  |
| :----------------------------------------------------------- | :-----: | :-----: | :------------------------------------------------: | :-----: |
| [**Learning Video Representations from Large Language Models**](https://arxiv.org/abs/2212.04501)[![Star](https://img.shields.io/github/stars/facebookresearch/lavila?style=social&label=Star)](https://github.com/facebookresearch/lavila) | LaViLa  | 12/2022 | [code](https://github.com/facebookresearch/lavila) |  CVPR   |


#### 👀 Vid-LLM Instruction Tuning

##### Fine-tuning with Connective Adapters

| Title                                                        |     Model     |  Date   |                         Code                         | Venue |
| :----------------------------------------------------------- | :-----------: | :-----: | :--------------------------------------------------: | :---: |
| [**Video-LLaMA: An Instruction-Finetuned Visual Language Model for Video Understanding**](https://arxiv.org/abs/2306.02858) [![Star](https://img.shields.io/github/stars/DAMO-NLP-SG/Video-LLaMA.svg?style=social&label=Star)](https://github.com/DAMO-NLP-SG/Video-LLaMA) |  Video-LLaMA  | 06/2023 |  [code](https://github.com/DAMO-NLP-SG/Video-LLaMA)  | arXiv |


##### Fine-tuning with Insertive Adapters

| Title                                                        |  Model   |  Date   |                    Code                    | Venue |
| :----------------------------------------------------------- | :------: | :-----: | :----------------------------------------: | :---: |
| [**Otter: A Multi-Modal Model with In-Context Instruction Tuning**](https://arxiv.org/abs/2305.03726v1)[![Star](https://img.shields.io/github/stars/luodian/otter.svg?style=social&label=Star)](https://github.com/luodian/otter) |  Otter   | 06/2023 |  [code](https://github.com/luodian/otter)  | arXiv |

##### Fine-tuning with Hybrid Adapters

| Title                                                        |   Model   |  Date   |                     Code                     | Venue |
| :----------------------------------------------------------- | :-------: | :-----: | :------------------------------------------: | :---: |
| [**VTimeLLM: Empower LLM to Grasp Video Moments**](https://arxiv.org/abs/2311.18445v1)[![Star](https://img.shields.io/github/stars/huangb23/vtimellm.svg?style=social&label=Star)](https://github.com/huangb23/vtimellm) | VTimeLLM  | 11/2023 | [code](https://github.com/huangb23/vtimellm) | arXiv |

#### 🦾 Hybrid Methods

| Title                                                        |        Model        |  Date   |                             Code                             | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :----------------------------------------------------------: | :---: |
| [**VideoChat: Chat-Centric Video Understanding**](https://arxiv.org/abs/2305.06355)[![Star](https://img.shields.io/github/stars/OpenGVLab/Ask-Anything.svg?style=social&label=Star)](https://github.com/OpenGVLab/Ask-Anything) |      VideoChat      | 05/2023 | [code](https://github.com/OpenGVLab/Ask-Anything)  [demo](https://huggingface.co/spaces/ynhe/AskAnything) | arXiv |

#### 💎 Training-free Methods

| Title                                                        |        Model        |  Date   | Code | Venue |
| :----------------------------------------------------------- | :-----------------: | :-----: | :--: | :---: |
| [**SlowFast-LLaVA: A Strong Training-Free Baseline for Video Large Language Models**](https://arxiv.org/abs/2407.15841) |   SlowFast-LLaVA    | 07/2024 |  -   | arXiv |


---

## Tasks, Datasets, and Benchmarks

#### Recognition and Anticipation

| Name               |                            Paper                             | Date |                            Link                             |  Venue  |
| :----------------- | :----------------------------------------------------------: | :--: | :---------------------------------------------------------: | :-----: |
| **Charades**       | [**Hollywood in homes: Crowdsourcing data collection for activity understanding**](https://arxiv.org/abs/1604.01753v3) | 2016 |        [Link](http://vuchallenge.org/charades.html)         |  ECCV   |


#### Captioning and Description
| Name               |                            Paper                             | Date |                            Link                             |  Venue  |
| :----------------- | :----------------------------------------------------------: | :--: | :---------------------------------------------------------: | :-----: |
|**Microsoft Research Video Description Corpus (MSVD)**|[**Collecting Highly Parallel Data for Paraphrase Evaluation**](https://aclanthology.org/P11-1020.pdf)|2011|[Link](https://www.cs.utexas.edu/users/ml/clamp/videoDescription/#data)|ACL|


#### Grounding and Retrieval
| Name               |                            Paper                             | Date |                            Link                             |  Venue  |
| :----------------- | :----------------------------------------------------------: | :--: | :---------------------------------------------------------: | :-----: |
|**Epic-Kitchens-100**|[**Rescaling Egocentric Vision**](https://arxiv.org/abs/2006.13256v4)|2021|[Link](https://epic-kitchens.github.io/2021)|IJCV|


#### Question Answering
| Name               |                            Paper                             | Date |                            Link                             |  Venue  |
| :----------------- | :----------------------------------------------------------: | :--: | :---------------------------------------------------------: | :-----: |
|**MSVD-QA**|[**Video Question Answering via Gradually Refined Attention over Appearance and Motion**](https://dl.acm.org/doi/10.1145/3123266.3123427)|2017|[Link](https://github.com/xudejing/video-question-answering)|ACM Multimedia|

#### Video Instruction Tuning
##### Pretraining Dataset
| Name               |                            Paper                             | Date |                            Link                             |  Venue  |
| :----------------- | :----------------------------------------------------------: | :--: | :---------------------------------------------------------: | :-----: |
|**VidChapters-7M**|[**VidChapters-7M: Video Chapters at Scale**](https://arxiv.org/abs/2309.13952)|2023|[Link](https://antoyang.github.io/vidchapters.html)|NeurIPS|


##### Fine-tuning Dataset
| Name               |                            Paper                             | Date |                            Link                             |  Venue  |
| :----------------- | :----------------------------------------------------------: | :--: | :---------------------------------------------------------: | :-----: |
|**MIMIC-IT**|[**MIMIC-IT: Multi-Modal In-Context Instruction Tuning**](https://arxiv.org/abs/2306.05425)|2023|[Link](https://github.com/luodian/otter)|arXiv|


#### Video-based Large Language Models Benchmark

| Title                                                        |  Date   |                            Code                            |              Venue               |
| :----------------------------------------------------------- | :-----: | :--------------------------------------------------------: | :------------------------------: |
| [**LVBench: An Extreme Long Video Understanding Benchmark**](https://arxiv.org/abs/2406.08035) | 06/2024 |    [code](https://github.com/THUDM/LVBench)    |                -                 |

## Contributing

We welcome everyone to contribute to this repository and help improve it. You can submit pull requests to add new papers, projects, and helpful materials, or to correct any errors that you may find. Please make sure that your pull requests follow the "Title|Model|Date|Code|Venue" format. Thank you for your valuable contributions!


### 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yunlong10/Awesome-LLMs-for-Video-Understanding&type=Date)](https://star-history.com/#yunlong10/Awesome-LLMs-for-Video-Understanding&Date)

### ♥️ Contributors

Our project wouldn't be possible without the contributions of these amazing people! Thank you all for making this project better.

[Feng Kai](https://github.com/fengkaifengkai/18704466567.github.io) @ University of Rochester \



<a href="https://github.com/yunlong10/Awesome-LLMs-for-Video-Understanding/graphs/contributors">
  <img src="https://github.com/fengkaifengkai/AgentSocial" />
</a>

