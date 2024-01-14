---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an undergraduate student at [the Department of Electronic Engineering](https://www.ee.tsinghua.edu.cn/en/), Tsinghua University, supervised by [Prof. Shengjin Wang](http://web.ee.tsinghua.edu.cn/wangshengjin/en/index/2817/list/index.htm) and [Dr. Yali Li](http://web.ee.tsinghua.edu.cn/liyali/en/index.htm). Interested in unraveling the principles of neuronal population, I am working on the topic of application of deep learning in neuroscience.

For more information, please check out my [CV](files/CV.pdf).


# Publication

 Xin L., **Siqi L.**, Yali L., Shengjin W. (2023). **Improving individual brain prediction via a generalizable group brain encoding model.** *(In preparation)*

 Zijian Z., Yali L., Yue Z., **Siqi L.**, Shengjin W. (2023). **FTAN: Exploring frame-text attention for lightweight video captioning.** International Conference on Computing and Pattern Recognition. *(Accepted)*


# Projects

## The Algonauts Project 2023

Trained an ConvNeXt-based encoding model with Feature Pyramid Network and sparse dictionary learning, in order to predict the fMRI signals of human brain with single-trail images viewed by the subjects, caption of the input images and behaviour data of the subjects as input. The model ranked 5th on the final leader board of the [competition](http://algonauts.csail.mit.edu/challenge.html). [Visualization](images/005_cvailab.png) of the prediction and [accuracy report](files/Submission_Report_Summary.svg) are available.

## Analyzing Brain Imaging of Visual Cognition with Transformer

With Transformer models based on Pytorch, multi-label classification is performed on fMRI images of the human brain in the [NSD dataset](https://www.nature.com/articles/s41593-021-00962-x) based on the labels of the images viewed by the subjects. Code and materials are available [here](https://github.com/LSQamI/Brain-Decode).

## Tsinghua University 2021 Competition of Intelligent Robot

Trained a CNN to enable the Ultra96-V2-based intelligent robot to recognize different targets. Let it detect blocks of different colors, and avoid stationary or moving obstacles. Calibrated images from its camera against grid markers to confirm its position to let it walk accurately following a planned path. [Demo](https://github.com/LSQamI/Robot)

## Predicting World Temperature with Gaussian Process Regression

Used 1880 to 2021 World temperature data from NASA to train and estimate a GPR model, whose MAE was less than that of other researchers’ predictions by neural network. Predicted that world temperature would rise rapidly, with 1℃ higher than today’s temperature in 2050. [Link](https://github.com/LSQamI/GPR)