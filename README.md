# awesome-cross-domain-policy-transfer-for-embodied-agents ![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
This is a collection of research and review papers for cross-domain policy transfer for embodied agents. Feel free to star and fork. Original paper: [A Comprehensive Survey of Cross-Domain Policy Transfer for Embodied Agents](https://arxiv.org/abs/2402.04580).

## Maintainers
[Haoyi Niu](https://t6-thu.github.io/) (Tsinghua University), [Xianyuan Zhan](http://zhanxianyuan.xyz/) (Tsinghua University)

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


### Cross-Dynamics Policy Transfer
**Dynamics gaps** occur when interactions between embodiments and their deploying environments, or interactions among different parts of the embodiment itself, follow different transitional dynamics, such as stiffness, gear dead zones of embodiments, body mass, and friction.

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
