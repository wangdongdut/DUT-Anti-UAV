# DUT Anti-UAV Detection and Tracking

# Detection
* **Dataset:**
  * Examples:  
    ![avatar](https://github.com/wangdongdut/Anti-UAV-Detection-Tracking/blob/master/AntiUAVDetection.jpg)
  * Download[GoogleDrive]：[train](https://drive.google.com/open?id=1RVsSGPUKTdmoyoPTBTWwroyulLek1eTj), [val](https://drive.google.com/open?id=1333uEQfGuqTKslRkkeLSCxylh6AQ0X6n), [test](https://drive.google.com/open?id=1L1zeW1EMDLlXHClSDcCjl3rs_A6sVai0)
  * Download[Baidu]：[train](https://pan.baidu.com/s/1-ogC7P_K6lwYAqIS8bgIUQ )[u955], [val](https://pan.baidu.com/s/15sekmPn0hYNQS05Makbmtw )[wkzs], [test](https://pan.baidu.com/s/1GiA-bKlvMSBkzUwYvo-RiA)[ik4d]

* **Results:**

# Tracking
* **Dataset:**
  * Examples:  
  * Download[GoogleDrive]：[img](https://drive.google.com/open?id=1dlSPDggg6TRFMcC1jlYIJxxzUQS1mIh9), [gt](https://drive.google.com/open?id=16PE3tBhT0lUGZLA8-zIRYvNUvxfhFZJq)
  * Download[Baidu]：[img](https://pan.baidu.com/s/1OTExqKgvUnqpENtTDu_gGQ)[oine], [gt](https://pan.baidu.com/s/1nkGNERDVgmYIAiwFTdj2xA )[e8mr]
* **Results:**

# Paper
  **Jie Zhao, Jingshu Zhang, Dongdong Li, Dong Wang. Vision-based Anti-UAV Detection and Tracking. IEEE Transactions on Intelligent Transportation Systems, 2022. [[Arxiv](https://arxiv.org/abs/2205.10851)]**


# References

* **Detection**
  * **SSD: Wei Liu, Dragomir Anguelov, Dumitru Erhan, Christian Szegedy, Scott E. Reed, Cheng-Yang Fu, Alexander C. Berg.** <br />
    **"SSD: Single Shot MultiBox Detector." ECCV (2016).**
  * **Faster R-CNN: Shaoqing Ren, Kaiming He, Ross B. Girshick, Jian Sun.** <br /> 
    **"Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks." ECCV (2016).**
  * **Cascade-RCNN: Zhaowei Cai, Nuno Vasconcelos.** <br /> 
    **"Cascade R-CNN: Delving Into High Quality Object Detection." CVPR (2018).**
    [[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Cai_Cascade_R-CNN_Delving_CVPR_2018_paper.pdf)]
  * **ATSS: Shifeng Zhang, Cheng Chi, Yongqiang Yao, Zhen Lei, Stan Z. Li.** <br /> 
    **"Bridging the Gap Between Anchor-Based and Anchor-Free Detection via Adaptive Training Sample Selection." CVPR (2020).**
    [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Bridging_the_Gap_Between_Anchor-Based_and_Anchor-Free_Detection_via_Adaptive_CVPR_2020_paper.pdf)]
  * **YOLOX: Zheng Ge, Songtao Liu, Feng Wang, Zeming Li, Jian Sun.**
    **"YOLOX: Exceeding YOLO Series in 2021." CoRR abs/2107.08430 (2021).**
    [[paper](https://arxiv.org/abs/2107.08430)]
  * **mmdetection：https://github.com/open-mmlab/mmdetection**
  
* **Tracking**
  * **ECO: Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg.** <br /> 
    **"ECO: Efficient Convolution Operators for Tracking." CVPR (2017).**
    [[paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Danelljan_ECO_Efficient_Convolution_CVPR_2017_paper.pdf)]
    [[code](https://github.com/visionml/pytracking)]
  * **SiamFC: Luca Bertinetto, Jack Valmadre, Joao F. Henriques, Andrea Vedaldi, Philip H. S. Torr.** <br /> 
    **"Fully-Convolutional Siamese Networks for Object Tracking." ECCV (2016).**
    [[paper](https://arxiv.org/pdf/1606.09549.pdf)]
    [[code](https://github.com/HonglinChu/SiamTrackers)]
  * **SiamPRN++: Bo Li, Wei Wu, Qiang Wang, Fangyi Zhang, Junliang Xing, Junjie Yan.** <br /> 
    **"SiamRPN++: Evolution of Siamese Visual Tracking with Very Deep Networks." CVPR (2019).**
    [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_SiamRPN_Evolution_of_Siamese_Visual_Tracking_With_Very_Deep_Networks_CVPR_2019_paper.pdf)]
    [[code](https://github.com/STVIR/pysot)]
  * **ATOM: Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg.** <br /> 
    **"ATOM: Accurate Tracking by Overlap Maximization." CVPR (2019).**
    [[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Danelljan_ATOM_Accurate_Tracking_by_Overlap_Maximization_CVPR_2019_paper.pdf)]
    [[code](https://github.com/visionml/pytracking)]
  * **DIMP: Goutam Bhat, Martin Danelljan, Luc Van Gool, Radu Timofte.** <br />
    **"Learning Discriminative Model Prediction for Tracking." ICCV (2019).** 
    [[paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Bhat_Learning_Discriminative_Model_Prediction_for_Tracking_ICCV_2019_paper.pdf)]
    [[code](https://github.com/visionml/pytracking)]
  * **SPLT: Bin Yan, Haojie Zhao, Dong Wang, Huchuan Lu, Xiaoyun Yang.** <br /> 
    **"Skimming-Perusal' Tracking: A Framework for Real-Time and Robust Long-Term Tracking." ICCV (2019).**
    [[paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf)]
    [[code](https://github.com/iiau-tracker/SPLT)]
  * **LTMU: Kenan Dai, Yunhua Zhang, Dong Wang, Jianhua Li, Huchuan Lu, Xiaoyun Yang.** <br />
    **"High-Performance Long-Term Tracking with Meta-Updater." CVPR (2020).** 
    [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Dai_High-Performance_Long-Term_Tracking_With_Meta-Updater_CVPR_2020_paper.pdf)]
    [[code](https://github.com/Daikenan/LTMU)]
  * **TransT: Xin Chen, Bin Yan, Jiawen Zhu, Dong Wang, Xiaoyun Yang, Huchuan Lu.** <br />
    **"Transformer Tracking." CVPR (2021).** 
    [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Chen_Transformer_Tracking_CVPR_2021_paper.pdf)]
    [[code](https://github.com/chenxin-dlut/TransT)]

# Related Papers

* Nan Jiang, Kuiran Wang, Xiaoke Peng, Xuehui Yu, Qiang Wang, Junliang Xing, Guorong Li, Qixiang Ye, Jianbin Jiao, Zhenjun Han, Jian Zhao. <br />
`"Anti-UAV: A Large-Scale Benchmark for Vision-Based UAV Tracking."` IEEE Transactions on Multimedia (2022). 
  [[paper](https://ieeexplore.ieee.org/document/9615243)][[project](https://github.com/ucas-vg/Anti-UAV)]

* Fredrik Svanstrom, Cristofer Englund, Fernando Alonso-Fernandez. <br />
  `"Real-Time Drone Detection and Tracking With Visible, Thermal and Acoustic Sensors."` ICPR (2021). 
  [[paper](https://ieeexplore.ieee.org/document/9413241)]     
  
* Stamatios Samaras, Diamantidou Eleni, Dimitrios Ataloglou, Nikos Sakellariou, Anastasios Vafeiadis, Vasilis Magoulianitis, 
  Antonios Lalas, Anastasios Dimou, Dimitrios Zarpalas, Konstantinos Votis, Petros Daras, Dimitrios Tzovaras. <br />
  `"Deep Learning on Multi Sensor Data for Counter UAV Applications - A Systematic Review."`  Sensors (2019). 
  [[paper](https://www.mdpi.com/1424-8220/19/22/4837)]   
  
* Eren Unlu, Emmanuel Zenou, Nicolas Riviere, Paul-Edouard Dupouy. <br />
  `"Real-Time Drone Detection and Tracking With Visible, Thermal and Acoustic Sensors."` IPSJ Transactions on Computer Vision and Applications (2019). 
  [[paper](https://link.springer.com/article/10.1186/s41074-019-0059-x)]  
  
* Ye Wang, Yueru Chen, Jongmoo Choi, C.-C. Jay Kuo. <br />
  `"Towards Visible and Thermal Drone Monitoring with Convolutional Neural Networks."` APSIPA Transactions on Signal and Information Processing (2019)
  [[paper](https://www.cambridge.org/core/journals/apsipa-transactions-on-signal-and-information-processing/article/towards-visible-and-thermal-drone-monitoring-with-convolutional-neural-networks/B2C49AEA077EE25F895FE84F84F16178)]  

# Other Datasets & Resources

* **[Anti-UAV Workshop & Challenge](https://anti-uav.github.io/):** https://anti-uav.github.io/

* **[Halmstad Drone Dataset](https://github.com/DroneDetectionThesis/Drone-detection-dataset):** https://github.com/DroneDetectionThesis/Drone-detection-dataset

* **[USC Drone Dataset](https://github.com/chelicynly/A-Deep-Learning-Approach-to-Drone-Monitoring):** https://github.com/chelicynly/A-Deep-Learning-Approach-to-Drone-Monitoring
