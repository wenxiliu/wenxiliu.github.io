---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %
  {% include archive-single.html %}
{% endfor %}

## Image Segmentation
* Weixiang Yang, Qi Li, **Wenxi Liu\***, Yuanlong Yu, Yuexin Ma, Shengfeng He, Jia Pan: *Projecting Your View Attentively: Monocular Road Scene Layout Estimation via Cross-view Transformation*, CVPR 2021. [[code](https://github.com/JonDoe-297/cross-view)][[pdf](https://github.com/wenxiliu/wenxiliu.github.io/blob/master/files/CVPR21_Crossview.pdf)]
* Sucheng Ren, **Wenxi Liu**, Yongtuo Liu, Haoxin Chen, Guoqiang Han, Shengfeng He: *Reciprocal Transformations for Unsupervised Video Object Segmentation*, CVPR 2021.
* Bo Wang, Yiliang Chen, **Wenxi Liu**, Jing Qin, Yong Du, Guoqiang Han, Shengfeng He: *Real-Time Hierarchical Supervoxel Segmentation via a Minimum Spanning Tree*, IEEE Trans. Image Processing (TIP), 2020.
* Bo Wang, **Wenxi Liu**, Guoqiang Han, Shengfeng He: *Learning Long-term Structural Dependencies for Video Salient Object Detection*, IEEE Trans. Image Processing (TIP), 2020.
* Xiaosheng Yan, Feigege Wang, **Wenxi Liu\***, Yuanlong Yu, Shengfeng He, Jia Pan: *Visualizing the Invisible: Occluded Vehicle Segmentation and Recovery*, ICCV 2019 [[arxiv](https://arxiv.org/abs/1907.09381)]
* Feigege Wang, Yue Gu, **Wenxi Liu\***, Yuanlong Yu, Shengfeng He, Jia Pan: *Context-aware Spatio-recurrent Curvilinear Structure Segmentation.* CVPR 2019 [[pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Context-Aware_Spatio-Recurrent_Curvilinear_Structure_Segmentation_CVPR_2019_paper.pdf)]
* Shengfeng He, Rynson W. H. Lau, **Wenxi Liu**, Zhe Huang, Qingxiong Yang: *SuperCNN: A Superpixelwise Convolutional Neural Network for Salient Object Detection*. International Journal of Computer Vision (IJCV) 115(3): 330-344, 2015 

## Crowd and Multi-robots
* Anguo Zhang, Yueming Gao, Yuzhen Niu, **Wenxi Liu**, Yongcheng Zhou: *Coarse-to-Fine Person Re-Identification with Auxiliary-Domain Classification and Second-Order Information Bottleneck*, CVPR 2021.
* Liangyu Chai, Yongtuo Liu, **Wenxi Liu**, Guoqiang Han, Shengfeng He: *CrowdGAN: Identity-free Interactive Crowd Video Generation and Beyond*. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2020.
* Yongtuo Liu, Qiang Wen, Haoxin Chen, **Wenxi Liu**, Jing Qin, Guoqiang Han, Shengfeng He: *Crowd Counting via Cross-stage Refinement Networks*. IEEE Transactions on Image Processing (TIP), 2020.
* Tingxiang Fan, Pinxin Long, **Wenxi Liu**, Jia Pan: *Distributed Multi-Robot Collision Avoidance via Deep Reinforcement Learning for Navigation in Complex Scenarios*. International Journal on Robotics Research (IJRR), 2020.
* Tingxiang Fan, Pinxin Long, **Wenxi Liu**, Jia Pan, Ruigang Yang, Dinesh Manocha: *Learning Resilient Behaviors for Navigation Under Uncertainty.* ICRA 2020.
* **Wenxi Liu**, Yibing Song, Dengsheng Chen, Shengfeng He, Yuanlong Yu, Tao Yan, Rynson W. H. Lau: *Deformable Object Tracking with Gated Fusion.* IEEE Trans. Image Processing (TIP), 2019 [[arxiv](https://arxiv.org/abs/1809.10417)][[code](https://github.com/magiratex34/deform_tracking)]
* **Wenxi Liu**, Chun-Yang Zhang, Genggeng Liu, Yaru Su, Naixue Xiong: *Extraversion Measure for Crowd Trajectories.* IEEE Trans. on Industrial Informatics (TII), Special Section on Emerging Trends Issues and Challenges in Edge Artificial Intelligence, 2019 
* Tingxiang Fan, Xinjing Cheng, Jia Pan, Pinxin Long, **Wenxi Liu**, Ruigang Yang, Dinesh Manocha: *Getting Robots Unfrozen and Unlost in Dense Pedestrian Crowds.* IEEE Robotics and Automation Letters (RAL) 4(2): 1178-1185, 2019 
* Pinxin Long, Tingxiang Fan, Xinyi Liao, **Wenxi Liu**, Hao Zhang, Jia Pan: *Towards Optimally Decentralized Multi-Robot Collision Avoidance via Deep Reinforcement Learning.* ICRA 2018
* Pinxin Long, **Wenxi Liu\***, Jia Pan\*: *Deep-Learned Collision Avoidance Policy for Distributed Multiagent Navigation.* IEEE Robotics and Automation Letters (RAL) 2(2): 656-663, 2017 
* **Wenxi Liu**, Rynson W. H. Lau, Xiaogang Wang, Dinesh Manocha: *Exemplar-AMMs: Recognizing Crowd Movements From Pedestrian Trajectories*. IEEE Trans. Multimedia (TMM) 18(12): 2398-240, 2016 [[pdf](http://www.cs.cityu.edu.hk/~rynson/papers/tmm16.pdf)]
* **Wenxi Liu**, Rynson W. H. Lau, Dinesh Manocha: *Robust individual and holistic features for crowd scene classification*. Pattern Recognition (PR) 58: 110-120, 2016
* Sujeong Kim, Stephen J. Guy, **Wenxi Liu**, David Wilkie, Rynson W. H. Lau, Ming C. Lin, Dinesh Manocha: *BRVO: Predicting pedestrian trajectories using velocity-space reasoning*. International Journal on Robotics Research (IJRR) 34(2): 201-217, 2015
* **Wenxi Liu**, Antoni B. Chan, Rynson W. H. Lau, Dinesh Manocha: *Leveraging Long-Term Predictions and Online Learning in Agent-Based Multiple Person Tracking*. IEEE Trans. Circuits Syst. Video Techn. (TCSVT) 25(3): 399-410, 2015 [[pdf](http://www.cs.cityu.edu.hk/~rynson/papers/tcsvt15.pdf)]
* **Wenxi Liu**, Zhe Huang, Rynson W. H. Lau, Dinesh Manocha: *Data-driven sequential goal selection model for multi-agent simulation.* ACM Symposium on Virtual Reality Software and Technology (VRST). 2014
* Stephen J. Guy, Jur van den Berg, **Wenxi Liu**, Rynson W. H. Lau, Ming C. Lin, Dinesh Manocha: *A statistical similarity measure for aggregate crowd dynamics*. ACM Trans. Graph. (TOG) 31(6): 190:1-190:11, 2012
* **Wenxi Liu**, Rynson W. H. Lau, Dinesh Manocha: *Crowd simulation using Discrete Choice Model.* IEEE Virtual Reality (VR) 2012


## Image/Learning Related Works
* Yuzhen Niu, Jianbin Wu, **Wenxi Liu\***, Wenzhong Guo, Rynson W.H. Lau: *HDR-GAN: HDR Image Reconstruction from Multi-Exposed LDR Images with Large Motions*. IEEE Transactions on Image Processing (TIP), 2021. [[code](https://github.com/nonu116/HDR-GAN)]
* Yuzhen Niu, Guanchao Long, **Wenxi Liu\***, Wenzhong Guo, Shengfeng He: *Boundary-aware RGBD Salient Object Detection with Cross-modal Feature Sampling*, IEEE Trans. Image Processing (TIP), 2020.
* Yang-Geng Fu, Hong-Yun Huang, Yu Guan, Ying-Ming Wang, **WenxiLiu\***, Wei-Jie Fang: *EBRB cascade classifier for imbalanced data via rule weight updating*, Knowledge-Based Systems (KBS), 2021.
* Lei Yang, **Wenxi Liu**, Zhiming Cui, Nenglun Chen, Wenping Wang: *Mapping in a Cycle: Sinkhorn Regularized Unsupervised Learning for Point Cloud Shapes*, ECCV 2020.
* Yuzhen Niu, Qingyang Zheng, **Wenxi Liu\***, Wenzhong Guo: *Recurrent Enhancement of Visual Comfort for Casual Stereoscopic Photography*, IEEE Virtual Reality (VR) 2020 (Oral Presentation). 
* Chun-Yang Zhang, Yongyi Xiao, Jin-Cheng Lin, C. L. Philip Chen, **Wenxi Liu**, Yuhong Tong: *3D Deconvolutional Networks for the Unsupervised Representation Learning of Human Motions*, IEEE Transactions on Cybernetics 2020.
* Tao Yan, Jianbo Jiao, **Wenxi Liu**, Rynson WH Lau: *Stereoscopic Image Generation from Light Field with Disparity Scaling and Super-Resolution* IEEE Trans. Image Processing (TIP), 2020
* Tao Yan, Yiming Mao, Jianming Wang, **Wenxi Liu**, Xiaohua Qian, and Rynson Lau: *Generating Stereoscopic Images with Convergence Control Ability from a Light Field Image Pair.* IEEE Trans. Circuits Syst. Video Techn. (TCSVT) 2020
* Qiang Wen, Yinjie Tan, Jing Qin, **Wenxi Liu**, Guoqiang Han, Shengfeng He: *Single Image Reflection Removal Beyond Linearity.* CVPR 2019
* Chun-Yang, Zhang, Qi Zhao, C.L. Philip Chen, **Wenxi Liu**: *Deep compression of probabilistic graphical networks* Pattern Recognition (PR), 2019
* Dengsheng Chen, **Wenxi Liu\***, You Huang, Tong Tong, Yuanlong Yu: *Enhancement Mask for Hippocampus Detection and Segmentation.* IEEE International Conference on Information and Automation (ICIA), 2018 [[arxiv](https://arxiv.org/abs/1902.04244)]
* Hui Chen, Lan Wang, **Wenxi Liu**, Pheng-Ann Heng: *Combined X-ray and facial videos for phoneme-level articulator dynamics.* The Visual Computer 26(6-8): 477-486, 2010

