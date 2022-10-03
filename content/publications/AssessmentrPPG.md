---
title: "An assessment of algorithms to estimate respiratory rate from the remote photoplethysmogram"
date: 2020-06-14
pubtype: "Article"
featured: true
description: "D Luguern, S Perche, Y Benezeth, V Moser, L Dunbar, F Braun, A Lemkaddem, K Nakamura, R Gomez, J Dubois"
tags: ["Heart rate","Photoplethysmography"]
image: "/img/organicdevops.webp"
link: "https://openaccess.thecvf.com/content_CVPRW_2020/html/w19/Luguern_An_Assessment_of_Algorithms_to_Estimate_Respiratory_Rate_From_the_CVPRW_2020_paper.html"
fact: ""
weight: 400
sitemap:
  priority : 0.8
---

Duncan Luguern, **Simon Perche**, Yannick Benezeth, Virginie Moser, L Andrea Dunbar, Fabian Braun, Alia Lemkaddem, Keisuke Nakamura, Randy Gomez, Julien Dubois

### Abstract
The respiratory rate is important information in the healthcare environment. Consequently, research is done to develop a device that could measure the respiratory rate continuously with non-contact devices. Various methods were tried, such as radio-based, thermal imaging or remote photoplethysmography (rPPG). 

The rPPG method uses a video recording of the skin in ambient light conditions. It measures the small variations of light reflection induced by the amount of blood in vessels. This method allows the extraction of physiological parameters such as the heart rate or respiratory rate without any contact with the skin. The main issue with the rPPG technique is the lower signal quality compared with contact-based methods. 

In this paper, we assess the performance of the respiratory rate estimation algorithms with rPPG signals. The tested algorithms were designed for contact-PPG signals input. The use of the algorithms designed for contact PPG on remote PPG signals can lead to respiratory rate estimations with a mean absolute error below 3 breaths-per-minute. We benchmark our results using this standard and some other metrics to interpret the quality of the assessment.