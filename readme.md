# Materials for transfer learning [中文版](https://github.com/dududuAA/Transfer-learning-materials/blob/master/readme.md), [English version](https://github.com/dududuAA/Transfer-learning-materials/blob/master/Readme_English.md) 

update:
*Continue to update sice 2023*
* (2021,9,13) 新增25篇ICCV 2021 paper
* (2021,7,1) 新增1篇ACL 2021 paper (recommended)
* (2021,7,1) 新增1篇DASFAA 2021 paper
* (2021,6,26) 新增14篇VisDA 2021竞赛
* (2021,6,18) 新增14篇IJCAI 2021 papers、两个Presentation(valse, eccv 2020 tutorial)
* (2021,6,14) 更新14篇ICLR 2021 papers
* (2021,6,9) 新增17篇ICML 2021 papers
* (2021,6,5) 新增51篇 CVPR 2021 papers
* (2021,3,5) 新增video DA papers
* (2021,3,3) 新增1个video DA contest (Domain Adaptation for Action Recognition)
* (2021,2,25）新增 2个 CVPR 2020 workshop and 1个 ICML 2020 workshop
* (2021,2,7）新增 3个 DA papers
* (2021,1,14）新增 ICLR 2021 papers
* (2021,1,7）新增2个 DA paper
* (2020,12,14）新增7个 continous DA paper
* (2020,12,10）新增1个DA paper
* (2020,12,5）新增4个DA paper
* (2020,11,25）新增5个DA paper 
<!--
* (2020,11,3）新增1个DA paper, 新增1个related paper
* (2020,10,30) 新增1个related paper
* (2020,10,6) 新增2个DA paper,3个related paper
* (2020,10,5) 新增1个DA paper
* (2020,10,1) 新增2个DA paper, 1个related paper
* (2020,9,30) 新增2个DA paper, 1个related paper
* (2020,9,29) 新增迁移学习理论小结，OTL小结
* (2020,9,28) 新增DA paper
* (2020,9,6) 新增DA paper, 科研方法论相关视频
* (2020,8,29) 新增龙老师ccdm 2020报告视频
-->

- [Materials for transfer learning](#materials-for-transfer-learning)
  * [入门参考](#入门参考)
  * [迁移学习竞赛](#迁移学习竞赛)
  * [CCF截稿日期](#CCF截稿日期)
  * [Excellent Scholars](#excellent-scholars)
  * [新论文追踪](#新论文追踪)
  * [会议视频](#会议视频)
  * [Presentation](#presentation)
  * [novel papers](#novel_papers)
  * [Other githubs](#other-githubs)
  
## 入门参考
本部分内容适合初学者，将一些本领域中的经典论文按照时间线进行分类、梳理，分为浅层域适应、深度域适应、对抗域适应和域适应理论四部分。

针对每一部分，列举了3-4篇经典论文，建议详读这些经典论文，泛读这些经典论文的后续论文，并对其中的部分算法进行实现。

预期学习时间为2-3个月, 详细计划安排见[入门参考](https://github.com/dududuAA/Transfer-learning-materials/blob/master/discuss/plan.pptx)
<!--
围绕这些论文，曾有一个相应的讨论班，相关的日程和资料如下：

   - [week 1](https://github.com/dududuAA/TL_group/tree/master/discuss/week1_10-14)
   - [week 2](https://github.com/dududuAA/TL_group/tree/master/discuss/week2_10-23)
   - [week1 & week2 reference](https://github.com/dududuAA/TL_group/blob/master/discuss/week1%262%E5%8F%82%E8%80%83.pdf)
   - [week 3](https://github.com/dududuAA/TL/tree/master/discuss/week3_10-30)
   - [week 4](https://github.com/dududuAA/TL/tree/master/discuss/week4_11-07)
   - [week 5](https://github.com/dududuAA/TL/tree/master/discuss/week5_11-13)
-->
<!--
## 小结

- 迁移学习理论 [ppt](https://github.com/dududuAA/Transfer-learning-materials/blob/master/summary/theory.pptx), [pdf](https://github.com/dududuAA/Transfer-learning-materials/blob/master/summary/Domain_Divergence.pdf)
- Online Transfer Learning [pdf](https://github.com/dududuAA/Transfer-learning-materials/blob/master/summary/Online_transfer%20(4).pdf)

## 数据集

适用深度网络的数据集

* mnist, svhn, digit, mnistm, cifar, stl (以上皆为.mat格式) [链接](https://box.nju.edu.cn/d/b88420b4d9fd42e78ef5/)
* [Office](https://drive.google.com/file/d/0B4IapRTv9pJ1WGZVd1VDMmhwdlE/view), [Office-Home](https://drive.google.com/file/d/0B81rNlvomiwed0V1YUxQdC1uOTg/view), [VisDA-C](https://github.com/VisionLearningGroup/taskcv-2017-public/tree/master/classification), [Office-Caltech](http://www.vision.caltech.edu/Image_Datasets/Caltech101/101_ObjectCategories.tar.gz) from the official websites.

适用非深度网络的数据集(传统方法)
-->

## 迁移学习竞赛
- [VisDA 2017 in ICCV 2017](http://ai.bu.edu/visda-2017/)
- [VisDA 2018 in ECCV 2018](https://ai.bu.edu/visda-2018/)
- [VisDA 2019 in ICCV 2019](https://ai.bu.edu/visda-2019/)
- [VisDA 2020 in ECCV 2020](http://ai.bu.edu/visda-2020/)
- [Video DA in CVPR 2021](https://epic-kitchens.github.io/2021)
- [VisDA 2021 in NeurIPS 2021](http://ai.bu.edu/visda-2021/#data)

## CCF截稿日期
CCF推荐会议每年的举办时间会有稍稍的不同，此列表收集了当年的CCF推荐列表的截稿时间，包括了全部的CCF会议deadline和CCF期刊的special issue, 可作为一个近似参考，详细时间及内容建议查询官网确认。
链接：[Call4Papars](http://www.call4papers.cn:8080/ccf/ccf-8.jsp)

## Excellent Scholars
- [龙明盛 清华大学](http://ise.thss.tsinghua.edu.cn/~mlong/)
- [Judy Hoffman Georgia Tech](https://www.cc.gatech.edu/~judy/)
- [Kate Aaenko Boston University](https://www.bu.edu/cs/profiles/kate-saenko/)
- [宫博庆 Google Research](http://boqinggong.info/)
- [宫明明 墨尔本大学](https://mingming-gong.github.io/)
- [李晶晶 电子科技大学](https://lijin118.github.io/)
- [Kuniaki Saito Boston University(Ph.D)](http://cs-people.bu.edu/keisaito/)
- [Zhao Han CMU](https://www.cs.cmu.edu/~hzhao1/)
- [李汶 ETH](http://www.vision.ee.ethz.ch/~liwenw/)
- [张磊 重庆大学](http://www.leizhang.tk/)
- [庄福振 中科院计算所](http://www.intsci.ac.cn/users/zhuangfuzhen/)
- [张宇 南方科技大学](https://yuzhanghk.github.io/)
- [王晋东 微软亚洲研究院](http://jd92.wang/)
- [Sinno Jialin Pan NTU](https://www.ntu.edu.sg/home/sinnopan/index.html)

## 新论文追踪

- [Topic: domain adaptation](http://arxitics.com/search?q=domain%20adaptation&sort=updated)
- [Topic: transfer learning](http://arxitics.com/search?q=transfer%20learning&sort=updated#1904.01376/abstract)
- [Topic: Semi-supervised](http://arxitics.com/search?q=semi-supervised&sort=updated)


   	
## 会议视频
- [VALSE 2020 7.31-8.5](http://valser.org/2020/#/)
- [ICLR 2020 视频回放(maybe 科学上网)](https://iclr.cc/virtual_2020/calendar.html#tab-Monday)
-->
	
## Presentation
   - 2021.10 Hoffman, Judy Understanding and Mitigating Bias in Vision Systems [视频](https://smartech.gatech.edu/handle/1853/65390)
   - ECCV 2020 tutorial Domain Adaptation for Visual Applications [视频](https://europe.naverlabs.com/eccv-2020-domain-adaptation-tutorial/)
   - VALSE Webinar 20210609-15 总第241期 领域自适应方法与进展 [报告1](https://www.bilibili.com/video/BV1uB4y1M7ZP), [报告2](https://www.bilibili.com/video/BV1M64y1d7yr), [panel](https://www.bilibili.com/video/BV1m44y167wy), 
   - 龙明盛 CCDM 2020 [视频](https://www.bilibili.com/video/BV1ZK4y1Y77u?from=search&seid=13208916633723128421) , [ppt](http://ise.thss.tsinghua.edu.cn/~mlong/doc/transfer-learning-theories-and-algorithms-ccdm20.pdf)
   - VALSE Webinar 20-19期 迁移学习 (个人非常推荐, 对新手不友好，对进阶有帮助，质量很高!) [视频](https://www.bilibili.com/video/BV19v411q7jk), [报告简介](https://mp.weixin.qq.com/s/HaLUIlDEP4ThdfSgM5-Gog)
   - 龙明盛_NJU2019 Transfer Learning Theories and Algorithms [ppt](https://github.com/dududuAA/TL_group/tree/master/presentation/%E9%BE%99%E6%98%8E%E7%9B%9B_NJU2019_Transfer%20Learning%20Theories%20and%20Algorithms)
   - 龙明盛 Valse 2019 Transfer Learning_From Algorithms to Theories and Back   [视频](https://www.iqiyi.com/v_19rsjxgml0.html) [ppt](https://github.com/dududuAA/TL_group/tree/master/presentation/%E9%BE%99%E6%98%8E%E7%9B%9B_valse2019_Transfer%20Learning_From%20Algorithms%20to%20Theories%20and%20Back)
   - 吴恩达 NIPS 2016  Nuts and bolts of building AI applications using Deep Learning  [视频(需科学上网)](https://www.youtube.com/watch?v=wjqaz6m42wU),[ppt](https://github.com/dududuAA/Transfer-learning-materials/blob/master/presentation/%E5%90%B4%E6%81%A9%E8%BE%BE_NIPS2016_Nuts%20and%20bolts%20of%20building%20AI%20applications%20using%20Deep%20Learning/Slides.pdf)
   - 游凯超 智源论坛 2019 领域适配前沿研究--场景、方法与模型选择 [视频](https://www.bilibili.com/video/BV15J411W7KX?from=search&seid=8739501206493640960),[ppt](https://youkaichao.github.io/files/icml2019/923.pdf)
   - 王玫   2019 deep_domain_adaptation [视频](https://www.bilibili.com/video/av39436440/), [ppt](https://github.com/dududuAA/Transfer-learning-materials/blob/master/presentation/%E7%8E%8B%E7%8E%AB_2019_deep_domain_adaptation/deep%20domain%20adaptation%20tutorial-small.pdf)   

## Novel_papers
### 1) Novel_papers on transfer learning
| number| Title   | Conference/journel + year| Code | Keywords |  Benenit for us |
|  --- |----  | ----  | ---- | ---- | ---- |
|211| Learning to Diversify for Single Domain Generalization ([paper](https://arxiv.org/abs/2108.11726))|ICCV 2021||Single DG||
|210| PIT: Position-Invariant Transform for Cross-FoV Domain Adaptation ([paper](https://arxiv.org/abs/2108.07142))|ICCV 2021|[code](https://github.com/sheepooo/PIT-Position-Invariant-Transform)|UDA|good paper|
|209| Semantic Concentration for Domain Adaptation ([paper](https://arxiv.org/abs/2108.05720))|ICCV 2021||UDA||
|208| Zero-Shot Domain Adaptation with a Physics Prior ([paper](https://arxiv.org/abs/2108.05137))|ICCV 2021 | [code](https://github.com/Attila94/CIConv)|zero-shot DA|
|207| BiMaL: Bijective Maximum Likelihood Approach to Domain Adaptation in Semantic Scene Segmentation ([paper](https://arxiv.org/abs/2108.03267))|ICCV 2021||UDA, Scene Segmentation||
|206| Domain Generalization via Gradient Surgery ([paper](https://arxiv.org/abs/2108.01621))|ICCV 2021||DG||
|205| Adversarial Unsupervised Domain Adaptation with Conditional and Label Shift: Infer, Align and Iterate ([paper](https://arxiv.org/abs/2107.13469))|ICCV 2021||UDA||
|204| Recursively Conditional Gaussian for Ordinal Unsupervised Domain Adaptation ([paper](https://arxiv.org/abs/2107.13467))|ICCV 2021||UDA||
|203| Improve Unsupervised Pretraining for Few-label Transfer ([paper](https://arxiv.org/abs/2107.12369))|ICCV 2021||pre-train||
|202| Generalized Source-free Domain Adaptation ([paper](https://arxiv.org/pdf/2108.01614.pdf))|ICCV 2021|[homepage](https://sites.google.com/view/g-sfda/g-sfda)|GSFDA||
|201| Seasonal Contrast: Unsupervised Pre-Training from Uncurated Remote Sensing Data ([paper](https://arxiv.org/abs/2103.16607))|ICCV 2021|[code](https://github.com/ElementAI/seasonal-contrast)|pre-train||
|200|Calibrated prediction in and out-of-domain for state-of-the-art saliency modeling ([paper](https://arxiv.org/abs/2105.12441))|ICCV 2021||||
|199| On Generating Transferable Targeted Perturbations ([paper](https://arxiv.org/abs/2103.14641))|ICCV 2021 | [code](https://github.com/Muzammal-Naseer/TTP)|||
|198|Boosting the Generalization Capability in Cross-Domain Few-shot Learning via Noise-enhanced Supervised Autoencoder ([paper](https://arxiv.org/pdf/2108.05028.pdf))|ICCV 2021||cross-domain few shot||
|197|IDM: An Intermediate Domain Module for Domain Adaptive Person Re-ID([paper](https://arxiv.org/abs/2108.02413))|ICCV 2021|[code](https://github.com/SikaStar/IDM)|UDA, Re-ID||
|196|Universal Cross-Domain Retrieval: Generalizing Across Classes and Domains([paper](https://arxiv.org/pdf/2108.08356.pdf))|ICCV 2021||DA, Retrieval|new direction|
|195|Transporting Causal Mechanisms for Unsupervised Domain Adaptation([paper](https://arxiv.org/abs/2107.11055))|ICCV 2021|[code](https://github.com/yue-zhongqi/tcm)|UDA|good paper|
|194|Domain Adaptive Video Segmentation via Temporal Consistency Regularization(([paper](https://arxiv.org/pdf/2107.11004.pdf))|ICCV 2021|[code](https://github.com/Dayan-Guan/DA-VSN)|video semantic segmentation, UDA||
|193|Dual Path Learning for Domain Adaptation of Semantic Segmentation([paper](https://arxiv.org/pdf/2108.06337.pdf))|ICCV 2021|[code](https://github.com/royee182/DPL)|UDA, semantic segmentation||
|192|LabOR: Labeling Only if Required for Domain Adaptive Semantic Segmentation([paper](https://arxiv.org/pdf/2108.05570.pdf))|ICCV 2021||active liked UDA, semantic segmentation|new direction|
|191|Multi-Target Adversarial Frameworks for Domain Adaptation in Semantic Segmentation([paper](https://arxiv.org/pdf/2108.06962.pdf))|ICCV 2021||multi target DA, semantic segmentation||
|190| Multi-Anchor Active Domain Adaptation for Semantic Segmentation([paper](https://arxiv.org/pdf/2108.08012.pdf))|ICCV 2021||Active DA, semantic segmentation||
|189|Generalize then Adapt: Source-Free Domain Adaptive Semantic Segmentation ([paper](https://arxiv.org/pdf/2108.11249.pdf))|ICCV 2021|[project](https://sites.google.com/view/sfdaseg)|SFDA, Semantic Segmentation|| 
|188|Unsupervised Domain Adaptive 3D Detection with Multi-Level Consistency ([paper](https://arxiv.org/pdf/2107.11355.pdf))|ICCV 2021||DA, 3D detection||
|187|Vector-Decomposed Disentanglement for Domain-Invariant Object Detection ([paper](https://arxiv.org/pdf/2108.06685.pdf))|ICCV 2021||DA, object detection||
|186|Matching Distributions between Model and Data: Cross-domain Knowledge Distillation for Unsupervised Domain Adaptation ([paper](https://aclanthology.org/2021.acl-long.421.pdf))|ACL 2021||SFDA|good paper, recommended|
|185|cross-domain error minimization for unsupervised domain adaptation ([paper](https://arxiv.org/abs/2106.15057))|DASFAA 2021|[code](https://github.com/yuntaodu/CDEM)|cross-domain error, UDA| **new method from new theory**|
|184|TIDOT: A Teacher Imitation Learning Approach for Domain Adaptation with Optimal Transport|IJCAI 2021||UDA||
|183|Domain Generalization under Conditional and Label Shifts via Variational Bayesian Inference|IJCAI 2021||DG|new problem|
|182|Deep Reinforcement Learning Boosted Partial Domain Adaptation|IJCAI 2021||Partial DA|
|181|Source-free Domain Adaptation via Avatar Prototype Generation and Adaptation|IJCAI 2021||source-free, prototype||
|180|Adversarial Spectral Kernel Matching for Unsupervised Time Series Domain Adaptation| IJCAI 2021||ts, da||
|179|Graph Consistency Based Mean-Teaching for Unsupervised Domain Adaptive Person Re-Identification ([paper](https://arxiv.org/abs/2105.04776))|IJCAI 2021||UDA, re-id||
|178|Cross-Domain Few-Shot Classification via Adversarial Task Augmentation ([paper](https://arxiv.org/pdf/2104.14385.pdf))|IJCAI 2021|[code](https://github.com/Haoqing-Wang/CDFSL-ATA)|cross-domain few-shot||
|177|Dual Reweighting Domain Generalization for Face Presentation Attack Detection|IJCAI 2021||DG, face attack||
|176| Tool- and Domain-Agnostic Parameterization of Style Transfer Effects Leveraging Pretrained Perceptual Metric ([paper](https://arxiv.org/pdf/2105.09207.pdf))|IJCAI 2021||style transfer||
|176|DA-GCN: A Domain-aware Attentive Graph Convolution Network for Shared-account Cross-domain Sequential Recommendation ([paper](https://arxiv.org/pdf/2105.03300.pdf))|IJCAI 2021||cross-domain Recomm||
|175| Towards Robust Model Reuse in the Presence of Latent Domains|IJCAI 2021||Model reuse||
|174|Differentially Private Correlation Alignment for Domain Adaptation|IJCAI 2021||UDA||
|173|Residential Electric Load Forecasting via Attentive Transfer of Graph Neural Networks|IJCAI 2021||GNN||
|172|Regularising Knowledge Transfer by Meta Functional Learning|IJCAI 2021||Knowledge transfer||
|171|KD3A: Unsupervised Multi-Source Decentralized Domain Adaptation via Knowledge Distillation ([paper](https://arxiv.org/pdf/2011.09757.pdf))|ICML 2021|[code](https://github.com/FengHZ/KD3A)|MSDA||
|170|A Geometrical Approach to Learning Transferable Representation for Domain Adaptation Regression|ICML 2021||||
|169|A Bit More Bayesian: Domain-Invariant Learning with Uncertainty ([paper](https://arxiv.org/pdf/2105.04030.pdf))|ICML 2021||DG||
|168|Towards Domain-Agnostic Contrastive Learning ([paper](https://arxiv.org/abs/2011.04419))|ICML 2021||DA, contrastive learning||
|167|f-Domain Adversarial Learning: Theory and Algorithms ([paper](https://openreview.net/pdf?id=WqXAKcwfZtI))|ICML 2021||UDA||
|166|Cross-domain Imitation from Observation ([paper](https://arxiv.org/abs/2105.10037))|ICML 2021||DA,RL||
|165|Unbalanced minibatch Optimal Transport; applications to Domain Adaptation ([paper](https://arxiv.org/pdf/2103.03606.pdf))|ICML 2021||UDA||
|164|Domain Generalization using Causal Matching ([paper](https://arxiv.org/abs/2006.07500))|ICML 2021|[code](https://github.com/microsoft/robustdg)|DG||
|163|LAMDA: Label Matching Deep Domain Adaptation ([paper](https://nhatptnk8912.github.io/LAMBDA.pdf))|ICML 2021||UDA||
|162|Sequential Domain Adaptation by Synthesizing Distributionally Robust Experts ([paper](https://arxiv.org/abs/2106.00322))|ICML 2021|||new problem|
|161|Learn-to-Share: A Hardware-friendly Transfer Learning Framework Exploiting Computation and Parameter Sharing|ICML 2021|||new problem|
|160|Zoo-Tuning: Adaptive Transfer from A Zoo of Models|ICML 2021||fine-tune||
|159|CARTL: Cooperative Adversarially-Robust Transfer Learning |ICML 2021||||
|158|Transfer-Based Semantic Anomaly Detection|ICML 2021||||
|157|Uncovering the Connections Between Adversarial Transferability and Knowledge Transferability|ICML 2021||||
|156|Function Contrastive Learning of Transferable Meta-Representations ([paper](https://arxiv.org/abs/2010.07093))|ICML 2021||||
|155|Sharing Less is More: Lifelong Learning in Deep Networks with Selective Layer Transfer ([paper](https://openreview.net/forum?id=G8NSCGPEJM))|ICML 2021||||
|154|Cross-Domain Gradient Discrepancy Minimization for Unsupervised Domain Adaptation ([paper]())|CVPR 2021||||
|153|FixBi: Bridging Domain Spaces for Unsupervised Domain Adaptation([paper](https://arxiv.org/pdf/2011.09230.pdf))|CVPR 2021|[code](https://github.com/NaJaeMin92/FixBi)|augmented domain|new idea|
|152|Instance Level Affinity-Based Transfer for Unsupervised Domain Adaptation ([paper](https://arxiv.org/abs/2104.01286))|CVPR 2021|[code](https://github.com/astuti/ILA-DA)|UDA, instance level||
|151| Transferable Semantic Augmentation for Domain Adaptation ([paper](https://arxiv.org/pdf/2103.12562.pdf))|CVPR 2021||UDA, data augmentation||
|150|DRANet: Disentangling Representation and Adaptation Networks for Unsupervised Cross-Domain Adaptation([paper](https://arxiv.org/pdf/2103.13447.pdf))|CVPR 2021||UDA||
|149|Domain Adaptation with Auxiliary Target Domain-Oriented Classifier([paper](https://arxiv.org/abs/2007.04171))|CVPR 2021|[code](https://github.com/tim-learn/ATDOC)|UDA||
|148|MetaAlign: Coordinating Domain Alignment and Classification for Unsupervised Domain Adaptation([paper](https://arxiv.org/pdf/2103.13575.pdf))|CVPR 2021||UDA||
|96|Progressive Domain Expansion Network for Single Domain Generalization ([paper](https://arxiv.org/abs/2103.16050))|CVPR 2021|[code](https://github.com/lileicv/PDEN)|sigle domain generalization|good idea|
|147|Adversarially Adaptive Normalization for Single Domain Generalization ([paper](https://arxiv.org/pdf/2106.01899.pdf))|CVPR 2021||SDG||
|146|Uncertainty-Guided Model Generalization to Unseen Domains ([paper](https://arxiv.org/pdf/2103.07531.pdf))|CVPR 2021||DG, uncertain|new idea|
|145|FSDR: Frequency Space Domain Randomization for Domain Generalization ([paper](https://arxiv.org/abs/2103.02370))|CVPR 2021||DG, frequency domain|new idea|
|144| Few-Shot Image Generation via Cross-Domain Correspondence([paper](https://arxiv.org/abs/2104.06820))|CVPR 2021|[project](https://utkarshojha.github.io/few-shot-gan-adaptation/)|few-shot generation|new question|
|143| PixMatch: Unsupervised Domain Adaptation via Pixelwise Consistency Training ([paper](https://arxiv.org/pdf/2105.08128.pdf))|CVPR 2021||||
|142| RobustNet: Improving Domain Generalization in Urban-Scene Segmentation via Instance Selective Whitening ([paper](https://arxiv.org/pdf/2103.15597.pdf))|CVPR 2021|[code](https://github.com/shachoi/RobustNet)|DG||
|141|Generalization on Unseen Domains via Inference-Time Label-Preserving Target Projections([paper](https://arxiv.org/abs/2103.01134))|CVPR 2021||DG||
|140|Adaptive Methods for Real-World Domain Generalization([paper](https://arxiv.org/abs/2103.15796))|CVPR 2021||DG||
|139|A Fourier-Based Framework for Domain Generalization([paper](https://arxiv.org/pdf/2105.11120.pdf))|CVPR 2021||DG, fourier||
|138|Learning Invariant Representations and Risks for Semi-Supervised Domain Adaptation ([paper](https://arxiv.org/abs/2010.04647))|CVPR 2021||SSDA|good idea, good paper|
|137|Cross-Domain Adaptive Clustering for Semi-Supervised Domain Adaptation ([paper](https://arxiv.org/pdf/2104.09415.pdf))|CVPR 2021||SSDA||
|136| Semi-supervised Domain Adaptation based on Dual-level Domain Mixing for Semantic Segmentation([paper](https://arxiv.org/pdf/2103.04705.pdf))|CVPR 2021||||
|135| Multi-Source Domain Adaptation with Collaborative Learning for Semantic Segmentation([paper](https://arxiv.org/pdf/2103.04717.pdf))|CVPR 2021||MSDA||
|134| Dynamic Transfer for Multi-Source Domain Adaptation ([paper](https://arxiv.org/pdf/2103.10583.pdf))|CVPR 2021|[code](https://github.com/liyunsheng13/DRT)|MSDA||
|133|Curriculum Graph Co-Teaching for Multi-Target Domain Adaptation ([paper](https://arxiv.org/abs/2104.00808))|CVPR 2021|[code](https://github.com/Evgeneus/Graph-Domain-Adaptaion)|MTDA, graph||
|132|Multi-Target Domain Adaptation With Collaborative Consistency Learning|CVPR 2021||||
|131|Source-Free Domain Adaptation for Semantic Segmentation ([paper](https://arxiv.org/pdf/2103.16372.pdf))|CVPR 2021||SFDA+semantic segmentation||
|130| Unsupervised Multi-Source Domain Adaptation Without Access to Source Data([paper](https://arxiv.org/pdf/2104.01845.pdf))|CVPR 2021||MS SFDA||
|129|Divergence Optimization for Noisy Universal Domain Adaptation([paper](https://arxiv.org/abs/2104.00246))|CVPR 2021|||new porblem|
|128|Generalized Domain Adaptation ()|CVPR 2021||||
|127|Transferable Query Selection for Active Domain Adaptation ([paper](http://ise.thss.tsinghua.edu.cn/~mlong/doc/active-domain-adaptation-cvpr21.pdf))|CVPR 2021|[code](https://github.com/thuml/Transferable-Query-Selection)|ADA|new scrnario|
|126|Dynamic Domain Adaptation for Efficient Inference ([paper](https://arxiv.org/pdf/2103.16403.pdf))|CVPR 2021||fast inference, UDA|new problem|
|125| Cluster, Split, Fuse, and Update: Meta-Learning for Open Compound Domain Adaptive Semantic Segmentation([paper](https://arxiv.org/abs/2012.08278))|CVPR 2021||Open Compound Domain||
|124| Open Domain Generalization with Domain-Augmented Meta-Learning([paper](https://arxiv.org/pdf/2104.03620.pdf))|CVPR 2021||open set; DG|new scrnario|
|123|Prototypical Cross-Domain Self-Supervised Learning for Few-Shot Unsupervised Domain Adaptation([paper](https://arxiv.org/abs/2103.16765))|CVPR 2021|[project](http://xyue.io/pcs-fuda/index.html)|few-shot DA||
|122| Reducing Domain Gap by Reducing Style Bias([paper](https://arxiv.org/abs/1910.11645))|CVPR 2021|[code](https://github.com/hyeonseobnam/sagnet)|style|for mutil tasks|
|121| Post-Hoc Uncertainty Calibration for Domain Drift Scenarios([paper](https://arxiv.org/pdf/2012.10988.pdf))|CVPR 2021||Calibration, shift||
|120|Conditional Bures Metric for Domain Adaptation()|CVPR 2021||||
|119|OTCE: A Transferability Metric for Cross-Domain Cross-Task Representations([paper](https://arxiv.org/abs/2103.13843))|CVPR 2021||||
|118|Visualizing Adapted Knowledge in Domain Transfer ([paper](https://arxiv.org/abs/2104.10602))|CVPR 2021|[code](https://github.com/hou-yz/DA_visualization)|visualize|good tool|
|117|DARCNN: Domain Adaptive Region-Based Convolutional Neural Network for Unsupervised Instance Segmentation in Biomedical Images ([paper](https://arxiv.org/pdf/2104.01325.pdf))|CVPR 2021||DA + Instance segmentation||
|116|MetaCorrection: Domain-aware Meta Loss Correction for Unsupervised Domain Adaptation in Semantic Segmentation([paper](https://arxiv.org/pdf/2103.05254.pdf))|CVPR 2021|[code](https://github.com/cyang-cityu/MetaCorrection)|UDA, confusion matrix, meta learning||
|115|MeGA-CDA: Memory Guided Attention for Category-Aware Unsupervised Domain Adaptive Object Detection ([paper](https://arxiv.org/abs/2103.04224))|CVPR 2021||memory,UDA,object detection||
|114|Group-aware Label Transfer for Domain Adaptive Person Re-identification ([paper](https://arxiv.org/abs/2103.12366))|CVPR 2021|[code](https://github.com/JDAI-CV/fast-reid)|UDA,re-id,label group|similar idea with existing paper|
|113|Learning to Generalize Unseen Domains via Memory-based Multi-Source Meta-Learning for Person Re-Identification ([paper](https://arxiv.org/abs/2012.00417))|CVPR 2021|[code](https://github.com/HeliosZhao/M3L)|Re-id, DG||
|112|Regressive Domain Adaptation for Unsupervised Keypoint Detection ([paper](http://ise.thss.tsinghua.edu.cn/~mlong/doc/regressive-domain-adaptation-cvpr21.pdf))|CVPR 2021|[code](https://github.com/thuml/Transfer-Learning-Library)|DA regression|new problem|
|111|Domain-robust VQA with diverse datasets and methods but no target labels ([paper](https://arxiv.org/pdf/2103.15974.pdf))|CVPR 2021|[project](https://people.cs.pitt.edu/~mzhang/domain_robust_vqa/)|VWA, UDA|new scenario|
|110| Semantic Segmentation With Generative Models: Semi-Supervised Learning and Strong Out-of-Domain Generalization([paper](https://arxiv.org/pdf/2104.05833.pdf))|CVPR 2021|[project](https://nv-tlabs.github.io/semanticGAN/)|SSL, OODG||
|109| Spatio-temporal Contrastive Domain Adaptation for Action Recognition()|CVPR 2021||||
|100| Informative and Consistent Correspondence Mining for Cross-Domain Weakly Supervised Object Detection |CVPR 2021||||
|108|Prototypical Pseudo Label Denoising and Target Structure Learning for Domain Adaptive Semantic Segmentation ([paper](https://arxiv.org/pdf/2101.10979.pdf))|CVPR 2021|
|107|Adaptive Cross-Modal Prototypes for Cross-Domain Visual-Language Retrieval()|CVPR 2021||||
|106|Cross-Domain Similarity Learning for Face Recognition in Unseen Domains([paper](https://arxiv.org/pdf/2103.07503.pdf))|CVPR 2021||DG, face||
|105|Complete & Label: A Domain Adaptation Approach to Semantic Segmentation of LiDAR Point Clouds([paper](https://arxiv.org/pdf/2007.08488.pdf))|CVPR 2021||DG, point cloud||
|104|Learning Cross-Domain Correspondence for Control with Dynamics Cycle-Consistency ([paper](https://openreview.net/pdf?id=QIRlze3I6hX))|ICLR 2021|[project](https://sjtuzq.github.io/cycle_dynamics.html)|RL, DA, oral||
|103|Off-Dynamics Reinforcement Learning: Training for Transfer with Domain Classifiers ([paper](https://openreview.net/pdf?id=eqBwg3AcIAK))|ICLR 2021||RL, DA, poster||
|102|Domain-Robust Visual Imitation Learning with Mutual Information Constraints ([paper](https://openreview.net/pdf?id=QubpWYfdNry))|ICLR 2021||RL, DA, poster||
|101|Domain Generalization with MixStyle ([paper](https://openreview.net/pdf?id=6xHJ37MVxxp))|ICLR 2021|[code](https://github.com/KaiyangZhou/Dassl.pytorch)|DG, poster||
|100|In Search of Lost Domain Generalization ([paper](https://openreview.net/pdf?id=lQdXeXDoWtI))|ICLR 2021|[code](https://github.com/facebookresearch/DomainBed/)|DG, benchmark, poster||
|99|MetaNorm: Learning to Normalize Few-Shot Batches Across Domains ([paper](https://openreview.net/pdf?id=9z_dNsC4B5t))|ICLR 2021|[code](https://github.com/YDU-AI/MetaNorm)|DG, few-shot, poster||
|98|What Makes Instance Discrimination Good for Transfer Learning? ([paper](https://openreview.net/pdf?id=23ZjUGpjcc))|ICLR 2021|[project](http://nxzhao.com/projects/good_transfer/)|pre-train, poster||
|97|Adversarially-Trained Deep Nets Transfer Better: Illustration on Image Classification ([paper](https://openreview.net/pdf?id=ijJZbomCJIm))|ICLR 2021||pre-train, poster||
|96|A Unified Approach to Interpreting and Boosting Adversarial Transferability ([paper](https://openreview.net/pdf?id=X76iqnUbBjz))|ICLR 2021|[code](https://github.com/xherdan76/A-Unified-Approach-to-Interpreting-and-Boosting-Adversarial-Transferability)|Adversarial Transferability, poster||
|95|Self-training For Few-shot Transfer Across Extreme Task Differences ([paper](https://openreview.net/pdf?id=O3Y56aqpChA))|ICLR 2021|[code](https://github.com/cpphoo/STARTUP)|few shot, DA, oral||
|94|Scalable Transfer Learning with Expert Models ([paper](https://openreview.net/pdf?id=23ZjUGpjcc))|ICLR 2021||fine-tune, poster||
|93|Integrating Categorical Semantics into Unsupervised Domain Translation ([paper](https://openreview.net/pdf?id=IMPA6MndSXU))|ICLR 2021|[code](https://github.com/lavoiems/Cats-UDT)|Domain translation, poster||
|92|Improving Zero-Shot Voice Style Transfer via Disentangled Representation Learning ([paper](https://openreview.net/pdf?id=TgSVWXw22FQ))|ICLR 2021||Style transfer, poster||
|91|Tent: Fully Test-Time Adaptation by Entropy Minimization ([paper](https://openreview.net/pdf?id=uXl3bZLkr3c))|ICLR 2021|[code](https://github.com/DequanWang/tent)|test-time adaptation|new problem|
|90|Self-Supervised Policy Adaptation during Deployment ([paper](https://openreview.net/pdf?id=o_V-MjyyGV_))|ICLR 2021||RL, adaptation||
|89|Distance-Based Regularisation of Deep Networks for Fine-Tuning ([paper](https://openreview.net/pdf?id=IFqrg1p5Bc))|ICLR 2021||fine-tune||
|88|Contradictory-Structure-Learning-for-Semi-supervised-Domain-Adaptation ([paper](https://arxiv.org/pdf/2002.02545.pdf))|SDM 2021|[code](https://github.com/canqin001/UODA)|SS-DA||
|87|Unsupervised Domain Adaptation in Person re-ID via k-Reciprocal Clustering and Large-Scale Heterogeneous Environment Synthesis|AAAI 2021||UDA,re-id|similar to our idea|
|86|Exploiting Diverse Characteristics and Adversarial Ambivalence for Domain Adaptive Segmentation ([paper](https://arxiv.org/pdf/2012.05608.pdf))|AAAI 2021||diverser, UDA||
|85|Subtype-aware Unsupervised Domain Adaptation for Medical Diagnosis ([paper](https://arxiv.org/pdf/2101.00318.pdf))|AAAI 2021||UDA, application|similar idea with us|
|84|How does the Combined Risk Affect the Performance of Unsupervised Domain Adaptation Approaches? ([paper](https://arxiv.org/pdf/2101.01104.pdf))|AAAI 2021|[code](https://github.com/zhonglii/E-MixNet)|UDA, the thidr term of theory||
|83|Cross-Domain Grouping and Alignment for Domain Adaptive Semantic Segmentation ([paper](https://arxiv.org/pdf/2012.08226.pdf))|AAAI 2021||group alignment, UDA|similar idea with us|
|82|Bi-Classifier Determinacy Maximization for Unsupervised Domain Adaptation ([paper](https://arxiv.org/pdf/2012.06995.pdf))|AAAI 2021||UDA|improvement for MCD|
|81|A Free Lunch for Unsupervised Domain Adaptive Object Detection without Source Data ([paper](https://arxiv.org/pdf/2012.05400.pdf))|AAAI 2021||source-free, Objective detection||
|80|Unsupervised Domain Adaptation of Black-Box Source Models ([paper](https://arxiv.org/pdf/2101.02839.pdf))|Arvix 2021||source-free, black|new problem|
|79|Shuffle and Attend: Video Domain Adaptation ([paper](https://www.nec-labs.com/uploads/Documents/Media-Analytics/research-papers/Shuffle_and_Attend_Video_Domain_Adaptation.pdf))|ECCV 2020|[code](https://github.com/jinwchoi/SAVA.github.io)(not released now)|video DA||
|78|Adversarial Bipartite Graph Learning for Video Domain Adaptation ([paper](https://arxiv.org/abs/2007.15829))|MM 2020|[code](https://github.com/Luoyadan/MM2020_ABG)|video DA||
|77|Action Segmentation with Joint Self-Supervised Temporal Domain Adaptation ([paper](http://openaccess.thecvf.com/content_CVPR_2020/html/Chen_Action_Segmentation_With_Joint_Self-Supervised_Temporal_Domain_Adaptation_CVPR_2020_paper.html))|CVPR 2020|[code](https://github.com/cmhungsteve/SSTDA)|video, UDA||
|76|Continuous Domain Adaptation with Variational Domain-Agnostic Feature Replay ([paper](https://arxiv.org/pdf/2003.04382.pdf))|arvix 2020||continual DA|new question|
|75|Continual Learning for Domain Adaptation in Chest X-ray Classification ([paper](https://arxiv.org/pdf/2001.05922.pdf))|MLR 2020(under review)||continual DA|new question|
|74|Continual Domain Adaptation for Machine Reading Comprehension ([paper](https://arxiv.org/pdf/2008.10874.pdf))|CIKM 2020||continual DA|new question|
|73|Continual Unsupervised Domain Adaptation with Adversarial Learning ([paper](https://arxiv.org/pdf/2010.09236.pdf))|arvix 2020||continual DA|new question|
|72|Continual Adaptation of Visual Representations via Domain Randomization and Meta-learning ([paper](https://arxiv.org/pdf/2012.04324.pdf))|arvix 2020||continual DA|new question|
|71|Unsupervised Domain Adaptation without Source Data by Casting a BAIT ([paper](https://arxiv.org/pdf/2010.12427.pdf))|arvix 2020||source-free DA, prototype|good idea|
|70|A Review of Single-Source Deep Unsupervised Visual Domain Adaptation ([paper](https://arxiv.org/pdf/2009.00155v3.pdf))|arvix 2020||DA survey|good further directions|
|69|Supervised Contrastive Learning ([paper](https://arxiv.org/pdf/2004.11362.pdf))|NeurIPS 2020|[code](https://github.com/HobbitLong/SupContrast)|supervised CL||
|68|Discover, Hallucinate, and Adapt: Open Compound Domain Adaptation for Semantic Segmentation ([paper](https://proceedings.neurips.cc/paper/2020/file/7a9a322cbe0d06a98667fdc5160dc6f8-Paper.pdf))|NeruIPS 2020||open compound, DA|new problem|
|67|Your Classifier can Secretly Suffice Multi-Source Domain Adaptation ([paper](https://papers.nips.cc/paper/2020/file/3181d59d19e76e902666df5c7821259a-Paper.pdf))|NeruIPS 2020 |[code](https://sites.google.com/view/simpal)|MS, prediction agreement|simple yet effective method, new findings|
|66|Self-paced Contrastive Learning with Hybrid Memory for Domain Adaptive Object Re-ID ([paper](https://arxiv.org/abs/2006.02713))|NIPS 2020|[code](https://github.com/yxgeee/SpCL)|contrastive learning, DA, Re-ID|contrastive learning + DA|
|65|Unsupervised Domain Adaptation without Source Data by Casting a BAIT([paper](https://arxiv.org/pdf/2010.12427.pdf))|Arvix 2020||source-free, two classifiers|good idea|
|64|An Adversarial Domain Adaptation Network for Cross-Domain Fine-Grained Recognition([paper](https://openaccess.thecvf.com/content_WACV_2020/papers/Wang_An_Adversarial_Domain_Adaptation_Network_for_Cross-Domain_Fine-Grained_Recognition_WACV_2020_paper.pdf))|WACV 2020|[code](https://yimuwang96.github.io/DA-Retail/index.html#1-abstract)|fine-grained, DA| new question|
|63|Class-incremental Learning via Deep Model Consolidation ([paper](https://openaccess.thecvf.com/content_WACV_2020/papers/Zhang_Class-incremental_Learning_via_Deep_Model_Consolidation_WACV_2020_paper.pdf))|WACV 2020||||
|62|Impact of ImageNet Model Selection on Domain Adaptation([paper](https://openaccess.thecvf.com/content_WACVW_2020/papers/w3/Zhang_Impact_of_ImageNet_Model_Selection_on_Domain_Adaptation_WACVW_2020_paper.pdf))|WACV 2020 workshop||shallow methods with different deep features|**实验结果很迷惑**|
|61|Measuring Information Transfer in Neural Networks ([paper](https://arxiv.org/pdf/2009.07624.pdf))|arvix 2020|||maybe useful for DA|
|60|Open-Set Hypothesis Transfer with Semantic Consistency ([paper](https://arxiv.org/pdf/2010.00292.pdf))|arvix 2020||source free, open set||
|59|Don’t Stop Pretraining: Adapt Language Models to Domains and Tasks([paper](https://arxiv.org/pdf/2004.10964.pdf))|arvix 2020||pretraining|good papers|
|58|Measuring Information Transfer in Neural Networks([paper](https://arxiv.org/pdf/2009.07624.pdf))||||interesting paper|
|57|When Semi-Supervised Learning Meets Transfer Learning: Training Strategies, Models and Datasets([paper](https://arxiv.org/pdf/1812.05313.pdf))|||SSL, TL, experiments|many results related to multiple SSL methods can be seen in this paper|
|56|Learning the Stein Discrepancy for Training and Evaluating Energy-Based Models without Sampling ([paper](https://arxiv.org/pdf/2002.05616.pdf))|ICML 2020||stein discrepancy|a new metric that is never used in DA|
|55|Graph Optimal Transport for Cross-Domain Alignment ([paper]())|ICML 2020||Graph, optimal transport, DA||
|54|Unsupervised Transfer Learning for Spatiotemporal Predictive Networks ([paper](http://ise.thss.tsinghua.edu.cn/~mlong/doc/transferable-memory-icml20.pdf))|ICML 2020||||
|53|Estimating Generalization under Distribution Shifts via Domain-Invariant Representations ([paper](http://people.csail.mit.edu/stefje/papers/chuang_icml20.pdf))|ICML 2020|[code](https://github.com/chingyaoc/estimating-generalization)|new theory|**recommend to read**|
|52|Implicit Class-Conditioned Domain Alignment for Unsupervised Domain Adaptation ([paper](https://arxiv.org/pdf/2006.04996.pdf))|ICML 2020|[code](https://github.com/xiangdal/implicit_alignment)|ideas from theory|**recommend to read**|
|51|LEEP: A New Measure to Evaluate Transferability of Learned Representations ([paper](https://arxiv.org/pdf/2002.12462.pdf))|ICML 2020||new metric for transferability|easy to use for other tasks|
|50|Label-Noise Robust Domain Adaptation|ICML2020|||the author is a rising star|
|49|Progressive Graph Learning for Open-Set Domain Adaptation ([paper](https://arxiv.org/abs/2006.12087))|ICML 2020|[code](https://github.com/BUserName/PGL)|open set DA||
|48|Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation ([paper](https://arxiv.org/abs/2002.08546))|ICML 2020|[code](https://github.com/tim-learn/SHOT)|source-free DA |**recommend to read, new trneds**|
|47|Graph Optimal Transport for Cross-Domain Alignment ([paper](https://arxiv.org/pdf/2006.14744v2.pdf))|ICML 2020||graph for DA| connenction with GCN |
|46|Learning Deep Kernels for Non-Parametric Two-Sample Tests ([paper](https://arxiv.org/pdf/2002.09116.pdf))|ICML 2020|[code](https://github.com/fengliu90/DK-for-TST)|extend MMD to deep||
|45| Adversarial-Learned Loss for Domain Adaptation  | AAAI 2020 |  | noisy label, adversarial learning ||
|44|Transfer Learning for Anomaly Detection through Localized and Unsupervised Instance Selection| AAAI 2020 || transfer learning, anamaly detection||
|43|Dynamic Instance Normalization for Arbitrary Style Transfer|AAAI 2020| |dynamic instance normalization||
|42|AdaFilter: Adaptive Filter Fine-Tuning for Deep Transfer Learning|AAAI 2020||gated output, fine-tune||
|41|Bi-Directional Generation for Unsupervised Domain Adaptation|AAAI 2020||differert feature extractor, different classifiers|connection with ICML, the third term|
|40|Discriminative Adversarial Domain Adaptation|AAAI 2020| | discriminative information with adversarial learning||
|39|Domain Generalization Using a Mixture of Multiple Latent Domains|AAAI 2020||||
|38|Multi-Source Distilling Domain Adaptation|AAAI 2020||multi-source||
|37|Cross-Modal Cross-Domain Moment Alignment Network for Person Search ([paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Jing_Cross-Modal_Cross-Domain_Moment_Alignment_Network_for_Person_Search_CVPR_2020_paper.pdf))|CVPR 2020||cross-modal, DA, Person search|new problem|
|36|Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision|CVPR 2020|[code](https://github.com/feipan664/IntraDA)|Entropy adversarial based||
|35|Rethinking Class-Balanced Methods for Long-Tailed Visual Recognition from a Domain Adaptation Perspective|CVPR 2020||long-tailed||
|34|Unsupervised Domain Adaptation via Structurally Regularized Deep Clustering|CVPR 2020|[code](https://github.com/huitangtang/SRDC-CVPR2020)|cluster||
|33|Stochastic Classifiers for Unsupervised Domain Adaptation|CVPR 2020||stochastic two classifiers|simialer to MCD|
|32|Progressive Adversarial Networks for Fine-Grained Domain Adaptation|CVPR 2020||fine-grained|similar to mutil-aspect opinion analysis|
|31|Model Adaptation: Unsupervised Domain Adaptation without Source Data|CVPR 2020|||**Recommend to read, new problems**|
|30|Towards Inheritable Models for Open-Set Domain Adaptation|CVPR 2020|[code](https://sites.google.com/view/inheritune)|||
|29|Unsupervised Domain Adaptation with Hierarchical Gradient Synchronization ([paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Hu_Unsupervised_Domain_Adaptation_With_Hierarchical_Gradient_Synchronization_CVPR_2020_paper.pdf))|CVPR 2020||class gropu, DA|new idea|
|28|Attract, Perturb, and Explore: Learning a Feature Alignment Network for Semi-supervised Domain Adaptation ([paper](https://arxiv.org/pdf/2007.09375.pdf))|ECCV 2020|[code](https://github.com/TKKim93/APE)|SSDA, intar-domain discrepancy|**good questions**|
|27|Joint Disentangling and Adaptation for Cross-Domain Person Re-Identification|ECCV 2020||||
|26|Extending and Analyzing Self-Supervised Learning Across Domains ([paper](https://arxiv.org/pdf/2004.11992.pdf))|ECCV 2020||||
|25|Dual Mixup Regularized Learning for Adversarial Domain Adaptation ([paper](https://arxiv.org/pdf/2007.03141.pdf))|ECCV 2020||||
|24|Label Propagation with Augmented Anchors: A Simple Semi-Supervised Learning baseline for Unsupervised Domain Adaptation ([paper](https://arxiv.org/pdf/2007.07695.pdf)|ECCV 2020|[code](https://github.com/YBZh/Label-Propagation-with-Augmented-Anchors)|SSL reguralization, Anchors|new methods, good writings|
|23|Class-Incremental Domain Adaptation([paper](https://arxiv.org/pdf/2008.01389.pdf))|ECCV 2020|||new problems|
|22|Simultaneous Semantic Alignment Network for Heterogeneous Domain Adaptation ([paper](https://arxiv.org/pdf/2008.01677.pdf))|ACM MM 2020|[code](https://github.com/BIT-DA/SSAN)|||
|21|Adversarial Graph Representation Adaptation for Cross-Domain Facial Expression Recognition ([paper](https://arxiv.org/pdf/2008.00859.pdf))|ACM MM 2020|||similar idea with us|
|20|Do Adversarially Robust ImageNet Models Transfer Better?|arvix 2020|[code](https://github.com/Microsoft/robust-models-transfer)|Many experiments||
|19|Visualizing Transfer Learning|arvix 2020||interesting||
|18|A SURVEY ON DOMAIN ADAPTATION THEORY:LEARNING BOUNDS AND THEORETICAL GUARANTEES ([paper](https://arxiv.org/pdf/2004.11829.pdf))|arvix 2020||theory||
|17|Joint Disentangling and Adaptation for Cross-Domain Person Re-Identification ([paper](https://arxiv.org/pdf/2007.10315.pdf))|arvix 2020|||Good ideas|
|16|Towards Recognizing Unseen Categories in Unseen Domains ([paper](https://arxiv.org/pdf/2007.12256.pdf))|arvix 2020|||new problems|
|15|MiCo: Mixup Co-Training for Semi-Supervised Domain Adaptation ([paper](https://arxiv.org/pdf/2007.12684.pdf))|arvix 2020|||good framework|
|14|Dynamic Knowledge Distillation for Black-box Hypothesis Transfer Learning ([paper](https://arxiv.org/pdf/2007.12355.pdf)|arvix 2020||||
|13|Learning from a Complementary-label Source Domain: Theory and Algorithms([paper](https://arxiv.org/pdf/2008.01454.pdf))|arvix 2020|[code](https://github.com/Yiyang98/BFUDA)||novel idea|
|12|A Review of Single-Source Deep Unsupervised Visual Domain Adaptation [paper](https://arxiv.org/pdf/2009.00155.pdf)|arvix 2020||Review|a good review! It contains many results of the state-of-the-art method|
|11|Neural transfer learning for natural language processing（[paper](https://aran.library.nuigalway.ie/bitstream/handle/10379/15463/neural_transfer_learning_for_nlp.pdf?sequence=1))|2019 PDH thesis||NLP, transfer lerning|very detailed related work|
|10|Drop to Adapt: Learning Discriminative Features for Unsupervised Domain Adaptation ([paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Lee_Drop_to_Adapt_Learning_Discriminative_Features_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf))|ICCV 2019|[code](https://github.com/postBG/DTA.pytorch)|Cluster assumption, DA|deal with misclassified samples|
|9|SpotTune: Transfer Learning through Adaptive Fine-tuning ([paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Guo_SpotTune_Transfer_Learning_Through_Adaptive_Fine-Tuning_CVPR_2019_paper.pdf))|CVPR 2019|[code](https://github.com/gyhui14/spottune)||dynamic routing is a general method|
|8|Parameter Transfer Unit for Deep Neural Networks ([paper](https://arxiv.org/abs/1804.08613))|PAKDD 2019 best paper|||good idea, **recommened  to read**|
|7|Heterogeneous Domain Adaptation via Soft Transfer Network ([paper](https://arxiv.org/pdf/1908.10552v1.pdf))|ACM MM 2019||||
|6|DARec: Deep Domain Adaptation for Cross-Domain Recommendation via Transferring Rating Patterns ([paper](https://www.ijcai.org/Proceedings/2019/0587.pdf))|IJCAI 2019||DA, cross-domain recommendation|classical work|
|5|Adversarial Domain Adaptation with Domain Mixup ([paper](https://arxiv.org/pdf/1912.01805.pdf))|IJCAI 2019||mix-ip, DA|new idea|
|4|Temporal Attentive Alignment for Large-Scale Video Domain Adaptation ([paper](http://openaccess.thecvf.com/content_ICCV_2019/html/Chen_Temporal_Attentive_Alignment_for_Large-Scale_Video_Domain_Adaptation_ICCV_2019_paper.html))|ICCV 2019|[code](https://github.com/cmhungsteve/TA3N)|video, DA| the first work with large dataset|
|3|PointDAN: A Multi-Scale 3D Domain Adaption Network for Point Cloud Representation ([paper](https://proceedings.neurips.cc/paper/2019/file/3341f6f048384ec73a7ba2e77d2db48b-Paper.pdf))|NeurIPS 2019|[code](https://github.com/canqin001/PointDAN)|DA, point cloud||
|2|Incremental Adversarial Domain Adaptation for Continually Changing Environments ([paper](https://www.robots.ox.ac.uk/~mobile/Papers/2018ICRA_wulfmeier.pdf))|ICRA 2018||continual DA|new question|
|1|ADAPTING TO CONTINUOUSLY SHIFTING DOMAINS ([paper](https://openreview.net/pdf?id=BJsBjPJvf))|ICLR 2018 workshop||continual DA|new question|
|0|Information-Theoretical Learning of Discriminative Clusters for Unsupervised Domain Adaptation ([paper](https://icml.cc/2012/papers/566.pdf))|ICML 2012||||
### 2) Novel_papers on related fileds
|number|  Title   | Conference/journel + year| Code | Keywords |  Benenit for us |
| ---- | ----  | ----  | ---- | ---- | ---- |
|22|MixMo: Mixing Multiple Inputs for Multiple Outputs via Deep Subnetworks ([paper](https://arxiv.org/pdf/2103.06132.pdf))|ICCV 2021||data augmentation||
|21|Amplitude-Phase Recombination: Rethinking Robustness of Convolutional Neural Networks in Frequency Domain ([paper](https://arxiv.org/pdf/2108.08487.pdf))|ICCV 2021|[code](https://github.com/iCGY96/APR)|data augmentation|maybe useful for UDA|
|20|OpenWGL: Open-World Graph Learning ([paper](https://par.nsf.gov/servlets/purl/10199471))|ICDM 2020| |open node classification|best student paper|
|19|FREE LUNCH FOR FEW-SHOT LEARNING: DISTRIBUTION CALIBRATION ([paper](https://arxiv.org/pdf/2101.06395.pdf))|ICLR 2021|[code](https://github.com/ShuoYang-1998/ICLR2021-Oral_Distribution_Calibration)|calibation| maybe for UDA|
|18| Semi-Supervised Action Recognition with Temporal Contrastive Learning([paper](https://rpand002.github.io/data/CVPR_2021_TCL.pdf))|CVPR 2021|[project](https://cvir.github.io/TCL/)|action recognition||
|17|Continual Adaptation of Visual Representations via Domain Randomization and Meta-Learning ([paper](https://arxiv.org/abs/2012.04324))|CVPR 2021||||
|16|Wasserstein-2 Generative Networks ([paper](https://openreview.net/pdf?id=bEoxzW_EXsa))|ICLR 2021||GAN， wassertein||
|15|Prototypical Contrastive Learning of Unsupervised Representations([paper](https://openreview.net/pdf?id=KmykpuSrjcq))|ICLR 2021||prototype, constractive learning|maybe for UDA|
|14|Self-Loop Uncertainty: A Novel Pseudo-Label for Semi-Supervised Medical Image Segmentation ([paper](https://arxiv.org/abs/2007.09854))|MICCAI 2020||ssl, pseudo label||
|13|Not All Unlabeled Data are Equal: Learning to Weight Data in Semi-supervised Learning ([paper](https://arxiv.org/pdf/2007.01293v1.pdf))|NIPS 2020||semi-supervised, weight smaples|it can be used in our work|
|12|Safe semi-supervised learning: a brief introduction ([paper](http://www.lamda.nju.edu.cn/liyf/paper/FCS19-SafeSSL.pdf))|||safe ssl|new concept, maybe useful for negative transfer|
|11|Safe Deep Semi-Supervised Learning for Unseen-Class Unlabeled Data ([paper](https://proceedings.icml.cc/static/paper_files/icml/2020/3231-Paper.pdf))|ICML 2020|[code](https://www.lamda.nju.edu.cn/code_DS3L)|ssl, unseen class|open set, maybe useful for negative transfer|
|10| (RECORD: Resource Constrained Semi-Supervised Learning under Distribution Shif[paper](http://www.lamda.nju.edu.cn/guolz/KDD2020_RECORD.pdf))|KDD 2020||online, distribution shift|maybe useful for negative transfer|
|9|Adversarial Examples Improve Image Recognition ([paper](http://boqinggong.info/papers/cvpr20-advprop.pdf))|CVPR 2020||Adversarial examples, image recognition, batch normalization|Same idea can be explored in DA|
|8| Collaborative Graph Convolutional Networks: Unsupervised Learning Meets Semi-Supervised Learning  | AAAI 2020 |  | unsupervised learning, semi-supervised learning ||
|7|Self-supervised Label Augmentation via Input Transformations|ICML 2020|[code](https://github.com/hankook/SLA)|self-supervised|ideas can be used to many tasks|
|6|Learning with Multiple Complementary Labels ([paper](https://arxiv.org/pdf/1912.12927.pdf))|ICML 2020||||
|5|Deep Divergence Learning ([paper](https://arxiv.org/pdf/2005.02612.pdf))|ICML 2020||divergence||
|4|Confidence-Aware Learning for Deep Neural Networks ([paper](https://arxiv.org/pdf/2007.01458.pdf))|ICML 2020|[code](https://github.com/daintlab/confidence-aware-learning)|confidence||
|3|Continual Learning in Human Activity Recognition:an Empirical Analysis of Regularization ([paper](https://arxiv.org/pdf/2007.03032.pdf))|ICML workshop|[code](https://github.com/srvCodes/continual-learning-benchmark)|Continual learning bechmark||
|2|Automated Phrase Mining from Massive Text Corpora ([paper](https://arxiv.org/pdf/1702.04457.pdf))|||||
|1|Adversarially-Trained Deep Nets Transfer Better([paper](https://arxiv.org/pdf/2007.05869.pdf)|arvix 2020|||new findings|
|0|Learning to Combine: Knowledge Aggregation for Multi-Source Domain Adaptation|arvix ([paper](https://arxiv.org/pdf/2007.08801.pdf))|||same ideas with us|

## Workshop collection
|  Title   | Conference + year| speaker |  Benenit for us |
|  ----  | ----  | ---- | ---- |
|Learning from Imperfect Data ([link](https://lidchallenge.github.io/index.html))| CVPR 2020 | ||
|Cross-Domain Few-Shot Learning (CD-FSL) Challenge ([link](https://www.learning-with-limited-labels.com/challenge))|CVPR 2020|||
|Uncertainty and Robustness in Deep Learning Workshop ([link](https://icml.cc/Conferences/2020/Schedule?showEvent=5717))|ICML 2020|

<!--
## tutorial_collection
|  Title   | Conference + year| speaker |  Benenit for us |
|  ----  | ----  | ---- | ---- |
|Weakly Supervised Domain Adaptation with Deep Learning ([link](http://mhug.disi.unitn.it/tutorial-acmmm16/pdf/dda-xgw.pdf))| ACM MM 2016 | Xiaogang Wang||
-->

## Other githubs
- [王晋东](https://github.com/jindongwang)
- [ThuML](https://github.com/thuml)
- [Awesome-1](https://github.com/zhaoxin94/awsome-domain-adaptation#distance-based-methods)
- [Awesome-2](https://github.com/barebell/DA)
