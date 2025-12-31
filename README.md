This repository contains a regularly updated paper list on the **roles and mechanisms of SFT and RL** in LLM reasoning training.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License](https://img.shields.io/badge/License-Apache_2.0-green.svg)](./LICENSE) ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/AnhaoZhao-LLMer/Awesome_SFT-RLVR_Mechanism/main?logo=github&color=blue) ![Static Badge](https://img.shields.io/badge/Contributions-welcome-blue.svg?style=flat) 

## Content

- [Content](#content)
- [Keywords Convention](#keywords-convention)
- [Papers](#papers)
  - [Comparison of Mechanisms between RLVR and SFT](#comparison-of-mechanisms-between-rlvr-and-sft)
  - [The Entropy Mechanism in RLVR](#the-entropy-mechanism-in-rlvr)
  - [Are RL-Posttraining Capabilities Fundamentally Novel?](#are-rl-posttraining-capabilities-fundamentally-novel)
  - [GRPO in RLVR: Flaws and Corrections](#grpo-in-rlvr-flaws-and-corrections)
  - [Exploration–Exploitation Optimization in GRPO](#explorationexploitation-optimization-in-grpo)


## Keywords Convention

![](https://img.shields.io/badge/RLVR-blue) Abbreviation

![](https://img.shields.io/badge/ICML2025-orange) Conference

![](https://img.shields.io/badge/Entropy-green) Main Features

## Papers

### Comparison of Mechanisms between RLVR and SFT
- **On the Generalization of SFT: A Reinforcement Learning Perspective with Reward Rectification**  
  *Yongliang Wu, Yizhou Zhou, Zhou Ziheng, Yingzhe Peng, Xinyu Ye, Xinting Hu, Wenbo Zhu, Lu Qi, Ming-Hsuan Yang, Xu Yang*. [[pdf](https://arxiv.org/abs/2508.05629)], 2025.08. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Retaining by Doing: The Role of On-Policy Data in Mitigating Forgetting**  
  *Howard Chen, Noam Razin, Karthik Narasimhan, Danqi Chen*. [[pdf](https://arxiv.org/abs/2510.18874)], 2025.10. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **SFT Memorizes, RL Generalizes: A Comparative Study of Foundation Model Post-training**  
  *Tianzhe Chu, Yuexiang Zhai, Jihan Yang, Shengbang Tong, Saining Xie, Dale Schuurmans, Quoc V. Le, Sergey Levine, Yi Ma*. [[pdf](https://arxiv.org/abs/2501.17161)], 2025.01. ![](https://img.shields.io/badge/ICML2025-orange)
- **PretrainZero: Reinforcement Active Pretraining**  
  *Xingrun Xing, Zhiyuan Fan, Jie Lou, Guoqi Li, Jiajun Zhang, Debing Zhang*. [[pdf](https://arxiv.org/abs/2512.03442)], 2025.12. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **The Path Not Taken: RLVR Provably Learns Off the Principals**  
  *Hanqing Zhu, Zhenyu Zhang, Hanxian Huang, DiJia Su, Zechun Liu, Jiawei Zhao, Igor Fedorov, Hamed Pirsiavash, Zhizhou Sha, Jinwon Lee, David Z. Pan, Zhangyang Wang, Yuandong Tian, Kai Sheng Tai*. [[pdf](https://arxiv.org/abs/2511.08567)], 2025.11. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **One-Token Rollout: Guiding Supervised Fine-Tuning of LLMs with Policy Gradient**  
  *Rui Ming, Haoyuan Wu, Shoubo Hu, Zhuolun He, Bei Yu*. [[pdf](https://arxiv.org/abs/2509.26313)], 2025.09. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **On-Policy Distillation**  
  *Kevin Lu and Thinking Machines Lab*. [[pdf](https://thinkingmachines.ai/blog/on-policy-distillation/)], 2025.10. ![](https://img.shields.io/badge/Blog2025-orange)
- **SRFT: A Single-Stage Method with Supervised and Reinforcement Fine-Tuning for Reasoning**  
  *Yuqian Fu, Tinghong Chen, Jiajun Chai, Xihuai Wang, Songjun Tu, Guojun Yin, Wei Lin, Qichao Zhang, Yuanheng Zhu, Dongbin Zhao*. [[pdf](https://arxiv.org/pdf/2506.19767)], 2025.06. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Towards a Unified View of Large Language Model Post-Training**  
  *Xingtai Lv, Yuxin Zuo, Youbang Sun, Hongyi Liu, Yuntian Wei, Zhekai Chen, Lixuan He, Xuekai Zhu, Kaiyan Zhang, Bingning Wang, Ning Ding, Bowen Zhou*. [[pdf](https://arxiv.org/pdf/2509.04419)], 2025.09. ![](https://img.shields.io/badge/Arxiv2025-orange)

### The Entropy Mechanism in RLVR

- **The Entropy Mechanism of Reinforcement Learning for Reasoning Language Models**  
  *Ganqu Cui, Yuchen Zhang, Jiacheng Chen, Lifan Yuan, Zhi Wang, Yuxin Zuo, Haozhan Li, Yuchen Fan, Huayu Chen, Weize Chen, Zhiyuan Liu, Hao Peng, Lei Bai, Wanli Ouyang, Yu Cheng, Bowen Zhou, Ning Ding*. [[pdf](https://arxiv.org/abs/2505.22617)], 2025.05. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Rethinking Entropy Interventions in RLVR: An Entropy Change Perspective**  
  *Zhezheng Hao, Hong Wang, Haoyang Liu, Jian Luo, Jiarui Yu, Hande Dong, Qiang Lin, Can Wang, Jiawei Chen*. [[pdf](https://arxiv.org/abs/2510.10150)], 2025.10. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Beyond the 80/20 Rule: High-Entropy Minority Tokens Drive Effective Reinforcement Learning for LLM Reasoning**  
  *Shenzhi Wang, Le Yu, Chang Gao, Chujie Zheng, Shixuan Liu, Rui Lu, Kai Dang, Xionghui Chen, Jianxin Yang, Zhenru Zhang, Yuqiong Liu, An Yang, Andrew Zhao, Yang Yue, Shiji Song, Bowen Yu, Gao Huang, Junyang Lin*. [[pdf](https://arxiv.org/abs/2506.01939)], 2025.06. ![](https://img.shields.io/badge/NeurIPS2025-orange)
- **Quantile Advantage Estimation for Entropy-Safe Reasoning**  
  *Junkang Wu, Kexin Huang, Jiancan Wu, An Zhang, Xiang Wang, Xiangnan He*. [[pdf](https://arxiv.org/abs/2509.22611)], 2025.09. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Clip-Low Increases Entropy and Clip-High Decreases Entropy in Reinforcement Learning of Large Language Models**  
  *Jaesung R. Park, Junsu Kim, Gyeongman Kim, Jinyoung Jo, Sean Choi, Jaewoong Cho, Ernest K. Ryu*. [[pdf](https://arxiv.org/pdf/2509.26114)], 2025.09. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Decomposing the Entropy-Performance Exchange: The Missing Keys to Unlocking Effective Reinforcement Learning**  
  *Jia Deng, Jie Chen, Zhipeng Chen, Wayne Xin Zhao, Ji-Rong Wen*. [[pdf](https://arxiv.org/pdf/2508.02260)], 2025.08. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Reasoning with Exploration: An Entropy Perspective**  
  *Daixuan Cheng, Shaohan Huang, Xuekai Zhu, Bo Dai, Wayne Xin Zhao, Zhenliang Zhang, Furu Wei*. [[pdf](https://arxiv.org/pdf/2506.14758)], 2025.06. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Bottom-up Policy Optimization: Your Language Model Policy Secretly Contains Internal Policies**  
  *Yuqiao Tan, Minzheng Wang, Shizhu He, Huanxuan Liao, Chengfeng Zhao, Qiunan Lu, Tian Liang, Jun Zhao, Kang Liu*. [[pdf](https://arxiv.org/pdf/2512.19673)], 2025.12. ![](https://img.shields.io/badge/Arxiv2025-orange)
  
### Are RL-Posttraining Capabilities Fundamentally Novel?

- **Reasoning with Sampling: Your Base Model is Smarter Than You Think**  
  *Aayush Karan, Yilun Du*. [[pdf](https://arxiv.org/abs/2510.14901)], 2025.10. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model?**  
  *Yang Yue, Zhiqi Chen, Rui Lu, Andrew Zhao, Zhaokai Wang, Yang Yue, Shiji Song, Gao Huang*. [[pdf](https://arxiv.org/abs/2504.13837)], 2025.04. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **On the Interplay of Pre-Training, Mid-Training, and RL on Reasoning Language Models**  
  *Charlie Zhang, Graham Neubig, Xiang Yue*. [[pdf](https://www.arxiv.org/abs/2512.07783)], 2025.12. ![](https://img.shields.io/badge/Arxiv2025-orange)

### GRPO in RLVR: Flaws and Corrections

- **DeepSeek-V3.2: Pushing the Frontier of Open Large Language Models**  
  *DeepSeek-AI*. [[pdf](https://arxiv.org/abs/2512.02556)], 2025.12. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Training-Free Group Relative Policy Optimization**  
  *Youtu-Agent Team*. [[pdf](https://arxiv.org/pdf/2510.08191)], 2025.10. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **The Surprising Effectiveness of Negative Reinforcement in LLM Reasoning**  
  *Xinyu Zhu, Mengzhou Xia, Zhepei Wei, Wei-Lin Chen, Danqi Chen, Yu Meng*. [[pdf](https://arxiv.org/abs/2506.01347)], 2025.06. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **GPG: A Simple and Strong Reinforcement Learning Baseline for Model Reasoning**  
  *Xiangxiang Chu, Hailang Huang, Xiao Zhang, Fei Wei, Yong Wang*. [[pdf](https://arxiv.org/abs/2504.02546)], 2025.04. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Understanding R1-Zero-Like Training: A Critical Perspective**  
  *Zichen Liu, Changyu Chen, Wenjun Li, Penghui Qi, Tianyu Pang, Chao Du, Wee Sun Lee, Min Lin*. [[pdf](https://arxiv.org/abs/2503.20783)], 2025.03. ![](https://img.shields.io/badge/COLM2025-orange)
- **DAPO: An Open-Source LLM Reinforcement Learning System at Scale**  
  *Qiying Yu, Zheng Zhang, Ruofei Zhu, Yufeng Yuan, Xiaochen Zuo, Yu Yue, Weinan Dai, Tiantian Fan, Gaohong Liu, Lingjun Liu, Xin Liu, Haibin Lin, Zhiqi Lin, Bole Ma, Guangming Sheng, Yuxuan Tong, Chi Zhang, Mofan Zhang, Wang Zhang, Hang Zhu, Jinhua Zhu, Jiaze Chen, Jiangjie Chen, Chengyi Wang, Hongli Yu, Yuxuan Song, Xiangpeng Wei, Hao Zhou, Jingjing Liu, Wei-Ying Ma, Ya-Qin Zhang, Lin Yan, Mu Qiao, Yonghui Wu, Mingxuan Wang*. [[pdf](https://arxiv.org/pdf/2503.14476)], 2025.03. ![](https://img.shields.io/badge/NeurIPS2025-orange)
- **Group Sequence Policy Optimization**  
  *Chujie Zheng, Shixuan Liu, Mingze Li, Xiong-Hui Chen, Bowen Yu, Chang Gao, Kai Dang, Yuqiong Liu, Rui Men, An Yang, Jingren Zhou, Junyang Lin*. [[pdf](https://arxiv.org/pdf/2507.18071)], 2025.07. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Soft Adaptive Policy Optimization**  
  *Chang Gao, Chujie Zheng, Xiong-Hui Chen, Kai Dang, Shixuan Liu, Bowen Yu, An Yang, Shuai Bai, Jingren Zhou, Junyang Lin*. [[pdf](https://arxiv.org/pdf/2511.20347)], 2025.11. ![](https://img.shields.io/badge/Arxiv2025-orange)

### Exploration–Exploitation Optimization in GRPO

- **Learning to Reason under Off-Policy Guidance**  
  *Jianhao Yan, Yafu Li, Zican Hu, Zhi Wang, Ganqu Cui, Xiaoye Qu, Yu Cheng, Yue Zhang*. [[pdf](https://arxiv.org/abs/2504.14945)], 2025.04. ![](https://img.shields.io/badge/NeurIPS2025-orange)
- **SimKO: Simple Pass@K Policy Optimization**  
  *Ruotian Peng, Yi Ren, Zhouliang Yu, Weiyang Liu, Yandong Wen*. [[pdf](https://arxiv.org/pdf/2510.14807)], 2025.10. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **JustRL: Scaling a 1.5B LLM with a Simple RL Recipe**  
  *Bingxiang He, Zekai Qu, Zeyuan Liu, Yinghao Chen, Yuxin Zuo, Cheng Qian, Kaiyan Zhang, Weize Chen, Chaojun Xiao, Ganqu Cui, Ning Ding, Zhiyuan Liu*. [[pdf](https://arxiv.org/pdf/2512.16649)], 2025.12. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **SimKO: Simple Pass@K Policy Optimization**  
  *Ruotian Peng, Yi Ren, Zhouliang Yu, Weiyang Liu, Yandong Wen*. [[pdf](https://arxiv.org/pdf/2510.14807)], 2025.10. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **Rethinking Sample Polarity in Reinforcement Learning with Verifiable Rewards**  
  *Xinyu Tang, Yuliang Zhan, Zhixun Li, Wayne Xin Zhao, Zhenduo Zhang, Zujie Wen, Zhiqiang Zhang, Jun Zhou*. [[pdf](https://www.arxiv.org/pdf/2512.21625)], 2025.12. ![](https://img.shields.io/badge/Arxiv2025-orange)
- **TreeRL: LLM Reinforcement Learning with On-Policy Tree Search**  
  *Zhenyu Hou, Ziniu Hu, Yujiang Li, Rui Lu, Jie Tang, Yuxiao Dong*. [[pdf](https://arxiv.org/pdf/2506.11902)], 2025.06. ![](https://img.shields.io/badge/ACL2025-orange)