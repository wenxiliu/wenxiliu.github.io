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

## Segmentation 
* *Edge Distraction-aware Salient Object Detection* <br>Sucheng Ren, **Wenxi Liu**, Jianbo Jiao, Guoqiang Han, Shengfeng He<br> **IEEE Transactions on Multimedia, 2023**
* *From Contexts to Locality: Ultra-high Resolution Image Segmentation via Locality-aware Contextual Correlation* <br>Qi Li, Weixiang Yang, **Wenxi Liu\***, Yuanlong Yu, Shengfeng He <br>**ICCV 2021** [[pdf](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_From_Contexts_to_Locality_Ultra-High_Resolution_Image_Segmentation_via_Locality-Aware_ICCV_2021_paper.pdf)][[arxiv](https://arxiv.org/abs/2109.02580)][[code](https://github.com/liqiokkk/FCtL)]
* *Projecting Your View Attentively: Monocular Road Scene Layout Estimation via Cross-view Transformation*, <br>Weixiang Yang, Qi Li, **Wenxi Liu\***, Yuanlong Yu, Yuexin Ma, Shengfeng He, Jia Pan<br>**CVPR 2021** [[pdf](https://openaccess.thecvf.com/content/CVPR2021/papers/Yang_Projecting_Your_View_Attentively_Monocular_Road_Scene_Layout_Estimation_via_CVPR_2021_paper.pdf)][[code](https://github.com/JonDoe-297/cross-view)]
* *Reciprocal Transformations for Unsupervised Video Object Segmentation* <br>Sucheng Ren, **Wenxi Liu**, Yongtuo Liu, Haoxin Chen, Guoqiang Han, Shengfeng He <br>**CVPR 2021**
* *Boundary-aware RGBD Salient Object Detection with Cross-modal Feature Sampling* <br>Yuzhen Niu, Guanchao Long, **Wenxi Liu\***, Wenzhong Guo, Shengfeng He <br>**IEEE Trans. Image Processing (TIP), 2020**
* *Real-Time Hierarchical Supervoxel Segmentation via a Minimum Spanning Tree* <br>Bo Wang, Yiliang Chen, **Wenxi Liu**, Jing Qin, Yong Du, Guoqiang Han, Shengfeng He <br>**IEEE Trans. Image Processing (TIP), 2020**
* *Learning Long-term Structural Dependencies for Video Salient Object Detection*<br>Bo Wang, **Wenxi Liu**, Guoqiang Han, Shengfeng He <br>**IEEE Trans. Image Processing (TIP), 2020**
* *Visualizing the Invisible: Occluded Vehicle Segmentation and Recovery*<br>Xiaosheng Yan, Feigege Wang, **Wenxi Liu\***, Yuanlong Yu, Shengfeng He, Jia Pan <br>**ICCV 2019** [[arxiv](https://arxiv.org/abs/1907.09381)]
* *Context-aware Spatio-recurrent Curvilinear Structure Segmentation* <br>Feigege Wang, Yue Gu, **Wenxi Liu\***, Yuanlong Yu, Shengfeng He, Jia Pan <br>**CVPR 2019** [[pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Context-Aware_Spatio-Recurrent_Curvilinear_Structure_Segmentation_CVPR_2019_paper.pdf)]
* *Enhancement Mask for Hippocampus Detection and Segmentation* <br>Dengsheng Chen, **Wenxi Liu\***, You Huang, Tong Tong, Yuanlong Yu <br>**IEEE International Conference on Information and Automation (ICIA), 2018** [[arxiv](https://arxiv.org/abs/1902.04244)]
* *SuperCNN: A Superpixelwise Convolutional Neural Network for Salient Object Detection* <br>Shengfeng He, Rynson W. H. Lau, **Wenxi Liu**, Zhe Huang, Qingxiong Yang <br>**International Journal of Computer Vision (IJCV), 2015**

## Crowd and Multi-robots
* *Frame-Event Alignment and Fusion Network for High Frame Rate Tracking* <br>Jiqing Zhang, Yuanchen Wang, **Wenxi Liu**, Meng Li, Jinpeng Bai, Baocai Yin, Xin Yang<br>**CVPR 2023**
* *End-to-End Trajectory Distribution Prediction Based on Occupancy Grid Maps* <br>Ke Guo, **Wenxi Liu**, Jia Pan <br>**CVPR 2022**
* *Monocular Camera-based Complex Obstacle Avoidance via Efficient Deep Reinforcement Learning* <br>Jianchuan Ding, Lingping Gao, **Wenxi Liu**, Haiyin Piao, Jia Pan, Zhenjun Du, Xin Yang, Baocai Yin <br> **IEEE Trans. Circuits Syst. Video Techn. (TCSVT), 2022**
* *Coarse-to-Fine Person Re-Identification with Auxiliary-Domain Classification and Second-Order Information Bottleneck* <br>Anguo Zhang, Yueming Gao, Yuzhen Niu, **Wenxi Liu**, Yongcheng Zhou <br>**CVPR 2021**
* *A Vision-based Irregular Obstacle Avoidance Framework via Deep Reinforcement Learning* <br>Lingping Gao, Jianchuan Ding, **Wenxi Liu**, Haiyin Piao, Yuxin Wang, Xin Yang, Baocai Yin <br>**IROS 2021**
* *CrowdGAN: Identity-free Interactive Crowd Video Generation and Beyond* <br>Liangyu Chai, Yongtuo Liu, **Wenxi Liu**, Guoqiang Han, Shengfeng He  <br>**IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2020**
* *Crowd Counting via Cross-stage Refinement Networks* <br>Yongtuo Liu, Qiang Wen, Haoxin Chen, **Wenxi Liu**, Jing Qin, Guoqiang Han, Shengfeng He <br>**IEEE Transactions on Image Processing (TIP), 2020**
* *Distributed Multi-Robot Collision Avoidance via Deep Reinforcement Learning for Navigation in Complex Scenarios* <br>Tingxiang Fan, Pinxin Long, **Wenxi Liu**, Jia Pan <br>**International Journal on Robotics Research (IJRR), 2020**
* *Learning Resilient Behaviors for Navigation Under Uncertainty* <br>Tingxiang Fan, Pinxin Long, **Wenxi Liu**, Jia Pan, Ruigang Yang, Dinesh Manocha <br>**ICRA 2020**
* *Over-crowdedness Alert! Forecasting the Future Crowd Distribution* <br>Yuzhen Niu, Weifeng Shi, **Wenxi Liu***, Shengfeng He, Jia Pan, Antoni B. Chan<br>**Arxiv 2020** [[arxiv](https://arxiv.org/abs/2006.05127)]
* *Recurrent Distillation based Crowd Counting* <br>Yue Gu, **Wenxi Liu*** <br>**Arxiv 2020** [[arxiv](https://arxiv.org/abs/2006.07755)]
* *Deformable Object Tracking with Gated Fusion* <br>**Wenxi Liu**, Yibing Song, Dengsheng Chen, Shengfeng He, Yuanlong Yu, Tao Yan, Rynson W. H. Lau <br>**IEEE Trans. Image Processing (TIP), 2019** [[arxiv](https://arxiv.org/abs/1809.10417)][[code](https://github.com/magiratex34/deform_tracking)]
* *Extraversion Measure for Crowd Trajectories* <br>**Wenxi Liu**, Chun-Yang Zhang, Genggeng Liu, Yaru Su, Naixue Xiong <br>**IEEE Trans. on Industrial Informatics (TII), Special Section on Emerging Trends Issues and Challenges in Edge Artificial Intelligence, 2019** 
* *Getting Robots Unfrozen and Unlost in Dense Pedestrian Crowds* <br>Tingxiang Fan, Xinjing Cheng, Jia Pan, Pinxin Long, **Wenxi Liu**, Ruigang Yang, Dinesh Manocha <br>**IEEE Robotics and Automation Letters (RAL), 2019**
* *Towards Optimally Decentralized Multi-Robot Collision Avoidance via Deep Reinforcement Learning* <br>Pinxin Long, Tingxiang Fan, Xinyi Liao, **Wenxi Liu**, Hao Zhang, Jia Pan <br>**ICRA 2018**
* *Deep-Learned Collision Avoidance Policy for Distributed Multiagent Navigation* <br>Pinxin Long, **Wenxi Liu\***, Jia Pan\* <br>**IEEE Robotics and Automation Letters (RAL), 2017**
* *Exemplar-AMMs: Recognizing Crowd Movements From Pedestrian Trajectories* <br>**Wenxi Liu**, Rynson W. H. Lau, Xiaogang Wang, Dinesh Manocha <br>**IEEE Trans. Multimedia (TMM), 2016** [[preprint](http://www.cs.cityu.edu.hk/~rynson/papers/tmm16.pdf)]
* *Robust individual and holistic features for crowd scene classification* <br>**Wenxi Liu**, Rynson W. H. Lau, Dinesh Manocha <br>**Pattern Recognition (PR), 2016**
* *BRVO: Predicting pedestrian trajectories using velocity-space reasoning* <br>Sujeong Kim, Stephen J. Guy, **Wenxi Liu**, David Wilkie, Rynson W. H. Lau, Ming C. Lin, Dinesh Manocha <br>**International Journal on Robotics Research (IJRR), 2015**
* *Leveraging Long-Term Predictions and Online Learning in Agent-Based Multiple Person Tracking* <br>**Wenxi Liu**, Antoni B. Chan, Rynson W. H. Lau, Dinesh Manocha <br>**IEEE Trans. Circuits Syst. Video Techn. (TCSVT), 2015** [[preprint](http://www.cs.cityu.edu.hk/~rynson/papers/tcsvt15.pdf)]
* *Data-driven sequential goal selection model for multi-agent simulation* <br>**Wenxi Liu**, Zhe Huang, Rynson W. H. Lau, Dinesh Manocha <br>**ACM Symposium on Virtual Reality Software and Technology (VRST) 2014**
* *A statistical similarity measure for aggregate crowd dynamics* <br>Stephen J. Guy, Jur van den Berg, **Wenxi Liu**, Rynson W. H. Lau, Ming C. Lin, Dinesh Manocha <br>**ACM Trans. Graph. (TOG), 2012**
* *Crowd simulation using Discrete Choice Model* <br>**Wenxi Liu**, Rynson W. H. Lau, Dinesh Manocha <br>**IEEE Virtual Reality (VR) 2012**


## Miscellaneous
* *CIRI: Curricular Inactivation for Residue-aware One-shot Video Inpainting*<br> Weiying Zheng, Cheng Xu, Xuemiao Xu, **Wenxi Liu**, Shengfeng He<br>**ICCV 2023**
* *Diffuse3D: Wide-Angle 3D Photography via Bilateral Diffusion* <br>Yutao Jiang, Yang Zhou, Yuan Liang, **Wenxi Liu**, Jianbo Jiao, Yuhui Quan, Shengfeng He<br>**ICCV 2023**
* *Single-View View Synthesis with Self-Rectified Pseudo-Stereo* <br>Yang Zhou, Hanjie Wu, **Wenxi Liu**, Zheng Xiong, Jing Qin, Shengfeng He<br>**International Journal of Computer Vision (IJCV), 2023**
* *Progressive Moire Removal and Texture Complementation for Image Demoireing* <br>Yuzhen Niu, Zhihua Lin, **Wenxi Liu***, Wenzhong Guo<br>**IEEE Trans. Circuits Syst. Video Techn. (TCSVT), 2023**
* *Comment-Guided Semantics-Aware Image Aesthetics Assessment* <br>Yuzhen Niu, Shanshan Chen, Bingrui Song, Zhixian Chen, **Wenxi Liu** <br> **IEEE Trans. Circuits Syst. Video Techn. (TCSVT), 2022**
* *Perceptual-aware and Restorable Real-time Image Downscaling* <br>Yuzhen Niu, Luwei Zheng, Jiaqi Lin, Jianbin Wu, **Wenxi Liu\*** <br>**ICME 2022**
* *HDR-GAN: HDR Image Reconstruction from Multi-Exposed LDR Images with Large Motions* <br>Yuzhen Niu, Jianbin Wu, **Wenxi Liu\***, Wenzhong Guo, Rynson W.H. Lau <br>**IEEE Transactions on Image Processing (TIP), 2021** [[code](https://github.com/nonu116/HDR-GAN)]
* *EBRB cascade classifier for imbalanced data via rule weight updating* <br>Yang-Geng Fu, Hong-Yun Huang, Yu Guan, Ying-Ming Wang, **WenxiLiu\***, Wei-Jie Fang <br>**Knowledge-Based Systems (KBS), 2021**
* *Mapping in a Cycle: Sinkhorn Regularized Unsupervised Learning for Point Cloud Shapes* <br>Lei Yang, **Wenxi Liu**, Zhiming Cui, Nenglun Chen, Wenping Wang <br>**ECCV 2020** [[code](https://github.com/LeiYangJustin/Map-in-a-Cycle)]
* *Recurrent Enhancement of Visual Comfort for Casual Stereoscopic Photography* <br>Yuzhen Niu, Qingyang Zheng, **Wenxi Liu\***, Wenzhong Guo <br>**IEEE Virtual Reality (VR) 2020** (Oral) 
* *3D Deconvolutional Networks for the Unsupervised Representation Learning of Human Motions* <br>Chun-Yang Zhang, Yongyi Xiao, Jin-Cheng Lin, C. L. Philip Chen, **Wenxi Liu**, Yuhong Tong <br>**IEEE Transactions on Cybernetics 2020**
* *Stereoscopic Image Generation from Light Field with Disparity Scaling and Super-Resolution* <br>Tao Yan, Jianbo Jiao, **Wenxi Liu**, Rynson WH Lau <br>**IEEE Trans. Image Processing (TIP), 2020**
* *Generating Stereoscopic Images with Convergence Control Ability from a Light Field Image Pair* <br>Tao Yan, Yiming Mao, Jianming Wang, **Wenxi Liu**, Xiaohua Qian, and Rynson Lau <br>**IEEE Trans. Circuits Syst. Video Techn. (TCSVT), 2020**
* *Single Image Reflection Removal Beyond Linearity* <br>Qiang Wen, Yinjie Tan, Jing Qin, **Wenxi Liu**, Guoqiang Han, Shengfeng He <br>**CVPR 2019**
* *Deep compression of probabilistic graphical networks* <br> Chun-Yang, Zhang, Qi Zhao, C.L. Philip Chen, **Wenxi Liu** <br>**Pattern Recognition (PR), 2019**
* *Combined X-ray and facial videos for phoneme-level articulator dynamics* <br>Hui Chen, Lan Wang, **Wenxi Liu**, Pheng-Ann Heng <br>**The Visual Computer, 2010**

