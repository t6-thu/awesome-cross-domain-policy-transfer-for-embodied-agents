# awesome-cross-domain-policy-transfer-for-embodied-agents ![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
This is a collection of research and review papers for cross-domain policy transfer for embodied agents. Feel free to star and fork. Original paper: [A Comprehensive Survey of Cross-Domain Policy Transfer for Embodied Agents](https://arxiv.org/abs/2402.04580).

## Maintainers
[Haoyi Niu](https://t6-thu.github.io/), Jianming Hu, Guyue Zhou, [Xianyuan Zhan](http://zhanxianyuan.xyz/). (Tsinghua University)

## Architecture of the survey
The main architecture of the survey: domain gap taxonomy, overarching insights on methodologies, and future trends.
![main](https://github.com/t6-thu/awesome-cross-domain-policy-transfer-for-embodied-agents/assets/52534633/971b2e05-fd05-415c-815a-b9c45e4de071)

## Approaches categorized by handling different domain gaps
### Cross-Appearance Policy Transfer
**Appearance gaps** arise when observations in the source domain (e.g., simulations) exhibit differences in colors, background objects, illumination conditions, and rendering textures as compared to the target domain (e.g., reality), such as variations in coarse and fine rendering or high and low resolutions.

+ [Beyond pick-and-place: Tackling robotic stacking of diverse shapes](https://openreview.net/forum?id=U0Q8CrtBJxJ)
  + Alex X. Lee, Coline Manon Devin, Yuxiang Zhou, Thomas Lampe, Konstantinos Bousmalis, Jost Tobias Springenberg, Arunkumar Byravan, Abbas Abdolmaleki, Nimrod Gileadi, David Khosid, Claudio Fantacci, Jose Enrique Chen, Akhil Raju, Rae Jeong, Michael Neunert, Antoine Laurens, Stefano Saliceti, Federico Casarini, Martin Riedmiller, Raia Hadsell, Francesco Nori. CoRL 2021.
+ [A Versatile and Efficient Reinforcement Learning Approach for Autonomous Driving](https://ml4ad.github.io/files/papers2022/A%20Versatile%20and%20Efficient%20Reinforcement%20Learning%20Approach%20for%20Autonomous%20Driving.pdf)
  + Guan Wang*, Haoyi Niu*, Desheng Zhu, Jianming Hu, Xianyuan Zhan, Guyue Zhou. NeurIPS ML4AD Workshop, 2022.
+ [Reinforcement Learning with Augmented Data](https://proceedings.neurips.cc/paper/2020/hash/e615c82aba461681ade82da2da38004a-Abstract.html)
  + Misha Laskin, Kimin Lee, Adam Stooke, Lerrel Pinto, Pieter Abbeel, Aravind Srinivas. NeurIPS 2020.
+ [Rl-cyclegan: Reinforcement learning aware simulation-to-real](https://openaccess.thecvf.com/content_CVPR_2020/html/Rao_RL-CycleGAN_Reinforcement_Learning_Aware_Simulation-to-Real_CVPR_2020_paper.html)
  + Kanishka Rao, Chris Harris, Alex Irpan, Sergey Levine, Julian Ibarz, Mohi Khansari. CVPR 2020.
+ [Learning to Drive from Simulation without Real World Labels](https://ieeexplore.ieee.org/abstract/document/8793668?casa_token=BYN1ZXV3-AsAAAAA:7mYBQd6kH4DhjcvUaXTi_buq-f7ctZxh9m48jyPRPpTdNFdSNGJh_rIsnMheQ4Q5C7_Yvs6I1Ps)
  + Alex Bewley; Jessica Rigley; Yuxuan Liu; Jeffrey Hawke; Richard Shen; Vinh-Dieu Lam; Alex Kendall. ICRA 2019.
+ [Vr-goggles for robots: Real-to-sim domain adaptation for visual control](https://ieeexplore.ieee.org/abstract/document/8620258/?casa_token=SkhJ7BaIahQAAAAA:cpFAW1Sumh1w8qp_a--BWZi8xDpSoW9HV7oyW8ZEZ1pjfGXmlXNJrq3nv9eR8wfzYFIiascGG-s)
+ Jingwei Zhang, Lei Tai, Peng Yun, Yufeng Xiong, Ming Liu, Joschka Boedecker, Wolfram Burgard. RAL 2019.
+ [Domain randomization and pyramid consistency: Simulation-to-real generalization without accessing target domain data](https://openaccess.thecvf.com/content_ICCV_2019/html/Yue_Domain_Randomization_and_Pyramid_Consistency_Simulation-to-Real_Generalization_Without_Accessing_Target_ICCV_2019_paper.html)
  + Xiangyu Yue, Yang Zhang, Sicheng Zhao, Alberto Sangiovanni-Vincentelli, Kurt Keutzer, Boqing Gong. ICCV 2019.
+ [Meta-sim: Learning to generate synthetic datasets](http://openaccess.thecvf.com/content_ICCV_2019/html/Kar_Meta-Sim_Learning_to_Generate_Synthetic_Datasets_ICCV_2019_paper.html)
  + Amlan Kar, Aayush Prakash, Ming-Yu Liu, Eric Cameracci, Justin Yuan, Matt Rusiniak, David Acuna, Antonio Torralba, Sanja Fidler. ICCV 2019.
+ [Driving Policy Transfer via Modularity and Abstraction](https://proceedings.mlr.press/v87/mueller18a.html)
  + Matthias Mueller, Alexey Dosovitskiy, Bernard Ghanem, Vladlen Koltun. CoRL 2018.
+ [Virtual to Real Reinforcement Learning for Autonomous Driving](https://arxiv.org/abs/1704.03952)
  + Xinlei Pan, Yurong You, Ziyan Wang, Cewu Lu. BMVC 2017.
+ [Unpaired image-to-image translation using cycle-consistent adversarial networks](http://openaccess.thecvf.com/content_iccv_2017/html/Zhu_Unpaired_Image-To-Image_Translation_ICCV_2017_paper.html)
  + Jun-Yan Zhu, Taesung Park, Phillip Isola, Alexei A. Efros. ICCV 2017.
+ [Domain randomization for transferring deep neural networks from simulation to the real world](https://ieeexplore.ieee.org/abstract/document/8202133/?casa_token=qmso3zouBFwAAAAA:xeoNxuL049gCHUAYVT_YdMaykxDq26eRre4i-lGRlUC0gpgxvS0ihflhomT9Pj5DaFyweDl62WI)
  + Josh Tobin; Rachel Fong; Alex Ray; Jonas Schneider; Wojciech Zaremba; Pieter Abbeel. IROS 2017.

### Cross-Viewpoint Policy Transfer
**Viewpoint gaps** arise when the configuration of sensor setups (e.g., camera position and angles, etc.) can significantly influence the downstream policy learning of embodied agents.

+ [Third-Person Visual Imitation Learning via Decoupled Hierarchical Controller](https://proceedings.neurips.cc/paper_files/paper/2019/hash/8a146f1a3da4700cbf03cdc55e2daae6-Abstract.html)
  + Pratyusha Sharma, Deepak Pathak, Abhinav Gupta. NeurIPS 2019.
+ [One-Shot Imitation from Observing Humans via Domain-Adaptive Meta-Learning](https://m.roboticsproceedings.org/rss14/p02.pdf)
  + Tianhe Yu, Chelsea Finn, Annie Xie, Sudeep Dasari, Tianhao Zhang, Pieter Abbeel, Sergey Levine. RSS 2018.
+ [Time-Contrastive Networks: Self-Supervised Learning from Video](https://ieeexplore.ieee.org/abstract/document/8462891)
  + Pierre Sermanet, Corey Lynch, Yevgen Chebotar, Jasmine Hsu, Eric Jang, Stefan Schaal, Sergey Levine. ICRA 2018.
+ [Imitation from Observation: Learning to Imitate Behaviors from Raw Video via Context Translation](https://ieeexplore.ieee.org/abstract/document/8462901?casa_token=5jtnZqwsMKUAAAAA:tsEKMW90_y4ud1YJM9tC1b4P69aC5aXeAuFobzkDYUegImzRRfYLpVZ97_0qSJoNJAOiLpNRTy8)
  + YuXuan Liu; Abhishek Gupta; Pieter Abbeel; Sergey Levine. ICRA 2018.
+ [Sim2Real Viewpoint Invariant Visual Servoing by Recurrent Control](https://openaccess.thecvf.com/content_cvpr_2018/html/Sadeghi_Sim2Real_Viewpoint_Invariant_CVPR_2018_paper.html)
  + Fereshteh Sadeghi, Alexander Toshev, Eric Jang, Sergey Levine. CVPR 2018.
+ [Third Person Imitation Learning](https://openreview.net/forum?id=B16dGcqlx)
  + Bradly C Stadie, Pieter Abbeel, Ilya Sutskever. ICLR 2017.

### Cross-Dynamics Policy Transfer
**Dynamics gaps** occur when interactions between embodiments and their deploying environments, or interactions among different parts of the embodiment itself, follow different transitional dynamics, such as stiffness, gear dead zones of embodiments, body mass, and friction.


+ [State-Only Imitation Learning for Dexterous Manipulation](https://ieeexplore.ieee.org/abstract/document/9636557?casa_token=qBnOIzaMocEAAAAA:xgIy7mcMAl8RxPicPGvXzhAsJTDQX1LA0EqQacvHEo2Mabs_69i2rTfGxDV86ROn-Y8vBIn0beM)
  + Ilija Radosavovic; Xiaolong Wang; Lerrel Pinto; Jitendra Malik. IROS 2021.
+ [Off-Dynamics Reinforcement Learning: Training for Transfer with Domain Classifiers](https://openreview.net/forum?id=eqBwg3AcIAK)
  + Benjamin Eysenbach, Shreyas Chaudhari, Swapnil Asawa, Sergey Levine, Ruslan Salakhutdinov. ICLR 2021.
+ [An Imitation from Observation Approach to Transfer Learning with Dynamics Mismatch](https://proceedings.neurips.cc/paper_files/paper/2020/hash/28f248e9279ac845995c4e9f8af35c2b-Abstract.html)
  + Siddharth Desai, Ishan Durugkar, Haresh Karnan, Garrett Warnell, Josiah Hanna, Peter Stone. NeurIPS 2020.
+ [Offline Imitation Learning with a Misspecified Simulator](https://proceedings.neurips.cc/paper/2020/hash/60cb558c40e4f18479664069d9642d5a-Abstract.html)
  + Shengyi Jiang, Jingcheng Pang, Yang Yu. NeurIPS 2020.
+ [Active Domain Randomization](https://proceedings.mlr.press/v100/mehta20a.html)
  + Bhairav Mehta, Manfred Diaz, Florian Golemo, Christopher J. Pal, Liam Paull. CoRL 2020.
+ [State-only Imitation with Transition Dynamics Mismatch](https://openreview.net/forum?id=HJgLLyrYwB)
  + Tanmay Gangwani, Jian Peng. ICLR 2020.
+ [State Alignment-based Imitation Learning](https://openreview.net/forum?id=rylrdxHFDr)
  + Fangchen Liu, Zhan Ling, Tongzhou Mu, Hao Su. ICLR 2020.
+ [Learning dexterous in-hand manipulation](https://dl.acm.org/doi/abs/10.1177/0278364919887447)
  + Marcin Andrychowicz, Bowen Baker, Maciek Chociej, Rafal Jozefowicz, Bob McGrew, Jakub Pachocki, Arthur Petron, Matthias Plappert, Glenn Powell, Alex Ray, Jonas Schneider, Szymon Sidor, Josh Tobin, Peter Welinder, Lilian Weng, Wojciech Zaremba. IJRR, 2020.
+ [BayesSim: adaptive domain randomization via probabilistic inference for robotics simulators](https://roboticsproceedings.org/rss15/p29.pdf)
  + Fabio Ramos, Rafael Carvalhaes Possas, Dieter Fox. RSS 2019.
+ [How to pick the domain randomization parameters for sim-to-real transfer of reinforcement learning policies?](https://arxiv.org/abs/1903.11774)
  + Quan Vuong, Sharad Vikram, Hao Su, Sicun Gao, Henrik I. Christensen. Arxiv, 2019.
+ [Sim-to-Real Transfer of Robotic Control with Dynamics Randomization](https://ieeexplore.ieee.org/abstract/document/8460528?casa_token=MGinWlLWo_4AAAAA:ADFVzywGfFm2JUEfBOgkRx-Bg4U--s133C--1AhRrLn_e2sIG5B02BmFcvWlzZpD76XQA8ewLao)
  + Xue Bin Peng; Marcin Andrychowicz; Wojciech Zaremba; Pieter Abbeel. ICRA 2018.
+ [Grounded Action Transformation for Robot Learning in Simulation](https://ojs.aaai.org/index.php/AAAI/article/view/11044)
  + Josiah Hanna, Peter Stone. AAAI 2017.
+ [EPOpt: Learning Robust Neural Network Policies Using Model Ensembles](https://openreview.net/forum?id=SyWvgP5el)
  + Aravind Rajeswaran, Sarvjeet Ghotra, Balaraman Ravindran, Sergey Levine. ICLR 2017.
+ [Preparing for the Unknown: Learning a Universal Policy with Online System Identification](https://arxiv.org/abs/1702.02453)
  + Wenhao Yu, Jie Tan, C. Karen Liu, Greg Turk. arXiv 2017.
+ [Simulation-based design of dynamic controllers for humanoid balancing](https://ieeexplore.ieee.org/abstract/document/7759424?casa_token=gYQxUej--YsAAAAA:UKyns0UxIU1jLYWDO7Gx_T0YUOQmJTik5EltC6c50RoSdbmV21KE_NAAzFV08sIVkO0xRjEM-fM)
  + Jie Tan; Zhaoming Xie; Byron Boots; C. Karen Liu. IROS 2016.
+ [Transfer from Simulation to Real World through Learning Deep Inverse Dynamics Model](https://arxiv.org/abs/1610.03518)
  + Paul Christiano, Zain Shah, Igor Mordatch, Jonas Schneider, Trevor Blackwell, Joshua Tobin, Pieter Abbeel, Wojciech Zaremba. arXiv, 2016.
+ [Physically consistent state estimation and system identification for contacts](https://ieeexplore.ieee.org/abstract/document/7363481?casa_token=qJHU24ygihsAAAAA:V2eUbCLISEFHfX9NMCmIac9IdeySVQB072RyOyYJkAJQB1Dcaju234-xdmfKBi_xoI3_8rrQMNs)
  + Svetoslav Kolev, Emanuel Todorov. Humanoids 2015.
# In Progress...

### Cross-Morphology Policy Transfer
**Morphology gaps** arise when target embodiments exhibit different morphological designs compared to the source domain agents, e.g., variations in joint types, module shapes, and lengths, which may ultimately lead to a dynamics mismatch. **Morphology gaps** may also encompass variations in the dimensions and semantic meanings of state and action spaces, such as the number of observational sensors, limbs, and end effectors.

### Cross-Multi-Gap Policy Transfer
In many complex tasks, we might simultaneously encounter multiple types of domain gaps due to substantially different embodiments and deployed environments. 

## Citations
If the insights, categorizations, analyses and encapsulations in this survey paper/github collection are helpful with your project development, please cite the following paper:
```
@article{niu2024comprehensive,
  title={A Comprehensive Survey of Cross-Domain Policy Transfer for Embodied Agents},
  author={Niu, Haoyi and Hu, Jianming and Zhou, Guyue and Zhan, Xianyuan},
  journal={arXiv preprint arXiv:2402.04580},
  year={2024}
}
```
