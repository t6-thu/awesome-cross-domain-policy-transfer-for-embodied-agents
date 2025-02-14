# awesome-cross-domain-policy-transfer-for-embodied-agents ![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
This is a collection of research and review papers for cross-domain policy transfer for embodied agents. Feel free to star and fork. Original paper: [A Comprehensive Survey of Cross-Domain Policy Transfer for Embodied Agents](https://arxiv.org/abs/2402.04580), IJCAI 2024.

## Maintainers
[Haoyi Niu](https://t6-thu.github.io/), Jianming Hu, Guyue Zhou, [Xianyuan Zhan](http://zhanxianyuan.xyz/). (Tsinghua University)

## Architecture of the survey
The main architecture of the survey: domain gap taxonomy, overarching insights on methodologies, and future trends.
![main](https://github.com/t6-thu/awesome-cross-domain-policy-transfer-for-embodied-agents/assets/52534633/971b2e05-fd05-415c-815a-b9c45e4de071)

## Approaches categorized by handling different domain gaps
### Cross-Appearance Policy Transfer
**Appearance gaps** arise when observations in the source domain (e.g., simulations) exhibit differences in colors, background objects, illumination conditions, and rendering textures as compared to the target domain (e.g., reality), such as variations in coarse and fine rendering or high and low resolutions.

+ [Sim-to-Real Transfer via 3D Feature Fields for Vision-and-Language Navigation](https://openreview.net/forum?id=VFs1vbQnYN)
  + Zihan Wang, Xiangyang Li, Jiahao Yang, Yeqi Liu, Shuqiang Jiang. CoRL 2024.
+ [Get a Grip: Multi-Finger Grasp Evaluation at Scale Enables Robust Sim-to-Real Transfer](https://openreview.net/forum?id=1jc2zA5Z6J)
  + Tyler Ga Wei Lum, Albert H. Li, Preston Culbertson, Krishnan Srinivasan, Aaron Ames, Mac Schwager, Jeannette Bohg. CoRL 2024.
+ [Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection](https://openreview.net/forum?id=uJBMZ6S02T)
  + Jia-Feng Cai, Zibo Chen, Xiao-Ming Wu, Jian-Jian Jiang, Yi-Lin Wei, Wei-Shi Zheng. CoRL 2024.
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

+ [UniDrive: Towards Universal Driving Perception Across Camera Configurations](https://wzzheng.net/UniDrive/)
  + Ye Li, Wenzhao Zheng, Xiaonan Huang, Kurt Keutzer.
+ [Learning to Manipulate Anywhere: A Visual Generalizable Framework For Reinforcement Learning](https://openreview.net/forum?id=jart4nhCQr)
  + Zhecheng Yuan, Tianming Wei, Shuiqi Cheng, Gu Zhang, Yuanpei Chen, Huazhe Xu. CoRL 2024.
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

+ [Rapidly Adapting Policies to the Real World via Simulation-Guided Fine-Tuning](https://weirdlabuw.github.io/sgft/)
  + Patrick Yin, Tyler Westenbroek, Simran Bagaria, Kevin Huang, Ching-an Cheng, Andrey Kobolov, Abhishek Gupta. ICLR 2025.
+ [AnyRotate: Gravity-Invariant In-Hand Object Rotation with Sim-to-Real Touch](https://openreview.net/forum?id=8Yu0TNJNGK)
  + Max Yang, chenghua lu, Alex Church, Yijiong Lin, Christopher J. Ford, Haoran Li, Efi Psomopoulou, David A.W. Barton, Nathan F. Lepora. CoRL 2024.
+ [A Conservative Approach for Few-Shot Transfer in Off-Dynamics Reinforcement Learning](https://hal.science/hal-04574316/)
  + Paul Daoudi, Bogdan Robu, Christophe Prieur, Merwan Barlier, Ludovic Dos Santos. IJCAI 2024.
+ [Cross-Domain Policy Adaptation by Capturing Representation Mismatch](https://arxiv.org/abs/2405.15369)
  + Jiafei Lyu, Chenjia Bai, Jingwen Yang, Zongqing Lu, Xiu Li. ICML 2024.
+ [Contrastive Representation for Data Filtering in Cross-Domain Offline Reinforcement Learning](https://arxiv.org/abs/2405.06192)
  + Xiaoyu Wen, Chenjia Bai, Kang Xu, Xudong Yu, Yang Zhang, Xuelong Li, Zhen Wang. ICML 2024.
+ [OMPO: A Unified Framework for RL under Policy and Dynamics Shifts](https://arxiv.org/abs/2405.19080)
  + Yu Luo, Tianying Ji, Fuchun Sun, Jianwei Zhang, Huazhe Xu, Xianyuan Zhan. ICML 2024.
+ [Improving Offline Reinforcement Learning with Inaccurate Simulators](https://arxiv.org/abs/2405.04307)
  + Yiwen Hou, Haoyuan Sun, Jinming Ma, Feng Wu. ICRA 2024.
+ [H2O+: An Improved Framework for Hybrid Offline-and-Online RL with Dynamics Gaps](https://arxiv.org/abs/2309.12716)
  + Haoyi Niu, Tianying Ji, Bingqi Liu, Haocheng Zhao, Xiangyu Zhu, Jianying Zheng, Pengfei Huang, Guyue Zhou, Jianming Hu, Xianyuan Zhan. DMLR@ICLR 2024.
+ [What Went Wrong? Closing the Sim-to-Real Gap via Differentiable Causal Discovery](https://sites.google.com/view/sim2real-compass)
  + Peide Huang, Xilun Zhang, Ziang Cao, Shiqi Liu, Mengdi Xu, Wenhao Ding, Jonathan Francis, Bingqing Chen, Ding Zhao. CoRL 2023.
+ [AdaptSim: Task-Driven Simulation Adaptation for Sim-to-Real Transfer](https://irom-lab.github.io/AdaptSim/)
  + Allen Z. Ren, Hongkai Dai, Benjamin Burchfiel, Anirudha Majumdar. CoRL 2023.
+ [Cold Diffusion on the Replay Buffer: Learning to Plan from Known Good States](https://proceedings.mlr.press/v229/wang23e.html)
  + Zidan Wang, Takeru Oba, Takuma Yoneda, Rui Shen, Matthew Walter, Bradly C. Stadie. CoRL 2023.
+ [State Regularized Policy Optimization on Data with Dynamics Shift](https://proceedings.neurips.cc/paper_files/paper/2023/hash/67dd6a41bf9539cffc0fc0165e4d0616-Abstract-Conference.html)
  + Zhenghai Xue, Qingpeng Cai, Shuchang Liu, Dong Zheng, Peng Jiang, Kun Gai, Bo An. NeurIPS 2023.
+ [Cross-Domain Policy Adaptation via Value-Guided Data Filtering](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e8ad87f1076fb0f75d89a45828f186b0-Abstract-Conference.html)
  + Kang Xu, Chenjia Bai, Xiaoteng Ma, Dong Wang, Bin Zhao, Zhen Wang, Xuelong Li, Wei Li. NeurIPS 2023.
+ [When to Trust Your Simulator: Dynamics-Aware Hybrid Offline-and-Online Reinforcement Learning](https://proceedings.neurips.cc/paper_files/paper/2022/hash/ed3cd2520148b577039adfade82a5566-Abstract-Conference.html)
  + Haoyi Niu, Shubham Sharma, Yiwen Qiu, Ming Li, Guyue Zhou, Jianming Hu, Xianyuan Zhan. NeurIPS 2022.
+ [DARA: Dynamics-Aware Reward Augmentation in Offline Reinforcement Learning](https://openreview.net/forum?id=9SDQB3b68K)
  + Jinxin Liu, Zhang Hongyin, Donglin Wang. ICLR 2022.
+ [Learning Feasibility to Imitate Demonstrators with Different Dynamics](https://openreview.net/forum?id=MWtinPDqfZg)
  + Zhangjie Cao, Yilun Hao, Mengxi Li, Dorsa Sadigh. CoRL 2021.
+ [Learning From Imperfect Demonstrations From Agents With Varying Dynamics](https://ieeexplore.ieee.org/abstract/document/9387082?casa_token=96ay11JE8AQAAAAA:OikH6HMlley7dTKVP2c4RFhx4hXYITArQWXEs-MxcQt09BmHS2Le1GvtVDUKyRjI-ziPlVmZuVQ)
  + Zhangjie Cao, Dorsa Sadigh. RAL 2021.
+ [Auto-Tuned Sim-to-Real Transfer](https://ieeexplore.ieee.org/abstract/document/9562091?casa_token=9bMGJX4uY1wAAAAA:UOSLegeIaF16yzJSH8H4k9Yt8rnlRey6YvfQbEm0XtLPa9Q0UPsAasAz4Zx6kUVP6JvHCBQ1LIE)
  + Yuqing Du; Olivia Watkins; Trevor Darrell; Pieter Abbeel; Deepak Pathak. ICRA 2021.
+ [Data-Efficient Domain Randomization With Bayesian Optimization](https://ieeexplore.ieee.org/abstract/document/9327467?casa_token=plkXNJrD6KwAAAAA:WnG6p31T3vBNxS9t4uVPUgJC3aLIZIXY3DZ-6dkH53X_w2cAbX8WDddVekYz0i1Hv2xmazZJVZk)
  + Fabio Muratore; Christian Eilers; Michael Gienger; Jan Peters. RAL 2021. 
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

### Cross-Morphology Policy Transfer
**Morphology gaps** arise when target embodiments exhibit different morphological designs compared to the source domain agents, e.g., variations in joint types, module shapes, and lengths, which may ultimately lead to a dynamics mismatch. **Morphology gaps** may also encompass variations in the dimensions and semantic meanings of state and action spaces, such as the number of observational sensors, limbs, and end effectors.

+ [Body Transformer: Leveraging Robot Embodiment for Policy Learning](https://openreview.net/forum?id=Oce2215aJE)
  + Carmelo Sferrazza, Dun-Ming Huang, Fangchen Liu, Jongmin Lee, Pieter Abbeel. CoRL 2024.
+ [One Policy to Run Them All: an End-to-end Learning Approach to Multi-Embodiment Locomotion](https://openreview.net/forum?id=PbQOZntuXO)
  + Nico Bohlinger, Grzegorz Czechmanowski, Maciej Piotr Krupka, Piotr Kicki, Krzysztof Walas, Jan Peters, Davide Tateo. CoRL 2024.
+ [Cross Domain Policy Transfer with Effect Cycle-Consistency](https://arxiv.org/pdf/2403.02018.pdf)
  + Ruiqi Zhu, Tianhong Dai, Oya Celiktutan. ICRA 2024.
+ [Polybot: Training One Policy Across Robots While Embracing Variability](https://proceedings.mlr.press/v229/yang23c.html)
  + Jonathan Heewon Yang, Dorsa Sadigh, Chelsea Finn. CoRL 2023.
+ [Learning Robot Manipulation from Cross-Morphology Demonstration](https://openreview.net/forum?id=Opmqtk_GvYL)
  + Gautam Salhotra, I-Chun Arthur Liu, Gaurav S. Sukhatme. CoRL 2023.
+ [Multi-embodiment Legged Robot Control as a Sequence Modeling Problem](https://ieeexplore.ieee.org/abstract/document/10161034?casa_token=s1ptQ-eOeMQAAAAA:e8RcKVLTEKiTEyd8tYExmv2WsKc6SW7kH0ngu55f_63J3FerXMgYy3wHbq6qC1xG_d2RxHTX43c)
  + Chen Yu; Weinan Zhang; Hang Lai; Zheng Tian; Laurent Kneip; Jun Wang. ICRA 2023.
+ [MetaMorph: Learning Universal Controllers with Transformers](https://openreview.net/forum?id=Opmqtk_GvYL)
  + Agrim Gupta, Linxi Fan, Surya Ganguli, Li Fei-Fei. ICLR 2022.
+ [Embodied intelligence via learning and evolution](https://www.nature.com/articles/s41467-021-25874-z)
  + Agrim Gupta, Silvio Savarese, Surya Ganguli, Li Fei-Fei. Nature Communications, 2021.
+ [Task-agnostic morphology evolution](https://openreview.net/forum?id=CGQ6ENUMX6)
  + Donald J Hejna III, Pieter Abbeel, Lerrel Pinto. ICLR 2021.
+ [Hierarchically Decoupled Imitation For Morphological Transfer](http://proceedings.mlr.press/v119/hejna20a.html)
  + Donald Hejna, Lerrel Pinto, Pieter Abbeel. ICML 2020.

### Cross-Modality Policy Transfer

+ [Action Space Design in Reinforcement Learning for Robot Motor Skills](https://openreview.net/forum?id=GGuNkjQSrk)
  + Julian Eßer, Gabriel B. Margolis, Oliver Urbann, Sören Kerner, Pulkit Agrawal. CoRL 2024.
+ [Octo: An Open-Source Generalist Robot Policy](https://octo-models.github.io/)
  + Dibya Ghosh, Homer Walke, Karl Pertsch, Kevin Black, Oier Mees, Sudeep Dasari, Joey Hejna, Tobias Kreiman, Charles Xu, Jianlan Luo, You Liang Tan, Lawrence Yunliang Chen, Pannag Sanketi, Quan Vuong, Ted Xiao, Dorsa Sadigh, Chelsea Finn, Sergey Levine. RSS 2024.
+ [Weakly supervised correspondence learning](https://ieeexplore.ieee.org/abstract/document/9811729/)
  + Zihan Wang; Zhangjie Cao; Yilun Hao; Dorsa Sadigh. ICRA 2022.
+ [Cross-Modal Domain Adaptation for Cost-Efficient Visual Reinforcement Learning](https://proceedings.neurips.cc/paper/2021/hash/68264bdb65b97eeae6788aa3348e553c-Abstract.html)
  + Xiong-Hui Chen, Shengyi Jiang, Feng Xu, Zongzhang Zhang, Yang Yu. NeurIPS 2021.

### Cross-Multi-Gap Policy Transfer
In many complex tasks, we might simultaneously encounter multiple types of domain gaps due to substantially different embodiments and deployed environments. 

+ [xTED: Cross-Domain Adaptation via Diffusion-Based Trajectory Editing](https://t6-thu.github.io/xTED/)
  + Haoyi Niu, Qimao Chen, Tenglong Liu, Jianxiong Li, Guyue Zhou, Yi Zhang, Jianming Hu, Xianyuan Zhan. NeurIPS 2024 Workshop on Open-World Agents.
+ [Scaling Proprioceptive-Visual Learning with Heterogeneous Pre-trained Transformers](https://liruiw.github.io/hpt/)
  + Lirui Wang, Xinlei Chen, Jialiang Zhao, Kaiming He. NeurIPS 2024.
+ [OpenVLA: An Open-Source Vision-Language-Action Model](https://openvla.github.io/)
  + Moo Jin Kim, Karl Pertsch, Siddharth Karamcheti, Ted Xiao, Ashwin Balakrishna, Suraj Nair, Rafael Rafailov, Ethan Foster, Grace Lam, Pannag Sanketi, Quan Vuong, Thomas Kollar, Benjamin Burchfiel, Russ Tedrake, Dorsa Sadigh, Sergey Levine, Percy Liang, Chelsea Finn. CoRL 2024.
+ [EXTRACT: Efficient Policy Learning by Extracting Transferrable Robot Skills from Offline Data](https://openreview.net/forum?id=uEbJXWobif)
  + Jesse Zhang, Minho Heo, Zuxin Liu, Erdem Biyik, Joseph J Lim, Yao Liu, Rasool Fakoor. CoRL 2024.
+ [TieBot: Learning to Knot a Tie from Visual Demonstration through a Real-to-Sim-to-Real Approach](https://openreview.net/forum?id=Si2krRESZb)
  + Weikun Peng, Jun Lv, Yuwei Zeng, Haonan Chen, Siheng Zhao, Jichen Sun, Cewu Lu, Lin Shao. CoRL 2024.
+ [Evaluating Real-World Robot Manipulation Policies in Simulation](https://openreview.net/forum?id=LZh48DTg71)
  + Xuanlin Li, Kyle Hsu, Jiayuan Gu, Oier Mees, Karl Pertsch, Homer Rich Walke, Chuyuan Fu, Ishikaa Lunawat, Isabel Sieh, Sean Kirmani, Sergey Levine, Jiajun Wu, Chelsea Finn, Hao Su, Quan Vuong, Ted Xiao. CoRL 2024.
+ [TRANSIC: Sim-to-Real Policy Transfer by Learning from Online Correction](https://openreview.net/forum?id=lpjPft4RQT)
  + Yunfan Jiang, Chen Wang, Ruohan Zhang, Jiajun Wu, Li Fei-Fei. CoRL 2024.
+ [Scaling Cross-Embodied Learning: One Policy for Manipulation, Navigation, Locomotion and Aviation](https://openreview.net/forum?id=AuJnXGq3AL)
  + Ria Doshi, Homer Rich Walke, Oier Mees, Sudeep Dasari, Sergey Levine. CoRL 2024.
+ [Flow as the Cross-domain Manipulation Interface](https://openreview.net/forum?id=cNI0ZkK1yC)
  + Mengda Xu, Zhenjia Xu, Yinghao Xu, Cheng Chi, Gordon Wetzstein, Manuela Veloso, Shuran Song. CoRL 2024.
+ [Bridging the Sim-to-Real Gap from the Information Bottleneck Perspective](https://openreview.net/forum?id=Bq4XOaU4sV)
  + Haoran He, Peilin Wu, Chenjia Bai, Hang Lai, Lingxiao Wang, Ling Pan, Xiaolin Hu, Weinan Zhang. CoRL 2024.
+ [SHADOW: Leveraging Segmentation Masks for Cross-Embodiment Policy Transfer](https://openreview.net/forum?id=MyyZZAPgpy)
  + Marion Lepert, Ria Doshi, Jeannette Bohg. CoRL 2024.
+ [Any-point Trajectory Modeling for Policy Learning](https://xingyu-lin.github.io/atm/)
  + Chuan Wen, Xingyu Lin, John So, Kai Chen, Qi Dou, Yang Gao, Pieter Abbeel. RSS 2024.
+ [Mirage: Cross-Embodiment Zero-Shot Policy Transfer with Cross-Painting](https://robot-mirage.github.io/)
  + Lawrence Yunliang Chen, Kush Hari, Karthik Dharmarajan, Chenfeng Xu, Quan Vuong, Ken Goldberg. RSS 2024.
+ [Pushing the limits of cross-embodiment learning for manipulation and navigation](http://extreme-cross-embodiment.github.io/)
  + Jonathan Yang, Catherine Glossop, Arjun Bhorkar, Dhruv Shah, Quan Vuong, Chelsea Finn, Dorsa Sadigh, Sergey Levine. RSS 2024.
+ [Octo: An Open-Source Generalist Robot Policy](https://octo-models.github.io/)
  + Octo Model Team. RSS 2024.
+ [Open X-Embodiment: Robotic Learning Datasets and RT-X Models](https://robotics-transformer-x.github.io/)
  + Open X-Embodiment Collaboration. ICRA 2024.
+ [XSkill: Cross Embodiment Skill Discovery](https://xskill.cs.columbia.edu/)
  + Mengda Xu, Zhenjia Xu, Cheng Chi, Manuela Veloso, Shuran Song. CoRL 2023.
+ [Efficient Policy Adaptation with Contrastive Prompt Ensemble for Embodied Agents](https://openreview.net/forum?id=Ny3GcHLyzj)
  + Wonje Choi, Woo Kyung Kim, SeungHyun Kim, Honguk Woo. NeurIPS 2023.
+ [LIV: Language-Image Representations and Rewards for Robotic Control](https://penn-pal-lab.github.io/LIV/)
  + Jason Ma, Vikash Kumar, Amy Zhang, Osbert Bastani, Dinesh Jayaraman. ICML 2023.
+ [VIP: Towards Universal Visual Reward and Representation via Value-Implicit Pre-Training](https://sites.google.com/view/vip-rl)
  + Jason Ma, Shagun Sodhani, Dinesh Jayaraman, Osbert Bastani, Vikash Kumar, Amy Zhang. ICLR 2023.
+ [Cross-Domain Transfer via Semantic Skill Imitation](https://kpertsch.github.io/star/)
  + Karl Pertsch, Ruta Desai, Vikash Kumar, Franziska Meier, Joseph J. Lim, Dhruv Batra, Akshara Rai. CoRL 2022.
+ [Learn what matters: cross-domain imitation learning with task-relevant embeddings](https://arxiv.org/abs/2209.12093)
  + Tim Franzmeyer, Philip H. S. Torr, João F. Henriques. NeurIPS 2022.
+ [XIRL: Cross-embodiment Inverse Reinforcement Learning](https://x-irl.github.io/)
  + Kevin Zakka, Andy Zeng, Pete Florence, Jonathan Tompson, Jeannette Bohg, Debidatta Dwibedi. CoRL 2021.
+ [Cross-domain Imitation from Observations](https://arxiv.org/pdf/2105.10037)
  + Dripta S. Raychaudhuri, Sujoy Paul, Jeroen van Baar, Amit K. Roy-Chowdhury. ICML 2021.
+ [Domain Adaptive Imitation Learning](https://arxiv.org/abs/1910.00105)
  + Kuno Kim, Yihong Gu, Jiaming Song, Shengjia Zhao, Stefano Ermon. ICML 2020.
+ [Learning Cross-Domain Correspondence for Control with Dynamics Cycle-Consistency](https://sites.google.com/view/cycledynamics)
  + Qiang Zhang, Tete Xiao, Alexei A Efros, Lerrel Pinto, Xiaolong Wang. ICLR 2020.

## Existing Benchmarks
+ [ODRL: A Benchmark for Off-Dynamics Reinforcement Learning](https://github.com/OffDynamicsRL/off-dynamics-rl)
  + Jiafei Lyu, Kang Xu, Jiacheng Xu, Mengbei Yan, Jingwen Yang, Zongzhang Zhang, Chenjia Bai, Zongqing Lu, Xiu Li. NeurIPS 2024 Dataset and Benchmark Track.
+ [Evaluating Real-World Robot Manipulation Policies in Simulation](https://openreview.net/forum?id=LZh48DTg71)
  + Xuanlin Li, Kyle Hsu, Jiayuan Gu, Oier Mees, Karl Pertsch, Homer Rich Walke, Chuyuan Fu, Ishikaa Lunawat, Isabel Sieh, Sean Kirmani, Sergey Levine, Jiajun Wu, Chelsea Finn, Hao Su, Quan Vuong, Ted Xiao. CoRL 2024.

# Progress: Updated CoRL 2024!

## Citations
If the insights, categorizations, analyses and encapsulations in this survey paper/github collection are helpful with your project development, please cite the following paper:
```
@inproceedings{
    niu2024comprehensive,
    title={A Comprehensive Survey of Cross-Domain Policy Transfer for Embodied Agents},
    author={Niu, Haoyi and Hu, Jianming and Zhou, Guyue and Zhan, Xianyuan},
    booktitle={International Joint Conference on Artificial Intelligence},
    year={2024}
}
```
