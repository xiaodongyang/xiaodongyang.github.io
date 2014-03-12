---
layout: page
title: Projects
comments: no
---

## Abstract

<table width="680" border="0" align="center">
<tr>
<th scope="col"><p align="justify">We present an interactive surveillance event detection system. In the proposed system, a set of spatio-temporal features including STIP, MoSIFT, ActoinHOG, and Dense Trajectories are extracted, and a sliding temporal window is employed as the detection unit. Fisher Vector is used to encode low-level features as the representation of each sliding window. Both feature-level and decision-level fusions are used to combine multiple features. In order to deal with the highly imbalanced nature of surveillance data, the system performs detections using the CascadeSVMs algorithm according to each specific event and camera view. We develop two different interactive environments, one focuses on high throughput and the other includes related result expansion. In the primary run evaluations, our system ranks the first place on two event detection tasks. </p></th>
</tr>
</table>

<br>

## System Overview

<table width="680" border="0" align="center">
<tr>
<th scope="col"><img src="SED13_Overview.png" width="500" height="476"></th>
</tr>

<tr>
<th><p align="justify">Our system includes four major components: (1) low-level feature extraction, (2) video representation based on Fisher Vector, (3) event learning and predictoin by CascadeSVMs, and (4) human interaction.</p></th>
</tr>
</table>