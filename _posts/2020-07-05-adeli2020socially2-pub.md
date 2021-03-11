---
layout: pub
title: Socially and contextually aware human motion and pose forecasting
author: Adeli, Vida and Adeli, Ehsan and Reid, Ian and Niebles, Juan Carlos and Rezatofighi, Hamid
publisher: IEEE Robotics and Automation Letters (RA-L) & International Conference on Intelligent Robots and Systems (IROS20)
paper_link: https://arxiv.org/pdf/2007.06843
video_link: https://www.youtube.com/watch?v=sTBNdBco1Yo
project_link: true
year: 2020
comments: true
category: blog
---

<img src="../../images/papers/adeli2020socially2.png">

# Abstract

Smooth and seamless robot navigation while interacting with humans depends on predicting human movements. Forecasting such human dynamics often involves modeling human trajectories (global motion) or detailed body joint movements (local motion). Prior work typically tackled local and global human movements separately. In this paper, we propose a novel framework to tackle both tasks of human motion (or trajectory) and body skeleton pose forecasting in a unified end-to-end pipeline. To deal with this real-world problem, we consider incorporating both scene and social contexts, as critical clues for this prediction task, into our proposed framework. To this end, we first couple these two tasks by i) encoding their history using a shared Gated Recurrent Unit (GRU) encoder and ii) applying a metric as loss, which measures the source of errors in each task jointly as a single distance. Then, we incorporate the scene context by encoding a spatio-temporal representation of the video data. We also include social clues by generating a joint feature representation from motion and pose of all individuals from the scene using a social pooling layer. Finally, we use a GRU based decoder to forecast both motion and skeleton pose. We demonstrate that our proposed framework achieves a superior performance compared to several baselines on two social datasets.