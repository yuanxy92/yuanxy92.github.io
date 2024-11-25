---
layout: page
permalink: /research/gigapixel/index.html
title: Computational Imaging with Camera Arrays
---

## Computational Imaging with Camera Arrays
Camera array-based imaging uses a large number of inexpensive cameras to create virtual cameras that outperform real ones. 
They can function in many ways by changing the arrangement and aiming of the cameras. We developed an unstructured gigapixel array camera (UnstructuredCam), 
beyond the resolution of a single camera and human visual perception, which aims to capture the large-scale dynamic scene with both wide-FoV and high-resolution. We build a prototype camera array using one global camera and 19 local cameras. All the cameras are mounted on gimbals for adjusting the camera poses. 
<center>
<img width = '80%' src="/images/imgs/gigapixel/teaser.jpg">
</center>

Left is the captured videos, and right is the recorded screens. It was recoreded in Nanshan I park, Shenzhen. You can choose place to zoom in to see the details interactively.
The blue road sign is about 300 m away, the chinese and english characters are very clear. The license plate of the car in 150 m is clearly distinguishable.

<center><div style="position: relative; width: 85%; height: 0; padding-bottom: 45%;">
<video width="100%" height="100%" controls>
    <source src="https://github.com/yuanxy92/yuanxy92.github.io/raw/refs/heads/master/videos/gigapixel/realtime_demo.mp4" type="video/mp4">
</video></div></center><br>

By proposing the unstructured embedding algorithm, our UnstructuredCam is robust to local camera movement, loss, and addition because it could react and recover quickly with online recalibration. During realtime streaming, the local camera can be adjusted and online calibrated very quickly. Here, we move the camera from the red position to the yellow postion.
<center><div style="position: relative; width: 85%; height: 0; padding-bottom: 45%;">
<video width="100%" height="100%" controls>
    <source src="https://github.com/yuanxy92/yuanxy92.github.io/raw/refs/heads/master/videos/gigapixel/online_calibration_demo.mp4" type="video/mp4">
</video></div></center><br>

Our UnstructuredCam can also be extended for distant large-scale 3d videography, enabling an unprecedented VR experience:
<center><div style="position: relative; width: 85%; height: 0; padding-bottom: 45%;">
<video width="100%" height="100%" controls>
    <source src="https://github.com/yuanxy92/yuanxy92.github.io/raw/refs/heads/master/videos/gigapixel/3d_perception_demo.mp4" type="video/mp4">
</video></div></center><br>

Based on the UnstructuredCam We built the [PANDA and GigaMVS gigapixel dataset (Click me)](https://gigavision.cn/data/news?nav=DataSet%20Panda&type=nav&t=1732450676652) using our array camera to promote the study of large-scale, long-range, 
multi-target visual analysis centered on human behavior. More gigapixel videography captured by our UnstructuredCam:
<center><div style="position: relative; width: 85%; height: 0; padding-bottom: 45%;">
<video width="100%" height="100%" controls>
    <source src="https://github.com/yuanxy92/yuanxy92.github.io/raw/refs/heads/master/videos/gigapixel/more_demos.mp4" type="video/mp4">
</video></div></center><br>

### Publications and links
- [A modular hierarchical array camera (cover article)](https://www.nature.com/articles/s41377-021-00485-x), **Light: Science & Applications** 2021.
- [Multiscale gigapixel video: A cross resolution image matching and warping approach](https://ieeexplore.ieee.org/abstract/document/7951481), **IEEE International Conference on Computational Photography (ICCP)** 2017.
- [Multiscale-vr: Multiscale gigapixel 3d panoramic videography for virtual reality](https://ieeexplore.ieee.org/abstract/document/9105244/), **IEEE International Conference on Computational Photography (ICCP)** 2020.
- [Crossnet++: Cross-scale large-parallax warping for reference-based super-resolution](https://ieeexplore.ieee.org/abstract/document/9099445), **IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI)** 2020.
- [Panda: A gigapixel-level human-centric video dataset](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_PANDA_A_Gigapixel-Level_Human-Centric_Video_Dataset_CVPR_2020_paper.html), **IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)** 2020. [\<Dataset page\>](https://gigavision.cn/data/news?nav=DataSet%20Panda&type=nav&t=1732452632314)
- [GigaMVS: a benchmark for ultra-large-scale gigapixel-level 3D reconstruction](https://ieeexplore.ieee.org/abstract/document/9547729), **IEEE Transactions on Pattern Analysis and Machine Intelligence (PAMI)** 2021.[\<Dataset page\>](https://gigavision.cn/data/news?nav=GigaMVS%20RAWDATA&type=nav&t=1731982252980)
- [16位科学家、191项成果荣获2021年度北京市科学技术奖](https://www.beijing.gov.cn/zhengce/zcjd/202212/t20221230_2887402.html)
- [助力北京冬奥亿像素全景智能防控项目](https://www.zohetec.com/video/85-en.html)