---
#layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


<!-- ## *Learning from Multi-modality Data* -->


## *Learning with Noisy Labeled Data*

> In the medical domain, acquiring high-quality pixel-level annotations is often difficult due to the lack of experienced annotators and visual ambiguity in object boundaries. With limited budgets and efforts, the resulting annotated datasets would involve a varying amount of label noise, ranging from small boundary offsets to large region errors. The presence of label noises may mislead the segmentation model to memorize wrong semantic correlations, resulting in severely degraded generalizability. Hence, developing medical image segmentation techniques that are robust to noisy labels in training data is of great importance. We are interested in both closed-set and open-set label noises. We investigate label noises under the setting of weakly-supervised learning, semi-supervised learning, and domain adaptation. 
> ### *Relevant Publications:*
> * <a href="https://link.springer.com/chapter/10.1007/978-3-031-16440-8_56" target="_blank">Joint Class-Affinity Loss Correction for Robust Medical Image > Segmentation with Noisy Labels</a> [MICCAI'22]
> * <a href="https://openaccess.thecvf.com/content/CVPR2022/html/Guo_SimT_Handling_Open-Set_Noise_for_Domain_Adaptive_Semantic_Segmentation_CVPR_2022_paper.html" target="_blank">SimT: Handling Open-set Noise for Domain Adaptive Semantic Segmentation</a> [CVPR'22]
> * <a href="https://www.sciencedirect.com/science/article/abs/pii/S1361841522000469" target="_blank">Non-equivalent images and pixels: confidence-aware resampling with meta-learning mixup for polyp segmentation</a> [MedIA'22]
> * <a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930328.pdf" target="_blank">Unknown-Oriented Learning for Open Set Domain Adaptation</a> [ECCV'22]
> * <a href="https://doi.org/10.1016/j.media.2021.102196" target="_blank">Dynamic-weighting Hierarchical Segmentation Network for Medical Images</a> [MedIA'21]
> * <a href="https://openaccess.thecvf.com/content/CVPR2021/html/Guo_MetaCorrection_Domain-Aware_Meta_Loss_Correction_for_Unsupervised_Domain_Adaptation_in_CVPR_2021_paper.html" target="_blank">MetaCorrection: Domain-aware Meta Loss Correction for Unsupervised Domain Adaptation in Semantic Segmentation</a> [CVPR'21]

![Words](https://github.com/Guo-Xiaoqing/Guo-Xiaoqing.github.io/raw/master/images/noisy_labeled_data.png)



## *Learning from Cross-domain Labeled Data*

> With only unlabeled data available, we can transfer the knowledge learned from virtually synthesized labeled data, public labeled data, or labeled data from other medical centers (source domain data) to our unlabeled target domain data. In this scenario, when directly applied to target data, fully supervised learning models that learn on source data usually result in significant performance degradation and show unsatisfactory generalizability due to the domain gap. For instance, colonoscopy images from multiple centers often exhibit different imaging conditions, such as illumination effect and color distribution, because imaging devices and parameter settings are not well standardized. Therefore, bridging the domain gap is the key to effectively leveraging cross-domain labeled data for improving generalizability on unlabeled target domain data. We are interested in unsupervised domain adaptation, source free domain adaptation, and open-set domain adaptation.
> ### *Relevant Publications:*
> * <a href="https://openaccess.thecvf.com/content/CVPR2022/html/Guo_SimT_Handling_Open-Set_Noise_for_Domain_Adaptive_Semantic_Segmentation_CVPR_2022_paper.html" target="_blank">SimT: Handling Open-set Noise for Domain Adaptive Semantic Segmentation</a> [CVPR'22]
> * <a href="https://www.sciencedirect.com/science/article/pii/S1361841522001049" target="_blank">Source Free Domain Adaptation for Medical Image Segmentation with Fourier Style Mining</a> [MedIA'22]
> * <a href="https://ieeexplore.ieee.org/document/9583929" target="_blank">Graph-based Surgical Instrument Adaptive Segmentation via Domain-Common Knowledge</a> [TMI'22]
> * <a href="https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930328.pdf" target="_blank">Unknown-Oriented Learning for Open Set Domain Adaptation</a> [ECCV'22]
> * <a href="https://openaccess.thecvf.com/content/CVPR2021/html/Guo_MetaCorrection_Domain-Aware_Meta_Loss_Correction_for_Unsupervised_Domain_Adaptation_in_CVPR_2021_paper.html" target="_blank">MetaCorrection: Domain-aware Meta Loss Correction for Unsupervised Domain Adaptation in Semantic Segmentation</a> [CVPR'21]
> * <a href="https://doi.org/10.1016/j.media.2021.102052" target="_blank">Consolidated domain adaptive detection and localization framework for cross-device colonoscopic images</a> [MedIA'21]
> * <a href="https://ieeexplore.ieee.org/document/9423517" target="_blank">Mutual-Prototype Adaptation for Cross-Domain Polyp Segmentation</a> [JBHI'21]
> * <a href="https://ieeexplore.ieee.org/document/9636111" target="_blank">COINet: Adaptive Segmentation with Co-Interactive Network for Autonomous Driving</a> [IROS'21]
> * <a href="https://link.springer.com/chapter/10.1007/978-3-030-87199-4_26" target="_blank">Prototypical Interaction Graph for Unsupervised Domain Adaptation in Surgical Instrument Segmentation</a> [MICCAI'21]

![Words](https://github.com/Guo-Xiaoqing/Guo-Xiaoqing.github.io/raw/master/images/cross_domain_data.png)



## *Learning from Massive Unlabeled Data*

> Since the data distribution bias depends on the sample size, the scarce labeled data distribution often deviates from the desired one due to the small sample size, which inevitably leads to the overfitting problem of the optimized model. Fortunately, the unlabeled data is abundant and easy to access in real clinical practice. To make adequate use of unlabeled data along with scarce labeled data, we investigate the semi-supervised learning (SSL) methods in medical image diagnosis and segmentation. These SSL methods are capable of building better models that compensate for the lack of labeled training data, and are demonstrated to be beneficial for enhancing the generalizability of medical image analysis models. Moreover, we rethink the overfitting problem caused by scarce labeled data and propose a new strategy, coined Labeled-to-unlabeled Distribution Translation (L2uDT), by taking the advantages of data augmentation and SSL methods, aiming at alleviating the labeled data distribution bias problem. 
> ### *Relevant Publications:*
> * <a href="https://ieeexplore.ieee.org/document/9541376" target="_blank">Semantic-oriented Labeled-to-unlabeled Distribution Translation for Image Segmentation</a> [TMI'22]
> * <a href="https://doi.org/10.1016/j.media.2020.101733" target="_blank">Semi-supervised WCE Image Classification with Adaptive Aggregated Attention</a> [MedIA'20]
> * <a href="https://ieeexplore.ieee.org/document/9098417" target="_blank">Complementary Network with Adaptive Receptive Fields for Melanoma Segmentation</a> [ISBI’20]

![Words](https://github.com/Guo-Xiaoqing/Guo-Xiaoqing.github.io/raw/master/images/massive_unlabeled_data.png)



## *Learning with Scarce Labeled Data*

> Deep learning methods generally require large amounts of annotated data to prevent overfitting problem, which is a common concern when the model fitted to a limited training set results in a poor generalization ability to test data. However, high-quality annotated datasets are scarce in the medical domain, especially in *medical image segmentation* and *rare disease diagnosis*. Because manual pixel-wise annotations in medical image segmentation requires professional medical knowledge as well as a high degree of concentration, and it is hard to collect sufficient training data for rare diseases in practice. Consequently, the lack of abundant annotated datasets becomes a bottleneck to deep learning-based methods in medical image analysis. We are interested in learning with scarce labeled data through data augmentation and few-shot learning.
> ### *Relevant Publications:*
> * <a href="https://www.sciencedirect.com/science/article/abs/pii/S1361841522000469" target="_blank">Non-equivalent images and pixels: confidence-aware resampling with meta-learning mixup for polyp segmentation</a> [MedIA'22]
> * <a href="https://link.springer.com/chapter/10.1007/978-3-031-16437-8_49" target="_blank">Disentangle then Calibrate: Selective Treasure Sharing for Generalized Rare Disease Diagnosis</a> [MICCAI'22]
> * <a href="https://ieeexplore.ieee.org/document/9305717" target="_blank">Learn to Threshold: ThresholdNet with Confidence-Guided Manifold Mixup for Polyp Segmentation</a> [TMI’21]

![Words](https://github.com/Guo-Xiaoqing/Guo-Xiaoqing.github.io/raw/master/images/scarce_labeled_data.png)
