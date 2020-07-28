# RGB-D Salient Object Detection: A Survey

![alt text](./Fig0.jpg)


RGB-D Salient Object Detection: A Survey

Contributed by  [*Tao Zhou*](https://taozh2017.github.io), [*Deng-Ping Fan*](https://dpfan.net/).

--- *Last updated: 2020/07/26* --- 


------


## Content:

1. <a href="#survey"> Related Reviews and Surveys to SOD </a>
2. <a href="#RGBDmodels"> RGB-D SOD Models </a>
3. <a href="#LFmodels">  Light Field SOD Models </a>
4. <a href="#datasets"> RGB-D SOD Datasets </a>
5. <a href="#evaluation"> Evaluation </a>
    1. <a href="#technical_CT">  Overall Evaluation: </a>
    1. <a href="#technical_CXR">  Attribute-based Evaluation: </a>


------

## Related Reviews and Surveys to SOD:  <a id="survey" class="anchor" href="#survey" aria-hidden="true"><span class="octicon octicon-link"></span></a>  

**No.** | **Year** | **Pub.** | **Title** | **Links** 
:-: | :-: | :-: | :-  | :-: 
01 | **2015** | **IEEE TIP**   |  Salientobject detection: A benchmark | [Paper](https://arxiv.org/pdf/1501.02741.pdf)/Project
02 | **2018** | **IEEE TCSVT** |  Review of visual saliency detectionwith comprehensive information | [Paper](https://arxiv.org/pdf/1803.03391.pdf)/Project
03 | **2018** | **ACM TIST**   |  A review of co-saliency detection algorithms: Fundamentals,applications, and challenges | [Paper](https://arxiv.org/pdf/1604.07090.pdf)/Project
04 | **2018** | **IEEE TSP**   |  Advanced deep-learning techniques for salient andcategory-specific object detection: A survey| [Paper](https://ieeexplore.ieee.org/document/8253582)/Project
05 | **2018** | **IJCV**       |  Attentivesystems: A survey | [Paper](https://link.springer.com/article/10.1007/s11263-017-1042-6)/Project
06 | **2019** | **CVM**        |  Salient object detection: A survey | [Paper](https://link.springer.com/content/pdf/10.1007/s41095-019-0149-9.pdf)/Project
07 | **2019** | **IEEE TNNLS** |  Object detection with deep learning: Areview | [Paper](https://arxiv.org/pdf/1807.05511.pdf)/Project
08 | **2019** | **arXiv**      |  Salient Object Detection in the Deep Learning Era-An In-Depth Survey | [Paper](https://arxiv.org/pdf/1904.09146.pdf)/[Project](https://github.com/wenguanwang/SODsurvey) 


------

## RGB-D SOD Models:  <a id="RGBDmodels" class="anchor" href="#RGBDmodels" aria-hidden="true"><span class="octicon octicon-link"></span></a>  

**No.** | **Year** | **Model** |**Pub.** | **Title** | **Links** 
:-: | :-: | :-: | :-  | :-  | :-: 
01 | **2012** | **DM**  | **ECCV**   | Depth matters: Influence of depth cues on visual saliency        | [Paper](https://link.springer.com/content/pdf/10.1007/978-3-642-33709-3_8.pdf)/Project 
02 | **2012** | **DMRCM | **ICCSE**  | Depth combined saliency detection based on region contrast model | [Paper](https://ieeexplore.ieee.org/document/6295184)/Project 
03 | **2013** | **LS    | **BMVC**   | An In Depth View of Saliency                                     | [Paper](http://www.cs.utah.edu/~thermans/papers/ciptadi-bmvc2013.pdf)/Project 
04 | **2013** | **RC    | **BMVC**   | Depth really Matters: Improving Visual Salient Region Detection with Depth | [Paper](http://cdn.iiit.ac.in/cdn/cvit.iiit.ac.in/images/ConferencePapers/2013/cv_deepth-really.pdf)/Project 
05 | **2013** | **SOS   | **Neurocomputing**   | Depth really Matters: Improving Visual Salient Region Detection with Depth | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231213002981)/Project 
02 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
03 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
04 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
05 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
06 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
07 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
08 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
09 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
10 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
11 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
12 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
13 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  
14 | **2020** | **BBS-Net** | **ECCV** | BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network | [Paper](http://dpfan.net/wp-content/uploads/ECCV2020_BBS-NetFDP.pdf)/[Project](https://github.com/zyjwuyan/BBS-Net)  


------

## Light Field SOD Models:  <a id="LFmodels" class="anchor" href="#LFmodels" aria-hidden="true"><span class="octicon octicon-link"></span></a>  



------

## RGB-D SOD Datasets:  <a id="datasets" class="anchor" href="#datasets" aria-hidden="true"><span class="octicon octicon-link"></span></a>  




------

## Evaluation:  <a id="evaluation" class="anchor" href="#evaluation" aria-hidden="true"><span class="octicon octicon-link"></span></a>  

 