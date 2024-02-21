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

+ [Virtual to Real Reinforcement Learning for Autonomous Driving](https://arxiv.org/abs/1704.03952)
  + Xinlei Pan, Yurong You, Ziyan Wang, Cewu Lu. BMVC 2017
+ [Unpaired image-to-image translation using cycle-consistent adversarial networks](http://openaccess.thecvf.com/content_iccv_2017/html/Zhu_Unpaired_Image-To-Image_Translation_ICCV_2017_paper.html)
  + Jun-Yan Zhu, Taesung Park, Phillip Isola, Alexei A. Efros. ICCV 2017

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
