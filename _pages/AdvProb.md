---
layout: archive
title: "Advanced Probability"
permalink: /AdvProb/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<!-- concentration inequality-->
<font size="3"><font color="#0000dd">Why non-asymptotic probability?</font><br /></font><br />
In compressed sensing and high dimensional data science, isometric embedding plays an crucial role which lay its foundation upon non-asymptotical analysis of random matrices. It can be dated back to 1990s, Bai-yin law state that:...... More precisely,....

please also check [Terrence Tao's notes](https://terrytao.wordpress.com/tag/bai-yin-theorem/)

<font size="3"><font color="#0000dd">How to estabilish uniform bounds?</font><br /></font><br />
Covering Nets technique: to get uniformly bound (usually operator bound or uniformly for $S^{n-1}$), one can use $\epsilon$-Net to help establish such. More precisely, the uniform bound for all $S^{n-1}$ can be in the same order of bounds for $\epsilon$-Net. So in each point in the epsilon Net, we have a bound and a fail probability, we can have the uniform bound for all points in the $\epsilon$-Net and union fail probability(fail probability for each point times $\epsilon$-Net size). Once we have the union fail probability and due to uniform bound for $\epsilon$-Net, we can state under such fail probability, the uniform bounds for $S^{n-1}$ can be estimated.

<font size="3"><font color="#0000dd">Sub-gaussian</font><br /></font><br />
<!-- 浅红色文字：<font color="#dd0000">浅红色文字：</font><br /> 
  浅蓝色文字：<font color="#0000dd">浅蓝色文字</font><br />
size为2：<font size="2">size为2</font><br />  -->
