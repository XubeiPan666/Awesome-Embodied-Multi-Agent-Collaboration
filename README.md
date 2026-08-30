

<h1 align="center">Awesome-Embodied-Multi-Agent-Collaboration</h1>
<p align="center">
    <b> Curated collection of papers and resources on Multi-Agent Collaboration.</b>
</p>


[![Awesome](https://awesome.re/badge.svg)](https://github.com/XubeiPan666/Awesome-Embodied-Multi-Agent-Collaboration)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![Last Commit](https://img.shields.io/github/last-commit/XubeiPan666/Awesome-Embodied-Multi-Agent-Collaboration?color=green)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-red)
![GitHub Repo stars](https://img.shields.io/github/stars/XubeiPan666/Awesome-Embodied-Multi-Agent-Collaboration?style=social)


> 🧭 Exploring Embodied AI and Multi-Agent Collaboration? We hope this collection proves useful in your journey. If you'd like to support the project, feel free to ⭐️ the repo and share it with your peers. Contributions are warmly welcome!

---

## 🔥 News

> 📢 This list is **actively maintained**, and community contributions are always appreciated!  
> Feel free to [open a pull request](https://github.com/XubeiPan666/Awesome-Embodied-Multi-Agent-Collaboration/pulls) if you find any relevant papers.

- 🎉 `2026-05`: **Repository launched to curate a comprehensive list of Embodied Multi-Agent Collaboration.**

---
- [🌟 Introduction](#-introduction)
- [📜 Papers](#-papers)
  - [🤖 Robotic Foundation Models & VLA](#-robotic-foundation-models--vla)
  - [🤝 Multi-Agent Collaboration Frameworks](#-multi-agent-collaboration-frameworks)
  - [🎮 Multi-Agent Reinforcement Learning](#-multi-agent-reinforcement-learning)
  - [📋 Task Planning & Coordination](#-task-planning--coordination)
  - [🦾 Manipulation & Dexterity](#-manipulation--dexterity)
  - [🌍 World Models & Generation](#-world-models--generation)

---
## 🌟 Introduction
This repository offers a **comprehensive and up-to-date collection** of research papers on **Embodied Multi-Agent Collaboration**.

> As embodied agents are increasingly integrated into complex real-world applications, the synergy of Multi-Agent Collaboration becomes essential, enabling groups of robots to coordinate their actions and perceptions to achieve collective goals far beyond the capability of any individual agent.


Whether you're a researcher, developer, or enthusiast, this is your go-to hub for exploring Embodied Multi-Agent Collaboration.

---
## 📜 Papers

### 🤖 Robotic Foundation Models & VLA
1. **Harness VLA: Steering Frozen VLAs into Reliable Manipulation Primitives via Memory-Guided Agents.**  
   *Yixian Zhang, Huanming Zhang, Feng Gao, Xiao Li, Zhihao Liu, Chunyang Zhu, Jiaxing Qiu, Yuchen Yan, Jiyuan Liu, Wenhao Tang, Zhengru Fang, Yi Nie, Changxu Wei, Yu Wang, Wenbo Ding, Chao Yu.* [[abs](https://arxiv.org/abs/2607.08448)] [[project](https://harnessvla.github.io/)] [[code](https://github.com/RLinf/RPent)], Arxiv 2026.07

2. **Qwen-RobotManip Technical Report: Alignment Unlocks Scale for Robotic Manipulation Foundation Models.**  
   *Qwen Team.* [[abs](https://arxiv.org/abs/2606.17846)] [[project](https://qwen.ai/blog?id=qwen-robotmanip)] [[code](https://github.com/QwenLM/Qwen-RobotManip)], Arxiv 2026.06

3. **T-Rex: Tactile-Reactive Dexterous Manipulation.**  
   *Dantong Niu, Zhuoyang Liu, Zekai Wang, Boning Shao, Zhao-Heng Yin, Anirudh Pai, et al.* [[abs](https://arxiv.org/abs/2606.17055)] [[project](https://tactile-rex.github.io/)] [[code](https://github.com/ZhuoyangLiu2005/T-Rex)], Arxiv 2026.06

4. **π0.7: a Steerable Generalist Robotic Foundation Model with Emergent Capabilities.**  
   *Physical Intelligence (Bo Ai, Ali Amin, Raichelle Aniceto, et al.).* [[abs](https://arxiv.org/abs/2604.15483)] [[project](https://www.pi.website/blog/pi07)] [[code](https://github.com/Physical-Intelligence/openpi)], Arxiv 2026.04

5. **TCoT: Trajectory Chain-of-Thoughts for Robotic Manipulation with Failure Recovery in Vision-Language-Action Model.**  
   *Xiang Li, Ya-Li Li, Yuan Wang, Huaqiang Wang, Shengjin Wang.* [[abs](https://ojs.aaai.org/index.php/AAAI/article/view/37577)] [[code](https://github.com/Serenos/TCoT)], AAAI 2026

6. **Adaptive Action Chunking at Inference-time for Vision-Language-Action Models.**  
   *Yuanchang Liang, Xiaobo Wang, Kai Wang, Shuo Wang, Xiaojiang Peng, Haoyu Chen, David Kim Huat Chua, Prahlad Vadakkepat.* [[abs](https://arxiv.org/abs/2604.04161)] [[project](https://lance-lot.github.io/adaptive-chunking.github.io/)], CVPR 2026

7. **Robotic Manipulation is Vision-to-Geometry Mapping (f(v) -> G): Vision-Geometry Backbones over Language and Video Models.**  
   *Zijian Song, Qichang Li, Jiawei Zhou, Zhenlong Yuan, Tianshui Chen, Liang Lin, Guangrun Wang.* [[abs](https://arxiv.org/abs/2604.12908)], Arxiv 2026.04

8. **Stable Language Guidance for Vision-Language-Action Models.**  
   *Zhihao Zhan, Yuhao Chen, Jiaying Zhou, Qinhan Lv, Hao Liu, Keze Wang, Liang Lin, Guangrun Wang.* [[abs](https://arxiv.org/abs/2601.04052)], Arxiv 2026.01

9. **Towards Generalizable Robotic Manipulation in Dynamic Environments.**  
   *Heng Fang, Shangru Li, Shuhan Wang, Xuanyang Xi, Dingkang Liang, Xiang Bai.* [[abs](https://arxiv.org/abs/2603.15620)] [[project](https://h-embodvis.github.io/DOMINO/)] [[code](https://github.com/H-EmbodVis/DOMINO)], ECCV 2026

10. **VLA Models Are More Generalizable Than You Think: Revisiting Physical and Spatial Modeling.**  
   *Weiqi Li, Quande Zhang, Ruifeng Zhai, Liang Lin, Guangrun Wang.* [[abs](https://arxiv.org/abs/2512.02902)], Arxiv 2025.12

11. **π0.5: a Vision-Language-Action Model with Open-World Generalization.**  
   *Kevin Black, Noah Brown, James Darpinian, Karan Dhabalia, Danny Driess, Adnan Esmail, Michael Equi, Chelsea Finn, Niccolo Fusai, Manuel Y. Galliker, Dibya Ghosh, Lachy Groom, Karol Hausman, Brian Ichter, Szymon Jakubczak, Tim Jones, Liyiming Ke, Devin LeBlanc, Sergey Levine, Adrian Li-Bell, Mohith Mothukuri, Suraj Nair, Karl Pertsch, Allen Z. Ren, Lucy Xiaoyang Shi, Laura Smith, Jost Tobias Springenberg, Kyle Stachowicz, James Tanner, Quan Vuong, Homer Walke, Anna Walling, Haohuan Wang, Lili Yu, Ury Zhilinsky.* [[abs](https://arxiv.org/abs/2504.16054)] [[project](https://pi.website/blog/pi05)] [[code](https://github.com/Physical-Intelligence/openpi)], CoRL 2025

12. **π0: A Vision-Language-Action Flow Model for General Robot Control.**  
   *Kevin Black, Noah Brown, Danny Driess, Adnan Esmail, Michael Equi, Chelsea Finn, Niccolo Fusai, Lachy Groom, Karol Hausman, Brian Ichter, Szymon Jakubczak, Tim Jones, Liyiming Ke, Sergey Levine, Adrian Li-Bell, Mohith Mothukuri, Suraj Nair, Karl Pertsch, Lucy Xiaoyang Shi, James Tanner, Quan Vuong, Anna Walling, Haohuan Wang, Ury Zhilinsky.* [[abs](https://arxiv.org/abs/2410.24164)] [[project](https://physicalintelligence.company/blog/pi0)] [[code](https://github.com/Physical-Intelligence/openpi)], Arxiv 2024.10

13. **SMART-LLM: Smart Multi-Agent Robot Task Planning using Large Language Models.**  
   *Shyam Sundar Kannan, Vishnunandan L. N. Venkatesh, Byung-Cheol Min.* [[abs](https://arxiv.org/abs/2309.10062)] [[code](https://github.com/SMARTlab-Purdue/SMART-LLM)], IROS 2024


### 🤝 Multi-Agent Collaboration Frameworks
1. **A Closed-Loop Multi-Agent Framework for Robust Multi-Robot Manipulation.**  
   *Yi-Xiang He, Lan Wei, Haoming Cen, Jian-Jian Jiang, Zhuohao Li, Guanxing Lu, Yihan Yang, Dandan Zhang, Wei-Shi Zheng.* [[abs](https://arxiv.org/abs/2607.06990)], RSS 2026

2. **LLawCo: Learning Laws of Cooperation for Modeling Embodied Multi-Agent Behavior.**  
   *Qinhong Zhou, Chuang Gan, Anoop Cherian.* [[abs](https://arxiv.org/abs/2606.28182)] [[project](https://merl.com/research/highlights/LLawCo)] [[code](https://github.com/merlresearch/llawco)], ICML 2026

3. **Distilling Collaborative Dynamics into Latent Space for Implicit Coordination in Decentralized Multi-Agent Manipulation.**  
   *Chanyoung Park, Minsung Yoon, Andrew Jeong, Sung-eui Yoon.* [[abs](https://arxiv.org/abs/2606.22982)] [[project](https://cosdeneb.github.io/cls-dp/)], IROS 2026

4. **CHORUS: Decentralized Multi-Embodiment Collaboration with One VLA Policy.**  
   *Ria Doshi, Tian Gao, Annie Chen, Chelsea Finn, Jeannette Bohg.* [[abs](https://arxiv.org/abs/2606.12352)] [[project](https://chorus-model.github.io)], Arxiv 2026.06

5. **Sentinel: Embodied Cooperative Spatial Reasoning and Planning.**  
   *Xiangye Lin, Hongxin Zhang, Ruxi Deng, Qinhong Zhou, Chuang Gan.* [[abs](https://arxiv.org/abs/2605.26239)] [[code](https://github.com/UMass-Embodied-AGI/Sentinel)], Arxiv 2026.05

6. **Seeing Together: Multi-Robot Cooperative Egocentric Spatial Reasoning with Multimodal Large Language Models.**  
   *Kunyu Peng, Zhikun Zhou, Kailun Yang, Di Wen, Yufan Chen, Junwei Zheng, Luc Van Gool.* [[abs](https://arxiv.org/abs/2605.18431)] [[code](https://github.com/KPeng9510/seeing-together)], Arxiv 2026.05

7. **CoEnv: Driving Embodied Multi-Agent Collaboration via Compositional Environment.**  
   *Li Kang, Yutao Fan, Rui Li, Heng Zhou, Yiran Qin, Zhemeng Zhang, Songtao Huang, Xiufeng Song, Zaibin Zhang, Bruno N.Y. Chen, Zhenfei Yin, Dongzhan Zhou, Wangmeng Zuo, Lei Bai.* [[abs](https://arxiv.org/abs/2604.05484)] [[code](https://github.com/MARS-EAI/CoEnv)], Arxiv 2026.04

8. **RoboOS-NeXT: A Unified Memory-based Framework for Lifelong, Scalable, and Robust Multi-Robot Collaboration.**  
   *Huajie Tan, Cheng Chi, Xiansheng Chen, Yuheng Ji, Zhongxia Zhao, Xiaoshuai Hao, Yaoxu Lyu, Mingyu Cao, Junkai Zhao, Huaihai Lyu, Enshen Zhou, Ning Chen, Yankai Fu, Cheng Peng, Wei Guo, Dong Liang, Zhuo Chen, Mengsi Lyu, Chenrui He, Yulong Ao, Yonghua Lin, Pengwei Wang, Zhongyuan Wang, Shanghang Zhang.* [[abs](https://arxiv.org/abs/2510.26536)] [[code](https://github.com/FlagOpen/RoboOS)], Arxiv 2025.10

9. **Thought Communication in Multiagent Collaboration.**  
   *Yujia Zheng, Zhuokai Zhao, Zijian Li, Yaqi Xie, Mingze Gao, Lizhu Zhang, Kun Zhang.* [[abs](https://arxiv.org/abs/2510.20733)], NeurIPS 2025

10. **RoboOS: A Hierarchical Embodied Framework for Cross-Embodiment and Multi-Agent Collaboration.**  
   *Huajie Tan, Xiaoshuai Hao, Cheng Chi, Minglan Lin, Yaoxu Lyu, Mingyu Cao, Dong Liang, Zhuo Chen, Mengsi Lyu, Cheng Peng, Chenrui He, Yulong Ao, Yonghua Lin, Pengwei Wang, Zhongyuan Wang, Shanghang Zhang.* [[abs](https://arxiv.org/abs/2505.03673)] [[code](https://github.com/FlagOpen/RoboOS)], Arxiv 2025.05

11. **RoboFactory: Exploring Embodied Agent Collaboration with Compositional Constraints.**  
   *Yiran Qin, Li Kang, Xiufeng Song, Zhenfei Yin, Xiaohong Liu, Xihui Liu, Ruimao Zhang, Lei Bai.* [[abs](https://arxiv.org/abs/2503.16408)] [[code](https://github.com/MARS-EAI/RoboFactory)], ICCV 2025

12. **Building Cooperative Embodied Agents Modularly with Large Language Models.**  
    *Hongxin Zhang, Weihua Du, Jiaming Shan, Qinhong Zhou, Yilun Du, Joshua B. Tenenbaum, Tianmin Shu, Chuang Gan.* [[abs](https://arxiv.org/abs/2307.02485)] [[project](https://umass-embodied-agi.github.io/CoELA/)] [[code](https://github.com/UMass-Embodied-AGI/CoELA)], ICLR 2024


### 🎮 Multi-Agent Reinforcement Learning
1. **Ego to World: Collaborative Spatial Reasoning in Embodied Systems via Reinforcement Learning.**  
   *Heng Zhou, Li Kang, Yiran Qin, Xiufeng Song, Ao Yu, Zilu Zhang, Haoming Song, Kaixin Xu, Yuchen Fan, Dongzhan Zhou, Xiaohong Liu, Ruimao Zhang, Philip Torr, Lei Bai, Zhenfei Yin.* [[abs](https://arxiv.org/abs/2603.14811)], Arxiv 2026.03

2. **Learning to Deliberate: Meta-policy Collaboration for Agentic LLMs with Multi-agent Reinforcement Learning.**  
   *Wei Yang, Jesse Thomason.* [[abs](https://arxiv.org/abs/2509.03817)], AAAI 2026

3. **GauDP: Reinventing Multi-Agent Collaboration through Gaussian-Image Synergy in Diffusion Policies.**  
   *Ziye Wang, Li Kang, Yiran Qin, Jiahua Ma, Zhanglin Peng, Lei Bai, Ruimao Zhang.* [[abs](https://arxiv.org/abs/2511.00998)] [[code](https://github.com/Ziyeeee/Policy-Lightning)], NeurIPS 2025

4. **VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning.**  
   *Li Kang, Xiufeng Song, Heng Zhou, Yiran Qin, Jie Yang, Xiaohong Liu, Philip Torr, Lei Bai, Zhenfei Yin.* [[abs](https://arxiv.org/abs/2506.09049)] [[code](https://github.com/MARS-EAI/VIKI-R)], NeurIPS 2025


### 📋 Task Planning & Coordination
1. **From Assumptions to Actions: Turning LLM Reasoning into Uncertainty-Aware Planning for Embodied Agents.**  
   *SeungWon Seo, SooBin Lim, Seongrae Noh, Haneul Kim, HyeongYeop Kang.* [[abs](https://arxiv.org/abs/2602.04326)] [[code](https://github.com/ssw03270/PCE_ICLR-26)], ICLR 2026

2. **Grounding Generative Planners in Verifiable Logic: A Hybrid Architecture for Trustworthy Embodied AI.**  
   *Feiyu Wu, Xu Zheng, Yue Qu, Zhuocheng Wang, Zicheng Feng, Hui Li.* [[abs](https://arxiv.org/abs/2602.08373)] [[project](https://sn0wm1an.github.io/)] [[code](https://github.com/Sn0wm1an/VIRF)], ICLR 2026

3. **RoboSafe: Safeguarding Embodied Agents via Executable Safety Logic.**  
   *Le Wang, Zonghao Ying, Xiao Yang, Quanchen Zou, Zhenfei Yin, Tianlin Li, Jian Yang, Yaodong Yang, Aishan Liu, Xianglong Liu.* [[abs](https://arxiv.org/abs/2512.21220)], Arxiv 2025.12

4. **ELHPlan: Efficient Long-Horizon Task Planning for Multi-Agent Collaboration.**  
   *Shaobin Ling, Yun Wang, Chenyou Fan, Tin Lun Lam, Junjie Hu.* [[abs](https://arxiv.org/abs/2509.24230)], Arxiv 2025.09

5. **Open-World Skill Discovery from Unsegmented Demonstration Videos.**  
   *Jingwen Deng, Zihao Wang, Shaofei Cai, Anji Liu, Yitao Liang.* [[abs](https://arxiv.org/abs/2503.10684)] [[project](https://craftjarvis.github.io/SkillDiscovery/)] [[code](https://github.com/CraftJarvis/SkillDiscovery)], ICCV 2025

6. **Collaborative Tree Search for Enhancing Embodied Multi-Agent Collaboration.**  
   *Lizheng Zu, Lin Lin, Song Fu, Na Zhao, Pan Zhou.* [[abs](https://openaccess.thecvf.com/content/CVPR2025/html/Zu_Collaborative_Tree_Search_for_Enhancing_Embodied_Multi-Agent_Collaboration_CVPR_2025_paper.html)] [[code](https://github.com/zulihit/CoTS)], CVPR 2025


### 🦾 Manipulation & Dexterity
1. **ASPIRE: Agentic Skill Programming through Iterative Robot Exploration.**  
   *Runyu Lu, Yubo Wu, Ethan Kou, Letian Fu, Wenli Xiao, Ajay Mandlekar, Yinzhen Xu, Guanya Shi, Ken Goldberg, Ang Chen, Mosharaf Chowdhury, Yuke Zhu, Linxi "Jim" Fan, Guanzhi Wang.* [[abs](https://arxiv.org/abs/2607.00272)] [[project](https://research.nvidia.com/labs/gear/aspire/)] [[code](https://github.com/NVlabs/ASPIRE)], Arxiv 2026.07

2. **Co-VLA: Coordination-Aware Structured Action Modeling for Dual-Arm Vision-Language-Action Systems.**  
   *Yandong Wang, Jiaqian Yu, Xiongfeng Peng, Lu Xu, Yamin Mao, Weiming Li, Jaewook Yoo, Dongwook Lee, Daehyun Ji, Mingbo Zhao, Chao Zhang.* [[abs](https://arxiv.org/abs/2606.20285)], Arxiv 2026.06

3. **Bimanual Robot Manipulation via Multi-Agent In-Context Learning.**  
   *Alessio Palma, Indro Spinelli, Vignesh Prasad, Luca Scofano, Yufeng Jin, Georgia Chalvatzaki, Fabio Galasso.* [[abs](https://arxiv.org/abs/2604.20348)], Arxiv 2026.04

4. **EnergyAction: Unimanual to Bimanual Composition with Energy-Based Models.**  
   *Mingchen Song, Xiang Deng, Jie Wei, Dongmei Jiang, Liqiang Nie, Weili Guan.* [[abs](https://arxiv.org/abs/2603.20236)] [[code](https://github.com/codeshop715/EnergyAction)], CVPR 2026

5. **ADM-DP: Adaptive Dynamic Modality Diffusion Policy through Vision-Tactile-Graph Fusion for Multi-Agent Manipulation.**  
   *Enyi Wang, Wen Fan, Dandan Zhang.* [[abs](https://arxiv.org/abs/2602.21622)], ICRA 2026

6. **TwinVLA: Data-Efficient Bimanual Manipulation with Twin Single-Arm Vision-Language-Action Models.**  
   *Hokyun Im, Euijin Jeong, Andrey Kolobov, Jianlong Fu, Youngwoon Lee.* [[abs](https://arxiv.org/abs/2511.05275)] [[project](https://jellyho.github.io/TwinVLA/)] [[code](https://github.com/jellyho/TwinVLA)], ICLR 2026

7. **Fabrica: Dual-Arm Assembly of General Multi-Part Objects via Integrated Planning and Learning.**  
   *Yunsheng Tian, Joshua Jacob, Yijiang Huang, Jialiang Zhao, Edward Gu, Pingchuan Ma, Annan Zhang, Farhad Javid, Branden Romero, Sachin Chitta, Shinjiro Sueda, Hui Li, Wojciech Matusik.* [[abs](https://arxiv.org/abs/2506.05168)] [[project](https://fabrica.csail.mit.edu)] [[code](https://github.com/yunshengtian/Fabrica)], CoRL 2025 (Best Paper Award)

8. **AnyBimanual: Transferring Unimanual Policy for General Bimanual Manipulation.**  
   *Guanxing Lu, Tengbo Yu, Haoyuan Deng, Season Si Chen, Yansong Tang, Ziwei Wang.* [[abs](https://arxiv.org/abs/2412.06779)] [[project](https://anybimanual.github.io)] [[code](https://github.com/Tengbo-Yu/AnyBimanual)], ICCV 2025


### 🌍 World Models & Generation
1. **Qwen-RobotWorld Technical Report: Unifying Embodied World Modeling through Language-Conditioned Video Generation.**  
   *Qwen Team.* [[abs](https://arxiv.org/abs/2606.17030)], Arxiv 2026.06

2. **Test-Time Mixture of World Models for Embodied Agents in Dynamic Environments.**  
   *Jinwoo Jang, Minjong Yoo, Sihyung Yoon, Honguk Woo.* [[abs](https://arxiv.org/abs/2601.22647)] [[code](https://github.com/doldam0/tmow)], ICLR 2026

3. **Efficient-WAM: A 1B-Parameter World-Action Model with Low-Cost Future Imagination.**  
   *Jiajun Li, Tiecheng Guo, Yifan Ye, Rongyu Zhang, Xiaowei Chi, Qianpu Sun, Ying Li, Yunfan Lou, Yan Huang, Zhihe Lu, Meng Guo, Shanghang Zhang.* [[abs](https://arxiv.org/abs/2606.10040)] [[code](https://github.com/jiajun613/Efficient-WAM)], Arxiv 2026.06

4. **Gamma-World: Generative Multi-Agent World Modeling Beyond Two Players.**  
   *Fangfu Liu, Kai He, Tianchang Shen, Tianshi Cao, Sanja Fidler, Yueqi Duan, Jun Gao, Igor Gilitschenski, Zian Wang, Xuanchi Ren.* [[abs](https://arxiv.org/abs/2605.28816)] [[project](https://research.nvidia.com/labs/toronto-ai/gamma-world/)] [[code](https://github.com/nv-tlabs/Gamma-World)], Arxiv 2026.05

5. **VGGT-Ω: Scaling Feed-Forward Reconstruction with Register Attention.**  
   *Jianyuan Wang, Minghao Chen, Shangzhan Zhang, Nikita Karaev, Johannes Schonberger, Patrick Labatut, Piotr Bojanowski, David Novotny, Andrea Vedaldi, Christian Rupprecht.* [[abs](https://arxiv.org/abs/2605.15195)] [[project](https://vggt-omega.github.io)] [[code](https://github.com/facebookresearch/vggt)], CVPR 2026 (Oral)

6. **MultiWorld: Scalable Multi-Agent Multi-View Video World Models.**  
   *Haoyu Wu, Jiwen Yu, Yingtian Zou, Xihui Liu.* [[abs](https://arxiv.org/abs/2507.18235)] [[project](https://cintellifusion.github.io/MultiWorld/)] [[code](https://github.com/CIntellifusion/MultiWorld)], Arxiv 2025.07

7. **Empowering Multi-Robot Cooperation via Sequential World Models.**  
   *Zijie Zhao, Honglei Guo, Shengqian Chen, Kaixuan Xu, Bo Jiang, Yuanheng Zhu, Dongbin Zhao.* [[abs](https://arxiv.org/abs/2509.13095)] [[code](https://github.com/zhaozijie2022/seqwm)], ICLR 2026

8. **VGGT: Visual Geometry Grounded Transformer.**  
   *Jianyuan Wang, Minghao Chen, Nikita Karaev, Andrea Vedaldi, Christian Rupprecht, David Novotny.* [[abs](https://arxiv.org/abs/2503.11651)] [[project](https://huggingface.co/spaces/facebook/vggt)] [[code](https://github.com/facebookresearch/vggt)], CVPR 2025 (Best Paper Award)

    
---
## 🎉 Contributing
⭐ Help us grow this repository! If you know any valuable works we’ve missed, don’t hesitate to contribute — every suggestion makes a difference!

We welcome and appreciate all contributions! Here’s how you can help:

- 📄 **Add or Update a Paper**  
  Contribute by adding a new paper or improving details of an existing one. Please consider the most appropriate category for the work.

- ✍️ **Use Consistent Formatting**  
  Follow the format of the existing entries to maintain clarity and consistency across the list.

- 🔗 **Include Abstract Link**  
  If the paper is from arXiv, use the `/abs/` link format for the abstract (e.g., `https://arxiv.org/abs/xxxx.xxxxx`).

- 💡 **Explain Your Edit (Optional but Helpful)**  
  A short note on why you think the paper deserves to be added or updated is appreciated and helps maintainers process your PR faster.

> **✅ Don't worry about getting everything perfect!**  
> Minor mistakes are totally fine — we’ll help fix them. What matters most is your contribution. Let's highlight your awesome work together!

---
## Acknowledgement
Thanks for the wonderful projects: [Awesome-LLM-Empathy](https://github.com/JhCircle/Awesome-LLM-Empathy) and [Awesome-Affordance-Learning](https://github.com/hq-King/Awesome-Affordance-Learning). This project is built upon them.

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Contributors

<a href="https://github.com/XubeiPan666/Awesome-Embodied-Multi-Agent-Collaboration/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=XubeiPan666/Awesome-Embodied-Multi-Agent-Collaboration" />
</a>
