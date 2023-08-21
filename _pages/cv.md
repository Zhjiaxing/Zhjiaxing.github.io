---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Hunan University, Civil Engineering (**[ARWU Top 15 Academic Subjects Worldwide]**(https://www.shanghairanking.com/rankings/gras/2022/RS0211)), 2024
* B.S. in Chongqing Jiaotong University, Civil Engineering, 2021

Publication 
======
1. **Ren, Y.**, Zhang, C.*, Zhu, M., Chen, R., Wang, J. (2023). Significance and formulation of ground loss in tunnelinginduced settlement prediction: a data-driven study. *Acta Geotechnica*, 1-16. (**Impact Factor : 6.0**) 

2. He, S.*, **Ren, Y.**, Liu, H., Liang, B., Du, G. (2022). A novel tunnel lighting method aided by highly diffuse reflective materials on the sidewall: Theory and practice. *Tunnelling and Underground Space Technology*, 122, 104336. (**Impact Factor : 6.9**)  

3. Geng, Z., Zhang, C.*, **Ren, Y.**, Zhu, M., Chen, R., Cheng, H. (2023). A Kriging-Random Forest Hybrid Model for Real-time Ground Property Prediction during Earth Pressure Balance Shield Tunneling. *arXiv preprint arXiv:2305.05128.* (Under revision) 

4. **Ren, Y.**, Zhang, C.*. (2023). A quality index for construction big data in EPB shield tunneling. (In preparing) 

*:Supervisor 

Experience 
======
* **Physics-informed inverse modeling for SWRC and HCF**
  * **Specify an inverse PINN for identifying SWRC and HCF:**  Encode the Richardson-Richards equation (RRE) with unknown parameters that determine the hydraulic properties into the loss function of a neural network, yielding a novel PINN for identifying the constitutive models
  * **Validation:** Simulated data and experiment data are utilized for demonstrating the effectiveness of the proposed framework 
![pinn](http://renyuhao825.github.io/images/pinn.png)
<center> Structure of the proposed framework. More details will be posted in an official release. </center>



* **Quality index for construction big data in EPB shield tunneling**
  * **Quality index development:** Pioneer the first quality measure for construction big data in EPB shield tunneling, which consists of three components, i.e., representativeness, diversity, and informativeness
  * **Verify the effectiveness of the proposed quality index:** The quality index of data is quantitatively compared with the performance of the models developed by data via a correlation analysis, the high R-values that more than 0.9 confirms the effectiveness of the quality index 
![qi](http://renyuhao825.github.io/images/qi.png)
<center> Validation process. More details will be posted in an official release. </center>

*  **Data-driven modeling for ground loss in EPB shield tunneling**
    * **Evaluation of existing methods for ground loss:** Survey the existing formulations for ground loss, and quantitatively evaluate them based on the collected field dataset 
    * **Hybrid model for tunneling-induced settlement:** Develop a random forest model for capturing the relationship between the ground loss and related features, which is integrated into the classical settlement solutions, yielding a hybrid model for tunneling-induced settlement
![rf](http://renyuhao825.github.io/images/rf.png)
<center> A hybrid algorithm for settlement prediction. More details can be found in the published version. </center>

* **Transfer learning for chamber pressure prediction in EPB shield tunneling**
  * **Transfer learning framework for chamber pressure prediction:** Introduced the transfer learning methods, e.g., fine-tuning, CORAL, and MMD, for enhancing the generalization ability of existing models in predicting chamber pressure from different projects
  * **Performance of the transfer learning frameworks:** Utilize two filed datasets from Tianjin City and Changsha City to quantitatively demonstrate the effectiveness of the selected transfer learning methods in the few-shots problem of chamber pressure prediction 
![tl](http://renyuhao825.github.io/images/tl.png)
<center> Transfer learning frameworks for predicting EPB chamber pressure. </center>

* **Surrogate model for structural response under dynamical loading**
  * **Surrogate model development:** We are the first to introduce deep neural operators e.g., DeepONet and FNO, into surrogate modeling for the response of underground structures under dynamical loading
  * **Transfer learning of surrogate model:** We implemented transfer learning methods for maintaining the effectiveness of the developed models under different geological conditions 


Honors and Awards  
======
1. **Chinese National Encouragement Scholarship** - May, 2019 
2. **First-class Prize** of Chongqing Mathematical Contest in Modeling- September, 2019 
3. **S-award** of International Mathematical Contest in Modeling - March, 2020