---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently an associate professor of School of Computer Science, NWPU.

My research interest includes pansharpening, multi-source image fusion and detection, image enhancement and infrared target detection. I have published more than 30 papers at the top international journal and conference.

# 🔥 News
- *2024.09.09*: &nbsp;🎉🎉 One paper is accepted by IEEE TIP.
- *2024.07.22*: &nbsp;🎉🎉 One paper is accepted by IEEE TGRS. 
- *2024.07.12*: &nbsp;🎉🎉 One paper is accepted by IEEE TITS.
- *2024.07.09*: &nbsp;🎉🎉 One paper is accepted by IEEE TMM.
- *2024.07.01*: &nbsp;🎉🎉 One paper is accepted by ECCV.


# 📝 Publications 
2024
- [Visual Prompt Tuning in Null Space for Continual Learning](https://arxiv.org/abs/2406.05658).
Yue Lu, Shizhou Zhang, De Cheng, **Yinghui Xing**, Nannan Wang, Peng Wang, Yanning Zhang, **NeuraIPS**, 2024.

- [CrossDiff: Exploring Self-Supervised Representation of Pansharpening via Cross-Predictive Diffusion Model](https://ieeexplore.ieee.org/abstract/document/10685062).
**Yinghui Xing**, Litao Qu, Shizhou Zhang, Kai Zhang, Yanning Zhang, Lorenzo Bruzzone, **IEEE Transactions on Image Processing**, 2024.
[**Code**](https://github.com/codgodtao/CrossDiff) 

- [Frequency-Guided Spatial Adaptation for Camouflaged Object Detection](https://arxiv.org/abs/2409.12421).
Shizhou Zhang, Dexuan Kong, **Yinghui Xing**, Yue Lu, Lingyan Ran, Guoqiang Liang, Hexu Wang, Yanning Zhang, **IEEE Transactions on Multimedia**, 2024.

- [MS-DETR: Multispectral Pedestrian Detection Transformer with Loosely Coupled Fusion and Modality-Balanced Optimization](https://ieeexplore.ieee.org/abstract/document/10669167).
**Yinghui Xing**, Shuo Yang, Song Wang, Shizhou Zhang, Guoqiang Liang, Xiuwei Zhang, Yanning Zhang, **IEEE Transactions on Intelligent Transportation Systems**, 2024.
[**Code**](https://github.com/YinghuiXing/MS-DETR)

- [Cross-Platform Video Person ReID: A New Benchmark Dataset and Adaptation Approach](https://arxiv.org/abs/2408.07500).
Shizhou Zhang, Wenlong Luo, De Cheng, Qingchun Yang, Lingyan Ran, **Yinghui Xing**, Yanning Zhang, **ECCV**, 2024.
[**Code**](https://github.com/FHR-L/VSLA-CLIP)

- [DDF: A Novel Dual-Domain Image Fusion Strategy for Remote Sensing Image Semantic Segmentation with Unsupervised Domain Adaptation](https://ieeexplore.ieee.org/abstract/document/10620432).
Lingyan Ran, Lushuang Wang, Tao Zhuo, **Yinghui Xing**, Houjun He, Yanning Zhang, **IEEE Transactions on Geoscience and Remote Sensing**, 2024.

- [Empower Generalizability for Pansharpening Through Text-Modulated Diffusion Model](https://ieeexplore.ieee.org/abstract/document/10613790).
**Yinghui Xing**, Litao Qu, Shizhou Zhang, Jiapeng Feng, Xiuwei Zhang, Yanning Zhang, **IEEE Transactions on Geoscience and Remote Sensing**, 2024.
[**Code**](https://github.com/codgodtao/TMDiff)

- [Complementary Fusion Network Based on Frequency Hybrid Attention for Pansharpening](https://ieeexplore.ieee.org/abstract/document/10446416).
**Yinghui Xing**, Litao Qu, Kai Zhang, Yan Zhang, Xiuwei Zhang, Yanning Zhang, **ICASSP**, 2024.

- [Improving Reliability of Heterogeneous Change Detection by Sample Synthesis and Knowledge Transfer](https://ieeexplore.ieee.org/abstract/document/10480439).
**Yinghui Xing**, Qi Zhang, Lingyan Ran, Xiuwei Zhang, Hanlin Yin, Yanning Zhang, **IEEE Transactions on Geoscience and Remote Sensing**, 2024.
[**Code**](https://github.com/zhangqiiii/SS-KT)

2023
- [Text-based person search in full images via semantic-driven proposal generation](https://dl.acm.org/doi/abs/10.1145/3606041.3618058).
Shizhou Zhang, De Cheng, Wenlong Luo, **Yinghui Xing**, Duo Long, Hao Li, Kai Niu, Guoqiang Liang, Yanning Zhang, **ACM MM Workshop Best Paper Award**, 2023.

- [FastICENet: A real-time and accurate semantic segmentation model for aerial remote sensing river ice image](https://www.sciencedirect.com/science/article/pii/S0165168423002244).
Xiuwei Zhang, Zixu Zhao, Lingyan Ran, **Yinghui Xing**, Wenna Wang, Zeze Lan, Hanlin Yin, Houjun He, Qixing Liu, Baosen Zhang, Yanning Zhang, **Signal Processing**, 2023.

- [Automatic Network Architecture Search for RGB-D Semantic Segmentation](https://dl.acm.org/doi/abs/10.1145/3581783.3612288).
Wenna Wang, Tao Zhuo, Xiuwei Zhang, Mingjun Sun, Hanlin Yin, **Yinghui Xing**, Yanning Zhang, **ACM MM**, 2023.

- [Ground-to-aerial person search: Benchmark dataset and approach](https://dl.acm.org/doi/abs/10.1145/3581783.3612105).
Shizhou Zhang, Qingchun Yang, De Cheng, **Yinghui Xing**, Guoqiang Liang, Peng Wang, Yanning Zhang, **ACM MM**, 2023.
[**Code**](https://github.com/yqc123456/HKD_for_person_search)

- [SSML-QNet: scale-separative metric learning quadruplet network for multi-modal image patch matching](https://dl.acm.org/doi/abs/10.24963/ijcai.2023/511).
Xiuwei Zhang, Yi Sun, Yamin Han, Yanping Li, Hanlin Yin, **Yinghui Xing**, Yanning Zhang, **IJCAI**, 2023.

- [Progressive modality-alignment for unsupervised heterogeneous change detection](https://ieeexplore.ieee.org/abstract/document/10177987).
**Yinghui Xing**, Qi Zhang, Lingyan Ran, Xiuwei Zhang, Hanlin Yin, Yanning Zhang, **IEEE Transactions on Geoscience and Remote Sensing**, 2023.

- [Dual modality prompt tuning for vision-language pre-trained model](https://ieeexplore.ieee.org/abstract/document/10171397).
**Yinghui Xing**, Qirui Wu, De Cheng, Shizhou Zhang, Guoqiang Liang, Peng Wang, Yanning Zhang, **IEEE Transactions on Multimedia**, 2023.
[**Code**](https://github.com/fanrena/DPT)

- [Runoff predictions in new-gauged basins using two transformer-based models](https://www.sciencedirect.com/science/article/pii/S0022169423006261).
Hanlin Yin, Wu Zhu, Xiuwei Zhang, **Yinghui Xing**, Runliang Xia, Jifeng Liu, Yanning Zhang, **Journal of Hydrology**, 2023.

- [AugFCOS: Augmented fully convolutional one-stage object detection network](https://www.sciencedirect.com/science/article/pii/S0031320322005787).
Xiuwei Zhang, Wei Guo, **Yinghui Xing**, Wenna Wang, Hanlin Yin, Yanning Zhang, **Pattern Recognition**, 2023.

- [ADHR-CDNet: Attentive differential high-resolution change detection network for remote sensing images](https://ieeexplore.ieee.org/abstract/document/9946010).
Xiuwei Zhang, Mu Tian, **Yinghui Xing**, Yuanzeng Yue, Yanping Li, Hanlin Yin, Runliang Xia, Jin Jin, Yanning Zhang, **IEEE Transactions on Geoscience and Remote Sensing**, 2023.
[**Code**](https://github.com/w-here/ASGO-113lab/tree/main/ADHR-CDNet)

2022
- [Learning spectral cues for multispectral and panchromatic image fusion](https://ieeexplore.ieee.org/abstract/document/9935814).
**Yinghui Xing**, Shuyuan Yang, Yan Zhang, Yanning Zhang, **IEEE Transactions on Image Processing**, 2022.

- [Pansharpening via frequency-aware fusion network with explicit similarity constraints](https://ieeexplore.ieee.org/abstract/document/10142023).
**Yinghui Xing**, Yan Zhang, Houjun He, Xiuwei Zhang, Yanning Zhang, **IEEE Transactions on Geoscience and Remote Sensing**, 2022.
[**Code**](https://github.com/YinghuiXing/FAFNet)

- [Wavefusion: Wavelet assistant fusion model for pan-sharpening](https://ieeexplore.ieee.org/abstract/document/9884867).
**Yinghui Xing**, Yan Zhang, Yanning Zhang, **IGARSS**, 2022.

- [ZeRGAN: Zero-reference GAN for fusion of multispectral and panchromatic images](https://ieeexplore.ieee.org/abstract/document/9669094).
Wenxiu Diao, Feng Zhang, Jiande Sun, **Yinghui Xing**, Kai Zhang, Lorenzo Bruzzone, **IEEE Transactions on Neural Networks and Learning Systems**, 2022.

- [Dual-collaborative fusion model for multispectral and panchromatic image fusion](https://ieeexplore.ieee.org/abstract/document/9310712).
**Yinghui Xing**, Shuyuan Yang, Zhixi Feng, Licheng Jiao, **IEEE Transactions on Geoscience and Remote Sensing**, 2022.

2021 and before
- [SSA-Net: Spatial scale attention network for image-based geo-localization](https://ieeexplore.ieee.org/abstract/document/9576727).
Xiuwei Zhang, Xiangchuang Meng, Hanlin Yin, Yixin Wang, Yuanzeng Yue, **Yinghui Xing**, Yanning Zhang, **IEEE Geoscience and Remote Sensing Letters**, 2021.

- [Hyperspectral and Multispectral Image Fusion via Variational Tensor Subspace Decomposition](https://ieeexplore.ieee.org/abstract/document/9486897).
**Yinghui Xing**, Yan Zhang, Shuyuan Yang, Yanning Zhang, **IEEE Geoscience and Remote Sensing Letters**, 2021.

- [Exploiting low-rank and sparse properties in strided convolution matrix for pansharpening](https://ieeexplore.ieee.org/abstract/document/9351613).
Feng Zhang, Haoran Zhang, Kai Zhang, **Yinghui Xing**, Jiande Sun, Quanyuan Wu, **IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing**, 2021.

- [Pan-sharpening via deep metric learning](https://www.sciencedirect.com/science/article/pii/S0924271618300212).
**Yinghui Xing**, Min Wang, Shuyuan Yang, Licheng Jiao, **ISPRS Journal of Photogrammetry and Remote Sensing**, 2018. 

- [Pansharpening with multiscale geometric support tensor machine](https://ieeexplore.ieee.org/abstract/document/8295005/).
**Yinghui Xing**, Min Wang, Shuyuan Yang, Kai Zhang, **IEEE Transactions on Geoscience and Remote Sensing**, 2018.

- [Fusion of panchromatic and multispectral images via coupled sparse non-negative matrix factorization](https://ieeexplore.ieee.org/abstract/document/7560598).
Kai Zhang, Min Wang, Shuyuan Yang, **Yinghui Xing**, Rong Qu, **IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing**, 2016.


# 🎖 Honors and Awards
- *2023.05* I was selected for the Youth Talent Support Program of the Xi'an Association for Science and Technology.
- *2022.07* One paper was selected as a ESI highly cited paper.

# 📖 Educations
- *2020.07 - now*, School of Computer Science, Northwestern Polytechnical University.
- *2014.09 - 2020.06*, School of Artifical Intelligence, Xidian University.
- *2010.09 - 2014.06*, School of Electronic Engineering, Xidian University. 
