---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true

---
## Real-Time Multitask Learning System for Joint  Detection of Face, Facial Landmark  and Head Pose
The rapid advancement of deep learning techniques has revolutionized the processing methods of various computer vision tasks, such as facial analysis, includ-
ing face detection, facial landmark detection (FLD), and head pose estimation (HPE) methods. This project shows the integration of these tasks, particularly when addressing the complexities posed by large-angle face poses. The primary contribution is the proposal of a real-time multitask detection system capable of simultaneously performing joint detection of faces, facial landmarks, and head poses. This system builds upon the widely adopted YOLOv8 detection framework.
![Our approach (Right) not only high in speed but robustness](../_data/headpose.gif "headpose")
<img src="../_data/headpose.gif" width="60%" alt="AltText" />
<img src="../_data/headpose.gif" alt="002_out_WFLW_model" width="512px">
<iframe src="../_data/headpose.gif" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>



## Intelligent human-machine interaction system

This system combines voice recognition as an entry point to perform various operations, including opening applications, controlling devices, and providing information. The development of this system requires in-depth expertise in voice recognition, natural language processing, internet connectivity, and human-machine interaction technologies. Additionally, it's important to ensure the system's scalability for easy integration of more functionalities and applications in the future. The system should also be adaptable to accommodate different user needs and allow for personalized settings and configurations. Here's a video I want to share:
width="560" height="315" 

<iframe src="//player.bilibili.com/player.html?aid=790163611&bvid=BV1iy4y1w7hr&cid=1312218152&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


 
## YOLOLandmark: end-to-end face and FLD

端到端的人脸关键点检测

<iframe height=498 width=510 src="../_data/WIN_20230324_22_12_35_Pro.mp4"></iframe>

## YOLODDD: end-to-end face and DDD

端到端的司机疲劳检测

<iframe height=498 width=510 src="../_data/WIN_20230324_22_12_35_Pro.mp4"></iframe>




```HTML
<video width="320" height="240" controls>
    <source src="../_data/WIN_20230324_22_12_35_Pro.mp4" type="video/mp4">
</video>
```

或者

```HTML
<video src="../_data/WIN_20230324_22_12_35_Pro.mp4" controls="controls" width="500" height="300"></video>
```

当然，除了`.mp4`它还支持其他的格式，但是对于不同的浏览器支持的格式不一样，见下表：

<table id="tfhover" class="tftable" border="1">
<tr><th>格式</th><th>IE</th><th>Firefox</th><th>Opera</th><th>Chrome</th><th>Safari</th></tr>
<tr><td>Ogg</td><td>No</td><td>3.5+</td><td>10.5+</td><td>5.0+</td><td>No</td></tr>
<tr><td>MPEG4</td><td>9.0+</td><td>No</td><td>No</td><td>5.0+</td><td>3.0+</td></tr>
<tr><td>WebM</td><td>No</td><td>4.0+</td><td>10.6+</td><td>6.0+</td><td>No</td></tr>
</table>


video 元素允许多个 source 元素。source 元素可以链接不同的视频文件。浏览器将使用第一个可识别的格式，这样我们只要多准备几个不同格式的视频就可以了。

用法：

```HTML
1. <video width="500" height="250" controls="controls">

2. <source src="movie.ogg" type="video/ogg">

3. <source src="../_data/WIN_20230324_22_12_35_Pro.mp4" type="video/mp4">

4. 您的浏览器不支持此种视频格式。

5. </video>
```

其次，这是对一些参数的说明：

```HTML
autoplay :出现该属性意味着视频在就绪后将自动播放，用法：autoplay="autoplay"

controls :出现该属性意味着向用户显示控件，如播放按钮等，用法：controls="controls"

height:设置高度      width:设置宽度

loop:自动重播，用法：loop="loop"

preload:视频在页面加载时进行加载并预备播放，用法：preload="auto" - 当页面加载后载入整个视频；preload="meta" - 当页面加载后只载入元数据；preload="none" - 当页面加载后不载入视频。注意：若使用了autoplay，则忽略preload

src:要播放视频的url
```

示例：
第一种：

```HTML
<video width="720" height="303" controls> #或者：<video width:60% height:auto controls>
<source src="../_data/WIN_20230324_22_12_35_Pro.mp4" type="video/mp4">
</video>
```

<video width="720" height="303" controls>
<source src="../_data/WIN_20230324_22_12_35_Pro.mp4" type="video/mp4">
</video>

第二种：

```HTML
<video src="../_data/WIN_20230324_22_12_35_Pro.mp4" controls="controls" width:100% height:auto></video>
```

<video src="../_data/WIN_20230324_22_12_35_Pro.mp4" controls="controls" width="720" height="405"></video> -->
