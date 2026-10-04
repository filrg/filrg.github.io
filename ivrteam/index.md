---
title: iVR
nav:
  order: 3
  tooltip: Meet the Immersive & Intelligent VR Streaming Team
---

# {% include icon.html icon="fa-brands fa-youtube" %}**Immersive & Intelligent VR Streaming (iVR)**

## **Our research fields**

The iVR Team conducts research on the delivery and optimization of advanced immersive media formats, including on-demand and live streaming of 360-degree video, volumetric video, and emerging representations such as dynamic point cloud. The team investigates adaptive streaming protocols, notably Dynamic Adaptive Streaming over HTTP (DASH), and focuses on enhancing the Quality of Experience (QoE) for users consuming immersive content.

{% include video.html
   video="videos/uol/stream.mpd"
   caption="A trip to Liverpool."
   width="100%"
   autoplay=true
%}

{% include section.html %}

## **Video transmission**

The iVR Team explores efficient transmission techniques for immersive visual content, with a particular interests but not limmited to 360-degree video and volumetric media such as dynamic point clouds. Our research addresses the challenges of rate adaptation, viewport-aware streaming, and real-time delivery over variable-bandwidth networks. We also investigate cloud-based and edge-assisted strategies to support latency-sensitive and bandwidth-intensive applications in eXtended Reality environments.

## **Quality of Experience**

Our work in Quality of Experience (QoE) aims to model, evaluate, and enhance user-perceived quality in immersive streaming scenarios. This includes developing objective QoE metrics tailored to spatial and temporal characteristics of 360-degree and volumetric video, and proposing user-centric adaptation mechanisms. The team also conducts subjective evaluations to better understand human perception under various viewing conditions, network fluctuations, and device capabilities.

## **Our works** 

{% capture content %}

{% include video.html 
caption="A 360 degree video based telepresence system for remote learning" 
video="videos/360-degree-virtual-classroom/stream.mpd" 
%}

{% include figure.html 
caption="A lightweight dynamic point cloud subjective test environment" 
image="images/fil/ivr/longdress.gif" 
link="https://github.com/QuangNguyenLong/DynamicPointCloudSubjectiveTest" %}

{% include figure.html 
caption="A point cloud preparation tool" 
image="images/fil/ivr/pcprep-logo-with-text.svg" 
link="https://github.com/filrg/pcprep" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

{% include button.html link="vr360-dash-demo" text="See our demo" icon="fa-solid fa-arrow-left" %}
{% include button.html link="members/co-truong-thu-huong.html" text="Contact head" icon="fa-solid fa-arrow-right" flip=true %}
